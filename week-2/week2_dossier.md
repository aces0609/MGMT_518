# Digital Transformation of Business (MGMT 518): Week 2 Dossier

*Prepared 2026-10-03; class prep section added 2026-10-06, HBR summary updated from the full text, and assignment requirements added from Canvas. Week 2: Technology Drivers, Cyber Security, and the Role of Customer Insight. Bracketed numbers [n] point to the References section. Statistics are as quoted by the instructors in the lectures and were not independently verified.*

Week 2 moves from what the technology is to why it is adopted, attacked or abandoned: technology only succeeds when it serves a business model, is secured by design, and solves a validated customer problem [1][2][3].

## TODO (Week 2)

Due dates are from the Canvas assignment list, Pacific time [8]. Week 2 opens Mon Oct 5 [8].

- [ ] **Before class (Mon Oct 5 on Zoom or Tue Oct 6 in person, per the course overview; confirm time in Canvas):** Watch the six recordings (about 70 minutes plus the Cyber Security video, whose length is not listed). Prep notes are in [Section 5](#5-class-prep-recordings-hbr-reading-and-questions-for-kristy-edwards) [1][2][3][4][5][6][7][8]
- [ ] **Before class:** Read "Know Your Customers' Jobs to Be Done" (HBR, Sept 2016), about 8 pages. A summary written from the full text is in Section 5 [9]
- [ ] **In class:** Kristy Edwards joins, so bring a point of view or a question. Suggested ones are in Section 5 [7][8][11]
- [ ] **Before the Project Plan:** Review the Project Plan Examples and Best Practices, the Discussion Guide Template and the Discussion Guide Best Practices (Canvas files, not read for this dossier) [8]
- [ ] **Sun Oct 11, 11:59 PM:** #1 Icebreaker & Team Contract (5 pts). Deliver a 1 to 2 page Team Collaboration Document as a PDF; one person submits for the team, with unlimited attempts [8]
    - [ ] Do at least one team-building activity (for example cook and eat together, or 1:1s practicing empathetic listening: share something important, then repeat it back in your own words)
    - [ ] Document: what you did and how it felt
    - [ ] Document: agreed communication channels and expected response times
    - [ ] Document: a decision-making rule for when the team disagrees
    - [ ] Document: an escalation mechanism for quality or timeliness problems
    - [ ] Document: all member names and an AI Use Statement
- [ ] **Sun Oct 11, 11:59 PM:** #2 Project Plan (15 pts). Deliver a customized VOC Interview Plan as a PDF, built by customizing the discussion guide template, with unlimited attempts [7][8]
    - [ ] Professional formatting with page numbers; project name, assignment title, team member names and date at the top or on a title page
    - [ ] Problem definition: what you want to learn, the decisions it will enable, and the assumptions you will test
    - [ ] Ideal respondent profile: process projects need at least 3 respondents from the same organization; market insights projects need 5 to 10
    - [ ] Interview logistics: how you will schedule, how you will transcribe, and who will conduct the interviews
    - [ ] A customized discussion guide
    - [ ] Optional recruiting plan if you will recruit more respondents
    - [ ] AI Use Statement
    - [ ] Grading: 15 to above 13 points if all elements are present with a clear problem definition and assumptions, a tailored guide, structured logistics and a fair workload split; 13 to above 10 if all are present but vague or generic; 10 or below if elements are missing or unclear [8]
- [ ] **Sun Oct 11, 11:59 PM:** Week 2 Quiz (5 pts) [8]
- [ ] **Weekly reflection:** The Week 1 module says each week has one; I found no separate Canvas item for it, so check the quiz page [8]
- [ ] **Optional:** Read Siebel Chapter 3, "The Information Age Accelerates" [8][10]
- [ ] **Coming up:** Discussion Post #3, Digital Transformation Reflection (15 pts) is due Sun Oct 18, 11:59 PM [8]

## 1. Siebel Chapter 3: the four technology pillars (optional reading)

**Convergence is the point.** Siebel's idea is that cloud, big data, AI and IoT matured at about the same time and can be layered, so each amplifies the others [1][10].

- **Cloud:** Scalable, on-demand infrastructure that turns capital expense into operating expense, lowering barriers for startups (the lecture's line: companies "die on the cash flow table"). Netflix runs on AWS. Today's issues are cost control, latency and sustainability [1].
- **Big data:** The raw material. Storage is cheap enough to analyze everything instead of samples, so the challenge is trust: data quality, governance and bias. The instructor is skeptical of synthetic "users" built from past interview data, and cites Target predicting pregnancies from purchases as a governance warning [1].
- **AI:** The intelligence layer. Generative AI now creates as well as predicts, but adoption is uneven and few firms have found value [1].
- **IoT:** The sensory layer. The value came less from smart toasters than from continuous data (glucose monitors, smart thermostats, precision agriculture) [1].
- **Feedback loop:** In a connected car, sensors (IoT) feed the cloud, data is aggregated (big data), models learn (AI) and results flow back to navigation. Limits remain when humans over-trust automation [1].

**Business basics behind adoption [1]:**
- Profit is revenue minus cost. A business model defines what value is created, how it is delivered and how it is captured. Netflix (streaming, subscriptions) works; WeWork's long-term leases against short-term memberships did not.
- Each function (marketing, HR, finance, IT) has its own KPIs, often tracked on a "bowler" scorecard. People adopt technology that helps them hit their KPIs, so ask what makes your boss look good.
- Cloud and big data are now mainstream infrastructure; AI and IoT are still finding their footing. The lecture cites generative AI piloting at about 25% of companies a year ago versus about 18% actively using it now.
- By function, IT adopts fastest (about 62%, per Economist Impact as cited), then marketing and sales (about 40%); operations is cautious; HR, finance and legal are slowest because of risk and compliance.
- McKinsey (as cited) estimates about 30% of today's hours worked could be automated by 2030, with growth in healthcare and STEM and the most risk in office support and customer service.

## 2. Cyber security

**Definition and evolution.** Chris Painter's definition: a continuous cycle of protection, detection, response and recovery. Practice moved from perimeter defense, to detection and response in the mid-2010s (banks flagging unusual card use), to security by design, Zero Trust ("never assume, always verify") and resilience planning [2].

**New attack surfaces [2]:**
- **IoT:** Devices were not designed to be connected or secure. About 15 billion connected devices existed in 2024; industrial IoT holds most of the value.
- **Cloud:** Centralization means one breach can affect thousands of organizations.
- **AI:** The line between trusted and untrusted data blurs.

**Case stories (as told by the instructor) [2]:**

| Case | What happened | Lesson |
| --- | --- | --- |
| Insecam (2014) | A Russian site streamed 8,000+ unsecured cameras still using default passwords; researchers had flagged a flaw affecting 400,000 D-Link cameras | Change factory-default passwords |
| St. Jude Medical (2016) | MedSec skipped responsible disclosure and partnered with short seller Muddy Waters; the stock fell about 5% in a day, nearly $1 billion | Ethics of disclosure: white hat, black hat or in between? |
| Stuxnet (2010) | Malware widely believed to be US-Israeli reached Iran's air-gapped Natanz plant via a USB stick, wrecked centrifuges and spoofed normal readings | First known cyberattack causing physical damage |
| Change Healthcare (Feb 2024) | Stolen low-level credentials, no multi-factor authentication and slow detection; $22 million paid; the ALPHV/BlackCat group then kept the money, and a splinter group (RansomHub) threatened a second extortion; 193 million people's data exposed | Most breaches start with people and missing basics |

**Ransomware** is now an industry: attacks rose about 25% from 2024 to 2025, and developers, attackers, brokers, negotiators and launderers each play a part. Healthcare is targeted because downtime endangers patients, medical records keep their value, and legacy systems are hard to patch [2].

**Generative AI.** The lecture cites The Economist's view that GenAI cannot reliably separate data from instructions, which enables prompt injection (a researcher hid commands in a LinkedIn bio and AI outreach tools leaked their system prompts). The "lethal trifecta" is untrusted content plus private data access plus the ability to act. The defense is to avoid combining all three, limit AI autonomy, and monitor [2].

**Takeaways:** Everything is hackable; security is a continuous process owned by everyone; most breaches start with people; analysts should treat external data as untrusted; leaders should ask who has access to what and how a breach would be contained [2].

## 3. Customer insight and problem definition

**Innovation is a numbers game [3].** The lecture contrasts "95% of GenAI pilots fail" (an MIT study as cited) with pharma R&D (about 93% fail), venture capital (returns concentrate in about 6% of investments), new product launches (about 50% miss targets) and ERP systems (about 75% fail). Odds improve with problem-first innovation, disciplined experimentation and customer validation.

**Start with the problem, not the solution [3].** The Segway had a famous inventor, a large budget and advanced technology, yet sold about 24,000 units in five years against a plan of 10,000 per week. It was built in secrecy, without customer validation or segmentation: an invention, not an innovation.

**Jobs to be done [3][9].** A job is the outcome a customer wants in a context; it is stable over time and solution-agnostic (Walkman, then iPod). It has three dimensions: functional (what I want to do), emotional (what I want to feel) and social (how I want to be seen). A monetizable job also needs people who will pay, and a problem is judged on intensity (shark bite or mosquito bite), frequency and density (market size). The HBR article makes the same case that customers "hire" products to do a job; I could access only a summary, not the full text [9].

**Research tools, from cheap and shallow to costly and deep [3]:** existing data, surveys, voice-of-customer interviews, ethnography, experiments. The instructor's two pet peeves are surveys (they lack the "why," and are best used after interviews to size a known problem) and focus groups (loud voices bias the room). Opinions are not behavior: "it's easy to open your mouth, hard to open your wallet" (shampoo buyers say ingredients but actually smell the bottle).

**Defining the problem worth solving [4]:**
- **Align on a metric and a baseline.** "Make the GenAI chat better" is vague; "cut response time to under 10 seconds" gives everyone a target. Beware the HIPPO (Highest Paid Person's Opinion): "If we have data, let's look at data. If all we have opinions, let's go with mine."
- **Ask why repeatedly.** The five-why method (Toyota, 1950s) is shown through the Jefferson Memorial parable: erosion, cleaning, bird droppings, spiders, insects, then floodlights on too early. Delaying the lights fixed the root cause.
- **Airport capstone:** To raise revenue, a team found concessions were the controllable lever, data showed dwell time and perceived dining value correlated with spending, and interviews revealed travelers did not know the airport enforces street pricing. 7 of 11 said knowing would make them buy more, which still needs experiments to confirm.

## 4. Voice-of-customer interviews: recruiting and the discussion guide

This feeds directly into the #2 Project Plan, where the Canvas assignment requires at least 3 respondents from the same organization for process projects, or 5 to 10 for market insights projects [5][6][8].

**Recruitment [5]:**
- **Screening:** Define your respondent profile and count first. If a sponsor lines up interviews, send a short email with the purpose, the time needed and a clear call to action.
- **Finding people:** Social posts (LinkedIn, Facebook, Reddit) with an attention-grabbing tagline, a picture and a clear next step, or your own network.
- **Screener survey:** A short multiple-choice form (age and income brackets, not exact values) that filters for people who actually do the activity; state that responses are used only for the class and stay private.
- **Tools:** Calendly for scheduling, Zoom to record (with consent), Otter.ai to transcribe, a content grid of quotes by question, and Miro or slides to share insights.

**Running the interview [6]:**
- Open briefly, ask permission to record, and be present (a note-taker is fine).
- Ask for stories ("When was the last time you...?"), "snorkel" the surface and "deep dive" when you hear strong emotion ("tell me more"), and avoid speculation about future behavior.
- Do not pitch, imply the person has a problem, or ask leading yes/no questions; favor what, when, where, who, how and why.
- Observe behavior, not opinions. Interviews can be an hour on as few as five questions.

## 5. Class prep: recordings, HBR reading and questions for Kristy Edwards

**The six recordings: one mini-section each**

### Siebel Chapter 3: The Information Age Accelerates (26:25) [1]

- **Layered loop:** Cloud, big data, AI and IoT reinforce each other (a connected car's sensors feed the cloud, the data is aggregated, models learn, and results flow back to navigation). Cloud turns capital expense into operating expense, and the big data challenge is now trust (quality, governance, bias).
- **Business model first:** A business model defines how value is created, delivered and captured (Netflix works, WeWork's long leases against short memberships did not). People adopt technology that helps them hit their KPIs, and adoption varies by function: IT about 62%, marketing and sales about 40%, operations cautious, HR, finance and legal slowest (figures as cited).
- **Adoption gap:** Generative AI pilots reportedly fell from about 25% of companies to about 18% actively using it, and McKinsey is cited saying about 30% of today's hours could be automated by 2030.

### Cyber Security (length not listed) [2]

- **How security evolved:** From a defensive wall, to detection and response (banks flagging unusual card use), to security by design, Zero Trust ("never assume, always verify") and resilience planning.
- **New surfaces:** IoT (default passwords on cameras, a pacemaker flaw used to short a stock, Stuxnet), cloud (ransomware as an industry, the Change Healthcare breach) and AI (prompt injection and the "lethal trifecta" of untrusted content, private data and the ability to act).
- **Takeaway:** Everything is hackable, most breaches start with people, and external data should be treated as untrusted until verified.

### The Importance of Customer Insight in Innovation & Transformation (19:19) [3]

- **Innovation is a numbers game:** Failure rates are high everywhere (the lecture cites 95% of generative AI pilots, about 93% of drugs, about 75% of ERP projects). Odds improve with problem-first thinking, disciplined experiments and customer validation. The Segway is the cautionary tale of a solution looking for a problem.
- **Jobs to be done:** A job is the outcome a customer wants in a context, stable over time and solution-agnostic, with functional, emotional and social dimensions. A problem is judged on intensity (shark bite or mosquito bite), frequency and density, and must be monetizable.
- **Research tools:** Existing data, surveys, voice-of-customer interviews, ethnography and experiments, from cheap and shallow to costly and deep. Surveys and focus groups are weak at finding the "why," and "it's easy to open your mouth, hard to open your wallet."

### Problem Definition (12:00) [4]

- **Metric and baseline:** "Make our GenAI chat better" is vague; "cut response time to under 10 seconds" is a target everyone can work toward. Beware the HIPPO, the Highest Paid Person's Opinion.
- **Five whys:** Keep asking why until you reach the root cause, a method from Toyota in the 1950s. In the Jefferson Memorial parable, erosion traced back to bird droppings, spiders, insects and finally the timing of the floodlights.
- **Airport case:** To raise revenue, a student team found concessions were the controllable lever, then interviews showed travelers did not know the airport enforces street pricing; 7 of 11 said knowing would make them buy more. Experiments would still be needed to confirm.

### VOC Recruitment and Interview Plan (7:29) [5]

- **Recruiting:** Define screening criteria and a respondent profile first. If a sponsor lines up interviews, send a short email with the purpose, time needed and a call to action; otherwise use social posts (tagline, picture, clear next step) or your own network.
- **Screener:** Keep it short and mostly multiple choice, use brackets for age and income, state that answers are used only for the class, and start with a closed question that checks the person actually does the activity.
- **Tools:** Calendly for scheduling, Zoom to record and Otter.ai to transcribe (with consent), a content grid of quotes by question, and Miro or slides to share insights.

### VOC Discussion Guide & Problem Interviews (4:26) [6]

- **Run the conversation:** Open briefly, chat to put the person at ease, and ask permission to record. Ask for stories ("When was the last time you...?"), stay on the surface like a snorkeler until you hear strong emotion, then dive deeper ("tell me more").
- **Avoid:** Speculation about future behavior, pitching, implying the person has a problem, and leading yes/no questions. Favor what, when, where, who, how and why, and add "or not" to a yes/no question.
- **Practicalities:** A note-taker is fine as long as the interviewer is fully present; other team members can send questions by chat. Two sample discussion guides are on Canvas.

**HBR article: "Know Your Customers' 'Jobs to Be Done'" (Christensen, Hall, Dillon and Duncan, Sept 2016) [9]**

*Summary written from the full text; paraphrased, with short quotes only.*

- **The problem:** Executives rate innovation as critical (84% in a McKinsey poll cited) but 94% are dissatisfied with their results, even though firms have more customer data than ever. The authors blame data built around correlations: customers who look alike, or a share who prefer version A. A 64-year-old, six-foot-eight reader of the *New York Times* does not buy it because of his age, height or shoe size, but because of a specific need in a specific moment.
- **The core idea:** Focus on the progress a customer is trying to make in a given circumstance, the "job to be done." People "hire" a product for a job and "fire" it if it does the job badly. Disruption theory explains how incumbents get beaten; jobs theory explains how to create things customers want to buy because it reaches the causal driver of a purchase.
- **Condo example:** A Detroit-area builder targeting downsizers got traffic but few sales, and adding features like bay windows did not help. Consultant Bob Moesta had buyers draw a timeline of how they got there, and found no demographic or feature pattern. What stood out was the dining room table: buyers could not move until they decided what to do with something that represented their family. The builder made room for a table, cut the second bedroom to do so, and added moving services, two years of storage and a sorting room. It raised prices by $3,500, and in 2007, while industry sales fell 49%, it grew 25%.
- **Four principles of a job:** It is about what someone wants to accomplish in a circumstance, not just a task. Circumstances matter more than customer traits, product attributes or trends (the condos competed with not moving at all). Good innovations solve problems with poor or no existing solutions. Jobs always have social and emotional dimensions, not just functional ones.
- **Beyond the job:** Nielsen found only 92 of more than 20,000 new products from 2012 to 2016 sold over $50 million in year one and held sales in year two, and each solved a specific, poorly done job (for example, Reese's Minis, with $235 million in two years). Lasting advantage then needs the right customer experience (American Girl sells experiences and stories, not just dolls; no detail was too small, even the box's "belly band") and aligned processes (Southern New Hampshire University redesigned its admissions and support around adult online students, with a goal of a follow-up call within 8.5 minutes and a personal adviser for each student).
- **Five questions to find jobs:** Do you have a job that needs doing yourself (American Girl, Care.com)? Where do you see nonconsumption (SNHU's older learners)? What workarounds have people invented (small businesses using Quicken, which led Intuit to a new market)? What tasks do people want to avoid, the "negative jobs" (CVS MinuteClinic)? What surprising uses have customers found (NyQuil taken for sleep led to ZzzQuil)?
- **B2B sidebar:** Intercom's cofounder Des Traynor describes how interviews with new and churned customers showed four jobs (observe, engage, learn, support). Customers used different words than the company did, and the company moved from one all-in-one price to four services.

**How it connects to your class project:** Moesta's method is the same kind of voice-of-customer interview as the lecture [3][6]: reconstruct the timeline of what led to a decision and look for the pushes (a problem to solve) and the pulls back (inertia, anxiety). When you interview for the Project Plan, ask about the last time someone dealt with the problem, not what feature they want, and note the social and emotional side of the job along with the functional side.

**Kristy Edwards: a point of view and questions [11]**

Her talk argues that AI-era attacks are mostly old threats at greater scale and speed plus a few new ones such as prompt injection and agents acting on their own; defenders must cover both, and security must be everyone's responsibility.

- **A point of view you could bring:** In regulated or high-stakes settings, the question is rarely whether a team can build something, but whether it can get permission to deploy it. Security by design, least-privilege access and guardrails on agents are how teams earn that permission, so safeguards enable adoption instead of only blocking it. Use this only if it matches your own view.
- **Questions:**
  1. You said agents force us to rethink permissions, identity and data access. What does least privilege look like for an AI agent in practice, and who should approve it?
  2. For organizations that build decisions on sensor and equipment data, where would you start securing the pipeline, and how should teams treat inbound data given prompt injection?
  3. You said security is underfunded because success is invisible. How do you make the business case to leadership before an incident?
  4. With attackers and defenders both gaining from AI, what is the first thing a non-security leader should do in the next 90 days?
- **Attribution:** Her claims about April and July 2026 AI security events are hers and were not independently verified, so attribute them to her if you cite them. The captions spell her name "Christy" and Canvas spells it "Kristi" or "Kristy."

## References

1. *Week 2: Siebel Chapter 3, The Information Age Accelerates* (26:25), lecture. PSU Media Space. https://media.pdx.edu/media/t/1_18aoqiew
2. *Cyber Security* lecture, MGMT 518. PSU Media Space. https://media.pdx.edu/media/t/1_0avfv025
3. *The Importance of Customer Insight in Innovation & Transformation* (19:19). PSU Media Space. https://media.pdx.edu/media/t/1_8n2r81ch
4. *Problem Definition* (12:00). PSU Media Space. https://media.pdx.edu/media/t/1_5mk7gxc7
5. *VOC Recruitment and Interview Plan* (7:29). PSU Media Space. https://media.pdx.edu/media/t/1_us1c8o3y
6. *VOC Discussion Guide & Problem Interviews* (4:26). PSU Media Space. https://media.pdx.edu/media/t/1_xvri7q7v
7. *Course Overview* (12:09), Week 1. PSU Media Space. https://media.pdx.edu/media/t/1_iog44gq1
8. *MGMT 518 Digital Transformation, Fall 2026* (PSU Canvas): Week 2 module page, module list and assignments, read 2026-10-03. https://canvas.pdx.edu/courses/120638/modules and https://canvas.pdx.edu/courses/120638/assignments (requires PSU login)
9. Christensen, C. M., Hall, T., Dillon, K., & Duncan, D. S. (2016, September). Know your customers' "jobs to be done." *Harvard Business Review*, September 2016 issue (HBR Reprint R1609D). https://hbr.org/2016/09/know-your-customers-jobs-to-be-done (summarized from a full-text copy you supplied; the copy is marked for individual research use, so it is not reproduced here)
10. Siebel, T. M. (2019). *Digital Transformation: Survive and Thrive in an Era of Mass Extinction*. RosettaBooks. (Optional reading; summarized here only via [1].)
11. *Guest Speaker: Kristy Edwards, Cyber Security & AI* (33:19), Week 1 recording. PSU Media Space. https://media.pdx.edu/media/t/1_a45y49qc

*Note:* Items 1 to 7 and 11 are summarized from the English captions of each video; item 9 is summarized from the article text you supplied. Slides, the Project Plan Examples and the Discussion Guide files on Canvas were not read. Third-party facts (Segway, Stuxnet, Change Healthcare, MIT and McKinsey figures and so on) are reported as the instructors present them.
