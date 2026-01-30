---
type: Question
status: Answered
belongs_to: "[[absence-data-reconciliation]]"
related_to:
  - "[[payroll-cut-off]]"
  - "[[manager-self-service-rollout]]"
  - "[[effective-dating]]"
_organized: true
---

# Can Managers Approve Absence After The Cut-Off?

If a line manager approves an absence in Talvento after the payroll cut-off for the period it falls in, what happens, and should Talvento block it?

## Current Answer

> [!info]
> Yes, they can, and Talvento should not block it. The approval keeps the absence date as its effective date and payroll picks it up in the next run as an adjustment. Agreed by Elspeth Harcourt and Fiona McBride on 2026-07-22. Blocking would push managers back to email.

## What we know

- In September 2026, 7% of absence requests were approved after the cut-off for their period ([[manager-self-service-rollout]]).
- Most are sickness absence recorded on return to work, which is the correct process.
- After the August interface fix, payroll processes these by absence date ([[payroll-interface-specification]]), so the deduction is right, just a month late.

## Follow-up

The reconciliation counts these separately as "late but correct", so they no longer inflate the mismatch rate from October ([[reconcile-absence-with-payroll]]).
