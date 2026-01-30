---
type: Question
status: Answered
belongs_to: "[[hris-user-acceptance-testing]]"
related_to:
  - "[[annual-leave-carry-over]]"
  - "[[compressed-hours]]"
  - "[[absence-conversion-specification]]"
_organized: true
---

# How Should Carry-Over Convert For Compressed Hours?

How should leave carried over in Staffora hours become a Talvento balance in days for staff whose working day is not 7.5 hours: part-time staff on shorter days and compressed-hours staff on longer ones?

## Current Answer

> [!success]
> Divide the carried-over hours by the person's own contracted daily hours from their working pattern, not by a standard 7.5-hour day, and round to two decimals. Where the pattern has days of different lengths, use the average contracted day. Agreed by the HRIS Steering Group on 2026-03-25, implemented by Rashid on 2026-04-10, retested on all 312 affected records on 2026-05-14.

## Why it came up

The first migration used 7.5 hours for everyone. A compressed-hours employee working four 9.25-hour days who carried over 70 hours got 9.33 days in Talvento instead of 7.57. A part-time employee on 5-hour days was short-changed the other way. 312 balances were wrong ([[uat-defect-review-2026-03-11]]).

## Rejected options

- **Convert everything at 7.5 hours and let employees query it.** The errors would have been permanent and repeated every year.
- **Keep balances in hours in Talvento for these staff.** Talvento allows it, but then managers see two different units in one team, and payroll's absence codes are in days.

Details: [[absence-conversion-specification]]. Background: [[annual-leave-carry-over]], [[compressed-hours]].
