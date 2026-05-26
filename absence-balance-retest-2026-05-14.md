---
type: Event
date: 2026-05-14
belongs_to: "[[hris-user-acceptance-testing]]"
related_to:
  - "[[rashid-karimi]]"
  - "[[absence-conversion-specification]]"
  - "[[compressed-hours]]"
_organized: true
---

# Absence Balance Retest 2026-05-14

The day [[rashid-karimi]] and I finished retesting all 312 absence balances that had converted wrongly in round 1 ([[uat-defect-review-2026-03-11]]).

- Method: for each record, a hand calculation in a spreadsheet from the Staffora hours balance and the contracted daily hours in the working pattern, compared with the Talvento balance after the rerun migration ([[absence-conversion-specification]]).
- Result: 312 of 312 matched to two decimal places. 9 had looked wrong at first; all 9 were working pattern changes in March and April that Staffora had not yet received. Fixed at source and rechecked.
- We also sampled 150 full-time records that had never been wrong, to check the fix had not broken them. All matched.
- Took eight working days across three weeks. Records were identified by person number in the masked test tenant only; the spreadsheet was deleted after sign-off.

Fiona reported the result to the Steering Group on 2026-05-20. The conversion rule question is closed: [[how-should-carry-over-convert-for-compressed-hours]].
