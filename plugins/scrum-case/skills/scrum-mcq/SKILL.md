---
name: scrum-mcq
description: "Answer or drill multiple-choice questions on the Scrum Guide 2020 and the PM, PO, BA, Developer and QA roles. Use for 'MCQ', 'trắc nghiệm Scrum', 'ôn Scrum', 'quiz me', 'Part A', or a pasted Agile/Scrum question."
---

# Scrum MCQ

**Live assessment: only if the competition rules allow AI tools.**

## How to answer

Letter, then one line of reason. Scrum questions follow the Scrum Guide 2020, not company habit. If the guide does not cover it, say so and mark confidence low. Watch for "not", "except", "select two", and absolute words.

## How to drill

Ask one question at a time, mixing easy and hard, general and role-specific. Wait for the answer, explain, track weak topics, repeat those.

## Scrum Guide 2020 (official source: scrumguides.org)

- Pillars: transparency, inspection, adaptation. Based on empiricism and lean thinking.
- Values: commitment, focus, openness, respect, courage.
- Scrum Team: 1 Product Owner, 1 Scrum Master, Developers; typically 10 or fewer; cross-functional, self-managing; no sub-teams or hierarchies.
- Accountabilities (not "roles" or job titles): Developers own the Sprint Backlog, quality via Definition of Done, daily adaptation. PO maximizes value, manages the Product Backlog (may delegate work, stays accountable), one person. SM establishes Scrum and is accountable for team effectiveness.
- Events (5): Sprint (1 month or less, container, next starts immediately); Sprint Planning (max 8h per one-month Sprint: why, what, how); Daily Scrum (15 min, for Developers); Sprint Review (max 4h, working session, not a release gate); Retrospective (max 3h, ends the Sprint).
- Only the PO can cancel a Sprint, when the Sprint Goal is obsolete.
- During a Sprint: nothing endangers the Sprint Goal, quality does not drop, backlog is refined as needed, scope may be renegotiated with the PO.
- Artifact → commitment: Product Backlog → Product Goal; Sprint Backlog → Sprint Goal; Increment → Definition of Done.
- Developers size the work. Developers select items for the Sprint. No one else tells them how to build it.
- An Increment exists once work meets the Definition of Done; several per Sprint are possible; they may be released before the Review. Not-Done items go back to the Product Backlog and are not presented.
- Organisation DoD standard is the minimum; teams on one product share one DoD.
- Not in the guide: story points, velocity, burndown as required, user stories, Definition of Ready, Sprint 0, hardening Sprint, project manager.

## Role knowledge (general industry practice)

- **PM:** scope, time, cost trade-off; critical path = longest dependent chain; threat responses: avoid, mitigate, transfer, accept, escalate; stakeholder power/interest grid; RACI (one Accountable per item).
- **PO:** MoSCoW, RICE = reach × impact × confidence / effort, WSJF = cost of delay / job size, Kano; MVP = smallest release that tests the value assumption.
- **BA:** BABOK v3 areas: planning and monitoring; elicitation and collaboration; requirements life cycle management; strategy analysis; requirements analysis and design definition; solution evaluation. Functional vs non-functional; INVEST; Given/When/Then; as-is vs to-be.
- **Developer:** version control, code review, CI (merge and test often), continuous delivery (always releasable) vs deployment (auto to production), TDD red-green-refactor, technical debt.
- **QA:** levels: unit, integration, system, acceptance. Smoke = broad build check, sanity = narrow check of a change, regression = old behaviour still works. Verification = built right, validation = right product. Severity = impact, priority = fix order. Entry/exit criteria. ISTQB principles: testing shows presence of defects; exhaustive testing is impossible; test early; defects cluster; tests wear out; context dependent; absence-of-errors fallacy.
