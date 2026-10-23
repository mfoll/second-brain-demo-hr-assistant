---
type: Source
source_type: Internal system
date_accessed: 2026-10-20
belongs_to: "[[maintain-hr-systems]]"
related_to:
  - "[[staffora]]"
  - "[[talvento-hris-migration]]"
  - "[[talvento-reports-i-use]]"
  - "[[human-resource-management-system-wikipedia]]"
_organized: true
---

# Talvento

Pellmore's new cloud HR information system and, since 2026-06-29, the master record for employee data. Payroll still reads from [[staffora]] until the cutover.

## Summary

Talvento is a cloud HRIS bought in 2025 under a three-year subscription, implemented with the vendor's partner ([[talvento-statement-of-work]], consultant [[mirela-dumitru]]). Modules live since 2026-06-29:

- **Core HR**: person and employment records, contracts, working patterns, with effective dating ([[effective-dating]]).
- **Organisation structure**: divisions, sites, departments, positions and the 2026 cost centre hierarchy ([[cost-centre-hierarchy-2026]]).
- **Absence**: requests, approvals, balances in days derived from each working pattern ([[annual-leave-carry-over]]).
- **Manager self-service**: absence approval, sickness recording, hours changes, leaver notifications ([[manager-self-service-rollout]]).
- **Employee self-service**: personal details, bank details, leave requests.

Integrations:

- **Hireloom to Talvento**: accepted candidates arrive as pending new starters; HR completes them ([[enter-new-starters-before-weekly-cutoff]]).
- **Talvento to IT**: accounts created, changed and disabled from Talvento changes ([[talvento-it-provisioning-design]]).
- **Talvento to payroll**: the interface file, in parallel run until cutover ([[payroll-interface-specification]], [[payroll-parallel-run]]).
- **[[learnmoor]]**: course completions feed Talvento nightly since 2026-07-20; full training history moves in phase 2, planned for 2027.

## Key Details

- Access is role-based: employee, line manager, HR assistant, HR advisor, HRBP, payroll, HRIS admin ([[talvento-access-roles-matrix]]).
- Every change has an effective date and a reason. Future-dated changes take effect overnight.
- Case management: HR cases are logged with references in the form HR-2026-xxxx, visible only to HR advisors and the HRBPs. My notes point to the reference, never the content ([[record-hr-cases-without-personal-data]]).
- Reports I use: [[talvento-reports-i-use]].

## Why It Matters

Talvento is where my data quality, absence and new starter work now happens. It fixed the things Staffora could not do (effective dating, self-service, real-time account changes) and introduced one thing we underestimated: absence in days, which cost us three months ([[uat-defect-review-2026-03-11]]).

## Caveats

- Payroll is not yet fed from Talvento; until cutover every change is keyed twice.
- Some Staffora reports have no Talvento equivalent yet (seven waived UAT scripts, [[uat-test-script-register]]).

## Source Location

Talvento web app (single sign-on). Configuration workbook and design decisions in the HRIS programme folder.
