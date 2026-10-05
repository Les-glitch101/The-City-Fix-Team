# Group 4 working system

Pothole Reporting and Repair Tracking. Four members, four weeks. Proposal due Friday 9 October at 12pm, everything due Thursday 29 October. This document is how we work so nobody drowns and nothing lands at the last minute.

The system has two halves. The five workstreams below are organised by the rubric criteria, because that is what we are marked on. The weekly grids near the end are the calendar that makes the workstreams happen day by day.

## How we run: phased SDLC

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

## Thursday nights and Friday showcases

Every Friday we show the group's progress, so Thursday night is evidence night. From 8pm, about an hour, all four, on campus or on a call. Each person brings proof of their own week: screenshots of what they built, their board cards moved, test results, draft pages. The night's output is a running showcase log (Google Doc) kept in five slide-sized blocks:

1. This week's goal and what shipped (Lesiamo)
2. The work, one block per member with a screenshot each (everyone writes their own)
3. Demo or walkthrough of the main thing that now works
4. Problems hit and decisions taken
5. Next week's plan (Lesiamo)

Friday, the blocks convert to slides in minutes and whoever built the demoed feature talks through it, so the talk stays balanced and nobody becomes the permanent speaker. Every deck gets saved. The decks are the evidence base for the coordination marks in B3 and the raw material for the final presentation.

Schedule: showcase 1 on Friday 9 October, straight after the 12pm proposal submission. Showcase 2 on Friday 16, which doubles as the phase 2 gate demo. Showcase 3 on Friday 23, with each author walking through their chapter draft. Week 4 has no Friday showcase; the final presentation on Thursday 29 replaces it.

## Board and tools

GitHub Projects, since we're already on GitHub. Columns: Backlog, This week, In progress, Review, Done. Maximum four cards in In progress, one per person. Every card names its owner, what done looks like, and the day it's due. WhatsApp for daily check-ins, Google Docs for the dissertation draft.

## The five workstreams

One criterion per person. The criterion is the chapter each of us is marked on; the build role is the work that feeds it. The marks in brackets are the rubric's.

| # | Rubric criterion | Marks | Owner | Build role feeding it |
|---|---|---|---|---|
| 1 | A1 Problem definition and domain analysis | 3 | Kgosi | Staff dashboard, Leaflet map, duplicate matching, priority rules |
| 2 | A2 Literature review and background | 4 | Crystal | Frontend: mobile reporting form and reporter status tracker |
| 3 | A3 SE methodology and architecture | 4 | Lesiamo | Lead: backend, database, API, Miss Lee liaison |
| 4 | A4 System evaluation and results | 5 | Raymond | Testing and QA: test plan, test cases, usability sessions |
| 5 | A5 Academic writing and structure | 4 | Lesiamo | Dissertation assembly, one-voice pass, Turnitin |

### Workstream 1: A1 Problem definition (Kgosi, 3 marks)

Exemplary band means exceptional clarity in the problem articulation, highly defined scope and user needs. Built from the Region B and AA figures, the stakeholder table, user stories for motorists and roads staff, and a scope statement.

- Week 1: verify the figures and save sources; stakeholder table; user stories started.
- Week 2: scope statement and problem framing final; draw the architecture and UML diagrams Lesiamo needs for A3.
- Week 3: full chapter draft by Friday 23; figures to Raymond by Thursday 22.
- Week 4: fold in gate feedback; final read of the whole dissertation.

### Workstream 2: A2 Literature review (Crystal, 4 marks)

Exemplary band means a critical review of existing solutions, not a listing, with flawless citations. The comparison table of reporting tools from week 2 is the spine of the chapter. Every claim cited, IEEE style.

- Week 1: verify the figures with sources (also feeds A1); scan existing pothole reporting tools.
- Week 2: comparison table of tools; reference list growing in IEEE format.
- Week 3: full chapter draft by Friday 23.
- Week 4: reference list finalised and handed to Lesiamo Monday 26; fixes from the Turnitin report.

### Workstream 3: A3 SE methodology and architecture (Lesiamo, 4 marks)

Exemplary band means a rigorous SDLC choice, crystal-clear architecture and UML diagrams, and a well-justified stack. The SDLC justification paragraph is already written in this document under "How we run".

- Week 1: requirements list v1, technical view; proposal text and submission.
- Week 2: API and database design; receive Kgosi's diagrams by Friday 16.
- Week 3: write the methodology chapter around the diagrams; draft by Friday 23.
- Week 4: assemble the dissertation, then run workstream 5.

### Workstream 4: A4 System evaluation and results (Raymond, 5 marks)

Exemplary band means thorough evaluation with excellent performance or usability data. This is the biggest single criterion in Part A. Two empirical exercises carry it: usability testing with drivers, and the triage comparison (staff triage reports with and without the priority classification, timing each run).

- Week 1: interview questions for drivers and staff; recruit 7 drivers so losing 2 still leaves 5.
- Week 2: test plan, usability task scripts, test cases for the reporting flow; first internal test.
- Week 3: usability sessions 1 to 7; triage comparison with Kgosi's metrics by Thursday 22; evaluation chapter draft by Friday 23.
- Week 4: final evaluation chapter with charts; slides v1; rehearsals and Q&A practice.

### Workstream 5: A5 Academic writing (Lesiamo, 4 marks)

Exemplary band means flawless formatting, logical progression and rigorous referencing across the whole document. This workstream starts only when the four chapter drafts land on Friday 23.

- Week 4, Monday 26: one-voice pass over the assembled dissertation; Crystal's reference list merged.
- Week 4, Tuesday 27: Turnitin check, similarity under 15%, fixes applied.
- Week 4, Wednesday 28: submit via the portal one day early.

### Handoffs between workstreams

| What | From | To | By |
|---|---|---|---|
| Architecture and UML diagrams for A3 | Kgosi | Lesiamo | Fri 16 Oct |
| Triage metrics and figures for A4 | Kgosi | Raymond | Thu 22 Oct |
| All four chapter drafts for assembly | everyone | Lesiamo | Fri 23 Oct |
| Final IEEE reference list for A5 | Crystal | Lesiamo | Mon 26 Oct |

## Week by week, day by day

Week 1, Planning and Requirements (Mon 5 to Fri 9 Oct)

| Day | Lesiamo | Crystal | Kgosi | Raymond |
|---|---|---|---|---|
| Mon 5 | Proposal page drafted from the group's notes | Verify the Region B and AA figures and save sources (A1, A2) | Set up GitHub repo, board and folder structure | Draft interview questions for drivers (A4) |
| Tue 6 | Stakeholder section and proposal formatting | Start literature scan: existing pothole reporting tools (A2) | Repo scaffolding: React front end, backend skeleton | Interview questions for roads staff; attempt contact with Region B |
| Wed 7 | Final proposal text, group sign-off | Literature notes into the shared doc (A2) | Draft database schema for reports, users, statuses (feeds A3) | Recruit 7 drivers for usability testing (A4) |
| Thu 8 | Apply the group's corrections to the proposal | Read and correct the proposal page | Read and correct the proposal page | Read and correct the proposal page |
| Fri 9 | Submit to Miss Lee on Teams by 12pm, then showcase 1 | Showcase 1: requirements started | Showcase 1: repo and schema shown | Showcase 1: interview questions shown |

Thursday 8 October from 8pm: showcase prep, all four. The Friday showcase lands straight after the 12pm submission; slides cover the proposal, the verified figures, the repo and the interview questions.

Week 2, Design and start of build (Mon 12 to Fri 16 Oct)

| Day | Lesiamo | Crystal | Kgosi | Raymond |
|---|---|---|---|---|
| Mon 12 | API endpoint design (A3) | Wireframes: reporting form and status tracker | Architecture diagram and UML use case diagram (for A3) | Test plan skeleton and usability task scripts (A4) |
| Tue 13 | Database schema final, migrations written | Build the reporting form UI | Leaflet map spike on a test page | Comparison table of existing tools (for A2) |
| Wed 14 | Report submission endpoint and photo storage | Wire GPS capture and photo upload to the API | Duplicate detection design, map clustering | Write test cases for the reporting flow |
| Thu 15 | Backend fixes from integration | Reporter status tracker page | Staff dashboard shell | First internal test of the reporting flow, log every bug |
| Fri 16 | Phase 2 gate: demo the reporting flow at showcase 2; receive diagrams from Kgosi (A3) | Same | Same; hand diagrams to Lesiamo | Write up test results; methodology notes |

Thursday 15 October from 8pm: showcase prep, all four. Friday's showcase doubles as the phase 2 gate demo.

Week 3, Implementation and Testing (Mon 19 to Fri 23 Oct)

| Day | Lesiamo | Crystal | Kgosi | Raymond |
|---|---|---|---|---|
| Mon 19 | Staff API: list reports, filter, update status | Status tracker polish, notification stubs | Backlog map on the dashboard | Test cases for duplicate matching |
| Tue 20 | Priority classification endpoint | Merge-duplicates UX so reporters see combined status | Priority rules and dashboard integration | Usability session prep: tasks, consent forms, devices |
| Wed 21 | Duplicate detection live, bug fixes | Bug fixes | Bug fixes | Usability sessions 1 to 3 (A4) |
| Thu 22 | Bug fixes | Bug fixes | Collect triage metrics, hand to Raymond (feeds A4) | Usability sessions 4 to 7, triage comparison test (A4) |
| Fri 23 | Methodology chapter draft (A3); present at showcase 3 | Literature review draft (A2); present it | Problem definition and introduction draft (A1); present it | Evaluation chapter draft (A4); present it |

Thursday 22 October from 8pm: showcase prep, all four. Each author walks through their own chapter draft at the Friday showcase. All drafts land with Lesiamo today.

Week 4, Evaluation, Documentation, Delivery (Mon 26 to Thu 29 Oct)

| Day | Lesiamo | Crystal | Kgosi | Raymond |
|---|---|---|---|---|
| Mon 26 | Assemble dissertation; one-voice pass (A5); receive reference list from Crystal | Reference list finalised, handed to Lesiamo | Evaluation charts final, working with Raymond | Slides v1 |
| Tue 27 | Turnitin check, similarity under 15% (A5) | Fixes from Turnitin report | Record a backup demo video | Rehearsal 1 and Q&A practice, note the gaps |
| Wed 28 | Submit dissertation via the portal, one day early | Final read of the dissertation | Final read of the dissertation | Rehearsal 2, full dress, slides final |
| Thu 29 | Final presentation and demo | Same | Same | Same |

No Friday showcase in week 4; the final presentation on Thursday 29 replaces it, and Wednesday 28's rehearsal is the last full run.

## Evidence for marks

The rubric rewards proof, not claims. From day one we keep: a screenshot of the board every Friday, every showcase deck, the phase gate review notes, interview questions and answers, test plans and test results, usability session notes with permission, and the Q&A practice questions. These feed the methodology section (criterion A3), the evaluation chapter (A4) and the group coordination part of the presentation (B3).

## Risks

- Testers cancel: we recruit 7 drivers in week 1 so losing 2 still leaves 5.
- Someone falls behind: the daily check-in catches it on day one, not deadline day. Lesiamo rebalances tasks the same day.
- Region B never answers: we proceed with the published figures and AA data, and note the limitation in the dissertation.
- Scope creep: new ideas go to the Backlog column. Nothing new enters the build after Tuesday of week 3; it becomes future work in the discussion chapter.
- Phase gates slip: cut scope from the backlog, never from testing or documentation.
- A chapter draft misses Friday 23: the A5 pass starts anyway with what landed; the missing author finishes overnight while the rest rehearse.
