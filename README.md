# CS6444 Project 1 - R and Graph Analytics

This repository contains the course project notebook for graph analytics on the Stanford Web Graph dataset.

## Overview

- Course: `CS6444 Big Data and Analytics`
- Project type: `R + igraph` notebook
- Main deliverable: [`main.ipynb`](./main.ipynb)
- Dataset format: directed edge list (`from`, `to`)

The analysis focuses on:

- baseline graph properties (size, sparsity, connectivity),
- directed-graph simplification for practical experimentation,
- additional `igraph` function exploration,
- required task outputs (centrality, paths, cliques, ego networks, power centrality, communities),
- constrained visualization (`30-100` vertices).

## Repository Structure

- [`main.ipynb`](./main.ipynb): final notebook/report.
- [`assignment.md`](./assignment.md): assignment statement.
- [`used_in_tutorial.md`](./used_in_tutorial.md): `igraph` functions already used in tutorial material.
- `data/web-Stanford.txt`: local dataset copy used for notebook execution.

## Requirements

- R (with `IRkernel` if running in Jupyter)
- Jupyter Notebook/Lab
- R packages:
  - `igraph`
  - `data.table`

The notebook installs missing R packages automatically from CRAN.

## Running the Notebook

### Option 1: Jupyter UI

Open the notebook and run all cells from top to bottom:

```bash
jupyter lab
```

or

```bash
jupyter notebook
```

### Option 2: CLI execution

```bash
jupyter nbconvert --to notebook --execute --inplace main.ipynb
```

## Data Path Behavior

The notebook checks dataset paths in this order:

1. `./data/web-Stanford.txt` (local repo run)
2. Kaggle input path (for Kaggle execution)

If neither path exists, execution stops with an explicit error.

## Reproducibility Notes

- Random operations are seeded inside the notebook (`cfg$seed`).
- The notebook is designed to run in a clean kernel session without manual edits.
- Outputs can be refreshed by re-running all cells.

## Submission Context

For course submission, the intended notebook is `main.ipynb`.
