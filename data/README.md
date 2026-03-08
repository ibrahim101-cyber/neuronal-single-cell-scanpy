# Data Directory

This folder contains the raw single-cell RNA sequencing dataset used in the analysis.

## Dataset

**10k Mouse Brain Cells (v3 chemistry)**

Source: 10x Genomics

The dataset contains gene expression counts for approximately 10,000 individual mouse brain cells.

## File Description

neuron_10k_v3_filtered_feature_bc_matrix.h5

This file contains the filtered gene-barcode matrix provided by 10x Genomics.

It includes:
- gene expression count matrix
- gene identifiers
- cell barcodes

## Processed Data

The processed AnnData object generated during analysis (`.h5ad`) is not included in this repository due to GitHub file size limits.

It can be recreated by running the analysis notebook:

notebooks/neuronal_analysis.ipynb

## Source

The dataset can also be downloaded directly from the 10x Genomics website.
