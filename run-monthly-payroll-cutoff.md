---
type: Procedure
belongs_to: "[[coordinate-payroll-and-absence]]"
related_to:
  - "[[payroll-cutoff-checklist-v2]]"
  - "[[payroll-cutoff-calendar]]"
  - "[[gemma-ashworth]]"
_organized: true
---

# Run Monthly Payroll Cut-Off

How I get People Services' changes to Group Payroll for the monthly payroll (cut-off the 15th, paid the 26th). Written in April 2025 with the checklist; updated on 2026-07-01 for double keying in Talvento and Staffora. Will change again at payroll cutover ([[when-should-payroll-cut-over-to-talvento]]).

## When to use

Every month, from the 10th to the 16th. If the 15th falls on a weekend, everything moves to the Friday before ([[payroll-cutoff-calendar]]).

## Inputs

- [[payroll-cutoff-checklist-v2]], monthly list.
- Talvento reports: starters this month, leavers this month, changes with effective date this month, absence approved since last cut-off ([[talvento-reports-i-use]]).
- Deskwell queue filtered to the payroll-related categories.
- One-off payment approvals from HRBPs (must be in by the 12th).

## Steps

1. **10th.** Run the starters and leavers reports. For each starter, check against [[group-payroll-new-starter-requirements]]; chase missing bank or tax details through the starter's onboarding contact, not the starter directly.
2. **12th.** Collect HRBP-approved one-off payments. Anything without written HRBP approval waits for next month.
3. **13th.** Check that every change keyed in Talvento this month is also in Staffora (nightly comparison report). Key any misses in Staffora with the effective date in the comment and flag them to Gemma ([[effective-dating]]).
4. **14th.** Run the absence report. Remind managers with unapproved absence in the period, by division list to the HRBPs, not by name to everyone.
5. **15th, by 17:00.** Send Gemma the monthly summary: counts by change type, any item needing attention, and the "nothing else to send" confirmation.
6. **16th.** Log anything that arrived after 17:00 on the 15th in the [[payroll-late-changes-log]] with its cause.

## Guardrails

- Never put pay amounts or a named person's details in email subjects or in these notes. The summary to Gemma uses payroll numbers; record-level detail stays in Talvento and the payroll system ([[record-hr-cases-without-personal-data]]).
- An off-cycle payment is Elspeth's decision, not mine. Ask, do not promise.

## Verification

After payday, check the late changes count with Elspeth's team and compare with the log. A difference means something was sent outside the checklist.
