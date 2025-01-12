# TCGAbiolinks-Transcriptomics-SNV-download

This repository contains an R script to download **miRNA transcriptome files** and **SNV (Single Nucleotide Variation)** files specific to the **BRCA2 gene** from patient samples available on TCGA using the `TCGAbiolinks` R package. 

The same script can be adapted to extract other data types, including RNA expression, proteomic profiling, DNA methylation, and mutation data, for specific genes or for the entire genome of patients in TCGA.

---

## Prerequisites

Before running the script, ensure that the following R packages are installed:

- **`SummarizedExperiment`**
- **`tidyverse`**
- **`maftools`**
- **`TCGAbiolinks`**

You can install these packages using the following commands in R:

```R
install.packages("tidyverse")
BiocManager::install(c("SummarizedExperiment", "TCGAbiolinks", "maftools"))
