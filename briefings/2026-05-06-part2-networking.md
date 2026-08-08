# Morning Briefing Part 2 — Networking
## Wednesday, May 6, 2026

## ⚠️ STOPPED AT QUALITY GATE

This briefing did not run because a required context file is empty.

### Status of required files

| File | Status | Notes |
|------|--------|-------|
| `context-library/career-plan.md` | ✅ Populated | Real data (Marta Axpe, Innovation leadership, Rotterdam NL) |
| `context-library/target-companies.md` | ✅ Populated | Tier 1+ list with real companies (IKEA, Philips, Unilever, Ocean Cleanup, Danone, etc.) |
| `context-library/connection-tracker.md` | ❌ Template only | Contains only placeholder text like `[Company Name]`, `[Person Name]`, `[date]`, `[yes/no]` |
| Active referral tracker | ❌ Not present | No `referral-tracker.md` or equivalent file found in `context-library/` |/

### Why this stops Part 2

Every section of Part 2 depends on real entries in `connection-tracker.md`:

- **Section A (25 connection requests):** "Identify coverage gap companies — companies in target-companies.md where the user has fewer than 4 connections logged in connection-tracker.md." With zero real connections, every company is a "gap," but the brief also requires personalized messages referencing each person's specific work/background — which cannot be generated without real names.
- **Section B (follow-ups):** Requires connections that moved from "requested" to "connected" in the last 48 hours. None exist.
- **Section C (referral nudges):** Requires referral requests already sent. None exist.

The skill's constraint is explicit: **"Use real names and roles from connection-tracker.md only. Do not fabricate connections."**

### What needs to happen before the next run

Choose one of the following:

1. **Bulk import (recommended).** Export your LinkedIn connections as a CSV (LinkedIn → Settings & Privacy → Data Privacy → Get a copy of your data → Connections). Drop the CSV into the chat and ask: "Auto-populate my connection tracker from this CSV." The OS will cross-reference against `target-companies.md` and surface contacts at your Tier 1+ companies.

2. **Manual seeding.** Add 10–20 people you already know (former colleagues, university contacts, ex-clients) to `connection-tracker.md` using the template structure. Tag each with company and role. Even a small seed set lets Part 2 produce useful output.

3. **Targeted prospecting list.** If the goal is to start cold, ask the OS to generate a prospecting list against your top 10 target companies first, then save those names into the tracker manually as you act on them.

A referral tracker file (e.g. `context-library/referral-tracker.md`) should also be created if you plan to track referral requests — Part 2's Section C reads from it.

### Carry-over notes for Part 3

Part 3 should treat networking as a **gap to close this week**, not as activity in flight. Suggest that the user spend 15 minutes today on the LinkedIn CSV import or on seeding 10 connections — that single action unlocks the entire networking arm of the OS.

---

## Candidate-Mode Notes (for the next run)

When `connection-tracker.md` is populated, apply these modes based on what was read from `career-plan.md` today:

- **Currently freelancing, ~2 months runway, 10 months into search:** Treat as time-sensitive but selective. Prioritize Tier 1 companies (IKEA, Philips, Unilever, Ocean Cleanup, Danone) and warm intros over cold volume.
- **NL-based, no relocation:** Allocate the majority of requests to NL-based contacts; European-remote contacts are secondary.
- **Dual-track (permanent + freelance) and dual-level (leadership + senior IC):** Mix targets accordingly — Director/Head/VP-of-Innovation peers for the leadership track, Lead/Principal Service Designers and UX Research leads for the IC track.
- **Brand-name CV gap (Culligan not widely known in EU):** Prioritize Philips, IKEA, Unilever, Google/YouTube alumni who can validate cross-industry pattern recognition; warm intros at recognizable EU brands compound in value.
- **Dutch is basic:** Filter out NL-only Dutch-language companies; prioritize international/English-first employers.

These modes are noted here so Part 3 and the next Part 2 run start with the right framing.
