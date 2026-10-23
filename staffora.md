---
type: Source
source_type: Internal system
date_accessed: 2026-10-19
belongs_to: "[[maintain-hr-systems]]"
related_to:
  - "[[talvento]]"
  - "[[staffora-quirks-cheat-sheet]]"
  - "[[staffora-decommissioning-plan]]"
  - "[[rashid-karimi]]"
_organized: true
---

# Staffora

Pellmore's legacy HR information system: on-premises, in use since 2011, licence ending on 2027-03-31. Since 2026-06-29 it is no longer the master record, but it still feeds payroll until the cutover to [[talvento]].

## Summary

Staffora held every Pellmore employee record from 2011 to June 2026: personal and contract details, organisation structure, line managers, cost centres, absence and the payroll export. It runs on a server in the Head Office data room and is supported under an annual licence. [[rashid-karimi]] has administered it since 2017.

What it holds now:

- About 4,100 active employee records and about 9,800 leaver records going back to 2011.
- Absence history, recorded in hours for everyone, including full-time staff.
- The weekly payroll export (every Thursday at 12:30, straight after the 12:00 cut-off) and the monthly export (the working day after the 15th).

## Key Details

- **Absence in hours.** Staffora stores every absence and every leave balance in hours. A full-time 37.5-hour employee's 25 days of leave is 187.5 hours. This worked until migration: Talvento stores balances in days derived from each person's working pattern, and the conversion of carry-over for part-time and compressed-hours staff went wrong for 312 records ([[uat-defect-review-2026-03-11]]).
- **Free-text cost centres before 2019.** Cost centre was a free-text field until 2019, which is why 604 records needed fixing during cleansing ([[hris-data-cleansing]]).
- **No effective dating.** A change overwrites the old value; history is kept only in an audit table that reports cannot reach. Backdated changes are entered as today's change with a note. See [[effective-dating]].
- **Duplicates.** A rehired employee got a new person number until 2021, hence most of the 212 candidate duplicates ([[staffora-duplicate-records-report-2025-10]]).
- **Reports.** About 140 saved reports, of which perhaps 30 are used. Inventory under way with Rashid.
- More quirks I learned the hard way: [[staffora-quirks-cheat-sheet]].

## Current status

- Double keying: since go-live every change is made in Talvento first, then in Staffora for payroll. Rashid's nightly comparison flags misses.
- Becomes read-only the day after the first Talvento-fed payroll is paid ([[when-should-payroll-cut-over-to-talvento]]).
- Licence ends 2027-03-31. Whether history is migrated, archived or extracted is open: [[what-happens-to-staffora-history-after-2027-03-31]]. Plan: [[staffora-decommissioning-plan]].

## Why It Matters

Staffora is why most of my migration work exists. Its hours-based absence, missing effective dating and old free-text fields are behind the cleansing, the go-live slip and the backdated-change differences in the [[payroll-parallel-run]]. Until cutover it is still how 4,100 people get paid, so nothing gets switched off early.

## Caveats

- Staffora counts are as of October 2026; leaver records still grow until read-only.
- No individual's data is recorded here; record-level issues point to the Staffora case reference ([[record-hr-cases-without-personal-data]]).

## Source Location

Staffora client on People Services machines; admin access Rashid only. Report inventory in the HRIS programme folder, `Talvento / Decommissioning / Staffora reports`.
