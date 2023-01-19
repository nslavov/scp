---
layout: default
title: mPOP
nav_order: 1
permalink: mPOP
description: "Minimal ProteOmic sample Preparation (mPOP) for single-cell proteomics by mass-spectrometry"
parent: Sample preparation

---
{% include social-media-links.html %}

&nbsp;

# Minimal Proteomic sample preparation (mPOP)
## Sample prep method by [Specht et al, 2018](https://www.biorxiv.org/content/10.1101/399774v1)
* [Data Websites](#data-websites)

&nbsp;

<span class="text-center">
[mPOP Article](https://www.biorxiv.org/content/10.1101/399774v1){: .btn .fs-5 .mr-4 }
[Nature Protocol](https://doi.org/10.1038/s41596-021-00616-z){: .btn .fs-5 .mr-4 }
[JoVE Protocol](https://www.jove.com/t/63802/single-cell-proteomics-preparation-for-mass-spectrometry-analysis?status=a65808k){: .btn .fs-5 .mr-4 }
</span>



[![Minimal ProteOmic sample Preparation (mPOP) method for single-cell proteomics](Figs/mPOP_SamplePrep.png){: width="90%" .center-image}][mPOP_Preprint]

&nbsp;

## Data Websites
 * [Specht et al., 2018](https://massive.ucsd.edu/ProteoSAFe/dataset.jsp?task=bfd7f21d718940fdbaccc0d58ad6b122)
 * [Specht et al., 2019](Specht_et_al_2019)
 * [Petelski et al., 2021](Petelski_et_al_2021)


&nbsp;



[Introduction](#abstract){: .btn .fs-4 .mr-3 }
[Advantages of mPOP](#advantages-of-mpop){: .btn .fs-4 .mr-3 }
[RAW Data](#data){: .btn .fs-4 .mr-3 }
[Videos](#talks){: .btn .fs-4 .mr-3 }


## Introduction

A major limitation to applying quantitative LC-MS/MS proteomics to small samples, such as single cells, are the losses incurred during sample cleanup. To relieve this limitation, **[Specht et al., 2018][mPOP_Preprint]** developed Minimal ProteOmic sample Preparation (mPOP). mPOP lyses cells by a freeze-heat cycle and uses only mass-spectrometry compatible chemicals, thus obviating sample cleanup. This approach expediting sample preparation in multi-well plates and simplifies its automation. Bulk SILAC samples processed by mPOP or by conventional urea-based methods [demonstrated][mPOP_Preprint] that mPOP results in complete, unbiased cell lysis and accurate relative quantification. mPOP can be easily intergraded with all [methods](methods) for single-cell proteomics by mass-spectrometry. Details of its integration with [SCoPE2](scope2) are described in a [Nature protocol](https://www.biorxiv.org/content/10.1101/2021.03.12.435034v1) and a [JoVE video protocol](https://www.jove.com/t/63802/single-cell-proteomics-preparation-for-mass-spectrometry-analysis?status=a65808k).


## Advantages of mPOP
  1. **mPOP uses equipment found in most laboratories**
     - Easy to adopt and implement without specialized equipment
  2. **mPOP uses only mass-spec compatible chemicals**
     - No cleanup steps are needed
  3. **mPOP is easy to automate**
     - Thus mPOP can prepare hundreds of single cells with little human handling
  4. **mPOP uses inexpensive and accessible consumables**  
     - This keeps costs below 1 USD / single cell.

The least reliable step of mPOP is single cell isolation via FACS sorting. The reliability of this step is dependent on the sorters and operators and can be high with experienced operators. Single cells can also be isolated by laser capture microdissection, manual cell picking, CellenONE, magnetic-activated cell sorting, and other methods. We have observed highly [consistent and reliable](https://doi.org/10.1038/s41596-021-00616-z) results from mPOP when isolating single cells with CellenONE.   

<!--   ![]({{site.baseurl}}Figures/Single-cell-Proteomics_Applications_iCarrier.png){: width="80%" .center-image}
To increase the throughput and quantitative accuracy of single-cell protein analysis by [SCoPE-MS](https://doi.org/10.1101/102681), we introduced many technical improvements in both the sample preparation and in the mass-spectrometry analysis. The [synergistic effect](https://www.biorxiv.org/content/biorxiv/early/2019/12/05/665307/T1.medium.gif) is to increase quantitative accuracy by 4-fold and the throughput of data acquisition about 8-fold. Below, we outline controlled experiments that illustrate the benefits of **individual** improvements. To comprehensively compare the mass-spec data at all levels (including chromatographic separation, precursor abundance, ion isolation, spectral purity, and peptide sequence identification), we include the full [Data-driven Optimization of MS (DO-MS)](https://do-ms.slavovlab.net) reports for each set of experiments. 
-->

&nbsp;



<h2 style="letter-spacing: 2px; font-size: 26px;" id="applications-and-data" >Applications & data</h2>
  *  [Specht et al, 2019](https://doi.org/10.1101/665307) used mPOP to prepare samples for [SCopE2](scope2) analysis of the emergence of macrophage polarization. **[Specht et al, 2019 data website](Specht_et_al_2019)**
  *  [Petelski et al, 2021](https://doi.org/10.1038/s41596-021-00616-z) demonstrated mPOP as part of a Nature Protocol for [SCopE2](scope2) analysis. **[Petelski et al, 2021 data website](Petelski_et_al_2021)**  
  * [Specht et al, 2018][mPOP_Preprint] developed mPOP and below are links to the data from benchmarking experiments demonstrating that:
     1. mPOP efficiently extracts proteins from all cellular compartments and delivers them for mass-spec analysis
     2. mPOP supports accurate and precise protein quantification consistent with quantification obtained from standard urea lysis  
       - [**http:**  MSV000082841](https://massive.ucsd.edu/ProteoSAFe/dataset.jsp?task=bfd7f21d718940fdbaccc0d58ad6b122)
       - [**ftp:** &nbsp; MSV000082841](ftp://massive.ucsd.edu/MSV000082841)

  &nbsp;


  &nbsp;


<h2 style="letter-spacing: 2px; font-size: 26px;" id="talks" >Recorded video presentations</h2>

### [YouTube Playlist](https://youtube.com/playlist?list=PLHLRxq8iKFsKQWxfn4uZppIwyhpYrY0Fd)

&nbsp;

<iframe width="560" height="315" src="https://www.youtube.com/embed/mz6Yq2XSu-8" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

&nbsp;

&nbsp;

<iframe width="560" height="315" src="https://www.youtube.com/embed/w48VxHymqo0" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
&nbsp;

&nbsp;  

&nbsp;

## About the project

This project on developing an automated sample preparation method for single-cell proteomics was supported by funding from the [NIH Director's Award](https://projectreporter.nih.gov/project_info_description.cfm?aid=9167004&icde=31336575).


[mPOP_Preprint]: https://doi.org/10.1101/399774 "Minimal ProteOmic sample Preparation (mPOP) method for single-cell proteomics by mass-spectrometry"

<!-- Petelski, A. A., Slavov, N., Specht, H. Single-Cell Proteomics Preparation for Mass Spectrometry Analysis Using Freeze-Heat Lysis and an Isobaric Carrier. J. Vis. Exp. (190), e63802, doi:10.3791/63802 (2022). -->

&nbsp;  

&nbsp;

&nbsp;

&nbsp;

&nbsp;

&nbsp;

&nbsp;

&nbsp;

&nbsp;

&nbsp;

&nbsp;

&nbsp;

&nbsp;

&nbsp;

&nbsp;

&nbsp;
