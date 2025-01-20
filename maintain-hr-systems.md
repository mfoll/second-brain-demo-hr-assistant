---
type: Responsibility
status: Active
related_to:
  - "[[hr-data-quality]]"
  - "[[fiona-mcbride]]"
  - "[[rashid-karimi]]"
has:
  - "[[talvento-hris-migration]]"
  - "[[payroll-parallel-run]]"
  - "[[manager-self-service-rollout]]"
  - "[[staffora]]"
  - "[[talvento]]"
_organized: true
---

# Maintain HR Systems

My part in keeping Pellmore's HR data right and the systems that hold it working: the move from [[staffora]] to [[talvento]], data quality checks, access requests and the reports People Services and the HR Business Partners ask for. I am not a system owner. [[fiona-mcbride]] runs the Talvento programme, [[rashid-karimi]] configures both systems, and the [[hris-steering-group-terms-of-reference|HRIS Steering Group]] decides. I test, clean, reconcile and write things down.

## Scope

- The [[talvento-hris-migration]] and its children: data cleansing, user acceptance testing, the payroll parallel run and manager self-service.
- HR data quality after go-live: the monthly [[hr-data-quality-scorecard]], duplicate and leaver checks, missing cost centres, wrong line managers.
- Access requests for HR roles in Talvento, checked against the [[talvento-access-roles-matrix]]; leaver access goes through IT ([[talvento-it-provisioning-design]]).
- Ad hoc reports for People Services from Talvento ([[talvento-reports-i-use]]).
- Not here: payroll cut-offs and absence reconciliation ([[coordinate-payroll-and-absence]]), Hireloom ([[coordinate-recruitment]]), Learnmoor ([[support-people-programmes]]), even where the data flows into Talvento.
- No individual employee's data in these notes. A record problem is described by category and count and, if needed, points to its Talvento case reference ([[record-hr-cases-without-personal-data]]).

## Current State

- Core HR has been live in Talvento since 2026-06-29, three months later than planned because 312 absence balances converted wrongly ([[uat-defect-review-2026-03-11]]).
- Payroll still reads from Staffora. Parallel runs: 37 unexplained differences in July, 9 in August, 0 in September. The October run closes on 2026-10-28 ([[payroll-parallel-run]]).
- Cutover date open: November or January. The Steering Group decides on 2026-11-04 ([[when-should-payroll-cut-over-to-talvento]]).
- Manager self-service: 288 of 410 line managers trained as of 2026-10-16 ([[manager-self-service-rollout]]).
- Staffora goes read-only after cutover; its licence ends 2027-03-31. What happens to its history is still open ([[what-happens-to-staffora-history-after-2027-03-31]]).

## Active Projects and Workflows

- [[talvento-hris-migration]] (umbrella), with [[payroll-parallel-run]] and [[manager-self-service-rollout]] active, [[hris-data-cleansing]] and [[hris-user-acceptance-testing]] completed.
- Monthly data quality check, first Monday of the month ([[hr-data-quality-scorecard]]).
- Steering Group papers: I take the actions and keep the defect and differences logs tidy for Fiona.

## Next Actions

- [ ] Get the October parallel run differences categorised by 2026-10-30 so Fiona has them for the 2026-11-04 paper.
- [ ] Bring the manager self-service trained count to 350 before peak starts on 2026-11-23.
- [ ] Draft, with Rashid, the list of Staffora reports nobody has replaced in Talvento yet.
- [ ] Agree with [[deborah-okwuosa]] who owns data quality now the project team is shrinking ([[who-owns-hr-data-quality-after-go-live]]).

## Maintenance Log

- 2026-10-21: Current state refreshed after the September run came back clean.
- 2026-06-29: Core HR live in Talvento.
- 2026-03-11: Go-live moved from 2026-04-01 to 2026-06-29.
- 2025-09-01: Talvento programme started; I joined as data and testing support.
- 2025-01-06: Created when I started keeping work notes here.
