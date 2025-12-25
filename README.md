# Hierarchical Clustering Analysis

**Biological data clustering with dendrogram visualization**

**Stack:** Python, Jupyter Notebook, scikit-learn

## Overview

This project implements hierarchical clustering techniques for biological data analysis, with emphasis on dendrogram generation and interpretation. It demonstrates agglomerative clustering methods and visualization strategies for understanding data structure.

## Problem & Approach

**Problem:** Apply hierarchical clustering to biological datasets and visualize relationships through dendrograms.

**Approach:**
- Implement agglomerative clustering algorithms
- Generate and interpret dendrograms
- Compare linkage methods (single, complete, average, Ward)
- Evaluate clustering quality with appropriate metrics

## Tech Stack

- Python 3.x
- Jupyter Notebook
- NumPy, scikit-learn
- Matplotlib/Seaborn for visualization

## Folder Structure

```
assignment_2_pobd/
├── code/
│   ├── clustering_analysis.ipynb    # Hierarchical clustering implementation
│   ├── periodic_expression.ipynb    # Periodic gene expression analysis
│   └── dendogram.jpg                # Generated dendrogram
├── data/
│   ├── methylation.csv              # Methylation data
│   └── periodic_gene_expression.tsv # Gene expression time series
├── requirements.txt
└── README.md
```

## Setup / Installation

```bash
pip install -r requirements.txt
```

## How to Run

```bash
cd assignment_2_pobd/code
jupyter notebook
```

## Data / Inputs

- `data/methylation.csv` - Methylation data for clustering analysis
- `data/periodic_gene_expression.tsv` - Time-series gene expression data

## Outputs

- `dendogram.jpg` - Hierarchical clustering visualization
- Cluster assignments and quality metrics

## Reproducibility Notes

- All paths relative to project directory
- Originally created in an academic setting

## Notes

- Two notebooks covering clustering techniques
- Dendrogram output included as example
