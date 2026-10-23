---
type: Source
source_type: Internal system
date_accessed: 2026-10-20
belongs_to: "[[run-hr-helpdesk]]"
related_to:
  - "[[helpdesk-ticket-categories]]"
  - "[[knowledge-base-rebuild]]"
  - "[[hr-service-delivery]]"
_organized: true
---

# Deskwell

The HR helpdesk ticketing tool and the employee-facing knowledge base that sits on top of it. People Services has used it since 2022; [[leon-adjei]] is the system owner and I am one of two admin users.

## Summary

Employees raise tickets through the Deskwell portal, by email to the HR inbox (which Deskwell converts to tickets) or from a "still need help?" button at the bottom of every knowledge base article. Tickets land in queues by category, get a first response, and close with a one-question satisfaction survey. The knowledge base is public to all staff, including on phones without a login, which matters for hub and depot staff.

## Key Details

- **Queues.** Four: HR Shared Services (most categories), Payroll liaison (pay, pensions; shared with Group Payroll), Recruitment and onboarding, and a restricted Employee relations queue only [[tomas-ferreira-lund]] and the HR Business Partners can open. Routing in [[deskwell-routing-rules]].
- **Categories.** 14 since 2025-06-16, down from 31 ([[helpdesk-ticket-categories]], old list in [[deskwell-category-list-2024]]).
- **First-response target.** Two working days for every category; pay queries in payroll week are routed to the top of the queue rather than given a separate target ([[first-response-time]]). Met for 91% of tickets in September 2026.
- **Volume.** About 1,000 to 1,300 tickets a month; 1,140 in September 2026.
- **Knowledge base.** 117 published articles as of 2026-10-20 (target 138). Every article carries an owner field and a review date; Deskwell emails the owner 30 days before the date and flags the article in red on the admin view once it passes ([[knowledge-article-lifecycle]]).
- **Reports.** Monthly ticket counts by category and queue, first-response compliance, satisfaction, article views and the "still need help?" click rate. These aggregate reports are what my [[diploma-research-project]] may use; ticket text may not.
- **Retention.** Closed tickets are kept for 24 months and then deleted automatically, agreed with [[kasia-wrobel]] in 2025.
- **Chatbot add-on.** Deskwell Assist was trialled from 2025-06-02 to 2025-11-14 and switched off ([[helpdesk-chatbot-trial]], [[deskwell-assist-trial-terms]]).
- **Integrations.** Reads employee name, work email, site and manager from the HR system to prefill tickets: from Staffora until 2026-06-29, from [[talvento]] since.

## Caveats

- Category is set by the triager, not the employee, so counts depend on triage discipline ([[ticket-triage]]).
- Email tickets have no category until triaged; on busy Mondays up to 60 sit uncategorised for a few hours.
- The view-based self-service figure is an estimate, see [[how-do-we-measure-self-service-resolution]].

## Source Location

Deskwell admin console and the monthly report export, People Services shared drive, folder "Helpdesk reports". Access through Leon.
