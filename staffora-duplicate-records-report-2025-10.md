---
type: Source
source_type: Internal report
date_accessed: 2025-10-24
belongs_to: "[[hris-data-cleansing]]"
related_to:
  - "[[staffora]]"
  - "[[rashid-karimi]]"
  - "[[staffora-data-issue-log]]"
_organized: true
---

# Staffora Duplicate Records Report 2025-10

Rashid's one-off report of candidate duplicate person records in Staffora, run on 2025-10-24.

## Summary

Matched on surname, date of birth and tax identifier, with fuzzy matching on first name. 212 candidate pairs. On review: 164 were rehires given a new person number (Staffora did that until 2021), 41 were genuine double employments, 7 were data entry duplicates.

## Why It Matters

171 were merged before migration; the 41 double employments became two assignments under one person in Talvento ([[talvento-migration-field-mapping]]). The report rules and the review sheet stayed in the restricted programme folder; this note holds counts only.

## Source Location

HRIS programme folder, `Cleansing / Duplicates 2025-10`.
