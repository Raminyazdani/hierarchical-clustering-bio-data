# Project Identity

## Display Title
Hierarchical Clustering for Biological Data

## Repo Slug
hierarchical-clustering-bio-data

## Tagline
Agglomerative clustering and dendrogram visualization for biological datasets

## GitHub Description
A Python implementation of hierarchical clustering algorithms applied to biological data, featuring dendrogram visualization, multiple linkage methods, and analysis of methylation and gene expression datasets.

## Primary Stack
Python, Jupyter Notebook, scikit-learn, NumPy, Pandas

## Topics/Keywords
- hierarchical-clustering
- bioinformatics
- data-analysis
- dendrogram
- scikit-learn
- python
- jupyter-notebook
- gene-expression
- methylation-analysis
- computational-biology
- agglomerative-clustering
- data-visualization

## Problem & Approach

**Problem:** Biological datasets often contain complex relationships that need to be explored through clustering. Understanding the hierarchical structure of biological data (e.g., cell types, gene expression patterns) is essential for discovering patterns and relationships.

**Approach:** This project applies hierarchical clustering techniques to biological data using agglomerative methods. It generates dendrograms to visualize relationships, compares different linkage methods (single, complete, average, Ward), and analyzes both DNA methylation profiles and periodic gene expression patterns.

## Inputs & Outputs

**Inputs:**
- `data/methylation.csv` - DNA methylation profiles across different cell types
- `data/periodic_gene_expression.tsv` - Time-series gene expression data from cell cycle experiments

**Outputs:**
- Dendrograms visualizing hierarchical relationships
- Cluster assignments and quality metrics
- Peak detection results for periodic expression patterns
- Statistical analysis and visualizations of clustering results
