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

&nbsp;

------------

&nbsp;


## Pipelines for data processing
### Pipelines from [Slavov Laboratory](https://slavovlab.net)
* The [Scripts and Pipelines for Proteomics (SPP)](https://github.com/SlavovLab/SPP) provides computational utilities for single-cell proteomics data. The code originated from the [SCoPE2 pipeline](https://doi.org/10.5281/zenodo.4339954), which was abstracted and generalized so that it can be used for analyzing data from other projects, including data acquired by [plexDIA](plexDIA), [pSCoPE](pSCoPE), and other [mass-spec methods](methods) for single-cell proteomics.
* The [SCoPE2 pipeline](https://doi.org/10.5281/zenodo.4339954) was developed to process the [SCoPE2](scope2) data from [Specht et al., 2019](Specht_et_al_2019) and it has been generalized in the SPP collection of scripts and pipelines.

### Pipelines by colleagues
 * Chris Vanderaa and Laurent Gatto have developed a Bioconductor package [scp](http://bioconductor.org/packages/release/bioc/html/scp.html) for manipulating, processing, and analyzing mass spectrometry-based single-cell proteomics data. The package implemented workflows from the [SCoPE2 pipeline](https://doi.org/10.5281/zenodo.4339954) using the 'QFeatures' package and added new functions.
 * Erwin Schoof and colleagues developed SCeptre, a Python pipeline used for processing single-cell proteomics data generated using an isobaric carrier experimental design.

&nbsp;

## Increasing confident peptide identifications
[DART-ID](https://dart-id.slavovlab.net/) implements principled Bayesian frameworks for global retention time (RT) alignment and for incorporating RT estimates towards improved confidence estimates of peptide-spectrum-matches.

&nbsp;  

## Visualizing LC-MS/MS data
[DO-MS](https://do-ms.slavovlab.net) is an an interactive [open source](https://github.com/SlavovLab/DO-MS) platform for their interactive visualization and analysis of LC-MS/MS data: Data-driven Optimization of MS (DO-MS)

---

## Community guidelines and recommendations

Analyzing proteins from single cells by tandem mass spectrometry (MS) has become technically feasible. While such analysis has the potential to accurately quantify thousands of proteins across thousands of single cells, the accuracy and reproducibility of such results may be undermined by numerous factors affecting experimental design, sample preparation, data acquisition, and data analysis. Establishing community guidelines and standardized metrics will enhance rigor, data quality, and alignment between laboratories. The community has proposed best practices, quality controls, and data reporting guidelines to assist in the broad adoption of reliable quantitative workflows for single-cell proteomics.

[Best practices >>](https://single-cell.net/guidelines)

---

&nbsp;

&nbsp;
