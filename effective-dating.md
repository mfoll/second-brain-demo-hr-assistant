---
type: Concept
belongs_to: "[[talvento-hris-migration]]"
related_to:
  - "[[talvento]]"
  - "[[staffora]]"
  - "[[parallel-run-review-2026-09-03]]"
_organized: true
---

# Effective Dating

Recording every change to an employee record with the date it takes effect, separately from the date it was keyed, and keeping the old value. A pay rise agreed on 3 October but backdated to 1 September is keyed on 3 October with an effective date of 1 September; the record shows both values and when each applied.

## Why it matters here

- [[talvento]] is effective-dated; [[staffora]] is not. In Staffora a change overwrites the old value and a backdated change is keyed as today's change with a note. Payroll reads the value, not the note.
- That mismatch is behind the backdated-change differences in the parallel run: 8 in July, 5 in August ([[parallel-run-review-2026-09-03]]). They will stop when double keying stops ([[when-should-payroll-cut-over-to-talvento]]).
- It also makes Talvento reports answerable "as at" a date, which Staffora's never were: headcount on 1 April, managers as at the survey date ([[talvento-reports-i-use]]).

## Practical rules I use

- Always ask "from when?" before keying a change, and put that in the effective date, not the comment.
- Future-dated changes take effect overnight on the date; a leaver keyed for Friday is still active until Saturday 00:00.
- A correction to a past record is a new effective-dated row, not an overwrite, so the history shows the mistake and its fix.
