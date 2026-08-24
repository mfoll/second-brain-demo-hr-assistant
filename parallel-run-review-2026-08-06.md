---
type: Event
date: 2026-08-06
belongs_to: "[[payroll-parallel-run]]"
related_to:
  - "[[gemma-ashworth]]"
  - "[[parallel-run-differences-log-2026]]"
  - "[[payroll-interface-specification]]"
_organized: true
---

# Parallel Run Review 2026-08-06

Review of the July 2026 monthly parallel run with [[gemma-ashworth]], [[elspeth-harcourt]], [[rashid-karimi]] and [[fiona-mcbride]].

- 37 unexplained differences across about 1,500 monthly payslips ([[parallel-run-differences-log-2026]]).
- By category: 14 absence deductions in a different pay period, 11 cost centre mapping errors, 8 backdated changes keyed in Staffora but not Talvento, 4 part-time hours rounding.
- The absence period issue is in the interface, not the data: Talvento sent absence by approval date, payroll expects it by absence date. Rashid and Mirela to fix ([[payroll-interface-specification]]); deployed 2026-08-14.
- Cost centres: [[beatrix-lowe]] to correct the mapping table for 11 cost centres.
- Backdated changes: no technical fix while double keying lasts. I added a daily check of backdated Staffora changes to my morning routine.

Elspeth's comment: "37 is fine for a first run, as long as it is not 37 next month." It was 9.
