# KrasI Analysis Pipeline

This repository contains Jupyter Notebooks for performing a pipeline of single-cell analysis. The general purpose of these notebooks is to perform batch correction/integration using scVI for uMAP visualization. For biological analysis, the data can be batch corrected or used raw for cNMF, which informs important biological programs. The final h5ad files are then used for lineage tracing experiments using cassiopeia. 

## Notebooks Overview

1.  **`run_scvi.ipynb`**: A general-purpose implementation of the pipeline on the KrasI dataset. 
2.  **`run_scvi_KPTracer_KRASi.ipynb`**: A specialized notebook focused on the integration of the previous KP-Tracer data with the new KrasI dataset. 

## Missing Critical Steps

1. Removal of CD45+ cells and re-running the analysis on both the general and integrated datasets. 
2. Removal of Tumor Mixes and re-running the analysis on both general and integrated datasets.
3. 
