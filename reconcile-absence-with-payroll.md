---
type: Procedure
belongs_to: "[[absence-data-reconciliation]]"
related_to:
  - "[[dariusz-nowicki]]"
  - "[[absence-reconciliation-reports-2026]]"
  - "[[why-do-absence-records-not-match-payroll]]"
_organized: true
---

# Reconcile Absence With Payroll

The monthly comparison of absence in Talvento with absence processed by payroll, run with [[dariusz-nowicki]]. Agreed at the [[absence-mismatch-review-2026-02-12]]; updated for Talvento in July 2026 and for the "late but correct" category in October 2026.

## When to use

The second week after each monthly payday, on a Tuesday or Wednesday (never Thursday, weekly cut-off).

## Inputs

- Talvento extract: absence records with an absence date in the reconciled month, with type, duration and approval date.
- Payroll extract from Dariusz: absence processed for the same month, by payroll code.
- Mapping of Talvento absence types to payroll codes.

## Steps

1. Match records on payroll number, absence date and type. Dariusz runs the match; I check the unmatched list.
2. Sort each mismatch into a cause: approved after cut-off and processed correctly next run ("late but correct"), approved after cut-off and not yet processed, type coded differently, part day or full day, backdated correction, other.
3. For "late but correct", no action; count only ([[can-managers-approve-absence-after-the-cut-off]]).
4. For the others, Dariusz corrects the payroll side; I route HR-side corrections to the manager through Talvento or to the HR advisor if it touches a case.
5. Write the one-page report: counts, rate, causes, by division only ([[absence-reconciliation-reports-2026]]).
6. Send to Elspeth, Deborah and the three HRBPs.

## Guardrails

- Counts by division, never by manager or employee name, in any report or note ([[record-hr-cases-without-personal-data]]).
- Sickness details are not discussed beyond the absence type. Occupational health is never part of the reconciliation.
- Do not report a division count below 10 mismatches as a separate line if it could identify someone; fold small sites into their division.

## Verification

The rate excluding "late but correct" should follow the trend in [[absence-mismatch-causes-2026]]. A jump of more than one point means check the extracts before reporting.
