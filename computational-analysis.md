---
layout: default
title: Computational analysis
nav_order: 6
permalink: computational-analysis
description: "Computational analysis pipelines, tools and algorithms for single-cell proteomics by mass-spectrometry"
has_children: true
---
{% include social-media-links.html %}

# Analysis of single-cell proteomics data
{:.no_toc}

{: .fs-5 .fw-300}
This section organizes computational pipelines for the analysis of single-cell proteomic and [proteogenomic](https://arxiv.org/abs/2308.07465) datasets. These pipelines can be used with the [data](data) and [methods](methods) of this portal.

* Will be replaced with the ToC, excluding the section header
{:toc}

&nbsp;

[*Perspective* on data analysis and interpretation](https://doi.org/10.48550/arXiv.2308.07465){: .btn .fs-5 .mb-4 .mb-md-0 .mr-2 }

------------

&nbsp;

<!-- Pipelines from [Slavov Laboratory](https://slavovlab.net)
-->

## Pipelines for data processing
### Scripts and Pipelines for Proteomics (SPP)
[SPP](https://github.com/SlavovLab/SPP) provides computational utilities for single-cell proteomics data. The code originated from the [SCoPE2 pipeline](https://doi.org/10.5281/zenodo.4339954), which was abstracted and generalized so that it can be used for analyzing data from other projects, including data acquired by [plexDIA](plexDIA), [pSCoPE](pSCoPE), and other [mass-spec methods](methods) for single-cell proteomics.

### QuantQC pipeline
The [QuantQC package](QuantQC) generates HTML reports for evaluating [nPOP](nPOP) sample preparation, stability of data acquisition, and quantification performance that can be easily shared with colleagues. QuantQC also facilitates exploratory data analysis such as visualizing agreement between peptides mapping to the same protein across clusters.   


### scp package
The [scp](http://bioconductor.org/packages/release/bioc/html/scp.html) Bioconductor package was developed by Chris Vanderaa and Laurent Gatto for manipulating, processing, and analyzing mass spectrometry-based single-cell proteomics data. The package implemented workflows from the [SCoPE2 pipeline](https://doi.org/10.5281/zenodo.4339954) using the 'QFeatures' package and added new functions.

### SCeptre
SCeptre is a Python pipeline developed by Erwin Schoof and colleagues. It is used for processing single-cell proteomics data generated using an isobaric carrier experimental design.

### SCoPE2 pipeline
The [SCoPE2 pipeline](https://doi.org/10.5281/zenodo.4339954) was developed to process the [SCoPE2](scope2) data from [Specht et al., 2019](Specht_et_al_2019) and it has been generalized in the SPP collection of scripts and pipelines.

&nbsp;

## Enhancing peptide identifications
### DART-ID
Data-driven Alignment of Retention Times for IDentification ([DART-ID](https://dart-id.slavovlab.net/)) implements principled Bayesian frameworks for global retention time (RT) alignment and for incorporating RT estimates towards improved confidence estimates of peptide-spectrum-matches.
### Rescoring pipelines
Peptides identified from search engines (both DDA and DIA acquisitions) can be rescored to increase the upgrade (increase conference in) correct identifications and downgrade incorrect ones. Two pipelines for such rescoring are  MSBooster and Oktoberfest.

&nbsp;  

## Optimizing LC-MS/MS & Visualizing data
### DO-MS: Data-driven Optimization of MS
[DO-MS](https://do-ms.slavovlab.net) is an [open source](https://github.com/SlavovLab/DO-MS) platform for optimizing LC-MS/MS workflows, identifying bottlenecks and performing QC. It supports both interactive and archival data visualization, including the generation of sharable reports. DO-MS stands for *Data-driven Optimization of MS (DO-MS)*

---

## Community guidelines and recommendations

Analyzing proteins from single cells by tandem mass spectrometry (MS) has become technically feasible. While such analysis has the potential to accurately quantify thousands of proteins across thousands of single cells, the accuracy and reproducibility of such results may be undermined by numerous factors affecting experimental design, sample preparation, data acquisition, and data analysis. Establishing community guidelines and standardized metrics will enhance rigor, data quality, and alignment between laboratories. The community has proposed best practices, quality controls, and data reporting guidelines to assist in the broad adoption of reliable quantitative workflows for single-cell proteomics.

[Best practices >>](https://single-cell.net/guidelines)

---

&nbsp;

&nbsp;
