---
type: Project
status: Completed
start: 2026-01-12
end: 2026-06-12
belongs_to: "[[talvento-hris-migration]]"
related_to:
  - "[[rashid-karimi]]"
  - "[[mirela-dumitru]]"
  - "[[acceptance-testing-wikipedia]]"
has:
  - "[[uat-test-script-register]]"
  - "[[uat-defect-log-2026]]"
  - "[[uat-defect-review-2026-03-11]]"
  - "[[uat-sign-off-2026-06-12]]"
_organized: true
---

# HRIS User Acceptance Testing

Testing Talvento against how People Services, managers and Group Payroll actually work, before go-live. I coordinated the testers, ran about a third of the scripts myself and kept the defect log.

## Outcome

All 214 test scripts passed or waived; signed off for the 2026-06-29 core HR go-live.

## Current State

- Signed off on 2026-06-12 ([[uat-sign-off-2026-06-12]]): 207 scripts passed, 7 waived with a workaround and an owner.
- 61 defects raised over the five months; 3 critical, all closed before sign-off ([[uat-defect-log-2026]]).

## Scope and Boundaries

Core HR, organisation structure, absence, manager and employee self-service, the Hireloom new starter handoff and the user provisioning feed. The payroll interface was tested separately in the [[payroll-parallel-run]]. Testing used a masked copy of migrated data; testers never saw real names in the test tenant, which was the condition [[kasia-wrobel]] set for using production-derived data.

## Working Context

Two rounds were planned, January to February and March. The first round found the defect that shaped everything after it: carry-over balances for part-time and compressed-hours staff converted wrongly from Staffora hours to Talvento days. 312 records were affected. At the [[uat-defect-review-2026-03-11]] the Steering Group moved go-live from 2026-04-01 to 2026-06-29, which turned UAT into three rounds:

1. **Round 1** (2026-01-12 to 2026-02-27): 214 scripts, 49 defects, including the conversion defect (UAT-D-031 in the log).
2. **Round 2** (2026-03-02 to 2026-04-24): retest of failed scripts plus new scripts for working patterns. 9 defects.
3. **Round 3** (2026-05-04 to 2026-06-05): full regression after the conversion fix, plus the 312-record retest ([[absence-balance-retest-2026-05-14]]). 3 defects, none critical.

Testers: me, [[aoife-brennan-hale]] for new starters, [[gemma-ashworth]] and [[dariusz-nowicki]] for payroll-relevant fields, two hub managers for self-service, and [[rashid-karimi]] for configuration fixes. [[mirela-dumitru]] triaged vendor-side defects.

The seven waived scripts are all reports that Talvento produces differently from Staffora. Each has an owner and a date in the [[uat-test-script-register]].

## Next Actions

- [ ] None. Closed at sign-off; open waivers are tracked under [[talvento-hris-migration]].

## Important Notes

- [[uat-test-script-register]]
- [[uat-defect-log-2026]]
- [[absence-conversion-specification]]
- [[moving-go-live-to-june-was-right]]

## Maintenance Log

- 2026-06-12: Signed off; 7 waivers.
- 2026-05-14: 312-record retest passed.
- 2026-03-11: Conversion defect drove the go-live move; UAT extended.
- 2026-01-12: Round 1 started.
