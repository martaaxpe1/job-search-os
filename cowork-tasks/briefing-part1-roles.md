# Morning Briefing - Part 1: New Roles
# Scan target companies, score roles, tailor resumes for top matches

> **Cowork setup:** Schedule at 7:00 AM weekdays. Saves output to `briefings/[YYYY-MM-DD]-part1-roles.md`.
> This part runs independently. Parts 2 and 3 reference its output.

---

Read all files in the job-search-os/context-library/ folder. Also read job-search-os/CLAUDE.md for system rules.

## Quality Gate

Before running, verify these files contain real data (not template placeholders like `[FILL IN]`):

1. **experience-library.md** -- If empty or placeholder-only, STOP. Say: "Your experience library is not filled in. Run `Help me build my experience library` first."
2. **career-plan.md** -- If empty or placeholder-only, STOP. Say: "Your career plan is not filled in. Fill in career-plan.md first."
3. **target-companies.md** -- If empty or placeholder-only, STOP. Say: "Your target companies list is not filled in. Fill in target-companies.md first."

If any check fails, do NOT proceed.

## Role Type Detection

Read `career-plan.md` to detect the user's target function (PM, SWE, Design, Data Science, Marketing, CS/Sales). All sections below adapt to the detected function. Search for function-appropriate roles, not PM roles by default.

---

## Motivation & Status

Determine what week of the job search this is by counting from the earliest application date in app-tracker (or OS creation date if no applications yet).

**If app-tracker.md does not exist or is empty:** Assemble pipeline data from `target-companies.md` (Status fields, Summary by Status table), `connection-tracker.md` (referral dates), `interview-history.md` (interview dates), and `briefings/` folder (recent activity). Note: "Pipeline stats assembled from alternative sources. For precise tracking, run `/app-tracker add` for each active application."

Display:
```
Week [N] of your search.
Stats since start: Applications: [N] | Interviews: [N] | Offers: [N]
[One sentence of data-driven coaching -- NOT generic motivation. Base it on actual patterns.]
```

---

## New Roles Scan

Search each company in target-companies.md for new postings in the user's target function from the last 24 hours. Check careers pages and LinkedIn.

**DATA QUALITY GATE:** If web search is unavailable or returns errors for a company, skip it and note: "[Company]: could not verify -- check manually." NEVER fabricate job listings. If you cannot find a real URL, do not include it.

**FRESHNESS VERIFICATION RULE — OPTION B (revised May 11, 2026 per Marta's instruction. Supersedes all prior freshness rules.):**

Past freshness rules (snippet dates, "live-fetch" body checks) repeatedly produced false-positive Top Roles — most recently May 11, 2026, when three of three "verified live" roles turned out to be 404s or filled positions. The failure modes are:

- Search engines (Google, Bing) cache snippet text for weeks/months after roles are pulled. Posted-date signals in snippets are unreliable.
- Aggregators (Glassdoor, LinkedIn third-party scrapes, designproject.io, servicedesignjobs.com, uxwork.nl) cache postings for months. They are useful for *discovery* but useless for *verification*.
- Official career portals (Workday, Phenompeople, Homerun, Greenhouse-hosted) serve templated JD pages from their CMS even after a requisition is closed. The HTML renders, the Apply button renders, but clicking through hits a 404.

**Option B rule (strict — accept lower volume in exchange for zero false positives):**

A role qualifies for the briefing only if ALL of the following hold:

1. **Official portal only.** The URL must be on the company's own careers portal (e.g., careers.<company>.com, jobs.<company>.com, <company>.com/careers). Aggregator URLs (Glassdoor, Indeed, LinkedIn third-party scrapes, designproject.io, servicedesignjobs.com, uxwork.nl, themuse.com, climatetechlist.com, etc.) are for *discovery only* and must not appear as the primary URL for any briefing role. If an aggregator surfaces a role, the next step is to find the same role on the company's own portal — if it isn't there, the role doesn't make the briefing.
2. **Live-fetch must return JD body content.** The JD page must be successfully fetched via WebFetch AND the response body must contain actual JD content (role title, responsibilities, requirements — not just navigation chrome). Empty bodies, redirects to a generic vacancies index, or pages that render as "careers homepage" instead of the JD itself disqualify the role.
3. **Posted-date signal in the page body.** The fetched page body must contain a posted-date signal (e.g., "Posted Feb 16, 2026", "Date posted: ...", "Job ID: R-1171956"). Snippet text from search results does not count. If the fetched page contains no posted-date or no Job ID, the role does not qualify.
4. **Posted within the last 30 days.** If the posted-date signal in the page body is >30 days old, the role does not qualify. Long-on-market = likely closed/filled, even if the page is still served.
5. **Already-applied filter.** Cross-check every candidate against `app-tracker.md` before tailoring. Roles applied to (and rejected/ghosted) within the last 12 months do not qualify, regardless of freshness.

**Marta verifies in parallel via LinkedIn manually.** This briefing's job is not to scan LinkedIn — Marta does that herself. The briefing's job is to surface the smaller set of roles that pass the strict gate above, with full tailoring + referral analysis ready to act on.

**Expected output volume under Option B: 0–2 Top Roles per day is normal. Some days zero is the correct answer.** Padding with lower-confidence roles defeats the point. If a day produces zero qualifying roles, the briefing should explicitly say so, and devote the briefing's energy to surfacing carryover conversion priorities (warm-path follow-ups, pending applications, referral activations) instead of net-new applications.

**Why no "Needs Manual Verification" tier:** the May 11 retro showed this half-credit tier became a dumping ground that diluted Marta's attention. Either a role passes the gate cleanly, or it's out. If Marta finds a role manually on LinkedIn that the briefing missed, the day's Part 1 + her LinkedIn scan together cover the field — Part 1 doesn't need to hedge.

**Discovery-only sources (acceptable for finding candidates to verify):** WebSearch on aggregator sites, search results from any source. These just surface possibilities. They never count as evidence the role is live.

**Verification sources (the only acceptable evidence of liveness):** WebFetch on the official portal URL, with the four conditions above satisfied.

**Forbidden patterns:**
- Claiming a role is "VERIFIED LIVE" based on snippet text alone.
- Trusting an aggregator's "Posted X days ago" timestamp.
- Surfacing a role with a caveat ("the JD page returned empty, but...") — if the gate isn't passed, the role doesn't go in.
- Fabricating a URL or a JD that wasn't actually fetched.

**Prioritize checking:**
- Companies where the user has connections (from connection-tracker.md)
- Top 20 companies in target-companies.md
- Companies with recent funding rounds or product launches

**SENIOR-LEVEL / EMPLOYED MODE:** If career-plan.md shows Director+ level AND currently employed, scan only the top 10 companies and only surface roles scoring 75+.

**REMOTE-ONLY MODE:** If career-plan.md shows remote-only preference, filter for roles mentioning "remote," "distributed," or "work from anywhere." Flag "hybrid" or "onsite" roles with a WARNING before scoring.

## Scoring & Tailoring

For each new role found:
1. Run job-fit-scorer (score 1-100 across 5 dimensions: skill match, seniority fit, culture signals, comp range, growth trajectory)
2. **Roles scoring 70+:**
   - Run resume-tailor using experience-library.md as source
   - Calculate keyword coverage score (% of JD requirements matched)
   - Run recruiter-reviewer sub-agent on the tailored resume
   - Run ats-checker sub-agent on the tailored resume
   - Auto-correct flagged issues and note all changes
3. **Roles scoring 60-69:** Flag as "Apply with referral only" and note which connections could refer
4. **Roles below 60:** Skip but log that they were reviewed

Surface up to 3 roles ranked by fit score. **Fewer is fine. Zero is fine.** Only roles that pass the Option B freshness gate AND score 70+ qualify for Top Roles. If no roles pass both, the briefing's "Top Roles Today" section says "No new qualifying roles today" and devotes its energy to the Carryover Priorities and Search Failures sections instead. Do not pad.

## Top Role Cards

For each of the top 3 roles (scoring 70+), include:

### [Role Title] at [Company] (Fit Score: [X]/100)

**Why this is a strong match:** [2-sentence summary highlighting strongest dimensions]

**Tailored Resume:**
- Status: [Generated / Auto-corrected / Needs manual review]
- Keyword coverage: [X]% ([N]/[M] JD requirements matched)
- Recruiter review: First impression [X]/10, Relevance [X]/10, Readability [X]/10
- ATS check: [PASS / PASS WITH WARNINGS / FAIL]
- Gaps: [JD requirements not matched by experience library]
- Auto-correction changes: [list specific changes]

**Referral Path:**
- Closest connection: [Name] at [Company] ([relationship strength])
- Draft referral message: [personalized message ready to send]
- If no connection: "No existing connection. Add to networking priority for this week."

**Work Product Prompt:**
Function-appropriate prompt for `/work-product`:
```
/work-product [Company] [Role Title] get-interview
```
Research hooks:
- [Specific thing to research about this company's product]
- [Specific recent event or launch to reference]
- [Specific user complaint or market dynamic to analyze]

**EXPERIENCE-FRIENDLY (Veteran Mode):** If career-plan.md shows 15+ years or legacy/enterprise employers, flag roles with signals like "seasoned leader," "deep expertise," "10+ years preferred." Format: "EXPERIENCE-FRIENDLY: [Company] [Role] -- JD values [signal]."

---

## Output

Save everything to `job-search-os/briefings/[YYYY-MM-DD]-part1-roles.md` using this format:

```markdown
# Morning Briefing Part 1 — Roles
## [Full Date, e.g., Monday, May 11, 2026]

> **Freshness rule:** Option B — official portal only, JD page live-fetched with body content + posted-date signal + ≤30 days old. Zero qualifying roles is a valid outcome. Marta is also scanning LinkedIn manually in parallel.

## Week [N] | [One sentence of data-driven coaching grounded in actual pipeline patterns]

Stats since start: Applications: [N] | Interviews: [N] | Offers: [N]

---

## ⚡ Urgent Action (Carryover)
[Active applications + warm-path conversions that need attention today, pulled from app-tracker.md, connection-tracker.md, and yesterday's briefing. This section is the primary focus when no new roles qualify.]

---

## Top Roles Today

[If zero roles pass the Option B gate:]
**No new qualifying roles today.** [One-sentence explanation: which companies were scanned, what was discarded and why.] Today's energy goes to the Carryover Priorities above and to any warm-path activations that are due.

[If ≥1 role passes the gate, for each (max 3):]

### N. [Role Title] at [Company] (Fit: [score]/100)
**Verification:** Live-fetched on [official portal URL]. Posted-date signal: "[exact text from page body]". Job ID: [if present].

[2-sentence match summary]

**Tailored Resume:** [status + coverage % + recruiter review + ATS check + gaps + auto-corrections]

**Referral Path:** [closest connection from connection-tracker.md or "No existing connection"]

**Work Product Prompt:** `/work-product [Company] [Role] get-interview`
Research hooks: [bulleted list]

Sources: [official portal URL only — no aggregators]

---

## Discarded Roles — Do Not Re-Surface
[Roles surfaced today via search but failed the Option B gate (aggregator-only, archived, expired, JD body empty, posted >30 days, already-applied). One line each with the specific failure reason. This prevents future runs from re-surfacing the same stale candidates.]

---

## Search Failures
[Companies where today's scan could not verify a fresh-posting role for Marta's function. Manual verification by Marta via LinkedIn is faster than further automated search.]

---

## Pipeline Stats Source
[Where the stats came from — app-tracker.md as primary, fallbacks if needed.]
```
