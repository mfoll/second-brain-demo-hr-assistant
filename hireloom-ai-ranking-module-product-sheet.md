---
type: Source
source_type: Vendor document
date_accessed: 2026-06-19
belongs_to: "[[ai-cv-screening-pilot]]"
related_to:
  - "[[bram-de-wit]]"
  - "[[automated-decision-making]]"
_organized: true
---

# Hireloom AI Ranking Module Product Sheet

The four-page product sheet [[bram-de-wit]] sent after the demo on 2026-06-18 ([[ai-ranking-vendor-demo-2026-06-18]]). Hireloom is the vendor's product; this is their description, not ours.

## Summary

The module gives each application a match score from 0 to 100 against the vacancy and orders the list by score. Recruiters see the score and the three factors that contributed most. It does not reject anyone automatically unless a customer configures a cut-off.

## Key Details

- Inputs: CV text, application answers, job description, and optionally the customer's past hiring outcomes for similar roles ("calibration").
- Calibration needs at least 500 past hires for a role family; we would have about 1,100 for warehouse operatives since 2022.
- Explanations: top three factors per application, such as shift availability or warehouse experience.
- Audit: score history kept per application; a bias report by gender and age band is "available on request".
- Configurable cut-off below which applications are hidden; off by default.

## Why It Matters

The calibration on past hires is the part that worries me and [[kasia-wrobel]]: it learns from decisions our own managers made. The cut-off setting is what would turn ranking into [[automated-decision-making]]. Questions for the DPIA are in [[dpia-screening-questions]].

## Caveats

Marketing material. Claims of accuracy ("finds top candidates 3x faster") come without method or data, and we have not seen the bias report.

## Source Location

- PDF attached to Bram's email of 2026-06-19, saved to People Services SharePoint, `Recruitment/AI ranking/Vendor product sheet.pdf`.
