---
type: Source
source_type: Documentation
url: https://www.rfc-editor.org/rfc/rfc7643
date_accessed: 2026-07-16
belongs_to: "[[talvento-hris-migration]]"
related_to:
  - "[[talvento-it-provisioning-design]]"
  - "[[scim-wikipedia]]"
_organized: true
---

# System for Cross-domain Identity Management: Core Schema

IETF RFC 7643, Proposed Standard, September 2015. Authors P. Hunt (editor), K. Grizzle, E. Wahlstroem, C. Mortimore.

## Summary

Defines the common schema for SCIM: the resource types (User, Group, enterprise user extension) and their attributes, such as user name, name parts, emails, active flag, manager, department and cost centre, plus how schemas are described and extended. The aim is to make user management across cloud services simpler by giving everyone the same data model.

## Why It Matters

[[olumide-fashola]] pointed me here when I asked which Talvento fields IT actually needs. The `active` attribute and the enterprise extension's manager, department and cost centre are the fields that matter for joiners, movers and leavers ([[talvento-it-provisioning-design]]). It made me understand why a wrong line manager or cost centre in Talvento is now an access problem, not just a reporting one ([[hr-data-quality]]).

## Caveats

A standard, not a description of our connector; Olumide's design maps to it "where possible".

## Source Links

- [RFC 7643](https://www.rfc-editor.org/rfc/rfc7643)
