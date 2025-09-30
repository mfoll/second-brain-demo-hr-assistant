---
type: Note
belongs_to: "[[talvento-hris-migration]]"
related_to:
  - "[[moving-go-live-to-june-was-right]]"
  - "[[fiona-mcbride]]"
  - "[[hris-user-acceptance-testing]]"
_organized: true
---

# Talvento Migration Lessons Learned

My running list of what I would do differently on another system migration. Started after the go-live slip, added to since. Fiona has asked for it for the programme closure report, so I keep it shareable.

## Testing

- Test conversions on edge cases in week one: part-time, compressed hours, nine-day fortnights, mid-year pattern changes, double employments. We found the carry-over defect in week six ([[uat-defect-review-2026-03-11]]).
- Write test scripts as real People Services scenarios ("a hub operative moves to nights and books leave the same week"), not feature lists.
- A masked test tenant is enough for almost everything. We never needed real names ([[kasia-wrobel]]'s condition).

## Data

- Fix ownership before fixing data. Line managers asked directly ignored 40% of requests; HRBPs got answers in a week ([[hris-data-cleansing]]).
- Ask Finance for the target cost centre structure before starting, not halfway ([[cost-centre-hierarchy-2026]]).

## Go-live

- Double keying is more expensive than it looks: about one day a week for People Services, plus the errors it creates ([[parallel-run-difference-categories]]). Plan the payroll cutover date before go-live, not after.
- Leavers keyed late broke provisioning ten days in ([[leaver-access-incident-2026-07-09]]). Test past-dated changes.

## People

- E-learning alone does not train team leaders ([[team-leaders-need-floor-training-not-e-learning]]).
- A two-page laminated guide beat everything else we produced ([[manager-self-service-quick-guide]]).
