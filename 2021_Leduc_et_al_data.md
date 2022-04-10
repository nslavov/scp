---
layout: default
title: Leduc et al, 2021
nav_order: 3.5
permalink: Leduc_et_al_2021
description: "Single-cell proteomics by SCoPE2 and nPOP | Slavov Laboratory"
parent: Single-cell protein data
---
{% include social-media-links.html %}


## Article: [Leduc et al, 2021](https://www.biorxiv.org/content/10.1101/2021.04.24.441211v1)
<!-- **Peer reviewed article:** -->

### Single-cell proteomics method: [SCoPE2](https://scp.slavovlab.net/SCoPE2)
**Sample preparation method: [nPOP](https://scp.slavovlab.net/nPOP)**

### Model systems:  Cell lines of monocytes (U937 cells) and Hela cells.


&nbsp;


[RAW Data](#raw_data){: .btn .fs-5 .mb-4 .mb-md-0 .mr-2 }
[Processed Data](#proc_data){: .btn .fs-5 .mb-4 .mb-md-0 .mr-2 }
[Videos](#talks){: .btn .fs-5 .mb-4 .mb-md-0 .mr-2 }



<h2 style="letter-spacing: 2px; font-size: 26px;" id="raw_data" >Raw Data from experiments benchmarking nPOP</h2>

* **MassIVE Repository:**
  - [**http:**  MSV000082841](https://massive.ucsd.edu/ProteoSAFe/dataset.jsp?task=0374fefddfc64cb8b400f77e4c19536e)
  - [**ftp:** &nbsp; MSV000082841](ftp://massive.ucsd.edu/MSV000087152)
  - [**http:**  MSV000088167](https://massive.ucsd.edu/ProteoSAFe/dataset.jsp?task=2f82c5f336a441d7a7aee378d84f7a58)
  - [**ftp:** &nbsp; MSV000088167](ftp://massive.ucsd.edu/MSV000088167)

  &nbsp;

  &nbsp;

<h2 style="letter-spacing: 2px; font-size: 26px;" id="proc_data" >Processed Data from experiments benchmarking nPOP</h2>

* [Peptides-raw.csv](https://drive.google.com/file/d/1cVEq5KIHdyhVfDObo31W2GbFH5XgDne8/view?usp=sharing)
   - `Peptides` **x** `single cells` at 1% FDR.  The first columns list the peptide sequences and each subsequent column corresponds to a single cell. Peptide identification is based on spectra analyzed by [MaxQuant](https://www.maxquant.org/)  and is enhanced by using [DART-ID](https://dart-id.slavovlab.net/) to incorporate retention time information. See [Specht et al., 2019](https://www.biorxiv.org/content/10.1101/665307v3) for details.

&nbsp;

* [Proteins-processed.csv](https://drive.google.com/file/d/1LHyHfE0WoyVWbMyhYD1DtnpVxfRz5a79/view?usp=sharing)
   - `Proteins` **x** `single cells` at 1% FDR, imputed and batch corrected.

&nbsp;

* [Cells.csv](https://drive.google.com/file/d/1PKaGrIOizIxx9zmrM7ShZYiTaM49p_9R/view?usp=sharing)
   - `Annotation` **x**  `single cells`. Each column corresponds to a single cell and the rows include relevant metadata, such as, cell type, measurements from the isolation of the cell, and derivative quantities, i.e., rRI, CVs, reliability. This file corresponds to Proteins-processed.csv and Peptides-raw.csv files.

&nbsp;


* [HeLa-proteins.csv](https://drive.google.com/file/d/1BMj5YF_qVu34JXkcBn54GhdB2fS2-_0z/view?usp=sharing)
   - `Proteins` **x** `single cells` for HeLa cells at 1% FDR, unimputed and z-scored.

&nbsp;

* [U-937-proteins.csv](https://drive.google.com/file/d/1BLNher4z0agGGoJjM2VRRGAGS077ONYi/view?usp=sharing)
   - `Proteins` **x** `single cells` for U-937 cells at 1% FDR, unimputed and z-scored.

&nbsp;


* [CellCycle-Proteins.csv](https://drive.google.com/file/d/1BM4ffkpu0vW_9rfSnmkPwA66RTGKRd21/view?usp=sharing)
   - A list of cell cycle dependent proteins used in analysis. Cell cycle protein and phases information was used from [Whitfield et al, 2002](http://genome-www.stanford.edu/Human-CellCycle/Hela/).

&nbsp;


<h2 style="letter-spacing: 2px; font-size: 26px;" id="talks" >Recorded video presentations</h2>

<iframe width="560" height="315" src="https://www.youtube.com/embed/DJ1U_KpMNcY" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>


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
