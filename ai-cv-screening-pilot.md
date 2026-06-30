---
type: Project
status: Idea
start: 2026-06-01
belongs_to: "[[coordinate-recruitment]]"
related_to:
  - "[[ai-in-recruitment]]"
  - "[[kasia-wrobel]]"
  - "[[bram-de-wit]]"
has:
  - "[[should-we-switch-on-hireloom-ai-ranking]]"
  - "[[hireloom-ai-ranking-module-product-sheet]]"
  - "[[ai-screening-dpia-screening-2026-07-08]]"
  - "[[how-hireloom-ai-ranking-would-work]]"
_organized: true
---

# AI CV Screening Pilot

Decide whether to switch on Hireloom's AI ranking module for high-volume roles (warehouse operatives, seasonal peak). The idea is [[marek-zielinski]]'s; [[kasia-wrobel]] (DPO) set the condition; I would run the test if one is approved.

## Outcome

A decision, backed by a data protection impact assessment, on whether to switch on the ranking module for high-volume roles. "No" is an acceptable outcome.

## Current State

- Idea. The module is licensed as part of our Hireloom contract but has never been switched on.
- [[bram-de-wit]] demonstrated it on 2026-06-18 ([[ai-ranking-vendor-demo-2026-06-18]]).
- At the screening meeting on 2026-07-08 Kasia concluded a full DPIA is needed before any use, even a shadow test on past applications ([[ai-screening-dpia-screening-2026-07-08]]).
- Nobody owns the DPIA yet. Marek parked it until after peak; it will not start before January 2027.

## Scope and Boundaries

Ranking applications for operative roles only. Not in scope: graduate, office or driver roles; any automated rejection. Whatever we do, a person reviews every application and makes every decision ([[automated-decision-making]]).

## Working Context

The module scores each application against the job description and past hires and orders the list. Marek's case: in peak, coordinators read about 1,900 applications in ten weeks, mostly for the same role. My reading notes are in [[how-hireloom-ai-ranking-would-work]]: the scores come from past hiring decisions, which is exactly where bias can come in ([[song-2026-algorithmic-bias-in-hr-recruitment-systems]], [[tripathi-2026-llms-in-hiring-scoping-review]]). For operative roles our only real criteria are availability, right to work and willingness to do shifts, which a screening question already filters. My stance is in [[ai-ranking-is-not-worth-it-for-warehouse-roles]].

## Next Actions

- [ ] Ask Marek in January whether he still wants the DPIA, and who owns it.
- [ ] If yes, get from Bram the written answers to Kasia's questions in [[dpia-screening-questions]].
- [ ] Measure how long screening actually takes in peak 2026 from Hireloom timestamps, so any case rests on numbers.

## Open Questions

- [[should-we-switch-on-hireloom-ai-ranking]]

## Important Notes

- [[hireloom-ai-ranking-module-product-sheet]]
- [[dpia-screening-questions]]
- [[ai-in-recruitment]]

## Do Not Do Yet

> [!danger]
> Do not switch the ranking module on, even in shadow mode on past applications, until a full DPIA is approved by Kasia Wróbel.

## Maintenance Log

- 2026-07-08: DPO requires a full DPIA before any use.
- 2026-06-18: Vendor demo.
- 2026-06-01: Idea logged after Marek raised it at the recruitment team meeting.
