# Digital Transformation of Business (MGMT 518): Week 2 Dossier

*Prepared 2026-10-03. Week 2: Technology Drivers, Cyber Security, and the Role of Customer Insight. Bracketed numbers [n] point to the References section. Statistics are as quoted by the instructors in the lectures and were not independently verified.*

Week 2 moves from what the technology is to why it is adopted, attacked or abandoned: technology only succeeds when it serves a business model, is secured by design, and solves a validated customer problem [1][2][3].

## TODO (Week 2)

Due dates are from the Canvas assignment list, Pacific time [8]. Week 2 opens Mon Oct 5 [8].

- [ ] **Before class (Mon Oct 5 on Zoom or Tue Oct 6 in person, per the course overview; confirm time in Canvas):** Watch the six recordings and read the HBR article. Kristy Edwards joins the class, so bring a point of view or a question [7][8]
- [ ] **Before class:** Read "Know Your Customers' Jobs to Be Done" (HBR, Sept 2016) [9]
- [ ] **Before the Project Plan:** Review the Project Plan Examples and Best Practices, the Discussion Guide Template and the Discussion Guide Best Practices (Canvas files, not read for this dossier) [8]
- [ ] **Sun Oct 11, 11:59 PM:** #1 Icebreaker & Team Contract (5 pts) [8]
- [ ] **Sun Oct 11, 11:59 PM:** #2 Project Plan (15 pts), including your interview schedule [7][8]
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

This feeds directly into the #2 Project Plan, where the Week 1 overview calls for 3 to 4 interviews on a single organization's process or 5 to 10 for a broader view [5][6][7].

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

## References

1. *Week 2: Siebel Chapter 3, The Information Age Accelerates* (26:25), lecture. PSU Media Space. https://media.pdx.edu/media/t/1_18aoqiew
2. *Cyber Security* lecture, MGMT 518. PSU Media Space. https://media.pdx.edu/media/t/1_0avfv025
3. *The Importance of Customer Insight in Innovation & Transformation* (19:19). PSU Media Space. https://media.pdx.edu/media/t/1_8n2r81ch
4. *Problem Definition* (12:00). PSU Media Space. https://media.pdx.edu/media/t/1_5mk7gxc7
5. *VOC Recruitment and Interview Plan* (7:29). PSU Media Space. https://media.pdx.edu/media/t/1_us1c8o3y
6. *VOC Discussion Guide & Problem Interviews* (4:26). PSU Media Space. https://media.pdx.edu/media/t/1_xvri7q7v
7. *Course Overview* (12:09), Week 1. PSU Media Space. https://media.pdx.edu/media/t/1_iog44gq1
8. *MGMT 518 Digital Transformation, Fall 2026* (PSU Canvas): Week 2 module page, module list and assignments, read 2026-10-03. https://canvas.pdx.edu/courses/120638/modules and https://canvas.pdx.edu/courses/120638/assignments (requires PSU login)
9. Christensen, C. M., Hall, T., Dillon, K., & Duncan, D. S. (2016, September). Know your customers' "jobs to be done." *Harvard Business Review*. https://hbr.org/2016/09/know-your-customers-jobs-to-be-done (premium article; only a web summary was accessible, not the full text)
10. Siebel, T. M. (2019). *Digital Transformation: Survive and Thrive in an Era of Mass Extinction*. RosettaBooks. (Optional reading; summarized here only via [1].)

*Note:* Items 1 to 7 are summarized from the English captions of each video. Slides, the Project Plan Examples and the Discussion Guide files on Canvas were not read. Third-party facts (Segway, Stuxnet, Change Healthcare, MIT and McKinsey figures and so on) are reported as the instructors present them.
