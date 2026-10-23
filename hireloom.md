---
type: Source
source_type: Internal system
date_accessed: 2026-10-19
belongs_to: "[[coordinate-recruitment]]"
related_to:
  - "[[candidate-experience]]"
  - "[[bram-de-wit]]"
  - "[[candidate-data-retention-schedule]]"
_organized: true
---

# Hireloom

Pellmore's applicant tracking system since 2022: vacancies, applications, interview booking, candidate emails and offer letters for every division. The talent acquisition team owns it; [[marek-zielinski]] holds the contract, Callum and I are the day-to-day admins. Vendor contact: [[bram-de-wit]].

## Summary

Hireloom holds every application from vacancy to offer. After an offer is accepted, the starter's details move to the HR system (Staffora until 2026-06-28, Talvento from 2026-06-29) through the new-starter export; Hireloom is not the employee record. What matters for my work: self-scheduling, the template library, offer letters, the retention settings, and the AI ranking module we have not switched on.

## Key Details

**Self-scheduling.** Hiring managers publish weekly interview slots; candidates get a link and book. Default for all first interviews since 2025-05-12 ([[self-scheduling-go-live-2025-05-12]]). Invites are sent as standard calendar files ([[rfc-5545-icalendar]]). If a link is not used within 48 hours, Hireloom flags the candidate for a phone call. Group assessment sessions of up to 12 for peak are set up as one slot with 12 places. How we use it: [[schedule-interviews-in-hireloom]].

**Templates.** 46 email templates after the 2025 rewrite ([[candidate-email-templates-2025]]), down from 71. Each has an owner and a review date in the template description field.

**Offer letters.** Five offer letter templates (permanent salaried, permanent hourly, fixed-term, seasonal, graduate) with merge fields for role, site, start date and pay rate ([[offer-letter-template-set]]). Pay values come from the approved offer and are never typed freehand. Marek approves every offer; seasonal peak offers have standing approval.

**Retention.** Unsuccessful candidates' data is deleted six months after the vacancy closes; the graduate talent pool is kept 12 months with consent ([[candidate-data-retention-schedule]]). Deletion runs as a scheduled purge I check twice a year.

**AI ranking module.** Licensed, never switched on. It would score and order applications against the job description and past hiring outcomes. Not to be used until a full DPIA is approved ([[ai-cv-screening-pilot]], [[hireloom-ai-ranking-module-product-sheet]]).

**Access.** About 140 hiring managers have accounts. Managers see only their own vacancies; HR Business Partners see their division; People Services sees all.

**Reporting.** Time to schedule, time to offer, funnel counts by vacancy, and the post-interview candidate survey ([[candidate-experience-survey-2025]]).

## Quirks

- A vacancy reopened after closing keeps its old close date for the purge, so candidates can be deleted early. Fix: clone the vacancy instead of reopening.
- The new-starter export to Talvento does not carry the induction session; we book that separately.
- Candidate emails sent from a manager's own mailbox are not logged. Managers are asked to use templates only.

## Why It Matters

Hireloom is where most of my recruitment week happens and where candidate data lives. Keeping it clean is part of [[coordinate-recruitment]]; keeping names and details in it, and out of my notes, is part of [[record-hr-cases-without-personal-data]].

## Caveats

Described from my admin use and the admin guide; I have not seen the vendor's technical documentation. Feature names may change at the 2027 renewal.

## Source Location

- Hireloom admin console, People Services workspace.
- Admin guide on the People Services SharePoint, `Recruitment/Hireloom/Admin guide v4`.
