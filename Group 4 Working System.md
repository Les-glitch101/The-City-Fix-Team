# Group 4 working system

Pothole Reporting and Repair Tracking. Four members, four weeks. Proposal due Friday 9 October at 12pm, everything due Thursday 29 October. This document is how we work so nobody drowns and nothing lands at the last minute.

## The method: phased SDLC

We follow the Software Development Life Cycle in phases across the four weeks:

1. Planning and Requirements (week 1)
2. Design (week 2, with the build of the core reporting flow starting mid-week)
3. Implementation and Testing (weeks 2 to 3)
4. Evaluation and Documentation (week 4)
5. Final delivery and presentation (29 October)

Why this model, in one paragraph we can reuse in the dissertation and the Q&A: the timeline was fixed at four weeks, the scope was defined at proposal stage, and the team is small, so a phased SDLC with verification built into every phase fit better than an open-ended iterative approach. Each phase produces a deliverable that feeds a dissertation chapter, and testing runs through design and implementation rather than waiting for a single test phase at the end.

Each phase ends with a gate: the whole group reviews the phase deliverable before the next phase opens. If a gate slips by more than two days, we cut scope from the backlog, never from testing or documentation.

## The daily cycle

- Every morning, 15 minutes, same time: each person says three things. What I finished yesterday. What I'm doing today. What's blocking me. In person on campus, otherwise in the WhatsApp group before 9am.
- Tasks are written as 1 to 3 hour pieces of work. One task in progress per person. Finish it, then pull the next from the phase plan below.
- A task is done only when one other member has checked it. Code gets run by someone else, a document section gets read by someone else. Anything finished moves to the Review column until checked.

## Board and tools

GitHub Projects, since we're already on GitHub. Columns: Backlog, This week, In progress, Review, Done. Maximum four cards in In progress, one per person. Every card names its owner, what done looks like, and the day it's due. WhatsApp for daily check-ins, Google Docs for the dissertation draft.

## Roles

| Person | Build role | Dissertation criterion (rubric marks) |
|---|---|---|
| Lesiamo | Lead. Backend and database (API, MySQL schema) | A3 SE methodology and architecture (4) and A5 academic writing (4). Also Miss Lee liaison, deadlines, dissertation assembly |
| Crystal | Frontend: mobile reporting form and reporter status tracker | A2 literature review and background (4) |
| Kgosi | Staff dashboard, Leaflet map, duplicate matching, priority rules | A1 problem definition and domain analysis (3); data and figures that feed A4 |
| Raymond | Testing and QA: test plan, test cases, usability sessions | A4 system evaluation and results (5). Also slides and rehearsal direction |

Swap if someone's actual skills say otherwise. The split that matters: one person owns the reporter-facing app, one owns the staff-facing app, one owns the server, one owns proving the thing works.

## Dissertation chapters by rubric criterion

Each person owns one numbered criterion and writes that chapter. All first drafts are due Friday 23 October, then Lesiamo assembles. What the exemplary band requires from each:

1. A1, Problem definition (Kgosi, 3 marks): problem framing, user stories, software context, real-world relevance. Built from the Region B and AA figures, the stakeholder table, user stories for motorists and staff, and a scope statement.
2. A2, Literature review (Crystal, 4 marks): critical review of existing tools and literature, not a listing. The comparison table of reporting tools from week 2 becomes the spine; every claim cited, IEEE style.
3. A3, SE methodology and architecture (Lesiamo, 4 marks): justified SDLC choice, architecture and UML diagrams, tech stack justification. Kgosi draws the diagrams in week 2, Lesiamo writes the rationale around them.
4. A4, System evaluation (Raymond, 5 marks): empirical testing, results interpretation, usability metrics, feasibility. Kgosi's figures and triage metrics feed in; Raymond interprets them.
5. A5, Academic writing (Lesiamo, 4 marks): formatting, logical progression, grammar, consistent referencing. One voice pass over the whole document on Monday 26, Turnitin check Tuesday 27, similarity under 15%.

Handoffs that make the integration work: Kgosi passes his diagrams to Lesiamo by Friday 16, his figures to Raymond by Thursday 22, and Crystal passes her reference list to Lesiamo by Monday 26.

## Week by week, day by day

Week 1, Planning and Requirements (Mon 5 to Fri 9 Oct)

| Day | Lesiamo | Crystal | Kgosi | Raymond |
|---|---|---|---|---|
| Mon 5 | Proposal page drafted from the group's notes | Verify the Region B and AA figures and save the sources | Set up GitHub repo, board and folder structure | Draft interview questions for drivers |
| Tue 6 | Stakeholder section and proposal formatting | Start literature scan: existing pothole reporting tools | Repo scaffolding: React front end, backend skeleton | Interview questions for roads staff; attempt contact with Region B |
| Wed 7 | Final proposal text, group sign-off | Literature notes into the shared doc | Draft database schema for reports, users, statuses | Recruit 7 drivers for usability testing |
| Thu 8 | Apply the group's corrections to the proposal | Read and correct the proposal page | Read and correct the proposal page | Read and correct the proposal page |
| Fri 9 | Submit to Miss Lee on Teams by 12pm | Requirements list v1 from interview answers | Requirements list v1, technical view | Confirm test participants, store their details |

Week 2, Design and start of build (Mon 12 to Fri 16 Oct)

| Day | Lesiamo | Crystal | Kgosi | Raymond |
|---|---|---|---|---|
| Mon 12 | API endpoint design | Wireframes: reporting form and status tracker | Architecture diagram and UML use case diagram | Test plan skeleton and usability task scripts |
| Tue 13 | Database schema final, migrations written | Build the reporting form UI | Leaflet map spike on a test page | Comparison table of existing tools for the literature review |
| Wed 14 | Report submission endpoint and photo storage | Wire GPS capture and photo upload to the API | Duplicate detection design, map clustering | Write test cases for the reporting flow |
| Thu 15 | Backend fixes from integration | Reporter status tracker page | Staff dashboard shell | First internal test of the reporting flow, log every bug |
| Fri 16 | Phase 2 gate: demo the reporting flow to the group | Same | Same | Write up test results; methodology notes for the dissertation |

Week 3, Implementation and Testing (Mon 19 to Fri 23 Oct)

| Day | Lesiamo | Crystal | Kgosi | Raymond |
|---|---|---|---|---|
| Mon 19 | Staff API: list reports, filter, update status | Status tracker polish, notification stubs | Backlog map on the dashboard | Test cases for duplicate matching |
| Tue 20 | Priority classification endpoint | Merge-duplicates UX so reporters see combined status | Priority rules and dashboard integration | Usability session prep: tasks, consent forms, devices |
| Wed 21 | Duplicate detection live, bug fixes | Bug fixes | Bug fixes | Usability sessions 1 to 3 |
| Thu 22 | Bug fixes | Bug fixes | Collect metrics: time to triage with and without priority classification | Usability sessions 4 to 7, triage comparison test |
| Fri 23 | Methodology chapter draft (A3) | Literature review draft (A2) | Problem definition and introduction draft (A1); figures to Raymond | Evaluation chapter draft (A4) |

Week 4, Evaluation, Documentation, Delivery (Mon 26 to Thu 29 Oct)

| Day | Lesiamo | Crystal | Kgosi | Raymond |
|---|---|---|---|---|
| Mon 26 | Assemble dissertation; academic writing pass (A5) | Reference list finalised, handed to Lesiamo | Evaluation charts final, working with Raymond | Slides v1 |
| Tue 27 | Turnitin check, similarity under 15% | Fixes from Turnitin report | Record a backup demo video | Rehearsal 1 and Q&A practice, note the gaps |
| Wed 28 | Submit dissertation via the portal, one day early | Final read of the dissertation | Final read of the dissertation | Rehearsal 2, full dress, slides final |
| Thu 29 | Final presentation and demo | Same | Same | Same |

## Evidence for marks

The rubric rewards proof, not claims. From day one we keep: a screenshot of the board every Friday, the phase gate review notes, interview questions and answers, test plans and test results, usability session notes with permission, and the Q&A practice questions. These feed the methodology section (criterion A3), the evaluation chapter (A4) and the group coordination part of the presentation (B3).

## Risks

- Testers cancel: we recruit 7 drivers in week 1 so losing 2 still leaves 5.
- Someone falls behind: the daily check-in catches it on day one, not deadline day. Lesiamo rebalances tasks the same day.
- Region B never answers: we proceed with the published figures and AA data, and note the limitation in the dissertation.
- Scope creep: new ideas go to the Backlog column. Nothing new enters the build after Tuesday of week 3; it becomes future work in the discussion chapter.
- Phase gates slip: cut scope from the backlog, never from testing or documentation.
