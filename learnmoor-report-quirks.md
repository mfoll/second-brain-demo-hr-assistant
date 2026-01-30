---
type: Note
belongs_to: "[[mandatory-training-compliance]]"
related_to:
  - "[[learnmoor]]"
  - "[[training-completion-rate]]"
  - "[[yetunde-balogun]]"
_organized: true
---

# Learnmoor Report Quirks

Things to correct or check before trusting a [[learnmoor]] compliance report. Mostly learned from [[yetunde-balogun]] and from getting it wrong.

- Long-term absence and parental leave are not excluded. Use the absence flag from Talvento and remove them by hand ([[training-completion-rate]]).
- Leavers in their notice period stay in until their leaving date. Exclude them.
- Agency workers appear under the hub's org unit; they hold only Fire Safety and Manual Handling, so filter them out of the other two courses.
- "In progress" SCORM attempts that timed out show as incomplete even if the person finished the content ([[sharable-content-object-reference-model]]). If someone says they did it, ask Yetunde to check the attempt log before arguing.
- The report runs on yesterday's data; classroom attendance can be up to a week late.
- Org units changed on 2026-06-29 with Talvento. For trends across that date, compare by division, not department.
- Never save a named list into a shared folder. Managers get their own team list in Learnmoor.
