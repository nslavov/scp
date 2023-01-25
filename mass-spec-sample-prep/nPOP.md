---
layout: default
title: nPOP
nav_order: 2
permalink: nPOP
description: "nano-ProteOmic droplet sample Preparation (nPOP) for single-cell proteomics by mass-spectrometry. Automated and high-throughput sample prep for proteomics"
parent: Sample preparation

---
{% include social-media-links.html %}

&nbsp;


# Droplet proteomic sample preparation (nPOP)

## Massively parallel sample prep method by [Leduc et al, 2021][nPOP_Preprint]
**Peer reviewed article:** Leduc A, Huffman RG, Cantlon J, Khan S, Slavov N, [Exploring functional protein covariation across single cells using nPOP](https://genomebiology.biomedcentral.com/articles/10.1186/s13059-022-02817-5) *Genome Biol* **23**, 261 [10.1186/s13059-022-02817-5](https://doi.org/10.1186/s13059-022-02817-5), [Data Websites](#data-websites)
<!--  * **Perspective:**  Slavov N., [Learning from natural variation across the proteomes of single cells](https://doi.org/10.1371/journal.pbio.3001512) -->

&nbsp;



[Research Article][nPOP_GeneomeBiology]{: .btn .fs-5 .mr-4 }
[nPOP @ protocols.io](https://www.protocols.io/view/highly-parallel-droplet-sample-preparation-for-sin-b8uyrwxw){: .btn .fs-5 .mr-4 }
[GitHub](https://github.com/SlavovLab/nPOP){: .btn .fs-5 .mr-4 }
[Q&A](https://groups.google.com/g/npop-sample-prep){: .btn .fs-5 .mr-4 }
[Videos](#talks){: .btn .fs-5 .mr-4 }


&nbsp;


[![nano-ProteOmic droplet sample Preparation (nPOP) method for single-cell proteomics by mass-spectrometry](Figs/nPOP_SamplePrep.png){: width="90%" .center-image}][nPOP_GeneomeBiology]

&nbsp;

## Data Websites
 * [Leduc et al., 2021](Leduc_et_al_2021)
 * [Derks et al., 2022](Derks_et_al_2022)
 * [Leduc et al., 2022](Leduc_et_al_2022)
 * [Huffman et al., 2022](Huffman_et_al_2022)


&nbsp;



[Introduction](#introduction){: .btn .fs-4 .mr-3 }
[Resources](#Resources){: .btn .fs-4 .mr-3 }
[Advantages of nPOP](#advantages-of-npop){: .btn .fs-4 .mr-3 }
[Applications](#applications-and-data){: .btn .fs-4 .mr-3 }
[Videos](#talks){: .btn .fs-4 .mr-3 }


## Introduction
The nano-ProteOmic sample Preparation (nPOP) uses piezo acoustic dispensing to isolate individual cells in 300 picoliter volumes and performs all subsequent preparation steps in small droplets on a fluorocarbon-coated slide. This design enables simultaneous sample preparation of thousands of single cells, including lysing, digesting, and labeling individual cells in volumes below 20 nl.

## Resources
The nPOP protocol can be found [here](https://www.protocols.io/view/highly-parallel-droplet-sample-preparation-for-sin-b8uyrwxw) and the cellenONE software files for performing sample prep can be found [here](https://drive.google.com/drive/folders/1EBeHGCQksMt3jItFVPxf-POEYiXQ7mGs).

Additionally, tools for mapping single cell image data from the cellenONE to sets run for LC/MS are available here on this [GitHub](https://github.com/Andrew-Leduc/CellenONE_mapper) page.


## Advantages of nPOP
  1. **nPOP can prepare thousands of single cells in a single batch**
     - This minimizes the # of batches and associated technical variation
  2. **nPOP uses only mass-spec compatible chemicals and volumes below 20 nl**
     - This results in [low background](https://www.biorxiv.org/content/biorxiv/early/2022/08/29/2021.04.24.441211/F2.large.jpg?width=800&height=600&carousel=1) and [low contamination](https://www.biorxiv.org/content/biorxiv/early/2022/08/29/2021.04.24.441211/F9.large.jpg?width=800&height=600&carousel=1)
  3. **nPOP droplet layouts are computationally programmable and thus very flexible**
     - Thus nPOP can be used for all multiplexed or label-free workflows without specialized consumables  
  4. **nPOP uses accessible consumables and small amounts of labels**  
     - This keeps costs down to about 10-20 cents / single cell.

nPOP uses the CellenONE instrument, which is commercially available. Without access to CellenONE, one may use [mPOP](mPOP), which can prepares a few hundred single cells in parallel. Both mPOP and nPOP are fully compatible with all [mass-spectrometry methods](methods) described in this portal.

&nbsp;

<h2 style="letter-spacing: 2px; font-size: 26px;" id="applications-and-data" >Applications & data</h2>
  *  [Leduc et al, 2021](https://www.biorxiv.org/content/10.1101/2021.04.24.441211v2) used nPOP to prepare samples for [SCopE2](scope2) analysis of the cell division cycle of U937 and Hela cells. **[Leduc et al, 2021 data website](Leduc_et_al_2021)**
  *  [Derks et al, 2022](https://www.biorxiv.org/content/10.1101/2021.11.03.467007v2) used nPOP to prepare samples for [plexDIA](plexDIA) analysis of single  melanoma, monocyte and pancreatic adenocarcinoma cells. **[Derks et al, 2022 data website](Derks_et_al_2022)**
  *  [Leduc et al, 2022](https://www.biorxiv.org/content/10.1101/2021.04.24.441211v3) used nPOP to prepare samples for [pSCopE](pscope) analysis of protein covariation in monocytes and melanoma cells. **[Leduc et al, 2022 data website](Leduc_et_al_2022)**
  *  [Huffman et al, 2022](https://doi.org/10.1101/2022.03.16.484655) used nPOP to prepare samples for [pSCopE](pscope) analysis of primary macrophages stimulated with LPS. **[Huffman et al, 2022 data website](Huffman_et_al_2022)**

&nbsp;

&nbsp;


<h2 style="letter-spacing: 2px; font-size: 26px;" id="talks" >Recorded video presentations</h2>

### [YouTube Playlist](https://youtube.com/playlist?list=PLHLRxq8iKFsKQWxfn4uZppIwyhpYrY0Fd)

&nbsp;

<iframe width="560" height="315" src="https://www.youtube.com/embed/DJ1U_KpMNcY" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

&nbsp;

&nbsp;

<iframe width="560" height="315" src="https://www.youtube.com/embed/TwVn6sw9l24" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

&nbsp;

&nbsp;

<iframe width="560" height="315" src="https://www.youtube.com/embed/Y5hOCYqbiEk" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>



[nPOP_Preprint]: https://doi.org/10.1101/2021.04.24.441211 "nano-ProteOmic droplet sample Preparation (nPOP) method for single-cell proteomics by mass-spectrometry"
[nPOP_GeneomeBiology]: https://genomebiology.biomedcentral.com/articles/10.1186/s13059-022-02817-5 "Exploring functional protein covariation across single cells using nPOP enabled single-cell proteomics by mass-spectrometry"



<!--
<span class="text-center"></span>
[bioRxiv Preprint](https://doi.org/10.1101/2020.08.24.264994){: .btn .fs-5 .mr-4 }

**Table of Contents**

1. [Abstract](#abstract)
2. [RAW Data](#data)


## Abstract

Mass spectrometry methods have enabled quantifying thousands of proteins at the single cell level. These methods open the door to tackling many biological challenges, such as characterizing heterogeneity in the tumor micro-environment and better understanding signaling pathways driving stem cell differentiation. To further advance single-cell MS analysis, we developed an automated nano-ProteOmic sample Preparation (nPOP). nPOP isolates individual cells in 300 picoliter volumes and performs all subsequent preparation steps in small droplets on a hydrophobic glass slide, which allows to keep sample volumes below 15 nl.


 


&nbsp;


<h2 style="letter-spacing: 2px; font-size: 26px;" id="data" >Data from experiments with increasing isobaric carriers</h2>

* **MassIVE Repository:**
  - [**http:**  MSV000082841](https://massive.ucsd.edu/ProteoSAFe/dataset.jsp?task=bfd7f21d718940fdbaccc0d58ad6b122)
  - [**ftp:** &nbsp; MSV000082841](ftp://massive.ucsd.edu/MSV000082841)

  &nbsp;

  &nbsp;


&nbsp;

&nbsp;  

&nbsp;

## About the project

This project on characterizing the isobaric carrier was conducted in the [Slavov Laboratory](https://slavovlab.net) and [SCP Center](https://center.single-cell.net) at [Northeastern University](https://www.northeastern.edu/), and was authored by [Harrison Specht](http://harrisonspecht.com) and [Nikolai Slavov](https://coe.northeastern.edu/people/slavov-nikolai/). Learn more about [single-cell mass-spectrometry analysis](https://scope2.slavovlab.net/mass-spec/single-cell-proteomics).  


This project was supported by funding from the [NIH Director's Award](https://projectreporter.nih.gov/project_info_description.cfm?aid=9167004&icde=31336575).

-->

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
