# Interview Prep — Adyen, Senior Service Designer (Platform Engineering)
Generated: 2026-09-02 | Updated: 2026-09-13
Stage: Round 1 — Recruiter Screening Call, 30 min, with Alina Mustakimova, scheduled 14.09.2026
Sources: Adyen's confirmation email, insider-data/company-intel/adyen.md (low confidence, PM-focused, not used below), friend intel (Chris, real recent Adyen recruiter-screen experience for this exact role), career-plan.md, qa-master.md, experience-library.md, interview-history.md, connection-tracker.md, web research (Sept 2026), Adyen Formula culture page (screenshot), Built In job posting for this exact req + aggregated Glassdoor/community interview questions [VERIFY: not confirmed for this specific call], live Adyen job postings for "PX"/Product Experience org terminology (Sept 2026, Section 0)

---

## Before You Read On

Per Adyen's email and Chris's first-hand, recent screen for this exact role, this is a **culture/motivation screen, not a skills interview** — loose and conversational, running roughly in this order: intro → tell me about yourself → ambitions/way of working → why Adyen → what do you know about Adyen → logistics → comp → your questions. Chris tried to raise substantive JD questions and was deflected to "ask the hiring manager" — don't push on role-definition gaps here.

**The one piece of real, specific feedback driving the changes below:** Chris was told his service design background read as **too consumer-oriented** for this role. The Built In posting confirms this is specifically Platform Engineering / DevEx work (bridging internal engineering systems with developer experience, ~80% strategic service mapping, ~20% hands-on UI/UX) [VERIFY: single web source]. So throughout — lead with your Culligan engineering/PCB work and YouTube backstage work, not Tikkie/consumer fintech.

Full process after this call: Hiring Manager → Portfolio (2 case studies) → Design Challenge → Leadership → Board/GLT. Deep design-craft belongs there, not here.

---

## 0. Role Clarity — Terminology, Requirement Check, Red Flags

*Context for you, not a script. Per "What NOT To Do On This Call" below, don't push any of this into tomorrow's screen — it's here so you understand the role correctly and so it's ready for the Hiring Manager round, where JD-definition questions actually belong.*

**"Greenfield," decoded:** Standard product/tech term — the opposite of "brownfield" (building on top of existing legacy systems/process). The JD line "Service design as a coordinated practice does not yet exist at Adyen... you are not inheriting a playbook, you are writing it" means literally that: no existing service-design methodology, cadence, templates, or stakeholder buy-in for *how this discipline operates* at Adyen. You'd be building the practice itself, not just doing service-design work inside one that already exists. Two-sided: real ownership and visibility, but zero scaffolding or precedent — you're also the one proving the discipline has value at all, with no one to point to who's done it before you. This is structurally the same shape as Story 4 (built the WEAREREASONABLEPEOPLE practice from 0→6) and Story 5 (built Culligan's innovation system from scratch, no established playbook) — a genuine pattern match, not a stretch.

Your own read is correct: this is not service design across Adyen's customer-facing payments product — it's service design *of the internal developer platform*, with Adyen's own ~1,500 engineers as the end users, starting with the Developer Center. The JD supports this directly ("Platform Engineering," "internal tools, workflows, and platform capabilities," "~1,500 engineers").

**"PX," decoded:** Adyen's internal name for its combined Research/Design/Content organization ("Product Experience") — confirmed across multiple current, live Adyen job postings (e.g. "Staff Product Experience Designer," "Product Experience Designer II") [source: web research, Sept 2026 — Adyen careers site + job boards, not an insider confirmation, but consistent across enough independent postings to treat as reliable]. "Socializing it across PX" means: once you've built a service-design method for Platform Engineering, part of the job is teaching/spreading it to Adyen's *wider* design org, not just applying it inside your own team — this is the JD's "multiplier effect" line.

**Do you have "a proven track record of using service design to simplify intricate workflows in SaaS or B2B products"? — Honest gap, not a clean yes.**

Real evidence, ranked:
- **Strongest, genuine match:** YouTube/Unspoken (Story 2) — you mapped the CS agent-side journey and designed/tested Salesforce workflow prototypes with real agents before handoff to development. Salesforce is exactly "B2B enterprise software," and this is directly a service-design-simplifies-an-intricate-workflow story, with real downstream metrics (170K+ cases, +65% agent productivity). But: it's one ~1-year engagement, and YouTube itself isn't a SaaS or B2B company — the workflow you touched (Salesforce) is.
- **Weaker, secondary:** Culligan's IoT dashboard + enterprise sustainability reporting for corporate ESG (Story 1) — B2B-adjacent (used by operations/facilities teams, feeds enterprise ESG reporting), but Culligan is a hardware/IoT manufacturer, not a SaaS company.
- **Not a real match:** Vueling (airline platform vision) and Ampelmann (maritime digital roadmap) were B2B strategy/vision consulting engagements — research and blueprinting, not hands-on workflow simplification you built and shipped.

**Verdict, per this OS's no-fabrication rule:** you have never worked inside a SaaS company, and you have one strong project (not a "track record" spanning years) of service design applied to a B2B software workflow. If this is asked directly — likely only from the Hiring Manager round onward, not tomorrow's screen — the honest, still-strong answer is: *"I haven't worked inside a SaaS company specifically, but the closest match is the YouTube project — mapping and redesigning Salesforce workflows for CS agents, which is exactly this kind of internal, B2B enterprise-software workflow simplification, with 65% higher agent productivity to show for it."* Don't claim broader SaaS/B2B breadth than that — it isn't there.

**Red flags spotted in this JD (for awareness, and for the Hiring Manager round — not tomorrow):**
1. **Scope is still undefined, and support looks thin.** "Could involve," "this role will be yours to shape," "broad, undefined spaces," plus "greenfield... you are writing it" — combined with Chris's intel that Adyen has only 1-2 Service Designers today, this likely means minimal structural support and no internal precedent to validate direction against. This is the same shape of concern Rabobank's interviewer already raised about you directly — "can she operate with less structure/support than her recent YouTube project" (`interview-history.md`). Worth having one tightened, reusable answer to "how do you operate with an undefined mandate and little support," not just a Rabobank-specific one — Story 5's stage-gate-from-scratch and Story 13's "create demand, then set guardrails" are your best raw material.
2. **The posting itself is messy** — two duplicate "Studies show that women..." DEI paragraphs, and multiple garbled words ("launc pad," "Service gn," "chany," "aery touchpoint"). Reads like a copy-paste/formatting error in this specific listing, not a signal about the company — don't over-read it, but also don't treat the JD's exact wording as precise; verify ambiguous requirements verbally once you're deeper in-process.
3. **No resourcing signal anywhere** — no mention of budget, headcount, or a design-ops/research partner. Worth a direct question in the Hiring Manager round: is there any dedicated support (research ops, content, a second designer) or is this a solo build.
4. **Office-first, Amsterdam-based** — already a non-issue for you (Rotterdam, short commute), just confirming there's no hidden relocation/remote catch.

---

## 1. Tell Me About Yourself

**Known pattern (`interview-history.md`):** 4 real live TMAY attempts (Rabobank R1, Rabobank mock, Rabobank R2, RoomPriceGenie R1) have run 2.5–4x over your ~90-second script, reverted to full chronology, and dropped the hard metric. Rehearsal alone hasn't fixed it — rehearse with a hard stop at word count, out loud, timed, and cut yourself off if you hit the limit.

- **Non-negotiable #1:** say "$2.5M" early — don't bury it.
- **Non-negotiable #2 (new):** the "hands-on with hardware and software engineers" line — your one-sentence pre-emptive answer to "too consumer-oriented," dropped in early rather than saved for later.
- Personal color (hometown, consulting-years locations, hobbies, cat) is now folded directly into the core script, per your call to keep it in rather than hold it back — Rotterdam tenure confirmed at 9 years.
- **⚠️ Known-risk decision, made and reaffirmed deliberately (2026-09-13):** `interview-history.md` shows the San Sebastián → Barcelona → Delft → Argentina chronological opening has coincided with a 2.5-3x overrun in 6/6 real live TMAY attempts, most recently 4 days ago at Rabobank R3 — the standing coaching note there is "cut everything before Culligan." You've chosen twice now to keep the personal opening anyway, and to add more of it, since Chris's account suggests this recruiter genuinely wants a casual "who are you" answer. The script below is now ~215 words / ~110-120 sec — noticeably longer than the ~130-word version, so the overrun risk is real and worth going in aware of, not a reason to cut it back on my own judgment.
- **Mitigation:** three hard pivot points to rehearse, not just one — (1) after the cat line, straight into "then I moved back to Rotterdam for good," (2) after the hobbies line, straight into "Most recently..." for Culligan, (3) don't backfill any of Barcelona/Argentina/hobbies once you've named them. Time it out loud with a stopwatch before the call — if you're over 2 min in rehearsal, the Culligan/$2.5M half is what to protect; cut personal color from the end backward, not the Culligan half.

**Voice-over — core, personal color included (~215 words / ~110-120 sec):**

> "I'm originally from San Sebastián, on the north coast of Spain — grew up between the mountains and the sea. I studied product design in Barcelona, then came to the Netherlands for my Master's in Strategic Product Design at TU Delft, and I've been in Rotterdam for about nine years now.
>
> I spent a few years in consulting — first in Argentina, then Barcelona, at a firm called INSITUM, right around when they opened their first European office there. Then I moved back to Rotterdam for good. Outside of work I lift weights and ski when I can — it's how I disconnect and keep a clear head for creative thinking. And fair warning if you see a cat wander across the screen at some point — she does that.
>
> Most recently I was Global Head of Innovation at Culligan, where I built a new connected product category from scratch, from early research through global launch, projected at $2.5M in first-year revenue — and that meant working hands-on with hardware and software engineers, not just designers. Right now I'm freelancing on a service design project for YouTube, on the backstage, agent-tooling side. I'm ready to embed somewhere long-term again, which is what drew me to Adyen."

**Cue-card notes (from the voice-over, at a glance):**
- San Sebastián, north Spain — mountains + sea
- Product design (Barcelona) → Master's, TU Delft
- ~9 years in Rotterdam
- Consulting: Argentina → Barcelona (INSITUM, first EU office)
- Weights + skiing — clear head for creative thinking
- Heads-up: cat may wander into frame
- Culligan — Global Head of Innovation — new category from scratch
- **$2.5M** first-year revenue
- Hands-on with hardware + software engineers
- Now: YouTube freelance — backstage / agent-tooling
- Ready to embed long-term → Adyen

**If she asks a direct follow-up beyond what's already in the script:**
- **More on the INSITUM years:** "INSITUM had a big presence across Latin America — I was there right as they were opening that first European office."
- **More on skiing/weights:** whatever comes naturally — the script line already covers the "why," no need for more detail unless she's genuinely curious.

---

## 2. Ambitions / Preferred Way of Working

- **Overqualification reframe:** Chris's intel that Adyen's Service Design function is young (one or two Service Designers so far) and leans toward Product Design scope is good news, not a concern to hide — you have a direct, real story for exactly this situation (Story 4 and Story 5, `experience-library.md`). This quietly pre-empts `career-plan.md` Weakness 3 (12 years, led a team of ~15) without you having to raise the management-scope question yourself.
- Day-to-day, you like being close to engineering, not handing off a deck — ties directly back to the "too consumer-oriented" fix.
- You actively use AI tools in your own workflow (real and current, not aspirational).
- You prefer hybrid, and you value direct, structured feedback both ways.

**Voice-over — core (~90 words):**

> "My ambition is to keep leading work where I'm close to both the research and the build — I don't want research and design to be separate disciplines, and I don't need a fully mature practice handed to me to do my best work. I've built things from zero twice — a UX research and service design practice from a team of 0 to 6, and Culligan's entire innovation function, including its IoT capability. I'm genuinely energised by that early-building phase. Day to day, I like being hands-on with engineering, and I use AI tools like Lovable and Midjourney to speed up my own prototyping and synthesis."

**Cue-card notes (from the voice-over, at a glance):**
- Ambition: stay close to research AND build
- Research + design — not separate disciplines
- Don't need a mature practice handed to me
- Built from zero twice: agency (0→6) + Culligan innovation/IoT
- Energised by early-building phase
- Hands-on with engineering, day to day
- AI tools: Lovable, Midjourney — speed up prototyping/synthesis

**If she goes deeper (backup — Adyen Formula behavioral questions, not confirmed to come up but ready) [VERIFY: aggregated source]:**

- **"Tell me about a time you took quick ownership of a project or decision"** (Adyen Formula #3/#8 — "launch fast and iterate" / "create our own path"): "I stepped in to lead a PCB redesign for one of our connected products during a component shortage, when the product's PM didn't have the technical depth to manage the pivot — coordinated hardware engineers and our manufacturing partners directly, with no playbook to follow." (This one lives only here now — the Why Adyen script below no longer uses it, to make room for the design-thinking-coaching material.)
- **"How do you handle giving or receiving direct, candid feedback?"** (Adyen Formula #6 — "we talk straight"): "At my last agency I managed and coached a team of designers and researchers — I built the feedback loops and maturity models myself, so direct feedback has always been a two-way structure for me, not something I only expect from others."
- **"Have you integrated AI tools into your design synthesis or research process?"**: "Yes, actively — I use Lovable, Stitch, Midjourney, and Zapier for prototyping, I completed IDEO U's 'Prototyping with AI' and DeepLearning.AI's Data Analytics certificate this year, and I built findsunspot.com — a real-time app using live weather and shadow-modelling data — with vibe coding."

---

## 3. Why Adyen

This is the section that changes most given Chris's "too consumer-oriented" feedback — lead with internal/technical proof, not consumer fintech.

- **Lead proof points, all real and traceable:** the lack of scaffolding for Service Design at Adyen (Section 0's "greenfield") as a genuine draw, not a caveat — you've built the practice itself from zero before, not just done the work inside one; Culligan IoT dashboard (predictive stocking, remote firmware updates, proactive maintenance) and hands-on collaboration with hardware/software engineers; leading a team of ~15 that included internal engineers and software dev partners, mentoring a junior dev to senior (he now leads a product area); teaching design thinking to other disciplines as a recurring pattern across your career — INSITUM (ran design thinking training and bootcamps directly for clients), WEAREREASONABLEPEOPLE (coached the researchers/designers building that practice from scratch), and Culligan (educated internal teams on design process and deliverables).
- **Most current and most relevant:** YouTube/Unspoken — currently mapping agent tooling and internal support workflows, designed and tested Salesforce workflow prototypes directly with agents before handoff to development. Real downstream metrics: 170K+ cases now running through the new system, agent productivity up 65%, CSAT at 4.5 (+0.5 above target). This is the closest thing in your portfolio to actual DevEx work, and it's live right now.
- **Natalja's intel (connection-tracker.md), still your most differentiated point:** at Adyen, designers are expected to do their own research, not hand it off to a separate function — matches exactly how you work.
- **Adyen Formula resonance, if culture comes up here:** #3 "we launch fast and iterate" and #8 "we create our own path" — building Culligan's innovation function from scratch, with no established playbook, is the honest tie.
- **Fintech/Tikkie — secondary, only if asked directly, don't lead with it:** "I've also worked in fintech directly — I led UX research for ABN AMRO's Tikkie, where we validated 4 monetization models and shipped one to production with a board-level business case."
- **Freelance-to-permanent bridge:** "I'm ready to embed somewhere long-term again."

**Voice-over — core:**

> "What draws me to this role specifically is that Service Design doesn't exist yet as a coordinated practice at Adyen — there's no scaffolding, which means I'd be building the discipline itself, not just applying it inside one that already exists. I've done that before: at Culligan I built the full IoT dashboard, working hands-on with hardware and software engineers. And teaching design thinking to other disciplines is something that's run through my whole career — at INSITUM I ran design thinking trainings and bootcamps directly for clients, at WEAREREASONABLEPEOPLE I coached the researchers and designers building that practice from scratch, and at Culligan I educated internal teams on design process so they could own more of it themselves. On my current project I'm on the backstage side too — mapping agent tooling and internal support workflows, and that work is now driving a 65% jump in agent productivity. I also like that at Adyen, designers do their own research rather than handing it off — that's exactly how I work. I'm ready to embed somewhere long-term again, and this is the kind of ground-floor, technical problem space I want to be doing that in."

**Cue-card notes (from the voice-over, at a glance):**
- Draws me: no scaffolding for Service Design — building the discipline itself
- Culligan: IoT dashboard + hands-on with engineers
- Teaching design thinking to other disciplines — INSITUM bootcamps, WARP coaching, Culligan internal education
- Current: backstage — agent tooling / internal workflows
- +65% agent productivity
- Adyen: designers do own research — matches how I work
- Ready to embed long-term — right problem space

**If she asks more specifically (backup) [VERIFY: aggregated source]:**

- **"How do you approach designing for highly technical users like developers or engineers?"** → "On the YouTube project I mapped the agent-side journey, not just the consumer side — diary studies, immersions, journey mapping — to surface friction in agent tooling and internal workflows, then designed and tested workflow prototypes directly with the people who use them before handoff to development. At Culligan it was the IoT dashboard — designing the operator/maintenance-facing side, not just the consumer touchpoint."
- **"Tell me about facilitating cross-functional alignment between engineering and product."** → The PCB redesign plus the Agile-rituals collaboration with engineering/PM/vendors at Culligan.

---

## 4. What Do You Already Know About Adyen

- **Core identity:** a single unified platform — one integration for acquiring, payments infrastructure, and increasingly issuing and money movement — rather than a patchwork of bolt-on providers.
- **Recent momentum (H1 2026):** net revenue up 21% (constant currency), full-year guidance of 21-23% growth; landed OpenAI as a new customer, expanded with Toast.
- **Platform expansion beyond payments:** acquired Talon.One (loyalty/promotions) and Orb (usage-based billing), launched Intelligent Money Movement and "Adyen Agentic" — directly relevant to a Platform Engineering Service Design role, since a bigger platform surface means more internal systems needing coherent service design.
- **Scale:** 4,000+ employees, 115+ nationalities, 28 offices.
- **The Adyen Formula — all 8 principles** (from the company culture page): we build to benefit all customers, not just one · we make good decisions considering long-term benefit · we launch fast and iterate · winning is more important than ego, we work as a team across cultures and time zones · we don't hide behind email, we pick up the phone · we talk straight without being rude · we seek out different perspectives to sharpen our ideas · we create our own path to grow toward our full potential.

Use 2-3 facts, don't recite all of them.

**Voice-over:**

> "What stands out to me about Adyen is the single unified platform — one integration for acquiring, payments infrastructure, and increasingly issuing and money movement, instead of a patchwork of providers. And you're pushing past pure payments now — the Talon.One and Orb acquisitions, Intelligent Money Movement, Adyen Agentic — which for a Platform Engineering design role tells me the internal systems are only going to get more complex, not less. I also read about the Adyen Formula — 'we launch fast and iterate' and 'we create our own path' really resonated, that's what building an innovation function from scratch at Culligan felt like."

**Cue-card notes (from the voice-over, at a glance):**
- Single unified platform — one integration (acquiring, infra, issuing/money movement)
- Not a patchwork of providers
- Beyond payments: Talon.One + Orb, Intelligent Money Movement, Adyen Agentic
- → internal systems getting more complex
- Adyen Formula: "launch fast, iterate" + "create our own path"
- Ties to building Culligan's function from scratch

[Source: web research, Sept 2026 — Adyen H1 2026 earnings coverage, Built In culture pages]

---

## 5. Practical Logistics

Per Adyen's email, expect: office-first hybrid setup, notice period, and whether you're interviewing elsewhere. Each is really its own one-liner:

- **Hybrid:** Amsterdam-based, office-first. You're Rotterdam-based — commutable, no issue.
- **Notice period:** you're freelance — no contractual notice period holding you. Realistic start is within a few weeks of agreeing terms.
- **Interviewing elsewhere:** yes, a few live processes — stay general, being selective is the point, no need to name companies unless pushed.

**Voice-over:**

> **Hybrid:** "I'm based in Rotterdam, which is a short commute to Amsterdam — office-first hybrid works fine for me."
>
> **Notice period:** "I'm freelancing, so there's no notice period holding me. Realistically I could start within a few weeks of us agreeing."
>
> **Interviewing elsewhere:** "Yes, I'm in a few live processes right now. I'm being selective, and this one stands out to me because of the problem you're solving."

**Cue-card notes (at a glance):**
- Hybrid: Rotterdam → short commute, office-first fine
- Notice: freelance, no contract, few weeks to start
- Elsewhere: yes, a few live processes, selective

---

## 6. Compensation Expectations

**The numbers:** Adyen's band for this role is **€90K–€120K**, per Chris's direct, recent, same-role intel. Chris anchored at €110K (excluding vacation/holiday allowance) and was told he was within range — €120K is the real ceiling. [VERIFY: broader web research also surfaced a €90K-€130K+ "total compensation" figure from aggregated sources — less reliable than Chris's first-hand account since it's not role/level-confirmed and likely blends base + equity/bonus. Treat Chris's €90-120K as the number that matters; the wider figure is directional upside only, not something to anchor on.]

**Your position:** your own target from `career-plan.md`/`qa-master.md` is €100-110K permanent, floor €80K. You have 12 years of experience — more senior than a typical candidate for a band topping at €120K. **Don't lowball yourself into the middle of the band — anchor near the top.**

**Voice-over:**

> "Based on my research and my 12 years of experience — including building research and design functions from scratch, team leadership, and end-to-end product launches — I'm targeting €115-120K gross for a role at this level. I know that's toward the top of a typical band, and I'm open to discussing the full package."

**Cue-card notes (at a glance):**
- Target: €115-120K gross
- Basis: 12 yrs, functions from scratch, team leadership, launches
- Top of band — open to full package
- If she confirms band: €120K in line — don't retreat
- Don't share freelance hourly rate (€140/h reads as €280K+)

**If she confirms the €90-120K band back to you (likely, per Chris's experience):**

> "That's helpful to know — €120K is right in line with where I'd expect to land given the scope and seniority."

---

## 7. My Questions to Them

Pick 1-2, don't ask all three:

> "What prompted Adyen to create this role now?" *(replaces the old "how is Service Design evolving as the platform expands beyond payments" question — that one wrongly assumed an existing, evolving SD function, and wrongly tied this internal-developer-platform role to Adyen's external product expansion (Talon.One/Orb/Agentic), which Section 0 confirms is a different, unrelated part of the business. This one is safe for a recruiter screen and doesn't touch role-definition gaps.)*

> "What does the office-first hybrid rhythm actually look like week to week?"

> "Since this is a fairly greenfield Service Design role in Platform Engineering, what does success look like in the first 6 months — is it more about establishing the internal service-mapping process, or shipping specific DevEx improvements?" *(new — DevEx-tailored, given the role recalibration)*

---

## What NOT To Do On This Call

- Don't push on JD inconsistencies or role-definition gaps, even ones you've spotted — Chris's recruiter deflected this to the hiring manager. Save it for that round.
- Don't over-prepare a long, structured pitch — this is a "get to know you" conversation. The personal color in Section 1 is meant to warm up the tight core script, not extend it.
- Don't lead with Tikkie/consumer fintech anywhere — Chris's specific feedback was that this reads as too consumer-oriented for this role.

---

## Pre-Call Checklist

- [ ] Time the Section 1 core script out loud with a hard stop — target 110-120 seconds, and rehearse the three pivot points (cat → Rotterdam, hobbies → Culligan, no backfilling)
- [ ] If you run over 2 min in rehearsal: cut personal color from the end backward, protect the Culligan/$2.5M half
- [ ] Have the PCB redesign and YouTube agent-tooling stories as your first answer to any "technical systems" question — not Tikkie
- [ ] Have the €115-120K number ready to say without hesitation
- [ ] Pick 2-3 "what I know about Adyen" facts, not all of them
- [ ] Pick 1-2 closing questions, not all three
- [ ] After the call: log it via `/interview-debrief` so this feeds Round 2 prep and your ongoing TMAY-pacing pattern tracking
