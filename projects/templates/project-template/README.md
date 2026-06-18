# <Project name>

> One-line description of what this project does and which **study topic** it
> applies. Example: *"Baseline churn model — applying scikit-learn classification
> from the Data Science track."*

- **Track:** <Data Analytics | Data Engineering | Data Science | ML Engineering | AI Engineering>
- **Concept being studied:** <e.g. logistic regression, Airflow DAGs, RAG>
- **Reference(s) used:** <link(s) from ../../references>
- **Status:** In progress | Done | On hold

## Goal

What question are you answering or what are you building? Keep it to 1–3
sentences.

## Definition of done

A short checklist so you know when to stop. Keep the project small!

- [ ] ...
- [ ] ...
- [ ] Wrote a short summary of what I learned in [reports/](reports/)

## Structure

```
.
├── data/
│   ├── raw/         # original, immutable input data (do NOT edit by hand)
│   └── processed/   # cleaned / transformed data produced by code
├── notebooks/       # exploratory, throwaway analysis (numbered: 01-..., 02-...)
├── src/             # reusable, importable code (the "real" logic)
├── tests/           # tests for code in src/
├── reports/         # outputs to share: figures, dashboards, write-ups
├── requirements.txt # project dependencies
└── README.md        # this file
```

## How to run

```bash
# Create and activate a virtual environment
python -m venv .venv
source .venv/bin/activate      # Windows: .venv\Scripts\activate

# Install dependencies
pip install -r requirements.txt

# ... then run notebooks/ or scripts in src/
```

## What I learned

Fill this in as you go — it is the most valuable part for your future self.

- ...
