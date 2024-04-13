---
layout: default
title: Protocols
nav_order: 7
description: "Protocols for single-cell proteomics by liquid chromatography tandem mass spectrometry LC-MS/MS. Protocols are applicable to label-free and multiplexed methods, including SCoPE2, plexDIA, pSCoPE, SCoPE-DIA and other methods."
permalink: protocols
has_children: false
---

{% include social-media-links.html %}

# Protocols for singe-cell proteomics
{:.no_toc}

{: .fs-5 .fw-300}
This section organizes protocols for preparing LC-MS/MS systems for single-cell proteomic analysis, preparing single-cell samples, optimizing and performing the analysis.

&nbsp;


* Will be replaced with the ToC, excluding the section header
{:toc}

------------

&nbsp;



## Preparing LC-MS/MS systems
The liquid chromatography system and the mass spectrometer need to be optimized for analyzing tiny protein samples to a state described here as *single-cell ready*. This preparation can be accomplished using bulk samples diluted to single-cell levels. The preparation has been described in multiple protocols, including by [Petelski *et al.*](https://www.nature.com/articles/s41596-021-00616-z), *Nature Protocols*.


 * Petelski A, Emmott E, Leduc A, Huffman RG, Specht H, Perlman D, Slavov N. [Multiplexed single-cell proteomics using SCoPE2](https://www.nature.com/articles/s41596-021-00616-z), *Nature Protocols*, 2021

&nbsp;

### Optimizing and benchmarking LC-MS/MS analysis
Our protocols for optimizing peptide separation and tandem mass spectrometry analysis include data driven pipelines named DO-MS. These protocols and the associated software tools are available at: [do-ms.slavovlab.net](https://do-ms.slavovlab.net/). DO-MS allows to optimization of duty cycle methods, peptide separation, number of survey scans per duty cycle, and quality control of single-cell data acquisition for [DDA](https://pubs.acs.org/doi/10.1021/acs.jproteome.9b00039) and [DIA](https://pubs.acs.org/doi/10.1021/acs.jproteome.3c00177) methods.

Achieving *single-cell readiness* is also discussed in [workshops](https://www.youtube.com/playlist?list=PLHLRxq8iKFsLJey2MshSlUhg1lGAj0dLW) of the Single Cell Proteomics Conference.

&nbsp;

<iframe width="560" height="315" src="https://www.youtube.com/embed/5nV9zbF9DT0?si=jB6a9k90dz8uObDi" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>


------------

&nbsp;

## Preparing single-cell samples
Preparing single cells for mass spectrometry protein analysis aims to maximize protein delivery to the detectors while at the same time minimizing contaminations. These objectives are challenging, especially when we would like to prepare and analyze tens of thousands of single cells.

### Protocols for multi-well sample preparation

The [mPOP](mPOP) protocol supports the preparation of a few hundred single cells in multi-well plates. It is described in the articled below:

 * Petelski A, Emmott E, Leduc A, Huffman RG, Specht H, Perlman D, Slavov N. [Multiplexed single-cell proteomics using SCoPE2](https://www.nature.com/articles/s41596-021-00616-z), *Nature Protocols*, 2021
 * Petelski A, Slavov N., Specht H, [Single-Cell Proteomics Preparation for Mass Spectrometry Analysis Using Freeze-Heat Lysis and an Isobaric Carrier](https://pubmed.ncbi.nlm.nih.gov/36571403/), *Jove*, 2022


### Protocols for highly parallel glass slide sample preparation

A high-throughput sample preparation has been described by [Leduc *et al.*](https://doi.org/10.1186/s13059-022-02817-5), *Geneome Biology*. The [nPOP](nPOP) protocol enables flexible experimental designs supporting different multiplexing schemes without requiring specialized consumables; nPOP supports all existing multiplexing approaches and can be easily programmed to new ones that may emerge. It can prepare over *3,000* single cells in parallel using 8-20nl reaction volumes per cell.

 * Leduc A, Koury L., Cantlon J., Slavov N. [Massively parallel sample preparation for multiplexed single-cell proteomics using nPOP](https://doi.org/10.1101/2023.11.27.568927), *bioRxiv* 2023.11.27.568927,  doi: 10.1101/2023.11.27.568927
 * Leduc A, Koury L., Cantlon J., Slavov N.  [Highly Parallel Droplet Sample Preparation for Single Cell Proteomics](https://dx.doi.org/10.17504/protocols.io.4r3l24r7qg1y/v3), *protocols.io*, doi: [dx.doi.org/10.17504/protocols.io.4r3l24r7qg1y/v3](https://dx.doi.org/10.17504/protocols.io.4r3l24r7qg1y/v3)


------------

&nbsp;



&nbsp;




&nbsp;

&nbsp;

&nbsp;
