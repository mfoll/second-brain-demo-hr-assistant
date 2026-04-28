---
type: Source
source_type: Internal specification
date_accessed: 2026-04-10
belongs_to: "[[hris-user-acceptance-testing]]"
related_to:
  - "[[how-should-carry-over-convert-for-compressed-hours]]"
  - "[[compressed-hours]]"
  - "[[rashid-karimi]]"
_organized: true
---

# Absence Conversion Specification

Rashid's specification for converting Staffora leave balances in hours into Talvento balances in days, version 2.0 of 2026-04-10, replacing the flat 7.5-hour rule.

## Summary

- Balance in days = Staffora hours divided by contracted daily hours from the person's working pattern on the conversion date.
- Patterns with unequal days (for example a nine-day fortnight) use the average contracted day.
- Round to two decimal places; no rounding to half days.
- Pattern changes after the conversion date are handled by Talvento natively.
- Test cases: full-time 7.5 hours, part-time on 5, 6 and 3.75 hours, compressed on 9.25 hours, nine-day fortnight, mid-year pattern change.

## Why It Matters

This is the fix that let Talvento go live on 2026-06-29. I retested all 312 affected records against it ([[absence-balance-retest-2026-05-14]]). Background: [[annual-leave-carry-over]].

## Source Location

HRIS programme folder, `Design / Absence conversion v2.0`.
