---
type: Source
source_type: Internal spreadsheet
date_accessed: 2026-02-27
belongs_to: "[[hris-data-cleansing]]"
related_to:
  - "[[data-quality-dimensions]]"
  - "[[rashid-karimi]]"
  - "[[data-cleansing-close-2026-02-27]]"
_organized: true
---

# Staffora Data Issue Log

The workbook where every data issue found in Staffora before migration was logged, assigned and closed. I built it in September 2025 and kept it until the cleansing closed.

## Summary

One row per issue, with category, division, rule that found it, owner, status (open, fixed, accepted) and, for accepted issues, the reason. Record identifiers are Staffora person numbers only, in a restricted tab. One tab per HRBP showed only their division's open issues.

Final counts at close (2026-02-27): 1,940 found, 1,862 fixed, 78 accepted. By category: 604 missing or invalid cost centres, 497 wrong or missing line managers, 388 leavers still active, 212 duplicate person records, 239 other.

## Why It Matters

The log is the evidence that Talvento started clean, and the source of the rules now in the monthly [[hr-data-quality-scorecard]]. It also taught me to sort issues by owner, not just by type ([[data-quality-dimensions]]).

## Caveats

Counts are of issues, not people: one record could have three issues.

## Source Location

HRIS programme folder, `Cleansing / Staffora issue log FINAL.xlsx`, restricted to the programme team. To be deleted with the programme records under the retention schedule.
