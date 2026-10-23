---
type: Source
source_type: Documentation
url: https://github.com/adlnet/xAPI-Spec
date_accessed: 2026-10-12
belongs_to: "[[mandatory-training-compliance]]"
related_to:
  - "[[should-learnmoor-be-replaced-by-talvento-learning]]"
  - "[[sharable-content-object-reference-model]]"
_organized: true
---

# xAPI Specification

The Experience API specification repository maintained by ADL on GitHub, version 1.0.3, which notes that the current version is xAPI 2.0 published through IEEE.

## Summary

xAPI is an interoperability specification for describing learner activity and experiences between technologies. The specification has three parts: about the API, the data model, and data processing, validation and security. Its central object is the Statement, built from an actor, a verb and an object, with optional result and context. Statements are stored in a Learning Record Store (LRS) and exchanged over a REST interface with trusted clients.

## Why It Matters

[[yetunde-balogun]] mentioned xAPI when we discussed whether Talvento's learning module could replace [[learnmoor]] ([[should-learnmoor-be-replaced-by-talvento-learning]]). Our packages use SCORM 1.2, which only reports completion from inside a browser course. xAPI could in principle record a practical session or a kiosk activity as well, which matters for Manual Handling. Neither Learnmoor nor Talvento has been checked for xAPI support yet; that is a question for the 2027 review, not a fact.

## Caveats

A specification, not a product guide. The repository is the older 1.0.3 version.

## Source Links

- [adlnet/xAPI-Spec on GitHub](https://github.com/adlnet/xAPI-Spec)
