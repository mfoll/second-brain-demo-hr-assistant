---
type: Project
status: Completed
start: 2025-09-15
end: 2026-02-27
belongs_to: "[[talvento-hris-migration]]"
related_to:
  - "[[hr-data-quality]]"
  - "[[rashid-karimi]]"
  - "[[data-quality-dimensions]]"
has:
  - "[[staffora-data-issue-log]]"
  - "[[staffora-duplicate-records-report-2025-10]]"
  - "[[data-cleansing-close-2026-02-27]]"
_organized: true
---

# HRIS Data Cleansing

Fixing or formally accepting every data issue found in Staffora before migration, so that Talvento started clean. I did most of the checking and chasing; [[rashid-karimi]] did the bulk fixes; the HR Business Partners answered for their divisions.

## Outcome

1,940 data issues in Staffora fixed or accepted before migration (duplicates, leavers still active, missing cost centres, wrong managers).

## Current State

- Completed on 2026-02-27 ([[data-cleansing-close-2026-02-27]]). 1,862 issues fixed, 78 accepted with a reason recorded in the [[staffora-data-issue-log]].
- The checks did not stop: the same rules now run monthly against Talvento in the [[hr-data-quality-scorecard]].

## Scope and Boundaries

Active employee records, the organisation structure, cost centres and line manager links. Leaver records older than six years were not cleaned; they stay in Staffora for the retention period ([[what-happens-to-staffora-history-after-2027-03-31]]). Pay data was checked by Group Payroll, not by us.

## Working Context

The issue log by category at close:

| Category | Found | Fixed | Accepted |
| --- | --- | --- | --- |
| Missing or invalid cost centre | 604 | 589 | 15 |
| Wrong or missing line manager | 497 | 497 | 0 |
| Leaver still active | 388 | 388 | 0 |
| Duplicate person records | 212 | 171 | 41 |
| Other (job titles, sites, contract types) | 239 | 217 | 22 |
| Total | 1,940 | 1,862 | 78 |

The 41 accepted duplicates are people with two genuine employments (for example a driver who also does weekend hub shifts on a separate contract). Talvento handles these as one person with two assignments, so the mapping, not the data, dealt with them ([[talvento-migration-field-mapping]]).

What worked: one tab per HR Business Partner with only their division's issues, and a Friday count to Deborah ([[cleansing-update-for-deborah-2026-02]]). What did not: asking line managers directly to confirm their teams. 40% never answered. The HRBPs got answers in a week.

Cost centres were the slowest because Finance was restructuring them at the same time. [[beatrix-lowe]] gave us the 2026 hierarchy ([[cost-centre-hierarchy-2026]]) in January and we mapped against that.

## Next Actions

- [ ] None. Closed on 2026-02-27.

## Important Notes

- [[staffora-data-issue-log]]
- [[staffora-duplicate-records-report-2025-10]]
- [[data-cleansing-wikipedia]]
- [[data-quality-dimensions]]

## Maintenance Log

- 2026-02-27: Closed with 78 accepted issues.
- 2026-01-16: Cost centre mapping restarted against the 2026 hierarchy.
- 2025-10-24: Duplicate report run; 212 candidate duplicates.
- 2025-09-15: Started.
