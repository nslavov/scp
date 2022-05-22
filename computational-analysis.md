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


## Pipelines for processing and analyzing single-cell protein data
The [SCoPE2 pipeline](https://github.com/SlavovLab/SCoPE2/tree/master/code) was developed to process the [SCoPE2](scope2) data from [Spech et al., 2019](Specht_et_al_2019). With small modifications, the pipeline has been used with [plexDIA](plexDIA) and [pSCoPE](pSCoPE) data as well.

&nbsp;

## Increasing confident peptide identifications
[DART-ID](https://dart-id.slavovlab.net/) implements principled Bayesian frameworks for global retention time (RT) alignment and for incorporating RT estimates towards improved confidence estimates of peptide-spectrum-matches.

&nbsp;  

## Visualizing LC-MS/MS data
[DO-MS](https://do-ms.slavovlab.net) is an an interactive [open source](https://github.com/SlavovLab/DO-MS) platform for their interactive visualization and analysis of LC-MS/MS data: Data-driven Optimization of MS (DO-MS)

---




&nbsp;



## Pipelines by colleagues
 * Chris Vanderaa and Laurent Gatto have developed a Bioconductor package [scp](http://bioconductor.org/packages/release/bioc/html/scp.html) with for manipulating, processing, and analyzing mass spectrometry-based single-cell proteomics data. The package implemented workflows from the [SCoPE2 pipeline](https://doi.org/10.5281/zenodo.4339954) using the 'QFeatures' package and added new functions.
