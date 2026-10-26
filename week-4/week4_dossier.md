# MGMT 518, Week 4 Dossier: From Data to Insight, Plus Privacy and Ethics

*Prepared 2026-10-25. Bracketed numbers [n] point to the References. Statistics, company examples and the guest's claims are as the speakers tell them and were not independently verified. The EU AI Act Explorer, the Orrick US AI Law Tracker and Siebel Chapter 5 were not read; see the note at the end.*

**The week in one line:** Data only creates value when it is clean, explored with curiosity, and told as a clear story to a specific audience, and as AI starts taking actions, privacy, ethics and accountability become leadership decisions rather than IT details [1][2][3][4][5][6].

## Contents

1. [TODO](#todo)
2. [The Rise of Big Data (Siebel Ch. 5 lecture)](#the-rise-of-big-data-siebel-ch-5-lecture)
3. [Storytelling, exploration and visualization](#storytelling-exploration-and-visualization)
4. [Privacy and ethics](#privacy-and-ethics)
5. [Leading Responsible AI](#leading-responsible-ai)
6. [Optional guest: Edward Egros on sports analytics](#optional-guest-edward-egros-on-sports-analytics)
7. [How the pieces connect](#how-the-pieces-connect)
8. [References](#references)

---

## TODO

Due dates are from the Canvas assignment list, Pacific time [8]. The Week 4 module date is Oct 19, so the in-class session with Nathan Christensen (Tuesday) has already happened.

### Due tonight (Sun Oct 25, 11:59 PM)

| Item | Points | Due |
| --- | --- | --- |
| Week 4 Quiz (the regular reflection quiz) | 5 | Sun Oct 25, 11:59 PM |
| Week 4 Viz Quiz (multiple choice on visualization best practices) | listed as 0 | Sun Oct 25, 11:59 PM |

The module page says you have two quizzes this week: the reflection quiz and an extra multiple-choice quiz on data visualization best practices [8]. Canvas lists the Viz Quiz at 0 points, so check how it is graded before deciding how much time to give it.

### Still on the schedule

| Item | Points | Due |
| --- | --- | --- |
| #3 Mid-Project Review | 40 | Sun Nov 1, 11:59 PM |
| Week 5 Quiz | 5 | Sun Nov 1, 11:59 PM |
| Week 5 Quiz: Creativity in the Age of AI (a second Week 5 quiz is also listed) | 5 | Sun Nov 1, 11:59 PM |
| Schedule and conduct project interviews (module says you should be in the middle of this) | no separate date | Week 4 activity |

Also from Week 3: the two classmate replies on Discussion Post #3 were due Wednesday of Week 4 (Oct 21) [8].

### Before the next session

- [ ] Watch the six required videos: Rise of Big Data (24:35), Storytelling with Data (8:52), Data Exploration (14:10), Data Visualization (9:17), Privacy and Ethics (7:38), Leading Responsible AI (13:34) [1][2][3][4][5][6]
- [ ] Browse the EU AI Act Explorer and the Orrick US AI Law Tracker [9][10]
- [ ] Optional: Siebel Ch. 5, and the Edward Egros interview (36:04) [7][11]

---

## The Rise of Big Data (Siebel Ch. 5 lecture)

*Instructor lecture [1]. The lecture compares Siebel's 2019 chapter with what happened since.*

- **Three Vs:** Big data is defined by volume, velocity and variety, and the data no longer fits "rows and columns." The lecture quotes Eric Schmidt (2010) that as much information is now created every two days as in all history up to 2003 [1].
- **Moore's Law:** Computing power doubling roughly every two years made big data possible, though the lecture notes it is a prediction, not a law of physics, and is nearing physical limits [1].
- **The pendulum:** Computing swings between centralized (mainframes), distributed (PCs), centralized again (cloud) and now back to the edge, where sensors and small language models filter or process data locally to save cost and protect privacy [1].
- **Promises and examples:** Siebel's three promises were accessible, intelligent and scalable data. The lecture cites Kaiser Permanente (readmissions down about 10%), Netflix (80% of viewing from recommendations), Walmart forecasting, Habitat for Humanity (fundraising up 155%) and Campbell Soup with Watson weather-triggered ads (2016) [1]. These figures are as stated in the lecture.
- **Siebel's five challenges, and how they aged:**

| 2019 challenge | Status today, per the lecture [1] |
| --- | --- |
| Multiplicity of systems | Still big. AI helps with mapping and cleaning but not governance or interoperability |
| High-frequency data | Easier, since edge processing summarizes it. Now a design question: what to capture and ignore |
| Data lakes | Partly solved by "lakehouses" that add governance and access control, but still hard |
| Data consistency | Still "garbage in, garbage out." The goal moved from one perfect database to trusted, interoperable sources (data mesh, fabric, semantic layers) |
| New tools and skills | Reversed: LLMs let non-technical people ask questions in plain English, so the issue is governance and responsible use |

- **New challenges the lecture adds:** governance and privacy; scarcity of good data (Reddit disclosed over $200 million in data-licensing contracts in its IPO filing, with one Google deal reported at $60 million a year); synthetic data and retrieval-augmented generation (RAG); and hidden human labor (the lecture cites about 1.2 million annotators claimed by Telus International, earning roughly $6 to $18 an hour) [1].
- **Closing frame:** Tim Cook's 2014 line, "When an online service is free, you're not the customer. You're the product." The lecture moves from storage questions to trust: who owns data, who monetizes it, how transparent systems are [1].

## Storytelling, exploration and visualization

*Three short lectures that build on each other: why stories, how to explore, how to draw [2][3][4].*

**Why stories [2].**
- Facts alone rarely change minds. The lecture says a statistic engages a small part of the brain while a story engages sensory, motor and emotional regions, and it cites "neural coupling" as the reason stories lower defenses.
- A data story has three parts: data (the evidence), narrative (context, rising insight, resolution) and visuals. Together, "data becomes insight, and insight becomes action."
- **Charts beat tables** for communicating an insight; tables are for reference. Remove clutter, sort bars, round numbers, and write an active headline ("Product C grew 88%") so the audience does not have to calculate. Think about the emotion each chart should produce.

**How to explore [3].**
- **Explorer versus explainer:** Exploration is messy and for you. Explanation is simplified and for a specific audience. The Indiana Jones metaphor frames it.
- **Three traps ("data forgeries"):** the *data cut* (raw slicing never packaged for an audience), the *data cameo* (starting from the conclusion and cherry-picking data) and *pretty dashboards with zero insight*. All come from skipping the thinking that connects exploration to explanation.
- **Pre-flight checklist:** define the mission (what decision will this inform?), know the terrain, assemble complete and credible data, check for duplicates, missing values and outliers, then pick the tool that fits. AI is a helpful but "not very trustworthy" co-pilot, so double-check it. The instructor's PDX survey example: one respondent claimed $20,000 of airport food spend, which would have wrecked an average.
- **Traps in the data:** survivorship bias (the WWII planes that did not return) and "the tyranny of the existing customers" (tied to Clayton Christensen); Anscombe's quartet (identical statistics, very different pictures); and correlation is not causation (the stork and margarine examples). The lecture's rule of thumb: you need roughly 30 data points before talking about correlation. With ten interviews, say "I see a pattern" and treat it as a hypothesis [3].
- Tufte, as quoted: the fundamental task of analysis is to make smart comparisons.

**How to draw [4].**
- Visualize the right data: ratios or calculated metrics (such as revenue per customer) can reveal what totals hide.
- Do the math for the audience: show the variance directly and use color deliberately.
- Match chart to purpose (bars to compare, lines for trends, scatter for relationships). Avoid pie charts unless there are two or three slices. Start bar charts at zero. Sort by size unless the categories have a natural order (time, income, age). Keep scales, colors and labels consistent across charts.
- Takeaways: choose the right data and chart, simplify, and design with purpose. "Clarity always beats cleverness" [4].

## Privacy and ethics

*Instructor lecture [5].*

- **Laws:** GDPR (EU, 2018) requires explicit prior consent; CCPA (California, 2018) gives consumers a right to opt out of selling or sharing. The lecture calls these proactive and reactive models [5].
- **Four AI privacy concerns:** data collection and consent; security risk from large data sets; surveillance (facial recognition); and inference, where AI predicts sensitive traits (health, politics) from patterns, which the lecture calls "predictive harm" [5].
- **Valid consent:** clear, specific, revocable. Examples: a location prompt in a navigation app, and asking interviewees whether an interview can be recorded and transcribed by AI, with a human transcription alternative if they say no. This is directly relevant to your VOC interviews. Invalid consent: pre-ticked boxes, silence, unreadable terms, scraping (Clearview AI is named) [5].
- **Ethics cases, as stated in the lecture:** HireVue dropped facial analysis in 2021 after criticism; Amazon scrapped a resume screener (2018) that penalized signals like "women's chess club" because it learned from biased history; LinkedIn's job recommendations favored men because of behavior in the training data. The lecture's lesson: "AI learned from our past behavior. And if that past is biased, the system will be, too" [5].
- Privacy ensures consent, ethics ensures fairness, security ensures resilience [5].

## Leading Responsible AI

*Instructor lecture update [6].*

- **Why it changed:** When AI moves from summarizing to acting (recommending, accessing data, contacting customers), one error can be a privacy, security, ethical and business problem at once. Treat AI risk as an interconnected system under enterprise risk management, not just IT or legal [6].
- **Shadow AI:** Like shadow IT, employees use AI tools without approval (pasting a confidential contract into a public tool). Banning is not realistic; use policy, approved tools, education and controls [6].
- **Governance = people, policy, technology, oversight.** Four questions: what AI is allowed, who approves it, who audits it, who is accountable. "The algorithm did it" is not an acceptable answer [6].
- **Human oversight:** Scale it to the consequence of being wrong (hiring, diagnosis, lending, legal, performance). Supporting a decision differs from making it. Transparency (do people know AI is involved?) and explainability (can we understand why?) support trust, which the lecture calls a design requirement [6].
- **Security both ways:** AI sharpens phishing, deepfakes and synthetic identities, and creates new attack surfaces (prompt injection, data leakage, data or model poisoning). Agents (which act) raise the stakes over co-pilots (which assist), so define their permissions, spending limits and when a human must approve [6].
- **Four leadership questions:** Can we? Should we? How should we? Who is accountable? And five executive questions before deployment: what decision or action will it influence; what data will it access; what happens when it is wrong; where must humans stay involved; who is accountable [6].

## Optional guest: Edward Egros on sports analytics

*Interview (36:04), hosted by an instructor whose name the captions give as "Vera Sell" (spelling unverified). Egros is described as a sports analytics expert and broadcaster working with FanDuel Sports Network West, with earlier stints at the NFL and Fox Sports, and a Substack called Ed with Sports [7]. Everything below is as stated by the speakers.*

- **Path:** Journalism and economics at SMU, inspired by Moneyball, then a master's in predictive analytics, then sports reporting that used analytics, then the betting space [7].
- **Example 1, baseball strength of schedule:** After two weeks of the season, he asked which teams had been lucky or unlucky. He joined pitch data from several sources, attached preseason projected WAR to each pitcher, weighted by innings faced, and plotted average pitching quality faced against win percentage in a 2-by-2. Most of the work was data manipulation: matching player IDs, fixing name variants (Mike versus Michael King) and removing missing projections. The host noted that a single pitcher ID acted as the "single source of truth" [7].
- **Example 2, field goals over expected (UFL):** With only box-score data, he used distance alone to build an expected make rate and ranked kickers by performance against it; the top kicker later got an NFL contract [7].
- **Lessons he gave:** Context matters; samples can be too small; state your assumptions and shortcomings; do not over-automate (he describes a tennis win-probability model that gave a top player about 70% when betting markets implied 95% or more); domain experts must review automated output. Advice to students: learn to code, communicate, and visualize creatively; and to convince the audience it matters, lead with the surprise [7].

---

## How the pieces connect

- **The week is one pipeline:** collect and clean (Big Data, exploration) → explore → explain with a story and chart (storytelling, visualization) → decide what you are allowed to do with the data and who is accountable (privacy, responsible AI) [1][3][4][5][6].
- **Data quality is the common thread.** The lecture says Siebel's data-consistency problem persists, the exploration video says the quality of insight cannot exceed the quality of data, and Egros spent most of his project matching names and IDs [1][3][7].
- **Human judgment stays in the loop.** Exploration says double-check AI, Responsible AI says keep humans where consequences are high, and Egros says domain expertise must review automated output [3][6][7].
- **For your project interviews:** Use the consent practice from the privacy lecture (ask before recording or AI transcription, offer a human alternative), and the exploration lecture's caution that a small number of interviews gives patterns, not correlations [3][5].
- **For your Mid-Project Review and Story Line:** Lead with the insight, then build the visual (active headline, one takeaway per chart, bars from zero, sorted) [2][4].
- **Connection to Week 3:** Christensen's "speed of trust" and Sklarew's point that people struggle to trust probabilistic output both reappear as trust and accountability in the Responsible AI lecture [6].

---

## References

1. *Siebel Chapter 5: The Rise of Big Data* (24:35). PSU Media Space. https://media.pdx.edu/media/t/1_if63ypmm
2. *The Power of Storytelling with Data* (8:52). PSU Media Space. https://media.pdx.edu/media/t/1_tmb9m7lo
3. *Introduction to Data Exploration* (14:10). PSU Media Space. https://media.pdx.edu/media/t/1_ede92pad
4. *Introduction to Data Visualization* (9:17). PSU Media Space. https://media.pdx.edu/media/t/1_sya4p4bh
5. *Privacy and Ethics* (7:38). PSU Media Space. https://media.pdx.edu/media/t/1_dgscbzf2
6. *Leading Responsible AI* (13:34). PSU Media Space. https://media.pdx.edu/media/t/1_h37x79gv
7. *Interview with Edward Egros on Sports Analytics* (36:04, optional). PSU Media Space. https://media.pdx.edu/media/t/1_pgmpx1m7
8. *MGMT 518 Digital Transformation, Fall 2026* (PSU Canvas): Week 4 module page and assignments, read 2026-10-25. https://canvas.pdx.edu/courses/120638/modules and https://canvas.pdx.edu/courses/120638/assignments (requires PSU login)
9. EU AI Act Explorer. https://artificialintelligenceact.eu/ai-act-explorer (assigned browsing; not read for this dossier)
10. Orrick US AI Law Tracker. https://ai-law-center.orrick.com/us-ai-law-tracker-see-all-states (assigned browsing; not read for this dossier)
11. Siebel, T. *Digital Transformation*, Chapter 5, "The Rise of Big Data" (optional; not re-read. Summarized only through the instructor's lecture [1]).

*Note:* Items 1 to 7 are summarized from the English captions of each video, and slides were not read. Caption errors are left as-is in the transcripts file, including the guest name "Stephen [UNKNOWN]" in the Privacy and Ethics video. Statistics and company stories are reported as the speakers stated them. The "Fireside Chat With Nathan Christensen" listed in the Week 4 module is the same recording as the Week 3 interview (https://media.pdx.edu/media/t/1_vsk6q707), already covered in the Week 3 dossier.
