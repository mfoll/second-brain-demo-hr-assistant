---
type: Concept
belongs_to: "[[maintain-hr-systems]]"
related_to:
  - "[[hr-data-quality]]"
  - "[[data-quality-wikipedia]]"
  - "[[hr-data-quality-scorecard]]"
_organized: true
---

# Data Quality Dimensions

The handful of separate ways a record can be wrong. Naming them helped me sort the 1,940 Staffora issues into things with different fixes and owners ([[hris-data-cleansing]]).

## The ones I use

- **Completeness**: the field is filled. Missing cost centres (604).
- **Accuracy**: the value is true. Wrong line manager (497).
- **Timeliness**: the value is current. Leavers still active (388), changes keyed after the cut-off.
- **Uniqueness**: one person, one record. Duplicates (212).
- **Consistency**: the same fact agrees across systems. Staffora versus Talvento, HR versus payroll absence ([[absence-data-reconciliation]]).
- **Validity**: the value is allowed. Cost centres that do not exist in Finance's hierarchy.

## Why it matters

Each dimension has a different owner and a different check. Completeness and validity can be checked by a report; accuracy needs someone who knows the truth, usually a manager or HRBP. That is why the [[hr-data-quality-scorecard]] reports each dimension separately rather than one score.

Source of the vocabulary: [[data-quality-wikipedia]].
