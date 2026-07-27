---
type: Project
status: Active
start: 2026-07-01
belongs_to: "[[talvento-hris-migration]]"
related_to:
  - "[[elspeth-harcourt]]"
  - "[[gemma-ashworth]]"
  - "[[parallel-payroll-run]]"
has:
  - "[[parallel-run-differences-log-2026]]"
  - "[[when-should-payroll-cut-over-to-talvento]]"
  - "[[parallel-run-review-2026-10-07]]"
  - "[[payroll-interface-specification]]"
_organized: true
---

# Payroll Parallel Run

Running monthly payroll twice, once from Staffora as normal and once from a Talvento feed in a test payroll, and explaining every difference, until we can trust Talvento to feed the real payroll. Group Payroll runs the payrolls; I trace the HR side of each difference.

## Outcome

Two consecutive parallel payroll runs with no unexplained differences between Staffora-fed and Talvento-fed payroll, then cutover.

## Current State

> [!info]
> July 2026: 37 unexplained differences. August: 9. September: 0. The October run closes on 2026-10-28; if it is clean, the two-run rule set on 2026-06-17 is met and the HRIS Steering Group decides the cutover date on 2026-11-04.

- Differences log: [[parallel-run-differences-log-2026]]; patterns: [[parallel-run-difference-categories]].
- The parallel run covers the monthly payroll only. The weekly payroll is compared on two sample weeks a month, because a full weekly parallel run would double Group Payroll's work every Thursday.
- Open decision: [[when-should-payroll-cut-over-to-talvento]].

## Scope and Boundaries

A difference counts as "explained" when we know its cause and it is either correct in Talvento or fixed in the interface. A difference that is correct in Talvento and wrong in Staffora (it happens) is explained. Pay rates and individual pay are Group Payroll's business; my log records categories and counts, never a named person's pay ([[record-hr-cases-without-personal-data]]).

## Working Context

The rule comes from the [[hris-steering-group-2026-06-17]]. Elspeth asked for three runs; Fiona argued two were enough if both were clean. Two consecutive clean runs was the compromise, with weekly samples on top.

What drove the counts down:

- **July (37):** 14 absence deductions landing in a different period, 11 cost centre mapping errors, 8 backdated changes keyed in Staffora but not Talvento, 4 rounding of part-time hours. Review: [[parallel-run-review-2026-08-06]].
- **August (9):** 5 backdated changes, 3 cost centres for new depots, 1 rounding. The interface fix for absence periods went in on 2026-08-14 ([[payroll-interface-specification]]). Review: [[parallel-run-review-2026-09-03]].
- **September (0):** 6 differences, all explained the same day. Review: [[parallel-run-review-2026-10-07]].

Backdated changes are the risk that has not gone away. They exist because of double keying, which will stop at cutover. That is Fiona's main argument for November.

## Active Workflows

- Payday plus two working days: Group Payroll sends the comparison. I trace HR-side causes with [[gemma-ashworth]] within three working days.
- Weekly samples on the second and fourth Thursday with [[dariusz-nowicki]].

## Next Actions

- [ ] Trace October differences by 2026-10-30.
- [ ] Draft the evidence section of the cutover paper with Fiona.
- [ ] Agree what happens to the parallel run if the Steering Group chooses January: keep running monthly, or pause until December.

## Open Questions

- [[when-should-payroll-cut-over-to-talvento]]
- [[can-managers-approve-absence-after-the-cut-off]]

## Important Notes

- [[parallel-run-differences-log-2026]]
- [[parallel-payroll-run]]
- [[payroll-cutover-options-comparison]]
- [[payroll-cutover-should-wait-for-january]]

## Maintenance Log

- 2026-10-07: September run clean.
- 2026-09-03: August run, 9 differences.
- 2026-08-14: Absence period fix deployed to the interface.
- 2026-08-06: July run, 37 differences.
- 2026-07-01: Started.
