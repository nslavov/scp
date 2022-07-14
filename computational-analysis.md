---
layout: default
title: Computational analysis
nav_order: 4
permalink: computational-analysis
description: "Computational analysis pipelines for single-cell proteomics by mass-spectrometry"
has_children: false
---
{% include social-media-links.html %}

# Analysis of single-cell proteomics data

&nbsp;

This section organizes computational pipelines for the analysis of single-cell proteomics data. These pipelines can be used with data generated from various [methods](methods) for single-cell proteomics.

------------

&nbsp;


## SCoPE2 pipeline
The [pipeline](https://doi.org/10.5281/zenodo.4339954) was developed to process the [SCoPE2](scope2) data from [Spech et al., 2019](Specht_et_al_2019), but with small modifications it has been used with [plexDIA](plexDIA) and [pSCoPE](pSCoPE) data as well.
* [Pipelines by colleagues](#pipelines-by-colleagues).

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



## Pipelines by colleagues
 * Chris Vanderaa and Laurent Gatto have developed a Bioconductor package [scp](http://bioconductor.org/packages/release/bioc/html/scp.html) for manipulating, processing, and analyzing mass spectrometry-based single-cell proteomics data. The package implemented workflows from the [SCoPE2 pipeline](https://doi.org/10.5281/zenodo.4339954) using the 'QFeatures' package and added new functions.
 * Erwin Schoof and colleagues developed SCeptre, a Python pipeline used for processing single-cell proteomics data generated using an isobaric carrier experimental design.

&nbsp;

&nbsp;


&nbsp;
