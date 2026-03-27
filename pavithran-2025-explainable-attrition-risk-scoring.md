---
type: Source
source_type: Scientific paper
url: https://doi.org/10.3389/fdata.2025.1699561
doi: 10.3389/fdata.2025.1699561
pmid: 41602602
licence: CC BY
date_accessed: 2026-03-09
belongs_to: "[[people-analytics]]"
related_to:
  - "[[can-we-predict-warehouse-turnover-from-talvento-data]]"
  - "[[jun-takahashi]]"
_organized: true
---

# Explainable attrition risk scoring for managerial retention decisions in human resource analytics

Pavithran MS, Vadivel SM. *Frontiers in Big Data*, 2025.

## Summary

Trains several machine learning models on a public employee attrition dataset, after encoding, scaling and rebalancing the classes, and calibrates the best one (a random forest) so its probabilities can be read as risks. Local and global explanation methods show which features push an individual's predicted risk up. The authors report very high discrimination on that dataset and argue that a calibrated, interpretable risk score helps managers prioritise retention.

## Why It Matters

[[jun-takahashi]] forwarded it when I asked about turnover at the hubs. It shows what attrition modelling looks like, and why I do not want it: it scores named individuals, on a dataset unlike ours, and the performance figures say nothing about a warehouse with seasonal contracts ([[can-we-predict-warehouse-turnover-from-talvento-data]]).

## Caveats

Public benchmark data, not a real workforce. No test of whether managers' decisions improved.

## Source Links

- [DOI 10.3389/fdata.2025.1699561](https://doi.org/10.3389/fdata.2025.1699561), PMID 41602602, open access (CC BY).
