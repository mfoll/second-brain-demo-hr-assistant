---
type: Source
source_type: Encyclopedia article
url: https://en.wikipedia.org/wiki/K-anonymity
date_accessed: 2026-06-04
licence: CC BY-SA 4.0
belongs_to: "[[engagement-survey-2026]]"
related_to:
  - "[[minimum-reporting-group]]"
  - "[[dpo-advice-survey-reporting-threshold]]"
_organized: true
---

# k-anonymity

## Summary

Defines k-anonymity as a property of anonymised data: each released record cannot be distinguished from at least k minus one others on the identifying attributes. The term was introduced by Samarati and Sweeney in 1998, building on earlier work by Dalenius. The article also explains the method's limits, for example when everyone in a group shares the same sensitive value.

## Why It Matters

[[kasia-wrobel]]'s memo referred to the idea ([[dpo-advice-survey-reporting-threshold]]), so I read this the day after. It gave me words for what the [[minimum-reporting-group]] does: a department report of 10 makes each answer one of at least 10. It also explains why filters are the danger, since each filter shrinks the group, and why the anti-differencing setting matters.

## Caveats

k-anonymity is about releasing records, while we release averages; the analogy is useful, not exact. It does not tell anyone what k should be, which is a judgement for the Steering Group.

## Source Links

- [k-anonymity](https://en.wikipedia.org/wiki/K-anonymity) (English Wikipedia, CC BY-SA 4.0)
