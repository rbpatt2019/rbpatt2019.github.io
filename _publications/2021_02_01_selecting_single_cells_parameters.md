---
title: "Selecting single cell clustering parameter values using subsampling-based clustering metrics"
collection: publications
permalink: /publication/2021_02_01_selecting_single_cell_parameters
excerpt: 'Here, we illustrate a subsampling-based approach (chooseR) that simultaneously guides parameter selection and characterizes cluster robustness.'
date: 2021-02-01
venue: 'BMC Bioinformatics'
citation: Patterson-Cross RB, Levine AJ, Menon V. Selecting single cell clustering parameter values using subsampling-based robustness metrics. BMC Bioinformatics. 2021 Feb 1;22(1):39. doi: 10.1186/s12859-021-03957-4. PMID: 33522897; PMCID: PMC7852188.
---

## Abstract

**Background**: Generating and analysing single-cell data has become a widespread approach to examine tissue heterogeneity, and numerous algorithms exist for clustering these datasets to identify putative cell types with shared transcriptomic signatures. However, many of these clustering workflows rely on user-tuned parameter values, tailored to each dataset, to identify a set of biologically relevant clusters. Whereas users often develop their own intuition as to the optimal range of parameters for clustering on each data set, the lack of systematic approaches to identify this range can be daunting to new users of any given workflow. In addition, an optimal parameter set does not guarantee that all clusters are equally well-resolved, given the heterogeneity in transcriptomic signatures in most biological systems.

**Results**: Here, we illustrate a subsampling-based approach (chooseR) that simultaneously guides parameter selection and characterizes cluster robustness. Through bootstrapped iterative clustering across a range of parameters, chooseR was used to select parameter values for two distinct clustering workflows (Seurat and scVI). In each case, chooseR identified parameters that produced biologically relevant clusters from both well-characterized (human PBMC) and complex (mouse spinal cord) datasets. Moreover, it provided a simple "robustness score" for each of these clusters, facilitating the assessment of cluster quality.

**Conclusion**: chooseR is a simple, conceptually understandable tool that can be used flexibly across clustering algorithms, workflows, and datasets to guide clustering parameter selection and characterize cluster robustness.

