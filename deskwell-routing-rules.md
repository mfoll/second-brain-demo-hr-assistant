---
type: Source
source_type: Internal document
date_accessed: 2025-06-13
belongs_to: "[[helpdesk-triage-categories]]"
related_to:
  - "[[deskwell]]"
  - "[[ticket-triage]]"
  - "[[tomas-ferreira-lund]]"
_organized: true
---

# Deskwell Routing Rules

The rules that send a categorised ticket to a queue and default assignee in [[deskwell]]. Drafted by me in May 2025, configured by [[leon-adjei]], live from 2025-06-16; last changed 2026-06-29 for Talvento.

## Summary

Rules are evaluated in order:

1. Employee relations category: restricted ER queue, [[tomas-ferreira-lund]]. Evaluated first since the go-live near miss ([[helpdesk-categories-go-live-2025-06-16]]).
2. Pay and payslips, Pensions and benefits: Payroll liaison queue. In payroll week (the five working days before the 15th, and Wednesday to Thursday noon for weekly pay) these go to the top.
3. Recruitment and references, Onboarding and new starters: Recruitment and onboarding queue ([[callum-rourke]], [[aoife-brennan-hale]]).
4. HR systems access: HR Shared Services, with access requests forwarded to the HRIS team.
5. Everything else: HR Shared Services general queue, picked by the rota ([[helpdesk-cover-rota-2026]]).
6. No category: back to the triager.

## Why It Matters

Explains where a ticket goes and why nobody outside ER sees ER content. The daily method is [[triage-a-deskwell-ticket]].

## Source Location

Deskwell admin console, "Automations"; documented copy in "Helpdesk/Routing rules v4".
