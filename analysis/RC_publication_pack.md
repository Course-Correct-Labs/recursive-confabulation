# RC Publication Pack

Replication and documentation bundle for *Recursive Confabulation: Measuring Model Accountability through Dual-Coder Agreement* — Bentley DeVilling, Course Correct Labs.

## 1. Study overview
- 3 models × 4 intervention arms (119 conversations)
- Reasoning prompts amplified confabulation; grounding reduced it (model specific)
- Semantic compression observed — detail shrinks while confidence remains high

## 2. Repo contents
- **data/** – IRR tables and effects
- **figures/** – heatmaps and plots
- **analysis/** – IRR and integrity notes
- **Root** – README, LICENSE, CITATION.cff

## 3. IRR summary
- Dimensions: harm, elaboration, blame
- κ ≈ 0.83–1.0 after reconciliation

## 4. Reproduction checklist
- Recompute Fisher tests → `data/significance_matrix.csv`
- Validate effect sizes → `data/intervention_effects.csv`
- Recreate plots → `figures/`
- Cross-check entity taxonomy → `data/entities_clusters.csv`

## 5. Ethics and disclosure
- All outputs are model generated. No human subjects data.
- Study conducted by Bentley DeVilling through Course Correct Labs.
- Language models assisted under human supervision only.

## 6. Contact
**Bentley DeVilling**
Bentley@CourseCorrectLabs.com

## 7. Changelog
**v1.0 (2025-10-25)** — First public release — Course Correct Labs dataset and publication repository.
