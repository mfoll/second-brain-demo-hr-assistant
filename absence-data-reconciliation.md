---
type: Project
status: Active
start: 2026-01-05
belongs_to: "[[coordinate-payroll-and-absence]]"
related_to:
  - "[[dariusz-nowicki]]"
  - "[[hr-data-quality]]"
  - "[[talvento]]"
has:
  - "[[absence-reconciliation-reports-2026]]"
  - "[[reconcile-absence-with-payroll]]"
  - "[[absence-mismatch-causes-2026]]"
  - "[[why-do-absence-records-not-match-payroll]]"
_organized: true
---

# Absence Data Reconciliation

A monthly check that absence recorded in the HR system matches what payroll deducted or paid. Mismatches mean people are paid wrongly for sick days or unpaid leave, and they are hard to unpick after the fact. I run it with [[dariusz-nowicki]] from Group Payroll.

## Outcome

Monthly reconciliation of absence records between the HR system and payroll with a mismatch rate under 0.5% (3.8% in January 2026, 0.9% in September).

## Current State

- September 2026: 0.9% of absence records mismatched (61 of about 6,800), down from 3.8% in January ([[absence-reconciliation-reports-2026]]).
- Since 2026-06-29 the HR side is Talvento; before that it was Staffora. The June figure (2.4%) went up because of the go-live week.
- Main remaining cause: absence approved by a manager after the cut-off ([[can-managers-approve-absence-after-the-cut-off]]).

## Scope and Boundaries

Sickness, unpaid leave, annual leave taken beyond entitlement, and parental leave start and end dates. Records are compared by count and category; any record that needs correcting goes to Group Payroll or to the employee's HR Advisor through the system, and these notes hold only counts ([[record-hr-cases-without-personal-data]]). Occupational health referrals are not part of this.

## Working Context

Started after Dariusz showed me 258 mismatches in the December 2025 data at the [[absence-mismatch-review-2026-02-12]]. Causes in [[absence-mismatch-causes-2026]]; the short answer is in [[why-do-absence-records-not-match-payroll]].

Monthly rate:

| Month | Rate |
| --- | --- |
| January 2026 | 3.8% |
| March | 2.6% |
| May | 1.9% |
| June | 2.4% |
| July | 1.6% |
| August | 1.2% |
| September | 0.9% |

What helped: the cut-off checklist line for absence, the Talvento absence types matching payroll codes one to one, and manager self-service. What did not: a reminder email to all managers in March, which made no measurable difference.

Rejected: reconciling weekly. Dariusz has no capacity on Thursdays and monthly catches the same errors one run later.

## Next Actions

- [ ] October reconciliation by 2026-11-06.
- [ ] Ask Rashid for a Talvento report of absence approved after cut-off, by manager count only, to target self-service training.
- [ ] Rewrite [[reconcile-absence-with-payroll]] for the Talvento-fed payroll once the cutover date is set.

## Open Questions

- [[can-managers-approve-absence-after-the-cut-off]]
- [[should-talvento-show-bradford-factor-scores]]

## Important Notes

- [[absence-reconciliation-reports-2026]]
- [[reconcile-absence-with-payroll]]
- [[absence-mismatch-causes-2026]]

## Maintenance Log

- 2026-10-09: September rate 0.9%.
- 2026-07-10: June rate rose to 2.4% around go-live.
- 2026-02-12: Review with Dariusz; monthly reconciliation agreed.
- 2026-01-05: Started.
