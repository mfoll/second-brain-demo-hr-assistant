---
type: Source
source_type: Documentation
url: https://www.rfc-editor.org/rfc/rfc5545
date_accessed: 2025-04-02
belongs_to: "[[interview-scheduling-overhaul]]"
related_to:
  - "[[hireloom]]"
  - "[[schedule-interviews-in-hireloom]]"
_organized: true
---

# Internet Calendaring and Scheduling Core Object Specification (iCalendar)

IETF RFC 5545, edited by B. Desruisseaux, September 2009. Standards Track; obsoletes RFC 2445.

## Summary

Defines the iCalendar data format for representing and exchanging calendar information (events, to-dos, journal entries, free/busy time) independently of any particular calendar service. It is the format behind the `.ics` invitation files most calendar programs exchange.

## Why It Matters

During the [[interview-scheduling-overhaul]], candidates on phones and non-Outlook calendars could not add our manual interview invites. Rashid Karimi pointed me to this standard: Hireloom can send self-scheduling confirmations as standard iCalendar invites, which work in any calendar. Switching that setting on in April 2025 cut "I didn't get the invite" calls to almost none.

## Caveats

I read the abstract and introduction only; the details of time zones and recurrence were not needed for us.

## Source Links

- [RFC 5545 at the RFC Editor](https://www.rfc-editor.org/rfc/rfc5545)
