# KrasI Analysis Pipeline

This repository contains Jupyter Notebooks for performing a pipeline of single-cell analysis. The general purpose of these notebooks is to perform batch correction/integration using scVI for uMAP visualization. For biological analysis, the data can be batch corrected or used raw for cNMF, which informs important biological programs. The final h5ad files are then used for lineage-tracing experiments with cassiopeia/pycea. 

## Notebooks Overview

1.  **`run_KRASi_scvi.ipynb`**: A general-purpose implementation of the pipeline on the KrasI dataset.
2. **`lineage_tracing_KRASi.ipynb`**: A general-purpose implementation of the cassiopeia pipeline on the KrasI dataset. 
3.  **`run_scvi_KPTracer_KRASi.ipynb`**: A specialized notebook focused on the integration of the previous KP-Tracer data with the new KrasI dataset.


*For some reason, some of the notebooks are not displaying on GitHub; they do, however, display if you open them with github.dev under the arrow in the upper right corner. 

## Critical Next Steps

1. Removal of CD45+ cells and re-running the analysis on both the general and integrated datasets. 
2. Removal of Tumor Mixes and re-running the analysis on both general and integrated datasets. 
