---
type: Source
source_type: Documentation
url: https://www.limesurvey.org/manual/Participant_settings
date_accessed: 2026-06-04
belongs_to: "[[engagement-survey-2026]]"
related_to:
  - "[[minimum-reporting-group]]"
  - "[[pulsewright]]"
_organized: true
---

# Participant Settings - LimeSurvey Manual

The LimeSurvey Manual page on participant settings for a survey, from the open-source survey tool's public documentation.

## Summary

The page explains settings for a survey's participants table: token length, anonymised responses, token-based response persistence, multiple responses per token, public registration and confirmation emails. With anonymised responses switched on, answers cannot be linked back to the participants table, even by an administrator.

## Why It Matters

I read it while preparing the [[survey-reporting-threshold-decision-2026-06-10|threshold meeting]] to understand the difference between two things people kept mixing up: whether the platform can link an answer to a person, and whether a report shows a group small enough to guess who answered. [[pulsewright]] keeps a respondent key (so we can use HR data for cuts without asking demographic questions); the protection is in reporting rules, not in unlinked storage. That distinction went into my explainer for depot managers ([[depot-results-rollup-explainer]]).

## Caveats

About a different product; used only to understand the general design choice. It says nothing about reporting thresholds.

## Source Links

- [Participant settings - LimeSurvey Manual](https://www.limesurvey.org/manual/Participant_settings)
