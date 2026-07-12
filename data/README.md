# Data Availability

This project uses publicly available transcriptomic and clinical data.

## TCGA-KIRC

Data were obtained from The Cancer Genome Atlas Kidney Renal Clear
Cell Carcinoma cohort.

The analysis requires:

- Gene-expression data
- Clinical and survival information
- Somatic mutation data

## External Validation Cohort

An independent validation cohort was obtained from E-MTAB.

Please replace this section with the exact accession number used
in the publication.

## Local File Organization

After downloading the data, users may organize local files as:

```text
data/
├── raw/
│   ├── tcga_kirc_expression.*
│   ├── tcga_kirc_clinical.*
│   ├── tcga_kirc_mutation.*
│   └── emtab_validation.*
└── processed/
