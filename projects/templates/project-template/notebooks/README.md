# Notebooks

Exploratory, narrative analysis lives here. Conventions:

- **Number notebooks** in execution order: `01-explore.ipynb`,
  `02-clean.ipynb`, `03-model.ipynb`, ...
- Treat notebooks as **throwaway / exploratory**. Once a piece of code is worth
  keeping, move it into [`../src`](../src) and write a test for it in
  [`../tests`](../tests).
- Read data from [`../data/raw`](../data) and write derived data to
  [`../data/processed`](../data).
