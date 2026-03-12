# 16S-microbiome-analysis-R
Reproducible R workflow for 16S rRNA microbial community analysis including QC, diversity analysis, ordination, and taxonomic composition.

# 16S Microbiome Analysis in R

This repository contains a reproducible workflow for analyzing 16S rRNA amplicon sequencing data in R.

The analysis includes quality control, diversity analysis, ordination, and taxonomic composition visualization.

## Overview

This workflow demonstrates common microbial community analysis steps using R and tidyverse-based data processing.

Key analyses include:

- sequencing depth assessment
- rarefaction analysis
- relative abundance calculation
- alpha diversity (Shannon index)
- beta diversity (NMDS ordination)
- taxonomic composition plot

## Tools used

- R
- tidyverse
- vegan
- SRS normalization
- ggplot2

## Repository structure

```
data/        input data tables
scripts/     RMarkdown workflow
figures/     output figures
```

## Example outputs

The workflow generates figures such as:

- sequencing depth plot
- rarefaction curves
- NMDS ordination
- taxonomic composition barplots

## Author

Laura Seidel  
PhD Microbiology / Genomics
