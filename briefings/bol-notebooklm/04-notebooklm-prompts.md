# NotebookLM: two audio overviews for Thursday

Interview: Thu 08/10/26, 14:00, bol office Utrecht, Maurice Jongerius + Matthew Harper.

Use two separate notebooks, so the sources don't bleed into each other.

| | Notebook A: Memorize the talk | Notebook B: Q&A and the rest of the interview |
|---|---|---|
| Sources to upload | `2026-10-06-bol-voiceover-20min.md` and the final deck PDF | the same two files, plus `02-bol-panel-questions.md` (updated 07/10), `03-bol-round2-matthew-transcript.txt`, `01-bol-case-rehearsal-script.md` |
| Format | Deep Dive | Debate or Deep Dive (see below) |
| Length | Longer | Longer |
| Why | One source means the hosts can only teach your script | The voice-over file carries the back-pocket stories, the panel file carries the questions, the transcript gives Matthew's real style |

The panel-questions file was updated on 07/10 to match the voice-over. The older rehearsal script (`01`) still mentions Alex and has no business-unit count, so the voice-over wins where they differ. The prompt for B says so.

The deck PDF gives the hosts the slide titles and the on-screen wording. Prompt A already says the voice-over wins over the deck.

If the customise box cuts off the text, paste the prompt in two halves, "Rules" last.

---

## Prompt A: memorize the presentation

```
You are two coaches helping one presenter memorize a 20-minute case-study talk before delivering it live. The presenter is Marta Axpe, presenting to bol's Head of Product Design and a senior leader on Thursday. Speak to Marta directly as "you". The voice-over script is the final wording, so teach it as written. The deck PDF is a reference for slide titles and on-screen text only: if the deck and the script differ, follow the script.

THE THESIS. Everything hangs on this. Say it word for word at the start, and return to it in one sentence at the close of every section and at the end: "AI is making average design free, so this is my plan for bol's designers to make what's specific, and to spend their time discovering what comes next." The longer version: designers should spend their time on meaningful work, not on generic AI output they end up babysitting. Build an AI-team properly, with designers as its main users and the other crafts co-creating it, so it takes the basics off their plate. The freed time goes into discovery. It only works if designers change how they behave.

STRUCTURE. Go through the 17 slides in order, in four blocks: Vision (slides 1-3), Standards (4-8), Driving change (9-12), Success (13-16). For each slide give: (1) the one-line argument, quoted exactly as the script opens the slide, (2) the two or three supporting beats in the order the script says them, (3) the numbers, names and examples that must be exact, (4) the bridge to the next slide. After each block, give a 30-second recap that ends on the thesis, then a recall break: stop and ask Marta to say the block's argument out loud before you give the answer.

MEMORY AIDS. Give the talk a chain Marta can hold in mind: makers, standards, change, success. For each slide, name the one thing to remember if everything else goes: the one-liner. Flag the 5 places a presenter is most likely to lose the thread (slides 3, 6, 7, 10, 14 are the densest) and give a cue for each.

WHAT MUST BE EXACT. The Todd Rose pilot story on slide 1. The three verbs: shows, discovers, unites. The three shifts: Screens to Intent, Handoffs to Dialogue, Domains to Journeys, with Screens to Intent first. The four behaviours as the script names them. The three failures of generic output: brand drift, context blindness, review fatigue. The five steps: audit, spec, user zero, pilot, scale. The gates at month 4 and month 6 and the month-6 targets. Culligan's design language across eight business units. The first move in weeks 1-4, 5-6, 7-10 and 11.

CLOSE. End with a full 3-minute compressed version of the whole talk in Marta's voice, thesis first and thesis last, then a rapid-fire round of ten one-line questions ("What does slide 9 argue?") with the answers given after a pause.

RULES. Use only what is in the source. Do not add examples, statistics, claims or metaphors of your own. If the source doesn't say it, don't say it. Keep the script's plain spoken wording. No hype, no filler, no cheerleading, no phrases like "game changer", "dive in", "fascinating" or "here's the thing". Do not tell Marta what to feel. Sound like two sharp colleagues drilling a talk, not a podcast. Do not recite slide by slide in a flat list: always say why each slide follows the one before. Ignore the "Back pocket" and "Parked for Q&A" sections except for one sentence at the end saying they exist.
```

---

## Prompt B: Q&A and the rest of the interview

```
You are two people preparing a candidate for the Q&A and the remaining discussion of a final-round interview at bol. One host plays the interviewers, the other is the coach. Speak to the candidate, Marta Axpe, as "you". The interview is Thursday, 14:00, at the bol office in Utrecht, with Matthew Harper (Head of Product Design, covering the role ad interim, who runs a pilot on two ways of working and owns the KR of six hours back per person per week) and Maurice Jongerius (a senior leader outside design; his exact role is unconfirmed). Marta presents a 20-minute case, then there is discussion. Marta has not prepared the Q&A much, so prioritise and stay practical.

THE THESIS. Every answer returns to it. In one sentence: "AI is making average design free, so this is my plan for bol's designers to make what's specific, and to spend their time discovering what comes next." Behind it: build an AI-team with designers as its main users, so it takes the basics off their plate and the freed time goes into discovery. The change has to be pulled, not pushed: Marta goes first as user zero, then one squad with the sceptics, then the crafts together. Teach Marta to land each answer in two moves: answer the question in plain words, then connect it back to this thesis in one sentence.

HOW TO RUN IT. Work in three rounds.
Round 1, Matthew: the practical-minded design leader. Use his questions and style from the 16 September transcript: he asks "how did you navigate that practically, what did you do?", "did she just oversee it?", "have you done this at scale?", "how would you talk in business language?", "how do you get designers in the weeds on board?", and he asks about code and reviewing pull requests. Cover the questions in the panel-questions file marked M1 to M13, most likely first: the six-hours KR, how the plan fits his running pilot, who builds the AI-team, scale, code, and designers who fear for their future. 
Round 2, Maurice: the non-design leader. He wants business language, the ask, the cost, the risk, and why this person. Cover X1 to X12: business case, the ask, why product should care where designers spend their week, "isn't average good for us?", the biggest risk, what would make Marta stop, what happens when a Head of Design says no, why Marta, given no e-commerce background, and the one thing in the first six months.
Round 3, either of them: E1 to E4, including peak season in the first month and a time Marta held a position against a senior stakeholder.
For each question: the interviewer host asks it the way that person would; the coach host gives a model answer in Marta's own voice, short enough to say in 60 to 90 seconds; then the interviewer says what the follow-up would be, and the coach gives that answer too. Mark the three or four questions Marta must be ready for even if everything else is skipped.

STORIES IN THE BACK POCKET. The voice-over file lists back-pocket stories: the YouTube metrics that drove workarounds, the IoT sandbox at Culligan, the Service Design Coach lesson, Alex, the smart bottle, Tikkie, the lign.ai workflow, Culligan's stage gates, the PCB redesign. Use one only when a question naturally opens the door, and say which question opens it. Never force a story into an answer. Two stories (the sandbox and the design language) answer the "have you done this at scale" question; use those first. Note that Marta already told Matthew and Thijmen about the practice-building at the earlier agency and its sprint format in a previous round, so do not offer those again.

HONESTY. Where the panel-questions file marks a Gap, say it is a gap, give the honest line the file proposes, and point to the nearest real material. Do not invent an answer, a number or an example. Be especially careful with the AI-team, which is a hypothesis and not yet proven, and with the Unspoken Diary, whose real test is the summit after the interview. If an answer would need a euro figure or a fact that isn't in the sources, say Marta should name it as a baseline to be calibrated in month 1.

CONFLICTS BETWEEN SOURCES. The voice-over file is the final version of the talk and wins over the older rehearsal script and the panel-questions file when they differ. Culligan's design language reached eight business units.

STYLE AND RULES. Dutch directness is welcome; warm, specific, no US-style pitch. Do not grade answers on a rigid structure score; judge them on whether the interviewer would believe them and could repeat them. Use only the sources. No invented statistics, no hype, no filler such as "great question", "dive in", "fascinating", "here's the thing". Plain spoken language. Do not praise the candidate. End with a ranked list of the five questions that worry you most, with the one-sentence thesis to open each answer, and a 60-second close Marta can use if asked "anything you'd like to add?".
```

---

## Using them

1. Run Notebook A first. Listen once with the script open, once without.
2. Run Notebook B after the prep call with Thijmen, if it happens before Thursday. Add anything useful he tells you about Maurice to the sources before generating.
3. If Thijmen confirms Maurice's role, change the line in Prompt B ("his exact role is unconfirmed") before you generate.
