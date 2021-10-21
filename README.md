# hello-world
My first project in GitHub! Yeahhhh! 
Hello! GitHub world!

## Abstract

(TEMP) A dysfunctional response to inhaled pathogens and toxins drives a substantial portion of the susceptibility to acute and chronic lung disease in the elderly. Using genetic lineage tracing, heterochronic adoptive transfer, parabiosis, and treatment with metformin, we found the lung microenvironment drives age-related transcriptomic changes in alveolar macrophages that include reductions in cell cycle genes and increased expression of inflammatory genes.  These changes are independent of alveolar macrophage ontogeny, circulating factors or circulating monocytes.  Changes in the microenvironment, including changes in extracellular matrix composition, induce a resistance to proliferative signals from CSF2. Severe injury can induce the replacement of long-lived tissue resident alveolar macrophages with monocyte-derived alveolar macrophages, but both respond similarly to a subsequent injury.  These findings place the lung microenvironment upstream of the dysfunctional immune responses to inhaled environmental challenge in aging.  

Single cell RNA-seq (scRNA-seq) captures the transcriptomic phenotype of multiple cell populations within a tissue simultaneously. We utilized widely used R package “Seurat” and Canonical Correlation Analysis procedure to aggregate and analyze together data from 6 published dataset. Our integration included a total number of 38 samples, covering age from 17 to 88. The merged dataset provided sufficient statistical power and homogeneity to allow discovery of common aging biomarkers across distinct cell populations. We concluded that there were no heterogeneity or emerging new cell groups in avalor macrophages, which is consistent with our observation in mouse. Through pseudo bulk, we identified 673 differentially expressed genes between young and old samples and these genes were significantly overlapped with our bulk RNAseq analysis in mouse alveolar macrophages.

## Prerequisites

Install all required R packages in the [R_requirement.txt](resources/R_requirement.txt) files using either bioconductor or CRAN

```
if (!requireNamespace("BiocManager", quietly = TRUE))
    install.packages("BiocManager")
BiocManager::install("package")
```
or

```
install.packages("package")
```
