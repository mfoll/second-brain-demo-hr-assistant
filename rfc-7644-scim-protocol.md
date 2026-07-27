---
type: Source
source_type: Documentation
url: https://www.rfc-editor.org/rfc/rfc7644
date_accessed: 2026-07-16
belongs_to: "[[talvento-hris-migration]]"
related_to:
  - "[[rfc-7643-scim-core-schema]]"
  - "[[how-fast-must-leavers-lose-system-access]]"
_organized: true
---

# System for Cross-domain Identity Management: Protocol

IETF RFC 7644, Proposed Standard, September 2015. Authors P. Hunt (editor), K. Grizzle, M. Ansari, E. Wahlstroem, C. Mortimore.

## Summary

Specifies the HTTP-based protocol for SCIM: how a client creates, reads, replaces, updates and deletes users and groups on a service provider, how it searches and filters, and how bulk operations, versioning and errors work. It sits on top of the schema in RFC 7643.

## Why It Matters

Read alongside the schema after the [[leaver-access-incident-2026-07-09]]. Disabling a user is an update to one attribute, which happens instantly once sent; the delay we had came from when our connector chose to send it, not from the standard ([[how-fast-must-leavers-lose-system-access]]). I only skimmed the sections on filtering and bulk.

## Source Links

- [RFC 7644](https://www.rfc-editor.org/rfc/rfc7644)
