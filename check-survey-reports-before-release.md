---
type: Procedure
belongs_to: "[[engagement-survey-2026]]"
related_to:
  - "[[minimum-reporting-group]]"
  - "[[jun-takahashi]]"
  - "[[data-minimisation]]"
_organized: true
---

# Check Survey Reports Before Release

The check [[jun-takahashi]] and I run on every engagement survey or pulse check output before it leaves People Services: dashboards, slides, spreadsheets and emails with figures.

## When to use

Any time survey results go to someone outside the two of us, including HRBPs, the People Committee and managers. Also for my diploma tables, which follow the same rule.

## Inputs

- The output to be released.
- The respondent counts for every group shown.
- The survey's settings in [[pulsewright]].

## Steps

1. Confirm the survey's threshold setting in Pulsewright is 10 and anti-differencing is on. New surveys start at the platform default of 5.
2. For every group in the output, check the respondent count is at least 10 ([[minimum-reporting-group]]). This includes every filter combination.
3. Check for differencing: if two groups in the same pack differ by fewer than 10 respondents (for example a site and the site minus one depot), remove the smaller cut.
4. Free text: only for groups of 10 or more, only after Jun has screened for names, sites smaller than a hub, and specific incidents. Comments never go into slides verbatim; use themes.
5. Remove any column that is not needed for the purpose ([[data-minimisation]]): no respondent key, no service band unless asked for.
6. Second pair of eyes: whoever did not build the output checks steps 2 to 4.
7. Record in the release log: what, to whom, date, who checked.

## Outputs

A released output and one log line.

## Verification

In June this check removed two filter combinations below 10 in an HRBP pack. If a check finds a problem after release, tell Jun and [[kasia-wrobel]] the same day and ask the recipient to delete the file.
