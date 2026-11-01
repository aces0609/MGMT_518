# MGMT 518, Week 5 Dossier: The Age of AI

*Prepared 2026-11-01. Bracketed numbers [n] point to the References. Statistics, stories and the guest's claims are as the speakers state them and were not independently verified. The research paper is summarized from its arXiv abstract and the Tech Xplore article; the full paper and the slide PDFs were not read. Siebel Chapter 6 was not re-read.*

**The week in one line:** AI has moved from generating answers to taking action, and the business questions have moved with it — what to let it do, how to prove value, and what constant AI help does to your own thinking [1][2][3][4].

## Contents

1. [TODO](#todo)
2. [Lecture: The Age of AI](#lecture-the-age-of-ai)
3. [Lecture update: AI at Work, From Answers to Action](#lecture-update-ai-at-work-from-answers-to-action)
4. [Guest: Jonathon Hensley, AI in Healthcare](#guest-jonathon-hensley-ai-in-healthcare)
5. [Reading: Human Creativity in the Age of LLMs](#reading-human-creativity-in-the-age-of-llms)
6. [How the pieces connect](#how-the-pieces-connect)
7. [References](#references)

---

## TODO

Due dates are from the Canvas assignment list, Pacific time [7]. The Week 5 module date is Oct 26.

**⚠️ Order matters for the Creativity quiz:** the module says to read the paper and the news article *without any AI help*, complete Part 1 of the quiz, and only then load the paper into an AI tool for Part 2 [7]. If you haven't done Part 1 yet, do it before reading the [Reading section](#reading-human-creativity-in-the-age-of-llms) below — that summary is exactly the AI assistance Part 1 asks you to avoid.

### Due tonight (Sun Nov 1, 11:59 PM)

| Item | Points |
| --- | --- |
| #3 Mid-Project Review (PDF progress deck) | 40 |
| Week 5 Quiz: Weekly Reflection | 5 |
| Week 5 Quiz: Creativity in the Age of AI (two parts; see note above) | 5 |

### Before the in-person session

- [ ] Watch "The Age of AI" (19:20) [1]
- [ ] Watch "AI at Work, From Answers to Action" (13:36) — it ends with homework: pick an organization you know and one process where AI could *execute*, what value that creates, and what could go wrong, for class discussion [2]
- [ ] Watch the Jonathon Hensley interview (duration not listed); he joins the class in person in November, so bring a question [3][7]
- [ ] Read the Kumar et al. paper and the Tech Xplore article (without AI first; see warning) [4][5][6]
- [ ] Optional: Siebel Ch. 6, The Age of AI [8]

**Looking ahead:** Week 6 Quiz is due Sun Nov 8, and #4 Story Line (25 pts) is due Sun Nov 15 [7].

---

## Lecture: The Age of AI

*Instructor lecture (19:20) [1]. The lecture explicitly goes beyond Siebel, whose 2019 book treated AI as emerging but not yet mainstream.*

- **Origins:** AI began as an academic concept in the 1950s — Turing's imitation game ("can machines think?"), then the 1956 Dartmouth workshop where John McCarthy coined the term. What changed since isn't the ambition, it's the accessibility [1].
- **Timeline to now:** expert systems in the 1980s (limited by compute), cloud and big storage in the 2010s, enterprise pilots around 2015, ChatGPT's launch (the lecture places mass adoption in 2023), and now reasoning models and agentic AI. A key catalyst was Google's 2017 transformer paper: a model that predicts the next token and iterates, which is why the same question can get two different answers — pattern recognition, not consciousness [1].
- **Terminology to keep straight:** AI ⊃ machine learning ⊃ deep learning; expert systems, NLP, statistics, data engineering and BI all sit nearby under "data science," which is why "data scientist" and "AI" mean different things at different organizations [1].
- **A model = algorithm + data,** and it lives in a cycle: collect and prepare data, train and test, deploy, monitor, retrain. Models are "harvested and farmed," not built once [1].
- **Data strategy:** structured vs unstructured data; public scraped data is free but unreliable, so firms buy proprietary data (the lecture's Wall Street Journal example) — the combination of data you wield makes your model unique [1].
- **Three learning types:** supervised (labeled data, human-heavy), unsupervised (the machine finds the patterns), reinforcement (rewards; how game-playing AI learned) — usually blended [1].
- **Agentic AI:** from thinking to acting — ChatGPT suggests the pumpkin pie recipe; an agent plans, shops, and schedules the delivery for your free afternoon [1].
- **Challenges:** garbage in, garbage out; biased hiring tools; hallucination and opacity; change management ("organizations need to do more than just ask employees to use AI"); proving ROI at scale; ethics and trust. Closing: AI is "a new operating system for business" — but by itself it is not a strategy [1].

## Lecture update: AI at Work, From Answers to Action

*Supplemental lecture (13:36) [2]. The central question: when does AI stop being a tool employees use and become a system that performs the work?*

- **Enterprise AI is three things:** the foundation model + the company's business context + integration into workflows. Two companies can use the same model and get very different results; the advantage is in the data, processes and integration [2].
- **Three capability shifts:** reasoning (multi-step problems, scenario evaluation), multimodality (text, images, audio together), and tool use. Combined, they make AI useful in processes — but "greater capability does not automatically mean greater reliability" [2].
- **Co-pilot → agent → multi-agent:** a co-pilot drafts and a human sends; an agent looks up the order, applies the refund policy, and acts within limits; multi-agent systems coordinate specialists across a workflow. More autonomy demands stronger controls — the business decision is *how much autonomy, under what circumstances* [2].
- **Build, buy or integrate:** buying AI already embedded in your CRM/ERP/HR platform is often fastest; integration connects a foundation model to proprietary data; building is rarely better. Five factors: differentiation, access to data, risk, speed to value, total cost of ownership [2].
- **Demo ≠ deployment:** a disciplined delivery lifecycle starts from the business problem and baseline, tests how often the system is wrong and what happens when it's wrong, then deploys, monitors and improves [2].
- **ROI discipline:** time saved is not realized value. Value shows up as more cases resolved with the same staff, retention, fewer errors — and the full cost includes integration, oversight, training and adoption. "A solution that employees don't use isn't going to deliver its projected benefits" [2].
- **Five executive questions:** where to apply AI; how to implement it; how to prove it works; who owns the outcome; what decisions stay human [2].

## Guest: Jonathon Hensley, AI in Healthcare

*Interview with the instructor (duration not listed). Hensley is a tech and healthcare advisor and fractional chief product officer [3][7]. Claims below are as stated by the speaker, not independently verified. The module spells his first name "Jonathon"; the captions use "Jonathan."*

- **Where AI is landing:** ambient AI on the patient side; on the provider side, transcribing encounters into SOAP notes for the EMR/EHR. But technology has pushed work *upstream* onto physicians — the doctor now does data entry a back office once did. His OB-GYN anecdote cuts both ways: transcription saves a bad typist time, but she checks everything, and a good typist might be slower overall [3].
- **The efficacy bar is higher:** a business tool that's right 85-86% of the time is fine; in healthcare "it has to be closer to 96%," because small errors (a dosage fraction) carry massive liability [3].
- **Systems of record → systems of action:** 30 years of digitization built records; the promise of AI is action — surfacing the relevant history in a 15-minute visit. The blockers are fragmentation and interoperability (standards like FHIR/HL7 exist, but vendors gate access), data quality, and privacy ("how do I protect the data from leaking into the model") [3].
- **Adoption is a human problem:** his rough split — 2-5% of staff become advanced users, ~70% dabble, the rest opt out. A hospital group (about 8 hospitals, 65 clinics) licensed AI tools for everyone and almost no one used them, because nobody defined the use cases per job function. Leaders must define "what good looks like" or the AI can't be trained to produce it [3].
- **Payers move fastest:** claims intake is well-defined, so AI scores what can auto-approve and humans handle the complex cases [3].
- **Fragmentation, lived:** his son got sick while traveling — an hour of paperwork across three systems, entering the same information repeatedly. "We put the burden on the patient" [3].
- **Futures:** simplification of the cost structure, a consolidated patient-owned health picture, wearables feeding continuity of care rather than episodic visits [3].
- **Security vs ethics:** security is table stakes (SOC 2, HITRUST — captions garble these) and mostly a people-and-culture problem; the ethics questions are live — disclosure, AI never prescribing without human review, and the radiology debate: if AI out-detects a specialist, where does the human sit, and does efficiency become taking advantage? [3]
- **Advice to students:** build cross-functional relationships ("understand their problems and what good looks like"); possible ≠ practical, so pencil out back-of-the-napkin ROI; and practice empathy — don't push the burden onto patients who arrive at their worst [3].

## Reading: Human Creativity in the Age of LLMs

*Kumar, Vincentius, Jordan & Anderson (University of Toronto), arXiv preprint [4]. Summarized from the abstract [4] and the Tech Xplore article [5]; the full paper was not read. **Do quiz Part 1 before reading this section** [7].*

- **Design:** two pre-registered experiments, about 1,100 participants, on the two core components of creativity: divergent thinking (alternative uses for an object) and convergent thinking (find the fourth word connecting three, e.g. "book" connects shelf, log, worm). During exposure rounds, participants got either GPT-4o answers, coach-like GPT-4o guidance, or no help; then everyone did a final round unassisted [4][5].
- **Findings:** LLM help boosted performance *while in use*, but in the unassisted test the no-AI control group outperformed those who had used the LLM. Idea homogenization persisted after the AI was removed — and was *more* pronounced for the coach-like condition. The co-author's analogy: "similar to the temporary boost provided by performance-enhancing steroids in sports" [5].
- **Why the course assigns it this way:** the two-part quiz has you experience exactly this — your own unassisted reading first, then the AI-assisted reading, then a reflection on the difference [7].

---

## How the pieces connect

- **Answers → action is the spine of the week:** the first lecture ends at agentic AI [1], the second builds the management frame for it (autonomy vs control, who owns the outcome) [2], and Hensley shows the same move as "systems of record → systems of action" in the hardest industry to do it [3].
- **The adoption numbers rhyme:** Hensley's 2-5% advanced users and the unused hospital licenses [3] are Week 3's trust-and-ownership story and the first lecture's change-management warning [1] — capability without defined use cases per role delivers nothing.
- **The creativity study is the counterweight:** the week's lectures are about delegating more to AI; the paper warns that constant delegation can erode the unassisted skill [4][5]. That tension — where AI amplifies versus where it atrophies — is the discussion the two-part quiz sets up.
- **For your project:** the Mid-Project Review is due tonight; the "AI at Work" homework (one process AI could execute, the value, the risk) is also a ready-made frame for your team's solution directions [2].

---

## References

1. *The Age of AI* (19:20; the Media Space title says "Week 4"). PSU Media Space. https://media.pdx.edu/media/t/1_d8utcay3
2. *AI at Work, From Answers to Action* (13:36). PSU Media Space. https://media.pdx.edu/media/t/1_3oq4em38
3. *Guest Speaker Jonathon Hensley, AI in Healthcare* (duration not listed). PSU Media Space. https://media.pdx.edu/media/t/1_zz6iydtg
4. Kumar, H., Vincentius, J., Jordan, E., & Anderson, A. (2024). *Human Creativity in the Age of LLMs: Randomized Experiments on Divergent and Convergent Thinking.* arXiv:2410.03703. https://arxiv.org/abs/2410.03703 (abstract read; full paper not read for this dossier)
5. Fadelli, I. (2024-10-30). "Study explores the impact of LLMs on human creativity." Tech Xplore. https://techxplore.com/news/2024-10-explores-impact-llms-human-creativity.html (read 2026-11-01)
6. PSU Library permalink for the paper (PSU sign-in required). https://search.library.pdx.edu/permalink/01ALLIANCE_PSU/aef15q/cdi_proquest_journals_3301569877
7. *MGMT 518 Digital Transformation, Fall 2026* (PSU Canvas): Week 5 module page and assignment list, read 2026-11-01. https://canvas.pdx.edu/courses/120638/modules (requires PSU login)
8. Siebel, T. *Digital Transformation*, Chapter 6, "The Age of AI" (optional; not re-read — the lecture [1] summarizes and extends it)

*Note:* Items 1-3 are summarized from the English captions of each video; slides were not read. Caption errors are left as-is in the transcripts file, including "the AI execution error" (likely "era") opening the second lecture, "CHAP-GPT"/"Chachapiti" for ChatGPT, "agentic AR" for agentic AI, and "fire HL7" (likely FHIR/HL7) and "sock to"/"high trust" (SOC 2/HITRUST) in the Hensley interview. The lecture places ChatGPT's launch in 2023; it launched in late November 2022, so treat that date as the lecture's framing of mass adoption.
