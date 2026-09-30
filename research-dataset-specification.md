---
type: Source
source_type: Internal document
date_accessed: 2026-09-24
belongs_to: "[[diploma-research-project]]"
related_to:
  - "[[helpdesk-ticket-categories]]"
  - "[[leon-adjei]]"
  - "[[repeat-query]]"
_organized: true
---

# Research Dataset Specification

The one-page specification [[leon-adjei]] and I agreed on 2026-09-24 for the monthly extract from Deskwell for my research project.

## Summary

One table, one row per month and category: ticket count, count reopened within 14 days, median days to resolve, and count of tickets in the category from an employee who had raised a ticket in the same category in the previous 30 days (the [[repeat-query]] count, computed inside Deskwell by Leon). Plus monthly views of the hybrid knowledge base articles.

## Key Details

- Categories: the 14 in [[helpdesk-ticket-categories]]; January to June 2025 mapped from the old 31 categories by Leon's lookup.
- Cells under 10 are blanked in my copy; Leon keeps the full counts.
- Leon produces it on the 5th of each month; I check the total against the published monthly figure.
- Nothing identifies an employee, site or team.

## Why It Matters

The only data the [[diploma-research-project]] uses. Computing the repeat count inside Deskwell means I never see who asked twice, only how many.

## Caveats

The 30-day window for repeats is a choice; 14 or 60 days would change the numbers. The category mapping for early 2025 is approximate.

## Source Location

Research folder in my work OneDrive, "Dataset spec v1" and the monthly extracts.
