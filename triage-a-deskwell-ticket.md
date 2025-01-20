---
type: Procedure
belongs_to: "[[run-hr-helpdesk]]"
related_to:
  - "[[ticket-triage]]"
  - "[[deskwell-routing-rules]]"
  - "[[record-hr-cases-without-personal-data]]"
_organized: true
---

# Triage a Deskwell Ticket

How whoever is on the helpdesk rota triages a new ticket in [[deskwell]]. Written by me in June 2025, updated 2026-06-29 for Talvento; used to train [[carys-whitlock]].

## Inputs

A new or uncategorised ticket in the HR Shared Services general queue.

## Steps

1. **Read the whole ticket once.** Do not reply yet.
2. **Check sensitivity first.**
   - Employee relations (complaint about a colleague, a grievance, a disciplinary): set category 14. The ticket moves to the restricted queue. Do not reply, forward or quote it.
   - Health, a safety concern about someone at work, or a request for an adjustment: assign to the division's HR Business Partner the same day with the note "for HRBP, see ticket". Do not summarise the content anywhere else.
3. **Set the category** (one of 14, [[helpdesk-ticket-categories]]). If two fit, choose the one whose owner can answer the question. Anything about notice periods is Leavers.
4. **Check urgency.**
   - Pay or a new starter's details in payroll week (five working days before the 15th, or Wednesday to Thursday 12:00 for weekly pay): flag "payroll week" ([[payroll-cutoff-calendar]]).
   - A new starter not set up for their first day: flag "urgent" and message the onboarding queue.
5. **Answer or route.**
   - If a knowledge base article answers it: reply with the link and one sentence in plain words. Mark "resolved by article".
   - If it needs an advisor or HR Business Partner ([[tiered-hr-service-model]]): assign, and tell the employee who will reply and roughly when.
6. **First response within two working days** ([[first-response-time]]). A holding reply counts only if it says what happens next.
7. **If no article answered a common question**, add the theme (not the ticket) to the article wish list in the [[knowledge-base-rebuild-tracker]].

## Guardrails

- Never copy ticket text into chat, email subjects, shared documents or notes ([[record-hr-cases-without-personal-data]]).
- Never answer questions about one person's hybrid arrangement, pay calculation or absence record from memory; check the system or route it.

## Verification

Leon reviews 20 random triaged tickets each month for category and routing; misfiles are discussed at the Monday huddle without names.
