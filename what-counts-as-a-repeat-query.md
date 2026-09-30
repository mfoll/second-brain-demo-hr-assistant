---
type: Question
status: Answered
belongs_to: "[[diploma-research-project]]"
related_to:
  - "[[repeat-query]]"
  - "[[research-dataset-specification]]"
_organized: true
---

# What Counts As A Repeat Query

For the research project I needed one definition of a repeat query that [[leon-adjei]] could compute inside Deskwell without me seeing individual tickets.

## Options considered

- Reopened tickets only: too narrow, since most people open a new ticket rather than reopen.
- Any second ticket from the same employee in a month: catches unrelated questions.
- Same employee, same category, within 30 days: chosen.

## Current Answer

Answered on 2026-09-24 with Leon: a repeat query is a ticket from an employee who had raised a ticket in the same category in the previous 30 days. Leon computes the monthly count per category; I receive counts only ([[research-dataset-specification]]). The definition and its limits are in [[repeat-query]].
