---
type: Source
source_type: Internal specification
date_accessed: 2026-07-14
belongs_to: "[[talvento-hris-migration]]"
related_to:
  - "[[olumide-fashola]]"
  - "[[how-fast-must-leavers-lose-system-access]]"
  - "[[rfc-7643-scim-core-schema]]"
_organized: true
---

# Talvento IT Provisioning Design

Olumide's design for creating, updating and disabling user accounts from Talvento, version 1.4 of 2026-07-14.

## Summary

- Talvento is the source for joiners, movers and leavers. A connector reads changes and updates the group's identity directory.
- Joiners: account created five working days before the start date (on the start date for hub operatives, who get a badge account only).
- Movers: department, manager and job title updated overnight; group memberships follow the department.
- Leavers: account disabled at the end of the termination date. Version 1.4 adds: a termination dated today or in the past disables within an hour.
- Attributes follow the SCIM core user schema where possible ([[rfc-7643-scim-core-schema]]).

## Why It Matters

Version 1.4 is the fix from the [[leaver-access-incident-2026-07-09]]. It makes HR's keying speed a security matter, not just a payroll one ([[how-fast-must-leavers-lose-system-access]]).

## Source Location

IT architecture wiki, "HR-driven provisioning (Talvento)".
