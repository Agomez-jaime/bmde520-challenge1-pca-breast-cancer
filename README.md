# PCA & Feature Redundancy — Breast Cancer Dataset

BMDE 520, McGill University — Challenge 1.

A short exploration of dimensionality reduction and feature redundancy on
scikit-learn's Breast Cancer Wisconsin dataset (30 numeric features per
sample, benign/malignant label).

## What's here

- **PCA to 2 components** on the full 30-feature dataset, plotted to visualize
  how separable the two classes are in a low-dimensional projection.
- **Pairwise Pearson correlation** across all 30 features, visualized as a
  histogram of off-diagonal correlation coefficients, to characterize how much
  redundancy exists in the raw feature set before any reduction.

## Files

- `challenge1_andrea_gomez.ipynb` — PCA projection and correlation analysis.

## Running it

The dataset loads directly from scikit-learn
(`sklearn.datasets.load_breast_cancer`), so the notebook runs standalone —
just run all cells.

## Author

Andrea Paola Gómez Jaime
