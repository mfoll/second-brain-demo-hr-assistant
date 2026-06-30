---
type: Note
date: 2026-06-23
belongs_to: "[[ai-in-recruitment]]"
related_to:
  - "[[hireloom-ai-ranking-module-product-sheet]]"
  - "[[ai-cv-screening-pilot]]"
_organized: true
---

# How Hireloom AI Ranking Would Work

My working notes after the demo, to make sure I understood the module before the DPIA screening. Not the vendor's words; my reading of the demo and [[hireloom-ai-ranking-module-product-sheet]].

## Flow as I understand it

1. Candidate applies; Hireloom reads the CV and the form answers.
2. The model compares them with the job description and gives a score from 0 to 100.
3. With calibration on, it also compares them with past applicants who were hired for similar roles and adjusts the score.
4. Recruiters see the list sorted by score, with three top factors per application.
5. Optional cut-off hides applications below a score.

## Where it could go wrong

- Step 3 learns from our managers' past choices. If past hires skewed towards people with warehouse experience, or towards some groups, the scores will too ([[algorithmic-bias-wikipedia]]).
- Step 4 changes behaviour even without a cut-off: people read from the top ([[automated-decision-making]]).
- Candidates cannot see or contest a score; nothing in our emails would say ranking was used.
- CVs from phones are often a few lines; a short CV might score low for reasons unrelated to the job.

## Questions I passed to Kasia

Training data, whether our data trains their model, how the factors are produced, bias reports, opt-out for candidates. All went into [[dpia-screening-questions]].
