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
.
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
cd code
jupyter notebook
```

Open either `clustering_analysis.ipynb` or `periodic_expression.ipynb` in the Jupyter interface and run the cells sequentially.

## Data / Inputs

- `data/methylation.csv` - Methylation data for clustering analysis
- `data/periodic_gene_expression.tsv` - Time-series gene expression data

## Outputs

- `dendogram.jpg` - Hierarchical clustering visualization
- Cluster assignments and quality metrics

## Reproducibility Notes

- All paths are relative to the project directory
- Run notebooks from the `code/` directory for correct relative paths
- Python 3.7+ recommended

## Notes

- Two notebooks covering clustering techniques
- Dendrogram output included as example
