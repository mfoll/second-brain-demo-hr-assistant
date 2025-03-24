---
type: Project
status: Completed
start: 2025-03-03
end: 2025-07-25
belongs_to: "[[coordinate-recruitment]]"
related_to:
  - "[[candidate-experience]]"
  - "[[callum-rourke]]"
  - "[[hireloom]]"
has:
  - "[[interview-scheduling-baseline-2025]]"
  - "[[self-scheduling-go-live-2025-05-12]]"
  - "[[schedule-interviews-in-hireloom]]"
  - "[[interview-scheduling-overhaul-closure-report]]"
_organized: true
---

# Interview Scheduling Overhaul

Move first interviews from email ping-pong to Hireloom self-scheduling links, so candidates book their own slot from the hiring manager's published availability. My first project of my own, sponsored by [[marek-zielinski]], run with [[callum-rourke]].

## Outcome

Reached on 2025-07-25: Hireloom self-scheduling links are used for all first interviews, and the median time from shortlist to booked interview fell from 4.2 to 1.6 working days.

## Current State

- Completed. Self-scheduling has been the default since 2025-05-12 ([[self-scheduling-go-live-2025-05-12]]).
- The median has held between 1.5 and 1.8 working days through 2026, including peak.
- Second interviews and assessment centres are still booked by a coordinator; that was out of scope and still makes sense.

## Scope and Boundaries

First interviews for every division. Out of scope: assessment centres, second interviews, agency workers (the agency books its own).

## Working Context

The baseline ([[interview-scheduling-baseline-2025]]) showed the delay was not candidates but hiring managers: availability arrived by email two or three days after the shortlist. The fix was to make managers publish weekly slots in Hireloom, then let candidates book. Managers at depots who live on the road objected; [[lucia-arbeloa]] agreed to try it with transport planners booking slots for her, which became the pattern for drivers ([[should-first-interviews-for-drivers-use-self-scheduling]]).

Invitations go out as standard calendar invites ([[rfc-5545-icalendar]]), which fixed the Outlook-only problem we had with the old manual invites. A phone fallback stayed for candidates who do not use the link within 48 hours.

## Next Actions

None. Monitoring of time to schedule continues in the monthly recruitment report.

## Important Notes

- [[interview-scheduling-baseline-2025]]
- [[interview-scheduling-overhaul-closure-report]]
- [[schedule-interviews-in-hireloom]]
- [[time-to-schedule]]

## Maintenance Log

- 2025-07-25: Closed; median 1.6 working days over June and July ([[interview-scheduling-overhaul-closure-report]]).
- 2025-05-12: Self-scheduling live for all divisions.
- 2025-04-14: Pilot with Head Office vacancies: 31 interviews, median 1.4 days.
- 2025-03-03: Started with the baseline analysis.
