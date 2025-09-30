---
type: Opinion
status: Active
confidence: High
belongs_to: "[[talvento-hris-migration]]"
related_to:
  - "[[uat-defect-review-2026-03-11]]"
  - "[[talvento-migration-lessons-learned]]"
  - "[[annual-leave-carry-over]]"
_organized: true
---

# Moving Go-Live To June Was Right

## Stance

The Steering Group was right to move Talvento go-live from 2026-04-01 to 2026-06-29 rather than correct 312 balances by hand. I thought so at the time, and the retest and the quiet go-live confirmed it.

## Why I think this

- The error came from a rule, so a manual fix would have been repeated at every future carry-over and every pattern change ([[how-should-carry-over-convert-for-compressed-hours]]).
- April is the start of the leave year. Wrong balances at that moment become wrong bookings, then wrong pay.
- The three months also bought a third UAT round that caught three more defects, none critical but all annoying.

## The cost

Three more months of Staffora licence and programme staff, and People Services keyed changes in two systems for longer. The payroll cutover is now closer to year-end than anyone wanted, which feeds the November versus January argument ([[when-should-payroll-cut-over-to-talvento]]).

## What would change my mind

Nothing now; the decision is past. The lesson I carry is to test conversions on edge cases (part-time, compressed hours, pattern changes) in the first week of UAT, not the fifth ([[talvento-migration-lessons-learned]]).
