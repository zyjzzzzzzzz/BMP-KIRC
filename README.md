# BMP-related Prognostic Modeling in KIRC

## Overview

This repository contains the computational analysis workflow for the development and external validation of a bone morphogenetic protein (BMP)-related mRNA prognostic signature in kidney renal clear cell carcinoma (KIRC).

The study integrates transcriptomic analysis, survival modeling, external validation, tumor microenvironment analysis, tumor mutation burden analysis, drug-sensitivity analysis, and RT-qPCR validation.

## Research Question

Can BMP-related transcriptional patterns provide prognostic information and reflect differences in the tumor microenvironment of kidney renal clear cell carcinoma?

## Analytical Workflow

1. TCGA-KIRC data acquisition and preprocessing
2. Differential expression analysis
3. Correlation analysis
4. LASSO feature selection
5. Univariate and multivariate Cox regression
6. Prognostic model construction
7. External validation using an E-MTAB cohort
8. Tumor microenvironment analysis
9. Tumor mutation burden analysis
10. Drug-sensitivity analysis
11. RT-qPCR validation
12. Figure generation

## Repository Structure

```text
code/       R scripts for data analysis
data/       Data-access instructions
results/    Selected figures and tables
docs/       Workflow documentation
