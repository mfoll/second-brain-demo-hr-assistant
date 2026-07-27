---
type: Note
belongs_to: "[[payroll-parallel-run]]"
related_to:
  - "[[parallel-run-differences-log-2026]]"
  - "[[effective-dating]]"
  - "[[when-should-payroll-cut-over-to-talvento]]"
_organized: true
---

# Parallel Run Difference Categories

What the unexplained parallel run differences were, and which kinds are gone for good. From the [[parallel-run-differences-log-2026]].

| Category | Jul | Aug | Sep | Fixed by |
| --- | --- | --- | --- | --- |
| Absence in a different pay period | 14 | 0 | 0 | Interface v1.3, absence by date ([[payroll-interface-specification]]) |
| Cost centre mapping | 11 | 3 | 0 | Mapping table; codes opened in both systems the same day ([[beatrix-lowe]]) |
| Backdated change in one system only | 8 | 5 | 0 | Daily check; ends with double keying |
| Part-time hours rounding | 4 | 1 | 0 | Rounding rule aligned to two decimals |
| Total unexplained | 37 | 9 | 0 | |

## What it means for cutover

Three of the four categories were system or mapping problems and are fixed. The fourth, backdated changes, is a process problem caused by keying in two systems. September had none only because I check every morning. That is the strongest evidence for Fiona's November case, and it is why my January preference is only medium confidence ([[payroll-cutover-should-wait-for-january]]).
