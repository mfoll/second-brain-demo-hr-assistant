---
type: Concept
belongs_to: "[[payroll-parallel-run]]"
related_to:
  - "[[payroll-wikipedia]]"
  - "[[data-migration-wikipedia]]"
  - "[[hris-steering-group-2026-06-17]]"
_organized: true
---

# Parallel Payroll Run

Running the same payroll through the old and the new source side by side, with real data, and comparing results line by line before letting the new source pay anyone. Only the old run pays; the new one is a test.

## What counts

- **Difference**: any payslip line that differs between the two runs.
- **Explained difference**: its cause is known and it is either correct in the new system or fixed. A difference where the new system is right and the old wrong is explained.
- **Unexplained difference**: the cause is unknown, or known and not fixed. The Pellmore rule is two consecutive monthly runs with none ([[hris-steering-group-2026-06-17]]).

## What it does not prove

- That rare cases work. A parallel month only tests what happened that month; year-end, leave year rollover and peak volumes need their own checks.
- That the weekly payroll works, unless the weekly payroll is run in parallel too. At Pellmore it is sampled two weeks a month, which is Elspeth's main reservation ([[when-should-payroll-cut-over-to-talvento]]).

It is one of the validation steps described for any system migration ([[data-migration-wikipedia]]). Our run: [[payroll-parallel-run]].
