---
type: Project
status: Completed
start: 2025-04-07
end: 2025-06-20
belongs_to: "[[run-hr-helpdesk]]"
related_to:
  - "[[leon-adjei]]"
  - "[[hr-service-delivery]]"
  - "[[ticket-triage]]"
has:
  - "[[helpdesk-ticket-categories]]"
  - "[[deskwell-routing-rules]]"
  - "[[helpdesk-category-workshop-2025-04-23]]"
  - "[[how-many-ticket-categories-do-we-need]]"
_organized: true
---

# Helpdesk Triage Categories

Cutting the [[deskwell]] ticket categories from 31 to 14, writing routing rules for each, and setting a first-response target. Leon sponsored it; I did the counting, the drafts and the testing. Completed on 2025-06-20.

## Outcome

Deskwell ticket categories cut from 31 to 14, with routing rules and a first-response target of two working days.

## Current State

> [!success]
> Live since 2025-06-16 and still in use. First response within two working days went from 48% of tickets in March 2025 to 91% in September 2026.

- The 14 categories and their monthly counts live in [[helpdesk-ticket-categories]]; the old list is archived as [[deskwell-category-list-2024]].
- Routing rules: [[deskwell-routing-rules]]. The daily method: [[triage-a-deskwell-ticket]].
- One change since: "Flexible working" was renamed "Hybrid and flexible working" on 2026-03-30, ahead of the anchor-day launch, so hybrid counts are comparable before and after.

## Scope and Boundaries

Categories, routing and the response target only. Not staffing levels (Leon and [[deborah-okwuosa]]), not the knowledge base (later, in [[knowledge-base-rebuild]]). The Employee relations category is routed to a restricted queue that the rest of us cannot open, by design.

## Working Context

The [[helpdesk-baseline-report-2025-03]] showed why: 31 categories, of which nine had fewer than five tickets a month and three overlapped ("Holiday", "Annual leave", "Leave requests"). About 38% of tickets were in "General enquiry", so routing was by whoever picked them up. Median first response was 4.6 working days.

Options considered at the [[helpdesk-category-workshop-2025-04-23]]:

1. **Keep 31 and retrain people.** Rejected: the overlap was the problem, not the training.
2. **Eight broad categories.** Rejected by [[tomas-ferreira-lund]] and Group Payroll: pay and absence each need their own route, and ER must be separable.
3. **Fourteen, each with one owning team.** Chosen. Every category has an owner and a default assignee; "General enquiry" went, and an uncategorised ticket now goes back to the triager rather than sitting.

The two-day first-response target came from Leon; I argued for one day for pay queries during payroll week, which became a routing priority rather than a separate target ([[what-first-response-target-should-the-helpdesk-use]]).

## Next Actions

- [ ] None outstanding. Category review is now part of the yearly knowledge base review.

## Important Notes

- [[helpdesk-ticket-categories]]
- [[deskwell-routing-rules]]
- [[ticket-triage]]
- [[first-response-time]]
- [[how-many-ticket-categories-do-we-need]]

## Maintenance Log

- 2026-03-30: Category 5 renamed to "Hybrid and flexible working".
- 2025-06-20: Closed after four weeks of live use; 79% within target in the first month.
- 2025-06-16: New categories live in Deskwell.
- 2025-04-23: Workshop agreed 14 categories.
- 2025-04-07: Started from the March baseline.
