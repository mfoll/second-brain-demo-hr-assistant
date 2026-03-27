---
type: Event
date: 2026-03-11
belongs_to: "[[hris-user-acceptance-testing]]"
related_to:
  - "[[talvento-hris-migration]]"
  - "[[annual-leave-carry-over]]"
  - "[[fiona-mcbride]]"
  - "[[rashid-karimi]]"
_organized: true
---

# UAT Defect Review 2026-03-11

The HRIS Steering Group's review of the first round of user acceptance testing, held as an extended Steering Group meeting. It moved the Talvento core HR go-live from 2026-04-01 to 2026-06-29.

## At a Glance

> [!note]
> 312 migrated absence balances were wrong: carry-over for part-time and compressed-hours staff had converted incorrectly from Staffora hours to Talvento days. The Steering Group chose to move go-live to 2026-06-29 and fix the conversion, rather than go live on 2026-04-01 with manual corrections.

## Attendees

[[adrian-fairclough]] (chair), [[fiona-mcbride]], [[deborah-okwuosa]], [[elspeth-harcourt]], [[rashid-karimi]], [[olumide-fashola]], [[mirela-dumitru]], and me taking the actions.

## What was found

- Round 1 ran 214 scripts from 2026-01-12 to 2026-02-27 and raised 49 defects; three were critical ([[uat-defect-log-2026]]).
- The critical one was UAT-D-031. [[staffora]] holds leave balances in hours. [[talvento]] holds them in days, worked out from each person's working pattern. The migration converted carried-over hours using a standard 7.5-hour day. For full-time staff that was right. For part-time staff on shorter days and for compressed-hours staff on longer days, it was not.
- 312 records were affected: 241 part-time and 71 compressed hours. Errors ranged from half a day to four days of leave, both too much and too little. I found it on 2026-02-19 when a compressed-hours test case at Hub West showed 9.33 days carried over instead of 7.57.
- The other two critical defects (a manager hierarchy loop in two depots and a missing leaver reason code) were already fixed.

## Options discussed

1. **Go live on 2026-04-01 and correct the 312 by hand.** Mirela's preferred option. Rejected: the corrections would sit in Talvento as manual adjustments with no rule behind them, every future carry-over would repeat the error, and April is when the new leave year starts and balances matter most.
2. **Go live on 2026-04-01 for full-time staff only.** Rejected by Elspeth: two systems of record for absence during the leave year rollover.
3. **Move go-live to 2026-06-29**, fix the conversion rule, rerun the migration and retest all 312 records. Chosen. Fiona confirmed 2026-06-29 was the first date that avoided month-end payroll and the April leave year start, and left time for a third UAT round.

## Decisions

- Go-live moved to 2026-06-29. Adrian to inform the Executive Committee.
- Rashid to rewrite the conversion using each person's contracted daily hours from their working pattern ([[absence-conversion-specification]]).
- Me to retest every one of the 312 records with Rashid after the fix, against a hand calculation ([[absence-balance-retest-2026-05-14]]).
- Staffora licence end (2027-03-31) unaffected.
- Communication to staff: none needed; nobody's balance had changed in the live system. Deborah to brief the HRBPs.

## Actions

- [x] Fix conversion rule (Rashid, 2026-04-10).
- [x] Retest 312 records (me and Rashid, done 2026-05-14).
- [x] Revised plan to the Steering Group (Fiona, 2026-03-25): [[talvento-go-live-cutover-plan]], replacing [[talvento-go-live-plan-april-2026]].

## Afterwards

My view at the time, and still: [[moving-go-live-to-june-was-right]]. The underlying idea is in [[annual-leave-carry-over]] and [[compressed-hours]]. The resolved question is [[how-should-carry-over-convert-for-compressed-hours]].
