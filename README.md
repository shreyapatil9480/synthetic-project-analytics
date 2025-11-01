# Synthetic Project Analytics

Which programs are at funding risk?

**Stakeholder:** Program Director

## Key Insights

- Three or more missed milestones precede at-risk funding reviews.
- Burn rate above 1.15x plan correlates with stakeholder escalation.
- Programs with 8+ stakeholders recover slower from milestone slips.

## Dataset

Primary file: `data/program_funding.csv`  
Target variable: `at_risk`

## Getting Started

```bash
pip install -r requirements.txt
jupyter notebook notebooks/analysis.ipynb
```

## CLI Usage

```bash
python src/train.py
python src/predict.py --input data/sample_input.csv
```

## Next Steps

Containerize training pipeline for scheduled retraining.

---
*Analytics portfolio project — 2025-10*
