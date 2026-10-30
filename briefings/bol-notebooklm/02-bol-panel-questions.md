# bol case: questions Matthew and Maurice could ask

Updated 07/10/26 to match the final voice-over (`2026-10-06-bol-voiceover-20min.md`). Where this file and the voice-over differ, the voice-over wins.

Changes since the first version: Culligan's design language is confirmed at eight business units. The IoT sandbox, the YouTube metrics story and the Service Design Coach lesson are now the named back-pocket material for M4, M10, X7, X9 and X10. Alex and the practice-building at the earlier agency are no longer offered unprompted. The smart bottle is framed as paused for resourcing, not killed on evidence. The token-cost answer now follows slide 14.

Back-pocket stories, and which question opens the door:
- IoT sandbox at Culligan: M10, X9, M12.
- YouTube metrics that drove workarounds: M1, X7.
- Service Design Coach lesson: M4.
- Alex: only if asked for a coaching example (M13 or an open question on developing people).
- Smart bottle: X3, and only with the resourcing caveat.
- Tikkie: X3.
- lign.ai workflow: M6.
- Culligan stage gates: X7.
- PCB redesign: M3, M6.

For the Q&A rehearsal. Each question has: **why they'd ask it**, **where the answer lives in the deck** (slide number plus the lines to use), and **Gap** where the deck has no prepared answer yet. For a gap, don't invent an answer: say it's a gap and point to the nearest real material named here.

Who's in the room:
- **Matthew Harper**, Head of Product Design, currently covering this role ad interim. His team released bol's partner agent in beta and learns from traces and evals. He's running a pilot on two ways of working. He owns the KR "six hours back per person per week". In the 16 September interview he asked: "did she just oversee it?" (Culligan), "have you done this at scale, with larger teams and different processes?", how she'd link the work to business objectives ("how would you talk in their language?"), how she'd get designers on board "in the weeds", and about committing and reviewing code. His style: "how did you navigate that practically? What did you do?"
- **Maurice Jongerius**: senior bol leader; his exact current role is to be confirmed. This round was originally planned as the business-case round. Treat him as the non-design leadership audience the brief says she'll be judged on.

Ordered by likelihood within each group.

---

## Matthew

### M1. "Our KR is six hours back per person per week. You're saying hours freed is the wrong measure. So what do I report upward?"
- Why: it's his KR, and slide 3 openly questions it.
- Answer (slides 3, 7, 14): not wrong, incomplete. "Hours freed measure speed, not whether the work got better, and if the time isn't redirected on purpose it gets absorbed back into delivery." Keep the KR, and pair it with where the hours go: share of design time on discovery (+10 pts at month 6, +20 at month 12) and work sent back for basics (−30%, −60%). Slide 7, reason 3: the hours freed are steered into discovery instead of being absorbed back into delivery.
- Back pocket: YouTube support agents. Their performance metrics inadvertently drove workarounds and call deflection, so the number looked fine while the work got worse. That's why every speed signal is paired with a quality or people signal.

### M2. "How does this fit the pilot I'm already running, with the two ways of working? Keep it, merge it or replace it?"
- Why: his pilot tests (a) staying within craft boundaries but sharing AI tools and artefacts, and (b) any craft executes, with accountability staying with the original craft. It measures quality and people's satisfaction.
- Answer (slide 10): "I'd observe workflows and build on the pilot Matthew is already running." M1–2 people row: "Listen, sit in reviews, join the ongoing pilot." Slide 14: people signals use the pilot's satisfaction measure. Slide 6: one contribution workflow where design and engineering both review a code change, which keeps accountability with each craft.
- Gap: the deck doesn't say which variant she backs. Safest move: don't pick a winner. Ask him: "What would the data need to show for you to say variant (b) is working?"

### M3. "Who actually builds the AI-team? Agent definitions, a headless browser, CI checks: that's engineering capacity. Where does it come from?"
- Why: he raised capacity limits and "budgets for tools we never used".
- Answer (slides 6, 7, 11): design owns intent (agent profiles, commands, heuristics); engineering owns infrastructure (token registry, data feeds, CI). Tool access is deliberately minimal: "read access to tokens, staging data, a headless browser, nothing more." One crew member at a time, starting from a measured failure (slide 7). What engineering gets back: it stops rejecting work for missing states and unmapped tokens. The test bed is where the crafts build it together (slide 11).
- Gap: no estimate of engineering effort or tool budget. Be ready to say the first crew member is small and the M4 gate decides whether it goes further.
- Nearest real material: the PCB redesign at Culligan. During a component shortage, Marta coordinated hardware engineers and the Chinese manufacturing partners to replace the component and restore supply. It shows she can work with engineering at the technical level.

### M4. "Our designers aren't in repos yet. How do you upskill them without taking time from delivery?"
- Why: he called upskilling against craft time "a tightrope" and named repos, code review and evals as the skill gap.
- Answer (slides 5, 10): what bol owes people: access, time, safety. Office hours when stuck (M5–6). The pilot squad works with the crew every day, so learning happens on real work.
- Gap: the deck has no explicit upskilling plan. Nearest real material: the 2024 Service Design Coach lesson. Theory needed heavy adaptation to each person's business context, so it worked best as a light common foundation (some reading), then hands-on conversation about their real day-to-day problems, with transferable examples and red flags. Marta would go further in that direction next time.

### M5. "What did you do yourself at Culligan, and what did the agency do?"
- Why: his R2 question was "did she just oversee it?"
- Answer (slide 12): "I owned the UX layer: who the users are, their journeys, and one UX character adapted to each context." If asked: co-designed the touchscreen, indicator and accessibility toolkits with the agency, and approved the work. The three cards on the slide (one colour, one meaning; motion that tells the truth about urgency; rules from real use) are the craft detail.

### M6. "Could you review a designer's pull request? What happens when a designer changes code they don't understand?"
- Why: he asked about committing and reviewing code in R2.
- Answer (slides 3, 6, 8): risk answer from slide 3: the sandbox, plus guardrails and co-review owned with engineering. Slide 6: output arrives as a code change and design and engineering both review it before it merges. Slide 8 is the hands-on proof: "I plan, review and test", "6 packages I can follow", and on the slide itself, "without deep code knowledge". Be honest about that line.
- Back pocket: lign.ai. Marta wireframed and wrote the agents' instructions, a brand designer applied branding to the components, and the engineer put them in a code library with design tokens (Marta did not build the token pipeline). She then tested on a coded, branded prototype, and conversations with engineering were about user flows, not visual details.

### M7. "Why the partner squad for the first pilot? And why that example?"
- Why: the partner domain is close to his own team.
- Answer (slides 7, 10, 16): the first move is tested in a partner squad. The pilot is one journey with a known pain, chosen with the Heads of Design. The bulk price grid is framed as a hypothesis on the slide: generic AI draws short, perfect titles; sellers upload 150 characters in capitals.
- Gap: the bulk price grid pain isn't confirmed with the Partner domain. Say so if he challenges it, and ask him whether it's real.

### M8. "Customers are shopping through agents now. Your plan is about designers' tools. When do designers start designing agent behaviour?"
- Why: the case brief names non-deterministic products as one of the four forces, and his team is learning from traces and evals on the partner agent.
- Answer (slides 2, 3, 7): why now on slide 2: the shopper agent is live and the partner agent is learning from traces and evals. The Discovers pillar: "shaping agents people trust". Slide 3, if asked: in 2027 designers make it real and design agent behaviour. Why production first: "You can't move time to discovery without compromising quality unless production is fixed first." Slide 7: the same five steps later work for agent behaviour; the partner agent in beta is a candidate after month 12.
- Gap: this is the thinnest point against the brief. Have one clear sentence on why agent behaviour comes after month 12, not before.

### M9. "How do you choose the sceptics, and what if they sink the pilot?"
- Why: in R2 he connected "start with the sceptics" to the adoption curve himself.
- Answer (slides 9, 10): sceptics "often defend the quality bar and debate until proven wrong"; "their objections show where the change breaks". Signal in M2–4: "Sceptics name failures the crew should catch." If it fails: the M4 gate is continue, change course or stop. "If the data says the standard is wrong, the standard changes."
- Gap: no selection criteria for which sceptics. Decide your answer.

### M10. "Have you done this at scale, with larger teams and different processes?"
- Why: he asked it in R2 and it was left as a gap.
- Answer (slides 9, 12): at Culligan nobody reported to me, and the language was adopted by the product category teams across eight business units. Long term it became the standard for every new product (mandatory, with marketing as the approval gate), and the bottle-free cooler won a Red Dot in 2026. This role scales through standards, tools and community, not reports.
- Use first: the IoT sandbox. Business units were sceptical, with no mandate or budget, so we self-funded a few pilots. After 2 or 3 showed value, the BUs funded it and put IoT on their own roadmaps. Then European markets pushed for bespoke builds. Marta mapped differences against commonalities, held 1:1s with each business, and found most needs were an API tweak, so components stayed universal. A flexible sandbox on shared global infrastructure, with the BUs owning their integration. Today 80% of Culligan's commercial drinking water products are built on it, and more businesses keep plugging in.
- Lesson if asked: offering to build it for them created dependency. The firm handover was the harder skill.

### M11. "High agency, high taste: those are tech-industry hiring labels. How do they fit bol's culture?"
- Why: bol's culture is community-led, and the labels come from outside it.
- Answer (slides 4, 11): the wording gets co-written with designers, researchers and writers, "the people who'll live by them". The rituals are built on bol's own beliefs: bold, curious, make it happen, stronger together. Each behaviour has a "what it's not" (agency is not taking the credit; taste is not pixel policing).

### M12. "Domains to journeys. Are you proposing to reorganise my teams?"
- Answer (slides 3, 10): "Could shift" the operating model. Domains keep their systems; journeys are owned with product; "Change structures only after the pilot shows it works." Boundaries: craft direction is mine to lead, delivery and performance stay with the domains, "so nobody loses territory."
- Back pocket: the IoT sandbox is the same pattern. A shared core stays universal, each business adds its own integration on top.

### M13. "Many designers are worried about their craft and their future. What do you say to them?"
- Why: slides 15 and 16 name it directly, and Matthew's team will be the ones living it.
- Answer (slides 15, 16): "The role will change either way. The opportunity is for designers to shape it." Designers have to be part of the change, including the decisions on how things will work: "done with them, not to them." What designers want is to use their curiosity to build what's next for people, and that is where their human perspective counts most.
- Back pocket, only if asked for a coaching example: Alex. He came from a hierarchical team, had nine years of field knowledge, and struggled to speak up. Marta created explicit moments where his opinion was the deciding one until challenging senior stakeholders became normal. He now runs the full flavoured-water category. Don't offer it unprompted.

---

## Maurice

### X1. "What's the business case? If we fund this, what do we get back, and when?"
- Why: this round was planned as the business-case round, and the HR assessment named business insight as a development area.
- Answer (slides 7, 13, 14, 16): the chain on the close: vision builds craft capability → standards turn it into team behaviour → the change approach makes it show up in the product → business result: fewer wrong bets built, less budget on rework, shoppers and partners keep choosing bol. Slide 7's six reasons (investment case, small reversible bets with gates, return in product terms, protects what makes bol distinct, scales by contribution not headcount, honest about compute). Timing: behaviour and time move in year one; product outcomes lag two to three quarters.
- Gap: no euro figure. Honest line: the baseline in month 1 comes first, then targets are calibrated with the Heads of Design.

### X2. "What do you need from us? What's the ask?"
- Answer (slide 2, if asked): "Invest in guardrails and skills now, so the hours AI frees go into discovery instead of more output." Plus access: tools, repositories, data and a safe sandbox, agreed with Engineering and Analytics (slides 3, 5).

### X3. "Why should the product organisation care where designers spend their week? We care about conversion and speed to market."
- Answer (slide 15): "a product innovation engine": more bets tested, wrong ones stopped before engineering builds them, right ones built with confidence. Month-12 targets: 3× hypotheses tested per squad, idea to tested hypothesis halved. "Kill your darlings because the evidence says so, not because time or budget ran out."
- Nearest real material: Tikkie. 10 experiments in 3 months, 4 revenue models validated, cashback shipped to production, and a board decision backed by evidence.
- Careful with the smart bottle (Story 11): it was paused for resourcing, not killed on evidence. Use it only to show how Marta keeps ahead-of-their-time work alive as an artefact, not as proof of the evidence-decides claim.

### X4. "'The end of average': but serving millions of customers well is exactly our business. Isn't average good for us?"
- Answer (slides 1, 2, 6): AI makes the average free for everyone, so it stops being an advantage. "Specific" means bol's real data and reality: Dutch retail copy like "Morgen in huis", partner edge cases, bol's tokens and tone of voice encoded in the crew. Todd Rose: designing for individuals, not the average person.

### X5. "If designers own journeys, where does that leave product managers?"
- Answer (slides 3, 11): designers own journeys "with product". The open question on slide 11, "If making is democratised, how do our roles get redefined?", is for the crafts to decide together, not for design alone.

### X6. "Every competitor gets the same AI tools. Why build our own AI-team instead of waiting for the vendors?"
- Answer (slides 7, 11): reason 4 on slide 7: bol's tokens, tone of voice and seller reality are encoded in the crew, which no vendor ships. The test bed's second lane scouts vendor tools as they ship; "the useful ones become commands or crew members, the rest we drop without cost."

### X7. "How will we know in six months that it's working, and what would make you stop?"
- Answer (slides 10, 14): gates agreed upfront. M4: deciding more on working artefacts, and did discovery time grow? Continue, change course or stop. M6: 30% of review decisions on a working prototype, 30% of AI output accepted first pass, discovery +10 pts, cognitive load stable. "If they hold, we scale; if not, we go back to audit and co-creation." Each speed signal is paired with a quality or people signal, and I don't track weekly active users of the commands: usage isn't value.
- Back pocket: Culligan's three-stage funnel. An 8-week time-boxed POC with no BU involvement and a leadership gate, then a shared gate on fit inside a BU, then handover with the BU owning decisions. It shows the gates are something Marta has run before.

### X8. "What's the biggest risk in your plan?"
- Answer (slide 3, if asked): "Building the AI-team can eat the time it should free, so start with one journey and change course if the rejection rate hasn't dropped by the M4 gate." Second risk: rising cognitive load (slide 11: tired from admin is not the same as tired from making something you see land; slide 14: if load rises and satisfaction doesn't, the change was badly designed).

### X9. "You'd be giving direction to Heads of Design who don't report to you. What happens when one of them says no?"
- Answer (slides 9, 10, 16): the change has to be adopted, it can't be announced into place. Relief first: the first move takes the basics off their desk. Boundaries: delivery and performance stay with the domains. The design council co-owns the rules.
- Gap: no escalation path in the deck. Use it as a question back: "When craft direction collides with a domain's delivery priority, who decides today?"
- Nearest real material: Story 12 (Brand as Blocker, a constraint that wouldn't move), and the IoT sandbox, where Marta was sensible about the relationship but firm about the boundary.

### X10. "What does it cost to run? You mention compute."
- Answer (slide 14 risk box): many companies now cap tokens per employee, because without a strategy and the know-how, AI gets expensive fast. "I don't know how bol handles this today, so I wouldn't assume." The framework needs a token budget per squad, proven commands shared instead of everyone prompting from scratch, cost per tested hypothesis in the quarterly read-out, and training in using large language models well. Compute and energy are reported next to time saved, in line with bol's B Corp commitment.
- Gap: no cost estimate. Say it's something to look at together.

### X11. "Why you? You haven't worked in e-commerce."
- Answer (slide 16): "It's an innovation brief wearing a design hat. I've built practices from zero before, and at Culligan I did it inside a company where nobody reported to me." Concede e-commerce in one sentence, then move on.
- Don't re-tell the practice-building at WEAREREASONABLEPEOPLE and its sprint format: Matthew and Thijmen heard it in an earlier round.

### X12. "If you could only do one thing in your first six months, what would it be?"
- Answer (slide 16): take the basics out of design reviews. Weeks 1–4 log what Heads of Design send back and why; weeks 5–6 turn the top three into the first crew member's rules; weeks 7–10 run it in a partner squad; week 11 read out review time per item.

---

## Either of them

### E1. "How does this connect to the agentic software development lifecycle the other craft leads are working on?"
- Why: Matthew told her in R2 that the other craft leads are setting that vision.
- Answer (slide 11): the craft leads run one shared test bed; Engineering brings the pipeline, tokens and staging data; any change to tools or ways of working goes through it first. Slide 14: the quarterly read-out keeps UX's voice in how roles and teams evolve.

### E2. "Your first month is our peak season (Black Friday, Sinterklaas, Christmas). Does the plan survive that?"
- Why: an offer now means a start in late autumn, when bol is at its busiest.
- Answer (slide 10): M1–2 asks very little of the teams: listen, sit in reviews, measure the baseline, set up the test bed. Heavier asks of the teams begin in M2–4.

### E3. "The Unspoken Diary hasn't been used yet. How do you know it works?"
- Answer (slide 8): it's on the slide: "success is still to be confirmed". The point is the process and the trade-offs: "I made every trade-off consciously, and could explain each one." Tested on real phones, with a fake date to rehearse all three days.

### E4. "Tell us about a time you held your position against a senior stakeholder."
- Why: the HR assessment named courage and being bold as development areas, so a behavioural probe is possible.
- Gap: not in the deck. Nearest real material: Story 12 (Brand as Blocker) and Story 11 (pausing the smart bottle).
