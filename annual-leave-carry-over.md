---
type: Concept
belongs_to: "[[coordinate-payroll-and-absence]]"
related_to:
  - "[[how-should-carry-over-convert-for-compressed-hours]]"
  - "[[compressed-hours]]"
  - "[[uat-defect-review-2026-03-11]]"
_organized: true
---

# Annual Leave Carry-Over

Unused annual leave moved from one leave year into the next. At Pellmore the leave year runs April to March and staff may carry over up to five days (pro rata for part-time staff), more only with HRBP approval for long absences.

## Why it is harder than it looks

The rule is in days, but what a "day" means depends on the person's working pattern. A five-day carry-over is 37.5 hours for someone on 7.5-hour days, 46.25 hours on a compressed four-day week of 9.25-hour days, and 25 hours on 5-hour part-time days. Any system that stores leave in one unit and converts to another has to know each person's pattern at the moment of conversion.

That is exactly what went wrong in the Talvento migration: [[staffora]] held carry-over in hours, [[talvento]] in days, and the first conversion assumed a 7.5-hour day for everyone. 312 balances were wrong ([[uat-defect-review-2026-03-11]]). The agreed conversion is in [[how-should-carry-over-convert-for-compressed-hours]].

## Where carry-over shows up

- Helpdesk tickets in April and May every year ([[helpdesk-ticket-categories]]).
- Absence reconciliation, when carried-over leave is taken in the first weeks of the leave year ([[absence-data-reconciliation]]).
- Pattern changes: when someone moves to compressed hours mid-year, their remaining balance is converted again.
