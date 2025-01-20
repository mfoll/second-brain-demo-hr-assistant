---
type: Note
belongs_to: "[[maintain-hr-systems]]"
related_to:
  - "[[staffora]]"
  - "[[rashid-karimi]]"
_organized: true
---

# Staffora Quirks Cheat Sheet

Things about Staffora nobody wrote down, collected from Rashid and from my own mistakes since October 2024. Still useful while it feeds payroll.

- Absence is in hours, always. A "day" in a report is the hours divided by 7.5, whatever the person's pattern.
- Saving a change with a past date does nothing to the past; it changes today's value. Put the real date in the comment and tell payroll ([[effective-dating]]).
- The "Leaver" tick does not end the record until the overnight batch; if you key a leaver after 18:00 it happens the night after.
- Cost centre field accepts anything typed before 2019 records were cleaned; the drop-down only appears on new records.
- Report Writer exports dates as text in US order. Convert before sorting.
- The duplicate check only looks at surname and date of birth, so a changed surname creates a new person.
- Do not use the "Copy employee" button. It copies the working pattern and the absence balance.
- Weekly export runs at 12:30 on Thursday. Anything keyed at 12:25 is in; at 12:35 it is next week ([[payroll-cutoff-calendar]]).
