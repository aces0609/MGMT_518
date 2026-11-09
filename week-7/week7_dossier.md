# MGMT 518, Week 7 Dossier: Digital Transformation in Practice

*Prepared 2026-11-08. Bracketed numbers [n] point to the References. Guest stories and figures are as the speakers tell them and were not independently verified. The Our World in Data chart, the Gartner Emerging Tech abstract and the Kurnoff & Lazarus book were not read. The Gartner article sits partly behind an email wall, so its full Hype Cycle chart was not seen.*

**The week in one line:** Technologies spread along an S-curve, and each wave spreads faster than the last. Hype runs ahead of value. The organizations that actually get value (the Trail Blazers, CleanHaus) start from a pain point, involve the people closest to it, and measure what the freed-up time turns into [1][2][3][4][5][6].

## Contents

1. [TODO](#todo)
2. [Creativity quiz debrief](#creativity-quiz-debrief)
3. [Reading: WIPO, How do new technologies diffuse?](#reading-wipo-how-do-new-technologies-diffuse)
4. [Reading: CACM, Technology Adoption](#reading-cacm-technology-adoption)
5. [Reading: Gartner Hype Cycle for AI 2026](#reading-gartner-hype-cycle-for-ai-2026)
6. [Trail Blazers: SBJ, Utley and the podcast](#trail-blazers-sbj-utley-and-the-podcast)
7. [Video: David Long, Portland Trail Blazers](#video-david-long-portland-trail-blazers)
8. [Video: Nat Parker, CleanHaus](#video-nat-parker-cleanhaus)
9. [How the pieces connect](#how-the-pieces-connect)
10. [References](#references)

---

## TODO

Due dates are from the Canvas assignment list, Pacific time [9].

> **Heads up:** the **Week 6 Quiz is due tonight (Sun Nov 8, 11:59 PM)** and shows as unsubmitted.

### Due dates

| Item | Points | Due |
| --- | --- | --- |
| Week 6 Quiz | 5 | **Sun Nov 8, 11:59 PM (tonight)** |
| Week 7 Quiz | 5 | Sun Nov 15, 11:59 PM |
| #4 Story Line (individual) | 25 | Sun Nov 15, 11:59 PM |
| Week 8 Quiz | 5 | Sun Nov 22, 11:59 PM |
| #5 Final Presentation Materials | 40 | Sun Nov 29, 11:59 PM |
| #6A Final In-Class Presentation | 40 | Tue Dec 1, 11:59 PM |
| Discussion Post #4: AI & The World Around Us | 10 | Sun Dec 6, 11:59 PM |

### This week

- [ ] Read the creativity quiz debrief [1]
- [ ] Read WIPO Ch. 1 closely: Key concepts, Stylized fact #1 and Box 1.1 on GenAI [2]
- [ ] Read the CACM adoption article and the Gartner AI Hype Cycle article; know the five phases [3][4]
- [ ] Read the SBJ Trail Blazers article; optional: Utley blog, "Say What Sucks" podcast [5][6][7]
- [ ] Watch David Long (28 min) and Nat Parker (41 min) [8]
- [ ] Solution storming and selection (no submission; be ready to discuss in class)
- [ ] Draft #4 Story Line

### #4 Story Line: what's required [9]

A 1 to 2 page outline (bullets are fine), drafted individually from the team's VOC research. Label it with your name, project, assignment name, course name and page numbers. Do your own thinking before you turn to AI.

- **Setup:** the business problem, the stakeholders and the stakes. Name the decision-maker you are telling the story to. Don't reveal findings yet.
- **Rising Insights:** 3 to 5 synthesized insights, with VOC evidence (respondent counts and quotes).
- **Big Aha:** one short, conversational "so what" statement that resolves the conflict.
- **Resolution:** the recommended solution (a technology, a process change or a next step). Optionally, the alternatives you considered.
- **AI Use Statement.**

---

## Creativity quiz debrief

The instructor's 33-slide debrief re-examines Kumar et al., *Human Creativity in the Age of LLMs* (CHI 2025), the paper from the Week 5 quiz [1].

**The study design.** Two pre-registered experiments with 1,100 people: 460 on divergent thinking (alternate uses) and 640 on convergent thinking (word-link puzzles). Participants were randomly assigned to No AI, AI Answers or AI Coaching. They practiced with that help for 3 to 6 minutes, played a 1-minute Snake game, then took the test alone [1].

**Where the claims outrun the evidence.** The debrief lists six flaws [1]:

1. **Timing.** The abstract raises "long-term" concerns, but the test came about one minute after the AI help.
2. **A zoomed axis.** Coaching vs. no AI on originality differs by about 0.09 points on a 5-point scale (2.79 vs. 2.70). The published figure's y-axis doesn't start at zero, so the gap looks large.
3. **Only one comparison is significant.** Coaching vs. no AI is significant (p = 0.005 on puzzles, p = 0.009 on originality). AI Answers vs. no AI is not (p = 0.682 and 1.000), and neither is Coaching vs. Answers (p = 0.064 and 0.126).
4. **"Trend" became "worse."** The Results section calls the p = 0.064 result a trend to treat cautiously. The Discussion states flatly that coaching performed worse.
5. **Self-ratings barely moved.** Self-rated creativity dropped 1.6, 3.6 and 5.6 points on a 100-point scale.
6. **Design limits.** A fine-tuned GPT-3 model scored originality, the study used only five objects, and the exposure was short.

**What the class did.** These counts cover 48 submissions [1]:

- Reading alone, 21 students chose "Negative." After an AI-aided review, 9 did.
- Spotting the gap between claim and evidence: 2 of 48 alone, 17 of 48 with AI.
- 22 students lost interest at the statistics and figures, which is exactly where the critique lives.
- How students prompted mattered. Asking for a summary reinforced the paper's claim. Asking AI to check the evidence surfaced the gap, and 10 students caught a real AI error by checking the paper.
- 33 of 48 concluded AI can both help and hurt creativity. 25 plan to "think first, then use AI."

**Other research.** The debrief also cites outside studies [1]:

- Doshi & Hauser (2024): AI access raised story novelty 8.1% and usefulness 9%, but made stories 10.7% more similar to each other.
- Dell'Acqua et al. (2023): consultants did more than 40% better on tasks inside the AI's frontier, and were 19 points less likely to be correct on a task outside it.

**Takeaway:** read the evidence yourself, form a view, ask AI to challenge the conclusion, then verify each claim in the source [1].

---

## Reading: WIPO, How do new technologies diffuse?

From the *World Intellectual Property Report 2026*, Chapter 1 [2].

**Key concepts** [2]:

- **Diffusion** is the aggregate spread of a technology across users over time. **Adoption** is one user or organization starting to use it, usually after adapting it.
- **Technology transfer** is a deliberate, often contractual, sharing of knowledge (licenses, joint ventures).
- **Knowledge spillovers** are unintended knowledge flows.
- Diffusing the *know-how* matters too. A farmer can use fertilizer without understanding its chemistry, but a firm adopting robotics needs programming and integration skills.

**Stylized fact #1, the S-curve.** It goes back to Griliches' 1957 hybrid-corn study [2]:

- Diffusion has three phases: slow uptake, rapid growth after a tipping point, then saturation.
- The slow start is social: potential adopters wait to see how early users fare.
- Falling prices, policy and complementary infrastructure can trigger the tipping point.
- **Limits:** not every technology follows a clean S-shape (some come in waves), and the curve describes data after the fact without explaining it.
- **Adoption vs. intensity:** 50% of firms "adopting" says little if most barely use it.
- **Where things sit now:** 2G through 4G are near saturation. 5G reached half the world in under five years. Renewables are mid-curve, projected to rise from 35% to 47% of global electricity by 2030.

**The other stylized facts** [2]:

- **#2: Newer technologies diffuse faster.** The time from limited to near-saturated household use roughly halved by the 1980s.
- **#3: Cross-country adoption lags are shrinking.** The telegraph took about 50 years to reach countries worldwide and the car about 36. Cellphones took under 20, and 3G and 4G only a few.
- **#4: The use-intensity gap.** The gap between rich and developing economies widened through the 20th century and is now narrowing for 3G, 4G and wind.

**Box 1.1, GenAI** [2]:

- ChatGPT reached users in virtually every country within days of its November 2022 launch.
- The US share of traffic fell from over 70% at launch to about 25% within a month, then settled near 20%.
- By mid-2023 it had about 500 million monthly users, roughly 12.5% of the global workforce.
- India, Brazil, Indonesia, the Philippines and Mexico use it well above what their income predicts.
- Low-income economies lag because of connectivity, data-center capacity and skills.
- It spreads fast because it runs on devices people already own and is often free.

---

## Reading: CACM, Technology Adoption

From *Communications of the ACM*, June 2020. The page shows no byline; the references point to Denning and Lewis [3].

**Adoption is speeding up** [3]:

- Time to reach 80% of households: landline phone about 60 years, electric power 33, color TV 15, social media about 12.
- The S-curve is the one stable pattern within otherwise chaotic adoption.

**Rogers' adopter bands (1962)** [3]:

- Early adopters: 12.5%, one to two standard deviations before the mean adoption time. They respond to novelty.
- The majority: 68%, within one standard deviation. They are imitators who wait until the technology seems reliable.
- Laggards: 2.5%, beyond two standard deviations. They resist and may never adopt.

**Moore's "chasm" (1991).** The article describes the idea without using the word. Startups saturate the small early-adopter market and run out of money before reaching the majority, so plan for the majority from day one [3].

**Bass model (1969).** Cumulative adoption S(t) depends on three parameters, which can be estimated from early sales [3]:

- **p:** spontaneous adoption (innovators)
- **q:** imitation (the majority)
- **N:** total market size

From these you get the inflection point t\*, when sales peak. The worked example is Tesla. The Model 3 has the lowest p, meaning imitators drive it, while BMW 3/4 sales fell from 140k to 66k. The article also describes "technology jumping," where each new model's curve rises as the last one falls.

**Other models.** The pipeline model, the funnel model (a 96% failure rate means about 25 ideas per product), and preferential attachment, which produces power-law timing that defeats standard forecasting [3].

**Limit:** the models size a market and time its peak, but give leaders no guidance for the surprises along the way [3].

---

## Reading: Gartner Hype Cycle for AI 2026

Article dated Oct 1, 2026, quoting VP Analyst Haritha Khandabattu [4].

**The five phases.** These come from Gartner's standard methodology; the free article doesn't spell them out [4]:

1. **Innovation Trigger:** a breakthrough sparks interest.
2. **Peak of Inflated Expectations:** publicity outruns proof.
3. **Trough of Disillusionment:** implementations disappoint and interest falls.
4. **Slope of Enlightenment:** real use cases and second-generation products appear.
5. **Plateau of Productivity:** mainstream adoption with clear value.

**What it tells you, and what it doesn't.** It shows where the conversation is, not adoption data. It is not a forecast that every technology will reach the plateau. Contrast it with the WIPO and CACM curves, which are fitted to actual usage.

**The 2026 headline: control before capability** [4]:

- The question has shifted from "can we build with AI" to "can we account for what it does and what it costs."
- GenAI concerns are now about reliability and ROI, not model capability.
- **The agent gap:** 17% of organizations have deployed AI agents, and more than 60% expect to within two years. Gartner expects more than 40% of agentic AI projects to be cancelled by end of 2027 over cost, unclear value or weak risk controls.
- **Prerequisites:** governance and identity infrastructure come before scaling agentic, physical or commerce-facing AI.
- **AI observability** is one of the most consequential entries. It acts as a telemetry layer that catches silent failures and plausible but wrong outputs. The market is still immature and fragmented.
- **Cost:** move from looking back at spend to actively preventing it. Gartner's three prongs are intelligence tiering, session budgets with circuit breakers, and automated cross-vendor cost controls. AI FinOps is immature.

**Relevance to your day job:** observability and silent failures is the same problem CBM monitoring solves for physical assets.

---

## Trail Blazers: SBJ, Utley and the podcast

**SBJ (Jul 29, 2024).** The article covers the Blazers' early AI work [5]:

- Chief Strategy and Innovation Officer Christa Stout admitted she didn't know where to start on an AI strategy.
- She and David Long became "great aggregators" of employee pain points.
- They formed a roughly 35-person AI committee and ran six months of trainings and lunch-and-learns.
- Jeremy Utley's two-week bootcamp trained 25 front-office staff, built on daily exercises. His motto: "The key to use is use."
- Early tools: *Betty Budget* (a custom GPT for budget codes), a brand-guide bot, and a survey assistant that flags negative comments to guest services via Slack.
- Stout's principle: the people closest to the problem are best suited to solve it.

**Utley, "From efficiency to impossibility."** The blog lays out three stages of AI value [6]:

1. **Value capture** (same work, faster). Betty Budget cut monthly reconciliation from 2 to 3 hours down to 30 to 45 minutes.
2. **Value compounding** (making impossible work possible). *David Detractor* and *Kelly Kindness* read every survey comment:
   - 50 hours a week across three departments became 3 hours for one person, about 2,400 hours a year.
   - Coverage went from 60% of comments within three weeks to 100% within 24 to 48 hours.
   - A complaint about a missing vegan hot dog led to a menu change within hours.
3. **Value creation** (new capabilities). Season-ticket holders trade unused tickets for retail or food credits instead of reselling them below face value. The team expects a 20% drop in secondary listings at scale, and the NBA has asked them to share it.

Other lessons from the blog [6]:

- Measure problems solved and revenue created, not logins.
- *Billy Brand* (the brand-guide bot) grew once it moved from Slack to a web tool, because people no longer felt watched using it.

**Podcast, Think Fast Talk Smart ep. 205, "Say What Sucks"** (May 2025, live at SXSW with Stout, Long and Utley) [7]:

- Reframe from "how can AI boost productivity?" to "what do employees hate about their jobs?"
- Naming the bots, leaders sharing their own personal AI use and celebrating experiments all reduced defensiveness.
- Early tools had low adoption until they were revised based on user feedback.

---

## Video: David Long, Portland Trail Blazers

28 min; interviewed by the instructor [8a].

**Who he is.** Ten seasons at the Blazers, moving from digital marketing and paid media into digital products: the web, the app, point-of-sale and the big screen [8a].

**Transformation is change management.** Getting excited about a tool is the easy part. The real work is informing staff, explaining the value and reporting it, so the launch itself doesn't become the output [8a].

**Start with a pain point.** Leaders should audit workflows. Long keeps a "bug list" (a Utley idea) of small frustrations noted through the day [8a].

**A failure.** An early GPT prospecting tool for the corporate-partnership team got zero adoption. He built it without the people closest to the problem, so AI became the output instead of the solution [8a].

**A success.** The guest-experience survey tool [8a]:

- Eight people across three departments spent 50 hours a week reading thousands of survey responses.
- A 2.5-week sprint built the tool with that group.
- The result: 3 hours a week for one person, and responses within 24 hours instead of up to two weeks.
- It has run for two years with full adoption.

**Lunch and Launch** (since 2023) [8a]:

- One hour, open to anyone from intern to C-suite. Nobody leaves until the room names 20 pain points.
- The key prompt is "what sucks about your job." It surfaces Einstellung-effect habits: familiar but inefficient fixes that get ingrained.
- Builders listen but don't participate or build live, so no one's idea gets favored.
- The team tags each pain point by pillar: fan experience, revenue or efficiency.
- Everyone gets **two dot votes**. Otherwise people vote with the C-suite. Two votes also let colleagues back each other ("Sue gives Tom one").
- The person who raised the pain point co-pilots the build and gets credit for it.

**Tools and governance** [8a]:

- **Tool-agnostic:** Claude Enterprise, ChatGPT Team and Copilot. Going all-in on one model silos departments out of the shared conversation.
- **RADAR** is the governance group: legal, IT, BI, developers and rotating department seats (HR, marketing and others).

**Don't report "time saved"** [8a]:

- It makes people nervous ("now you give me two hours more work") and implies their skill isn't valuable.
- Instead, reinvest the time and report the new output.
- The survey team now has AI surface *promoter* comments, so staff can reach out and thank fans. In his words, that is AI used for more human connection.

**Crystal ball and advice** [8a]:

- He takes weekly walks talking with Claude about threats to the business.
- He wonders what the "front end" (web, app, arena) looks like in 5 to 10 years.
- Advice: prototype fast from your bug list, learn the Einstellung effect, audit your own workflows, and bring the people closest to the problem into the solution.

---

## Video: Nat Parker, CleanHaus

41 min; interviewed by the instructor [8b].

**GlobeSherpa, the origin story** [8b]:

- It began as a PSU MIM class business plan for a smartphone travel guide.
- A classmate, Michael Gray, offered to build it, and Parker's academic director let them make the company their track.
- A mentor, Doug Fieldhouse of Vesta, wrote a $50k check at their first lunch.
- Portland's parking director rejected "Parking Sherpa," saying nobody trusts mobile payment. That director was later indicted for bribery by meter vendors.
- Parker pivoted to transit. A TriMet study showed fare collection cost about 45% of each dollar collected.
- He cold-called TriMet's staff directory and reached the letter S before someone agreed to meet.
- A signed MOU (9% of each ticket) unlocked $500k from angels, half of it tied to a real contract.
- The result was the nation's first multimodal transit mobile-ticketing system, around 2012.
- The Tesla story is true: he pitched a stranger at a red light, who turned out to be Scott Holdaway (ClarisWorks), and became an early investor.

**The exit.** GlobeSherpa raised about $4M, grew to 27 staff and reached about $2.2M ARR. TriMet's reputation made other agencies pay attention [8b].

- A RideScout CEO (owned by Daimler) approached Parker for payments at a conference, which led to an acquisition.
- The companies merged as **moovel North America** with Parker as CEO.
- **Daimler's thesis** was that people would stop owning cars in 20 to 30 years in favor of shared, autonomous fleets.
- **Why that was slow:**
  - Policy, right-of-way, taxation and insurance lagged behind the technology.
  - Automakers are incremental by nature, which made them a poor match for Uber's mindset.
  - A later Daimler–BMW mobility merger crumbled.

**CleanHaus, an AI-native company** [8b]:

- Software for short-term-rental turnover. It grew out of his own Airbnb properties and the "death by a thousand cuts" of texting cleaners and contractors.
- A Portland manager with 300 rentals had the same problem, which validated it.
- **The team:** Parker, Skip, principal engineer Brian Young and one developer in Pakistan, plus AI coding tools. He says they now out-produce his 50-plus engineers at moovel.
- **Value shifts toward people** who understand product, customers and go-to-market. Senior engineers still matter for prompting well, infrastructure and security.
- Internal agents review pull requests and turn meeting notes into action items, like a chief of staff.

**Broomy, the product** [8b]:

- A supervisor agent with sub-agents. It was renamed from "Klaus" after a trademark dispute.
- **Messaging by exception:** a sentiment engine logs trivia like dog hair, but escalates issues that block guest readiness, like a broken window. It then offers to dispatch a contractor and tracks the fix.
- Coming next: voice-first input for cleaners, automated bidding from three contractors, and computer vision through smart glasses.
- **The human stays where it differentiates.** Luxury guests pay for human contact, so the agent takes the back-office work and frees managers for hospitality.

**Advice** [8b]:

- Get your hands dirty and avoid analysis paralysis.
- He no longer writes requirements; he builds working prototypes.
- Speak to the top: cold-call the CEO, because middle management "is where ideas go to die."
- Find a mentor.

---

## How the pieces connect

- **The curves are getting steeper.** WIPO and CACM show each wave diffusing faster: about 60 years for landlines, 12 for social media, days to reach every country for ChatGPT [2][3]. That speed is why Gartner's 2026 cycle is about *control*. Adoption of agents has outrun governance, observability and cost discipline [4].
- **Adoption is not value.** WIPO's adoption-vs-intensity point, Utley's capture → compounding → creation ladder, and Long's refusal to report "time saved" make the same argument: count what changed, not who logged in [2][6][8a].
- **Rogers in the break room.** Lunch and Launch is a diffusion machine. Pain points come from the people closest to the work, the person who raised the problem co-pilots the build as an early adopter, and celebration pulls in the imitating majority. Long's zero-adoption prospecting tool is the chasm in miniature [3][8a].
- **The Hype Cycle at human scale.** Parker's Daimler story is a Peak of Inflated Expectations for car-free mobility; policy and insurance kept it in the trough for a decade. CleanHaus is a bet that agentic AI is now on the slope for narrow, rote workflows [4][8b].
- **The creativity debrief is about method.** Think first, have AI challenge your view, verify against the source. That same order applies to your Story Line: build Rising Insights from your own VOC evidence before asking AI for help [1][9].
- **For the Story Line:** both guests model a clean arc. A painful problem (50 survey hours a week; turnover chaos), insight from the people closest to it, and a resolution measured in outcomes rather than tools. Long's "what sucks" framing is a natural Setup hook for the job-search project.

---

## References

[1] MGMT 518, "Human Creativity in the Age of LLMs: What the Paper Claims, What the Data Show, and What You Found," Week 7 debrief (MGMT518_Week7_Creativity_Debrief_v3-1.pdf), Canvas. https://canvas.pdx.edu/courses/120638/files/17409464

[2] WIPO, *World Intellectual Property Report 2026*, Ch. 1, "How do new technologies diffuse?" https://www.wipo.int/web-publications/world-intellectual-property-report-2026/en/1-how-do-new-technologies-diffuse.html

[3] "Technology Adoption," *Communications of the ACM*, June 2020. https://cacm.acm.org/magazines/2020/6/245155-technology-adoption/fulltext

[4] Gartner, "The Latest Gartner Hype Cycle for Artificial Intelligence Puts Control Ahead of Capability," Oct 1, 2026. https://www.gartner.com/en/articles/hype-cycle-for-artificial-intelligence

[5] "Trail Blazers lead staff through ways artificial intelligence can build the business," *Sports Business Journal*, Jul 29, 2024. https://www.sportsbusinessjournal.com/Articles/2024/07/29/technology/

[6] J. Utley, "From Efficiency to Impossibility: How the Trail Blazers Prove AI Creates Value, Not Just Captures It." https://www.jeremyutley.com/blog/from-efficiency-to-impossibility

[7] *Think Fast Talk Smart*, ep. 205, "Say What Sucks: Catalyzing Organizational Change with AI," May 27, 2025. https://www.fastersmarter.io/205-say-what-sucks-catalyzing-organizational-change-with-ai/

[8a] "David Long, VP of Digital and Innovation at the Portland Trail Blazers," PSU Media Space. https://media.pdx.edu/media/t/1_a96f2kit

[8b] "Nat Parker, Transportation and Hospitality Transformation," PSU Media Space. https://media.pdx.edu/media/t/1_xw2gqy4h

[9] MGMT 518 Canvas: assignment list and "#4 Story Line" description. https://canvas.pdx.edu/courses/120638/assignments/1258234

*Caption errors corrected in this dossier:*

- "Vera Sell" is the interviewer as captioned.
- "Jeremy Atlee" → Jeremy Utley.
- "Einstein effect" / "insulin effect" → Einstellung effect.
- "cloud enterprise" → Claude Enterprise.
- "radar" → RADAR.
- "Clean House" / "Brumi" / "Moval" → CleanHaus / Broomy / moovel.
- "Calais" → likely a meter vendor name misheard.

The Parker captions skip a stretch near the end, from "socioeconomic perspective" to the wrap-up.
