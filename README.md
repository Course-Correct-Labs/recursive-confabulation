# Recursive Confabulation

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Course-Correct-Labs/recursive-confabulation/blob/main/notebooks/RC_reproduction.ipynb)

Dataset and replication materials for the study *Recursive Confabulation: Measuring Model Accountability through Dual-Coder Agreement* (κ = 0.83–1.0).
Includes harm, elaboration, and blame IRR data with full reproducibility.
Conducted by **Bentley DeVilling** through **Course Correct Labs**, an independent AI research group based in California.

## Repository structure
```
Recursive-Confabulation/
├─ data/               # all .csv tables used in analysis
├─ figures/            # visualizations (.png / .pdf)
├─ analysis/           # IRR reports, effects notes, publication pack
│  └─ RC_publication_pack.md
├─ notebooks/          # Colab reproduction notebook
│  └─ RC_reproduction.ipynb
├─ requirements.txt    # pinned dependencies
├─ README.md
├─ LICENSE
└─ CITATION.cff
```

## Contents
- IRR tables: harm, elaboration, blame
- Entity taxonomy and cluster counts
- Significance matrix and intervention effects
- Figures for confab vs correction and persistence heatmaps

## Summary of results
- Near-universal spontaneous confabulation (~97 %)
- Reasoning-style prompts increased persistence (25–31 pp)
- Grounding reduced confabulation for GPT-4o mini only
- Cross-feedback propagated falsehoods between models
- Responses shortened while confidence remained high (semantic compression)

## Reproducibility

**One click:**
- Open the Colab notebook via the badge above and run all cells.

**Local setup:**
```bash
python -m venv .venv && source .venv/bin/activate
pip install -r requirements.txt
python - <<'PY'
import pandas as pd
print(pd.read_csv('data/harm_irr.csv').shape)
PY
```

All .csv files are canonical. Example:
```python
import pandas as pd
df = pd.read_csv('data/harm_irr.csv')
```

## Citation
DeVilling, B. (2025). Recursive Confabulation: dataset and replication materials. Course Correct Labs. https://github.com/Course-Correct-Labs/recursive-confabulation

## License
**Code:** MIT License

**Data and text:** CC BY 4.0

See LICENSE.

## Maintained by
**Bentley DeVilling** — Course Correct Labs
Boulder Creek, CA
coursecorrectlabs.com
Bentley@CourseCorrectLabs.com
