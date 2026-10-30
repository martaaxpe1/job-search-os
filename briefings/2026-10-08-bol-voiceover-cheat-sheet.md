# The end of average · story cheat sheet
bol · Principal Craft Lead UX · Thu 08/10/26, 14:00 · Maurice + Matthew

**Bold line** = the argument of the slide. Bullets = what to hit. → = the bridge to the next slide.

**Spine:** AI makes average free → designers make bol specific → three shifts → two standards (behaviours + AI-team) → built like a product → proven in one squad → behaviour first, product later → better bets → own what AI can't average.

**Weak point thread (product design in a large org):** slide 04 (shared core, local fit) · **slide 08 (the bridge)** · slide 12 (8 BUs, none reporting to me).

---

## 01 · The end of average
**AI is excellent at the average. bol wins on the specific.**
- Todd Rose: the average person doesn't exist
- Systems built for "average" fit nobody
- bol's edge: the specific reality of its shoppers and partners

→ So what does that mean for design?

## 02 · AI makes average free
**Design's value moves to what AI can't produce.**
- Average is free for every competitor too
- Designers as makers: artefacts in code, on real data → stronger decisions, earlier
- The artefact is how product, engineering and data think together → fewer handoffs
- Saved time goes to curiosity: building what's next, for people, with people

→ But saved time doesn't redirect itself.

## 03 · Three shifts
**Time saved only becomes discovery time if the foundation is strong.**
- **Screens → Intent:** agents need the design system, bol's design language, guardrails (what we accept, accessibility, how it should feel)
  - Agents should move pixels the way an experienced bol designer would
  - Without it: time goes into reviewing output. Demoralising, and slower
- **Handoffs → Dialogue:** less explaining, the artefact on the table
- **Domains → Journeys:** needed when experiences become non-deterministic, for shoppers and partners

→ How do we make it real?

## 04 · Two standards make it real
**How designers work + an AI-team that guards bol's standards.**
- AI is already in every team. The change is agreeing how we work with it
- They need each other: behaviours without tools = a poster; tools without behaviours = generic, faster
- Shared core, local fit: same behaviours and core crew everywhere; each domain adds its own evidence, data and crew members
- Watch what stays in a domain and what moves into the universal system
- Co-written with designers, researchers, UX writers = "build it with your users"

## 05 · Four behaviours
**If we ask for behaviours, bol owes people the conditions to build them.**
- Adaptability · agency · curiosity (already strong in designers) · taste
- bol provides: **Access** (tools, repos, data, prototyping env) · **Time** (explore, study great work, critique real examples) · **Safety** (permission to experiment)
- Specific enough to coach and measure
- Hypothesis: competency expectations, decided with the Heads of Design

## 06 · "Quality is the hard bit"
**The AI-team checks the basics. Designers own the intent.**
- Matt's words: defining quality UX at bol is "the hard bit"
- Made with the designers who use it → trust between crafts; engineering stops rejecting work for missing states and unmapped tokens
- **Commands:** designers steer AI in natural language, and can still co-design by hand
- **Crew (sub-agents):** archetypes with a role and a mission, one per failure mode:
  - Brand drift · Context blindness · Review fatigue
  - ⚠ Your notes name only two. Don't drop context blindness: English placeholders instead of Dutch retail reality, missing partner edge cases
- Crew flags and proposes fixes; designer keeps the judgement (autonomy maybe later)
- Shared governance: **design owns intent** (agent profiles, command logic, heuristics) · **engineering owns infrastructure** (token registry, data feeds, CI checks)
- Every rejection becomes a new rule → the design system becomes an acceleration layer for AI

## 07 · Designers co-create the AI-team
**Build it like a product, with designers as its users.**
- Where to start → test → pilot → scale
- Business case: every crew member starts from a measured failure → first bets where rework costs most
- Return: fewer rejections by engineering; designers co-author it
- **Partner example (hypothesis):**
  - AI makes a neat bulk price grid with short, perfect titles
  - Real seller: 150-character ALL CAPS title, missing images → design breaks, caught in review
  - → Partner stress tester, persona "chaotic seller", flags what breaks
  - Pilot alongside the universal agents (accessibility, final reviewer)
  - Then: can any data-heavy team use it?
- *Optional, for Maurice:* "Where does that same seller data end up in the consumer journey?"

## 08 · From idea to a live product, without a dev team
**I already work this way. Same idea, small scale.**
- Built for the Unspoken Summit (this weekend): idea → live, on my own
- Same sequence: design system → spec + rules file → build → test → run
- Every designer a maker; handoffs → dialogue: I'd open the engineering conversation with a working thing, not a spec
- Biggest surprise: how fast I reached a version I was happy with
- Next test: real users, this weekend

**The bridge (your XXXX), bullets:**
- Small scale, yes. At bol's size the build is the easy part; making it work across squads that don't report to you is the hard part
- I've done that part: Culligan IoT started as a few self-funded pilots → today 80% of Culligan's commercial drinking water products are built on it
- Lesson: building it *for* the business units created dependency. What scaled: a sandbox on shared infrastructure, each business owning its own integration
- At bol, same split: designers make in a sandbox on bol's real components and data; engineering owns production
- First: weeks inside squads in both domains, learning how bol actually ships

**The bridge, spoken (~45 sec):**
> Of course this is at very small scale. At bol's size the build is the easy part. The hard part is making it work across many squads that don't report to you, and that's the part I've done before. At Culligan, IoT started as a few pilots we self-funded, and today 80% of Culligan's commercial drinking water products are built on it. What I learned is that building it *for* the business units created dependency. What scaled was a sandbox on shared infrastructure, where each business owned its own integration. At bol I'd apply the same split: designers make in a sandbox, on bol's real components and data, and engineering owns what goes to production. And before proposing any of it, I'd spend my first weeks inside squads in both domains, learning how bol actually ships.

**If they push: "You haven't done product design inside a large product org."**
- One clause, no more: "Not inside an e-commerce platform, no."
- YouTube: design inside a big tech delivery machine. The product team owned the backlog, the implementing teams adopted it → 170K+ cases on the new console, agent productivity +65%, CSAT 4.5
- lign.ai: once components lived in code with tokens (the engineer's work), engineering conversations moved from visual details to user flows
- "I'd learn bol's domain from its data and its researchers. That's how I've learned every domain I've worked in."

## 09 · Launch the change like a product
**No line authority, so the change has to be pulled, not pushed.**
- Same product-launch mindset as the agents
- Influence starts with curiosity: how do designers work today, what do they struggle with? No one-size-fits-all
- Influence grows through exchanges: actions, pilots, open conversations
- **Sceptics first:** they uncover blind spots and make it credible ("if the sceptics shaped it, others trust it")
- Enthusiasts bring energy; sceptics give it direction
- Say it out loud: some designers resist a change that seems to threaten the craft that made them good

## 10 · Prove it in one squad
**One shared bottleneck, one squad, one gate. Then domains adapt it.**
- First 6 months: pick a bottleneck common to the domains → build that part of the AI-team → one squad
- Gate signals: more decisions on working artefacts · less review time · more discovery time
- Hold → decide what scales. Don't hold → back to audit and spec
- Honest conversation about what doesn't work and what changed that we didn't expect

## 11 · Rituals + shared test bed
**Two concrete actions keep the change open and moving.**
- **Rituals (craft lab):** I open with my own findings and failures
  - The change adds cognitive load. Tired from admin ≠ tired from making something that lands
  - A space to unload frustrations and share wins
- Energy risk: track contributions, demos, rules changed. Two quiet cycles → ask the sceptics why → shrink, change or stop
- **Test bed, shared by all five crafts:** lines are blurring, so we learn each other's expertise
  - Any change to tools or ways of working goes through it first: simulated users + real data
  - Latest commands and crew live here first; I stress-test as user zero
  - New AI design and dev tools get tried early, safely
- *If research pushes back:* simulated users decide what's worth taking to real users. They never replace research
- Open question: if making is democratised and the lines blur, how do roles get redefined?

## 12 · Culligan's first design language
**Adoption was the hard part, because nobody reported to me.**
- Led the programme with brand; owned the UX layer; co-designed touchscreen, indicator and accessibility toolkits with the agency; approved the work
- Reviews = onboarding, especially for sceptics: a forum for concerns, and designers learned domain expertise
- Attendance grew because people saw the work getting better
- Short term: a category team redesigned its flagship on it voluntarily; teams trained
- Long term: standard for every new product; 8 business units (home + commercial) use it in their roadmaps
- Number to land: the first product built on all six layers won a **Red Dot in 2026**
- *Optional parallel:* "8 BUs, each with its own product team and roadmap, none reporting to me. The closest thing in my career to bol's domains, on a slower clock."
- What I'd change: one central brand gate works at hardware speed, not digital; quality and taste guardrails weren't built into the language itself → that's what the AI-team encodes

## 13 · Success is designers working differently
**It shows in how people work before it shows in the product.**
- Keeps leadership patient: early, honest signals instead of a promise
- Slowly but steadily: less rework, better output

## 14 · Behaviour and time first, then quality, then product
**The signals move in that order.**
- All targets are hypotheses, calibrated with the Heads of Design against a baseline
- Quality: AI output accepted first pass ↑ as work sent back for basics ↓ → guardrails, skills, evals pay off
- People: bol's engagement survey + a pilot satisfaction measure
- Contributions: designers writing their own commands and crew = the AI-team is becoming theirs
- **Risk 1, money:** token caps are common; I don't know bol's approach yet → token budget per squad, shared proven commands, training on LLMs
- **Risk 2, compute and energy:** reported next to time saved, in line with B Corp

## 15 · Discovery gets shorter and richer
**This is where it pays off: better product bets.**
- Kill your darlings because the evidence says so, not because time or budget ran out
- **Screens → Intent = time to think:** basics leave the review; hours go to framing and exploring new behaviours
- **Handoffs → Dialogue = shorter cycles:** working artefact on real data → decision in days → cheaper tests, more of them
- **Domains → Journeys = richer cycles:** whole-journey research and analytics → hypotheses about what shoppers and partners experience
- For bol: more bets tested, wrong ones stopped early, right ones built with confidence. Products stay distinct when every competitor has the same AI tools

## 16 · Own what AI can't average
**Back to the end of average: intent, conversation, the whole journey.**
- First move, assumption: reviews of AI-assisted work are eating the Heads of Design's week
- Ask Matthew: is that the right hurdle? **Then let him answer**
- Why designers care: curiosity to build what's next. Many worry about their craft and future; this is where their human perspective counts most
- Why me: an innovation brief wearing a design hat. I've built practices before; this time the practice is for designers
