---
type: Source
source_type: Internal document
date_accessed: 2026-06-30
belongs_to: "[[mandatory-training-compliance]]"
related_to:
  - "[[learnmoor]]"
  - "[[talvento]]"
  - "[[olumide-fashola]]"
_organized: true
---

# Learnmoor To Talvento Completion Feed Specification

The two-page interface specification for sending training completions from [[learnmoor]] to [[talvento]], version 1.2, signed off by [[yetunde-balogun]], [[olumide-fashola]] and [[rashid-karimi]] on 2026-06-30.

## Summary

A nightly file of completions recorded in Learnmoor that day, loaded into Talvento's learning history. Replaces the monthly CSV I used to upload into Staffora by hand.

## Key Details

- Fields: employee number, course code, completion date, expiry date. No scores, no attempts, no free text, following [[data-minimisation]].
- Agency workers are excluded because they have no Talvento record.
- Rejected rows (unknown employee number, course not mapped) go to an error file emailed to Yetunde and me each morning.
- Historic completions: one-off load of in-date mandatory completions only, 14,880 rows, done on 2026-07-18.

## Why It Matters

Managers in Talvento self-service now see their team's mandatory training status, which was one reason for the [[manager-self-service-rollout]]. It also removed a monthly half-day of my time.

## Caveats

Talvento shows the expiry date Learnmoor sends; if a refresh rule changes, both systems need updating. The error file had 30 to 40 rows a night in the first week, mostly new starters entered late.

## Source Location

HRIS programme document library, "Interfaces / Learnmoor feed v1.2".
