---
type: Source
source_type: Documentation
url: https://learn.microsoft.com/en-us/entra/identity/app-provisioning/plan-cloud-hr-provision
date_accessed: 2026-07-20
belongs_to: "[[talvento-hris-migration]]"
related_to:
  - "[[talvento-it-provisioning-design]]"
  - "[[olumide-fashola]]"
_organized: true
---

# Plan cloud HR application to Microsoft Entra user provisioning

Microsoft Learn documentation page (Microsoft Entra ID), last updated 2025-07-24.

## Summary

A deployment guide for connecting a cloud HR system to Microsoft's identity service so that the HR system drives the identity life cycle: accounts created for joiners, updated for movers and disabled for leavers. It covers planning the integration, choosing the HR system as the source of truth, mapping attributes, handling matching of existing accounts, scheduling and monitoring, and testing before going live.

## Why It Matters

[[olumide-fashola]] sent it to explain the joiner, mover, leaver model behind our own connector. I do not know which identity service Pellmore uses for every site and this page is not about Talvento; what I took from it is the general principle that once HR is the source of truth, HR keying speed and accuracy decide when people get and lose access ([[talvento-it-provisioning-design]], [[how-fast-must-leavers-lose-system-access]]).

## Source Links

- [Plan cloud HR application to Microsoft Entra user provisioning](https://learn.microsoft.com/en-us/entra/identity/app-provisioning/plan-cloud-hr-provision)
