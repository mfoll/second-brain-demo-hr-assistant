---
type: Project
status: Active
start: 2025-09-01
belongs_to: "[[maintain-hr-systems]]"
related_to:
  - "[[fiona-mcbride]]"
  - "[[hr-data-quality]]"
  - "[[mirela-dumitru]]"
has:
  - "[[payroll-parallel-run]]"
  - "[[manager-self-service-rollout]]"
  - "[[when-should-payroll-cut-over-to-talvento]]"
  - "[[uat-defect-review-2026-03-11]]"
  - "[[talvento-migration-lessons-learned]]"
_organized: true
---

# Talvento HRIS Migration

The programme moving Pellmore's HR records, organisation structure, absence and payroll feed from [[staffora]], the on-premises HR system used since 2011, to [[talvento]], a cloud HR system. [[fiona-mcbride]] is the programme manager; [[adrian-fairclough]] sponsors it and chairs the HRIS Steering Group. I joined in September 2025 as data and testing support for People Services.

## Outcome

All 4,100 employee records, the organisation structure and absence balances live in Talvento, payroll fed from Talvento, Staffora read-only before its licence ends on 2027-03-31.

## Current State

- Core HR, organisation structure, absence and manager self-service live in Talvento since 2026-06-29 ([[talvento-go-live-2026-06-29]]).
- Payroll still fed from Staffora. Parallel runs: 37 unexplained differences in July, 9 in August, 0 in September. The October run closes on 2026-10-28 ([[payroll-parallel-run]]).
- Cutover date undecided: [[fiona-mcbride]] wants November, [[elspeth-harcourt]] January 2027. HRIS Steering Group decides on 2026-11-04 ([[when-should-payroll-cut-over-to-talvento]]).
- 288 of 410 line managers trained in self-service as of 2026-10-16 ([[manager-self-service-rollout]]).
- Changes to employee data are keyed twice until cutover: in Talvento as the master, then in Staffora for payroll. Rashid's nightly comparison catches the misses.

## Scope and Boundaries

In scope: core HR records, organisation and cost centre structure, absence, manager and employee self-service, the payroll interface, user provisioning to IT, Staffora's retirement. Out of scope for this phase: Learnmoor training history (phase 2, 2027; only a nightly completions feed is live, since 2026-07-20), recruitment (stays in [[hireloom]], which hands new starters to Talvento), the engagement survey. Personal data moves under the vendor contract and the DPO's sign-off; nothing about an individual record goes in these notes.

## Working Context

The plan was a single go-live on 2026-04-01 ([[talvento-go-live-plan-april-2026]], now archived). It slipped because of one defect class. Staffora holds absence in hours; Talvento holds it in days, converted from each person's working pattern. The carry-over rules converted 312 balances wrongly, almost all part-time (241) and compressed-hours (71) staff. At the [[uat-defect-review-2026-03-11]] the Steering Group chose to move go-live to 2026-06-29 rather than go live with manual corrections. Rashid fixed the conversion ([[absence-conversion-specification]]) and I re-tested every one of the 312 records with him ([[absence-balance-retest-2026-05-14]]).

The payroll cutover is the second decision point. The Steering Group set the rule on 2026-06-17: two consecutive monthly parallel runs with no unexplained differences, then cut over at the next monthly payroll ([[hris-steering-group-2026-06-17]]). If October is clean, the rule is met. The disagreement is about timing, not readiness. Options in [[payroll-cutover-options-comparison]]; my own view in [[payroll-cutover-should-wait-for-january]].

## Active Workflows

- [[payroll-parallel-run]]: monthly comparison of Staffora-fed and Talvento-fed payroll with Group Payroll.
- [[manager-self-service-rollout]]: training sessions and the tracker.
- Nightly Staffora versus Talvento comparison report (Rashid); I clear the exceptions each morning.
- HRIS Steering Group every two weeks on Wednesdays; I keep the action log.

## Next Actions

- [ ] Categorise October parallel run differences with [[gemma-ashworth]] by 2026-10-30.
- [ ] Help Fiona write the cutover paper for 2026-11-04, with both options and their risks set out fairly.
- [ ] Finish the Staffora report inventory with [[rashid-karimi]] so read-only mode loses nothing anyone uses.
- [ ] Get a recommendation on Staffora history to the Steering Group before year-end ([[what-happens-to-staffora-history-after-2027-03-31]]).

## Open Questions

- [[when-should-payroll-cut-over-to-talvento]]
- [[what-happens-to-staffora-history-after-2027-03-31]]
- [[who-owns-hr-data-quality-after-go-live]]
- [[should-talvento-show-bradford-factor-scores]]

## Important Notes

- [[uat-defect-review-2026-03-11]]: why go-live moved.
- [[parallel-run-differences-log-2026]] and [[parallel-run-difference-categories]].
- [[talvento-statement-of-work]]: what the implementation partner owes us.
- [[talvento-migration-lessons-learned]]: my running list.
- [[staffora-decommissioning-plan]].

## Do Not Do Yet

> [!danger]
> Do not switch off the Staffora weekly payroll export or the double keying until the Steering Group has set a cutover date and Group Payroll confirms the first Talvento-fed run is paid. A missed export means people are not paid.

## Maintenance Log

- 2026-10-07: September parallel run clean; cutover date now the open decision.
- 2026-06-29: Core HR live in Talvento.
- 2026-06-17: Two-clean-runs rule set for payroll cutover.
- 2026-03-11: Go-live moved from 2026-04-01 to 2026-06-29.
- 2025-09-03: Steering Group kick-off.
