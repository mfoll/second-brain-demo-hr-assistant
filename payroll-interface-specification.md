---
type: Source
source_type: Internal specification
date_accessed: 2026-08-14
belongs_to: "[[payroll-parallel-run]]"
related_to:
  - "[[talvento]]"
  - "[[parallel-run-review-2026-08-06]]"
  - "[[elspeth-harcourt]]"
_organized: true
---

# Payroll Interface Specification

The specification of the file Talvento sends to the payroll system, version 1.3 of 2026-08-14.

## Summary

- Monthly file the working day after the 15th; weekly file Thursday 12:30.
- Contents: new starters, leavers, changes to pay-relevant fields (hours, contract, cost centre, bank details), absence records by payroll code. Each change carries its effective date.
- Version 1.3 change: absence is sent by absence date, not approval date, so that late approvals land in the right period as adjustments.
- Not in the file: pay rates (held in payroll), overtime (from depot timesheets).

## Why It Matters

The approval-date bug caused 14 of the 37 July differences ([[parallel-run-review-2026-08-06]]). The effective date on every change is what will end the backdated-change problem once Staffora stops feeding payroll ([[effective-dating]]).

## Source Location

HRIS programme folder, `Design / Payroll interface v1.3`.
