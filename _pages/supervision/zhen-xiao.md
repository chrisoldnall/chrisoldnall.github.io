---
layout: page
title: "Zhen Xiao"
permalink: /supervision/zhen-xiao/
---

## Zhen Xiao
### BSc Biomedical Sciences (Data Science)

### Project title
Exploring the application of protein language models to cancer survival analysis.

### Focus area
Low-grade glioma (LGG) and glioblastoma (GBM).

### Brief summary
This project uses protein language models to embed mutation data and assess their predictive power for cancer patient survival, comparing performance with traditional binary mutation indicators.

### Description
Recent advances in protein language models (PLMs) offer a powerful way to represent protein sequences and mutations in a biologically meaningful, high-dimensional space. This project explores how these embeddings can be used to stratify patients within different cancer types based on survival, tumour sub-types, and patient characteristics.

The project compares embedding-based stratification to models using binary mutation status for key cancer genes and evaluates whether PLMs better capture functional variation relevant to prognosis. It also visualises embeddings, investigates links with protein structural features, and assesses combined models for improved predictive accuracy.

Students begin by selecting well-characterised cancer-associated genes and retrieving mutation and clinical survival data from The Cancer Genome Atlas (TCGA). They then extract protein embeddings for mutated sequences using a pre-trained PLM (ESM2) and align these with patient-level outcome data.

Using dimensionality reduction methods (for example PCA and UMAP), embeddings are visualised to identify subgroup structure. Survival models (for example Cox proportional hazards) are then used to compare predictive performance between binary mutation indicators and embedding-based features. Finally, combined feature representations are tested and embedding dimensions are interpreted against known structural or functional domains and mutational functionality.

### Techniques
- Protein language models (ESM2)
- Cox proportional hazards models and Kaplan-Meier survival analysis
- Mutation annotation and protein feature mapping
- Python (pandas, lifelines, Biopython, matplotlib)

### Reading
- Lin, Z. et al. (2023). Evolutionary-scale prediction of atomic-level protein structure with a language model. *Science*, 379, 1123-1130. DOI: 10.1126/science.ade2574
- Vaswani, A. et al. Attention Is All You Need.
- The Cancer Genome Atlas Research Network (2008). Comprehensive genomic characterization defines human glioblastoma genes and core pathways. *Nature*, 455, 1061-1068.
