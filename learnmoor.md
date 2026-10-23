---
type: Source
source_type: Internal system
date_accessed: 2026-10-16
belongs_to: "[[mandatory-training-compliance]]"
related_to:
  - "[[yetunde-balogun]]"
  - "[[mandatory-training-catalogue]]"
  - "[[talvento]]"
_organized: true
---

# Learnmoor

Pellmore's learning management system: e-learning, classroom course booking and training records for all 4,100 employees and agency workers on site. Administered by [[yetunde-balogun]].

## Summary

Learnmoor hosts the four mandatory courses ([[mandatory-training-catalogue]]), around 140 optional e-learning modules, and bookings for classroom sessions such as Manual Handling practicals and hub induction training. It produces the completion reports used in [[mandatory-training-compliance]]. Since 2026-07-20 it sends completions to [[talvento]] nightly ([[learnmoor-talvento-completion-feed-spec]]).

## Key Details

- Users: loaded from the HR system. Until 2026-06-29 a weekly file from [[staffora]]; since then a daily file from Talvento. New starters appear the day after they are entered in the HR system.
- Agency workers: created by Yetunde from the agency list during peak; they are assigned Manual Handling and Fire Safety only.
- E-learning packages are SCORM 1.2; completion is recorded when the package reports "completed" or "passed" ([[sharable-content-object-reference-model]]).
- Hub operatives without work email log in with an employee number and PIN, at kiosks or on their own phones ([[hub-training-kiosk-pilot-results]]).
- Reports: the "Compliance by Org Unit" report is the one I use. It counts expired completions as incomplete, which is right, but does not exclude long-term absence or leavers in their notice period; see [[learnmoor-report-quirks]].
- Records move to Talvento: course code, completion date and expiry date only. Scores stay in Learnmoor.
- Licence renews 2027-01-31; cost line held by [[theo-varkey]] ([[training-budget-2026]]).

## Why It Matters

Every training figure I report comes from here. Knowing its quirks is the difference between 89% and an argument about 89% ([[training-completion-rate]]). Whether it survives the Talvento era is [[should-learnmoor-be-replaced-by-talvento-learning]].

## Caveats

Learnmoor shows who completed what; it does not show whether anyone learned anything. Classroom attendance is entered by trainers, sometimes a week late.

## Source Location

Learnmoor admin console (People Services role), reports menu. Report definitions saved by Yetunde in the L&D shared folder.
