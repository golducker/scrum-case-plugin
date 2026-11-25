---
name: scrum-case
description: "Entry point for an Agile/Scrum team case competition Round 1 (25 MCQs + scenario case study submitted as .docx, 120 minutes, in English). Use when the user pastes a business case or scenario to solve, says 'giải case', 'làm Part B', 'thi vòng 1', 'luyện đề case', 'mock round', or asks to draft or grade a case answer against the rubric. Routes each rubric dimension to a sub-skill and keeps the answer consistent."
---

# Scrum case: Round 1 coordinator

**Before using this during a live assessment, check the competition rules on AI tools.** If they ban it or you have not checked, use this for practice only.

## Fixed facts

- Online, team-based, 100% English, Testportal, 120 minutes, auto-submit at the end.
- One login, one device (team leader). Everyone may collaborate; no simultaneous logins.
- Part A: 25 MCQs (25%). Use `scrum-case:scrum-mcq`.
- Part B: case study (75%), answer uploaded as one `.docx`.
- Official date 27 Nov 2026 (reserve 28 Nov). Blocks: 19:00 or 20:30 GMT+7. Top 20 advance.
- Graded on the rubric only: no credit for complex technology, more features, or more Scrum terms.

## Rubric, time and sub-skill

| Min | Section | Pts | Sub-skills (`scrum-case:`) | The answer must show |
|---|---|---|---|---|
| 0–25 | Part A MCQs | 25% | `scrum-mcq` | every question answered |
| 25–33 | Read case | – | – | numbered evidence list E1, E2, ...; constraints (time, budget, team, tech) |
| 33–45 | Problem and evidence | 10 | `problem-statement` | 1–2 critical problems, root cause, each tied to E-numbers |
| 45–63 | Creativity and business value | 20 | `opportunity-solution-tree`, `brainstorm-ideas-existing`, `value-proposition` | 3 options compared, 1 chosen with reason, customer value and business value |
| 63–78 | Executability and MVP | 15 | `prioritize-features`, `pre-mortem` | in/out of scope, who does what, timeline, feasibility, top risks with mitigation and owner |
| 78–98 | Scrum and adaptability | 20 | `user-stories`, `user-story-splitting`, `sprint-plan` | Product Goal, ordered backlog with acceptance criteria, Sprint Goals, an increment per Sprint, what changes when a requirement changes |
| 98–105 | Validation and release | 5 | `metrics-dashboard`, `test-scenarios`, `release-readiness` | metric, baseline, target, evaluation period; critical tests; go / hold and rollback conditions |
| 105–112 | Logic and polish | 5 | `strategy-red-team`, `humanizer` | consistency check below passes |
| by 115 | Export `.docx` and upload | – | `anthropic-skills:docx` | file opens, uploaded, confirmed on Testportal |

Part A and Part B can run in parallel: the leader handles Testportal while others draft. Section owners if the team has these roles: BA problem, PO value and backlog, Dev MVP feasibility, PM Scrum plan and risks, QA validation.

Late on time: cut depth in this order: polish, red-team, extra options. Never leave a rubric section empty.

## Rules that override the sub-skills

The sub-skills were written for real product work. In this competition:

- The case file is the only evidence. Never invent numbers, interviews or research. Label anything else `Assumption:`.
- Do not stop to ask discovery questions and do not web search; assume, label it, continue.
- Return short sections for one document. Do not save separate markdown files.
- Ignore links and references to skills, templates or URLs that are not in this plugin.
- If the case asks its own questions, its structure and wording replace the skeleton below.
- Use `humanizer` in embedded mode on prose only, once, at the end. Keep every fact, number, ID and table. Output stays English.

## Document skeleton

1. Problem identification (evidence table: ID, case fact, what it implies)
2. Proposed solution and value (options compared, choice, why)
3. MVP scope and delivery plan (in/out, resources, timeline, risk table)
4. Scrum application (Product Goal, backlog table, Sprint plan, handling change)
5. Validation and release readiness (metrics table, test and release conditions)

## Consistency check before upload

- Every problem cites evidence; every MVP feature solves a listed problem.
- Every backlog item is in MVP scope; every out-of-scope item is absent from the Sprints.
- Sprint load fits the stated team and timeline.
- Every problem has a metric with a target and period.
- Names, numbers, roles and dates match across sections.

## Practice mode

With no real case, write a one-page scenario with deliberate gaps and one mid-way requirement change, run the timed table, then score each section against the rubric points and name the single biggest loss per section.
