---
layout: default
title: Huffman et al, 2022
nav_order: 5
permalink: Huffman_et_al_2022
description: "Single-cell proteomics by data from prioritized SCoPE, pSCoPE | Slavov Laboratory"
parent: Single-cell protein data
---
{% include social-media-links.html %}


## Article: [Huffman et al, 2022, version 2](https://www.biorxiv.org/content/10.1101/2022.03.16.484655v2)
* The data from [version 1](https://www.biorxiv.org/content/10.1101/2022.03.16.484655v1) are available at [Huffman et al, 2022, version 1](Huffman_et_al_2022_v1)
<!-- **Peer reviewed article:** -->

### Single-cell proteomics method: [pSCoPE](pSCoPE)
**Sample preparation method: [nPOP](nPOP)**

### Model systems:  Primary murine bone-marrow-derived macrophages, as well as HEK293 and melanoma cell lines.




&nbsp;


&nbsp;

[Processed pSCoPE Data]({{site.baseurl}}#processed-single-cell-protein-data){: .btn .fs-5 .mb-4 .mb-md-0 .mr-2 }
[RAW pSCoPE Data]({{site.baseurl}}#RAW-single-cell-protein-data){: .btn .fs-5 .mb-4 .mb-md-0 .mr-2 }
<!--[10x Genomics Data]({{site.baseurl}}#single-cell-RNA-data){: .btn .fs-5 .mb-4 .mb-md-0 .mr-2 }-->

&nbsp;

<h2 style="letter-spacing: 2px; font-size: 26px;" id="processed-single-cell-protein-data" >Metadata and data processed to ASCII text matrices</h2>
<h3 style="letter-spacing: 2px; font-size: 26px;" id="processed-single-cell-protein-data" >Benchmarking experiments: Figure 2a data, pSCoPE acquisition</h3>

* **Metadata:** [Cells.csv](https://drive.google.com/file/d/1lQKsHj0C2ABbOG-IFO4lIdKPDnH2AJnf/view?usp=sharing)
   - `Annotation` **x**  `single cells`. Each row corresponds to a single cell annotated with relevant metadata, such as, cell type if known, measurements from the isolation of the cell, and derivative quantities, i.e., rRI, CVs, reliability.

&nbsp;   

* [Peptides-raw.csv](https://drive.google.com/file/d/1ln3k08jrHS7IyMK0HBJ_0YMHYQ1Hx0fu/view?usp=sharing)
  - `Peptides` **x** `single cells` at 1% FDR.  The first 2 columns list the corresponding protein identifiers and peptide sequences and each subsequent column corresponds to a single cell. Peptide identification is based on spectra analyzed by [MaxQuant](https://www.maxquant.org/).
  <!-- See [Specht et al., 2019](https://www.biorxiv.org/content/10.1101/665307v3) for details. -->  

&nbsp;

* [Proteins-processed.csv](https://drive.google.com/file/d/1l_oiiLFnQwlRwQprU2tOC-fOa9Gpjyhz/view?usp=sharing)
   - `Proteins` **x** `single cells` at 1% FDR, imputed and batch corrected.


&nbsp;

<!--* [sdrf_meta_data.tsv](https://drive.google.com/file/d/1T8BTfNDlYQkBTs8La6YRSCyD1RwNTvqk/view?usp=sharing)
   -  Meta data following the [Sample to Data file format (SDRF) for Proteomics project guidelines](https://github.com/bigbio/proteomics-metadata-standard) for  for all single cells used in analysis constituting all figures.-->

&nbsp;

<!--* [Joint protein-RNA data](https://drive.google.com/file/d/130FWc-s-Pd-mx3ymg22bI1qH5fiT7Ktv/view?usp=sharing)
   - `Gene` **x**  `single cells`. Both sets imputed and batch-corrected separately then combined, taking only genes common to both data sets. Uniprot accession numbers used to denote gene.-->

<!--&nbsp;-->

<!--* [Signal-to-noise data](https://drive.google.com/file/d/16dmI7qNdpJlPOn83dOZFhHfXv0du5Dip/view?usp=sharing)
  - `Peptides` and `Proteins` **x** `single cells` at 1% FDR.  The first 2 columns list the corresponding protein identifiers and peptide sequences and each subsequent column corresponds to a single cell. The quantitation is the Signal-to-noise (S/N) ratio for each single cell's corresponding reporter ion extracted from the RAW file. The single cell identification numbers are [mapped](https://drive.google.com/file/d/1PUfiGhmInYP3JW5Xoul7Tikl9RSHyQcN/view?usp=sharing) to cell type and RAW file. Complete extracted S/N for each RAW file can be found [here](https://drive.google.com/drive/folders/18_BQ15_JQKzbDt1JZo36MaJuOhN3tJCX?usp=sharing).  -->

<h3 style="letter-spacing: 2px; font-size: 26px;" id="processed-single-cell-protein-data" >Benchmarking experiments: Figure 2b/c/d/e data, pSCoPE acquisition</h3>

* **Metadata:** [Cells.csv](https://drive.google.com/file/d/1kj78MqYLuuGNGrrbdo6yn6rcYrW1VFh_/view?usp=sharing)
   - `Annotation` **x**  `single cells`. Each row corresponds to a single cell annotated with relevant metadata, such as, cell type if known, measurements from the isolation of the cell, and derivative quantities, i.e., rRI, CVs, reliability.

&nbsp;

* [Peptides-raw.csv](https://drive.google.com/file/d/1klNkkwmZGGbSN_7-PSW0B3Npm7f61mej/view?usp=sharing)
  - `Peptides` **x** `single cells` at 1% FDR.  The first 2 columns list the corresponding protein identifiers and peptide sequences and each subsequent column corresponds to a single cell. Peptide identification is based on spectra analyzed by [MaxQuant](https://www.maxquant.org/).
  <!-- See [Specht et al., 2019](https://www.biorxiv.org/content/10.1101/665307v3) for details. -->

&nbsp;

* [Proteins-processed.csv](https://drive.google.com/file/d/1klrNDcw9D3DFTwSD8YuuNj2iVYLjIxXx/view?usp=sharing)
   - `Proteins` **x** `single cells` at 1% FDR, imputed and batch corrected.

&nbsp;



<h3 style="letter-spacing: 2px; font-size: 26px;" id="processed-single-cell-protein-data" >Benchmarking experiments: Figure 2a/b/c/d data, Shotgun acquisition</h3>

* **Metadata:** [Cells.csv](https://drive.google.com/file/d/1lrItjbGeBwlqblG1Vx4Mk8fta0lSbyU7/view?usp=sharing)
   - `Annotation` **x**  `single cells`. Each row corresponds to a single cell annotated with relevant metadata, such as, cell type if known, measurements from the isolation of the cell, and derivative quantities, i.e., rRI, CVs, reliability.

&nbsp;

* [Peptides-raw.csv](https://drive.google.com/file/d/1lwTcbxCtzFeSLWQZVkSR_9-tXmTP67zc/view?usp=sharing)
  - `Peptides` **x** `single cells` at 1% FDR.  The first 2 columns list the corresponding protein identifiers and peptide sequences and each subsequent column corresponds to a single cell. Peptide identification is based on spectra analyzed by [MaxQuant](https://www.maxquant.org/).
  <!-- See [Specht et al., 2019](https://www.biorxiv.org/content/10.1101/665307v3) for details. -->

&nbsp;

* [Proteins-processed.csv](https://drive.google.com/file/d/1m1jxJavwqxEv11hOVhwiGOlCP_6Lg4l6/view?usp=sharing)
   - `Proteins` **x** `single cells` at 1% FDR, imputed and batch corrected.

&nbsp;


<!-- * [sdrf_meta_data.tsv](https://drive.google.com/file/d/1T8BTfNDlYQkBTs8La6YRSCyD1RwNTvqk/view?usp=sharing)
   -  Meta data following the [Sample to Data file format (SDRF) for Proteomics project guidelines](https://github.com/bigbio/proteomics-metadata-standard) for  for all single cells used in analysis constituting all figures. -->  

<h3 style="letter-spacing: 2px; font-size: 26px;" id="processed-single-cell-protein-data" >Bone-marrow-derived macrophage experiments: Figures 4, 5, and 6</h3>

* **Metadata:** [Cells.csv](https://drive.google.com/file/d/1OHEf8PQ7REerh0kFlnxj3bHFQ2HTmRKL/view?usp=sharing)
   - `Annotation` **x**  `single cells`. Each row corresponds to a single cell annotated with relevant metadata, such as, cell type if known, measurements from the isolation of the cell, and derivative quantities, i.e., rRI, CVs, reliability.

&nbsp;

* [Peptides-raw.csv](https://drive.google.com/file/d/1mCNeDcxUT5eWKwSruC-aThnKM9PNtEcO/view?usp=sharing)
  - `Peptides` **x** `single cells` at 1% FDR.  The first 2 columns list the corresponding protein identifiers and peptide sequences and each subsequent column corresponds to a single cell. Peptide identification is based on spectra analyzed by [MaxQuant](https://www.maxquant.org/)  and is enhanced by using [DART-ID](https://dart-id.slavovlab.net/) to incorporate retention time information.
  <!-- See [Specht et al., 2019](https://www.biorxiv.org/content/10.1101/665307v3) for details. -->  

&nbsp;

* [Proteins-processed.csv](https://drive.google.com/file/d/1qHU5wtXoKxBcZ73QPWSUavOeO2xk1zvR/view?usp=sharing)
   - `Proteins` **x** `single cells` at 1% FDR, imputed and batch corrected.

&nbsp;


<!-- * [sdrf_meta_data.tsv](https://drive.google.com/file/d/1T8BTfNDlYQkBTs8La6YRSCyD1RwNTvqk/view?usp=sharing)
   -  Meta data following the [Sample to Data file format (SDRF) for Proteomics project guidelines](https://github.com/bigbio/proteomics-metadata-standard) for  for all single cells used in analysis constituting all figures. -->

<!-- * [DART-ID input](https://drive.google.com/drive/folders/1ohLco5KHX95jyXIZUAZDvrrbip1RzZ_1?usp=sharing) -->


&nbsp;
<!-- * [GSEA: GOrilla output](https://drive.google.com/drive/folders/1DCp_euY0Cj_NWWG5xQsx7CTN3ju5LI_O?usp=sharing)
&nbsp; -->

<!-- * [Minimal data files](https://drive.google.com/drive/folders/10pOMMlxHsFIyPa9X2auq6xKJssqFgo-D?usp=sharing) necessary for generating Peptides-raw.csv and Proteins-processed.csv -->

<h2 style="letter-spacing: 2px; font-size: 26px;" id="processed-single-cell-protein-data" >Files needed to regenerate preprint figures</h2>

&nbsp;

* [Additional data files](https://drive.google.com/file/d/1MDbBtue0UgI6qhAHeiXW-YnIk4ONHqST/view?usp=sharing) necessary for generating figures from the pSCoPE preprint.
<!-- [SCoPE2 article](https://doi.org/10.1101/665307). -->



&nbsp;


<h2 style="letter-spacing: 2px; font-size: 26px;" id="RAW-single-cell-protein-data" >pSCoPE RAW data and search results from MaxQuant</h2>
The Massive repository below contains RAW mass-spectrometry data files generated by a Q exactive instrument as well as the search results from analyzing the RAW files by [MaxQuant](https://www.maxquant.org/)  and by [DART-ID](https://dart-id.slavovlab.net/). Please consult the linked files for more information on the included files:

<!--* [MaxQuant results descriptions](https://drive.google.com/open?id=1qXThKpGPx1tBcxvYFvNM0zCSeyILDzE6) -->

* [Raw file descriptions](https://docs.google.com/spreadsheets/d/1EoBFPIgXXSYqP5khTAp7LMG75HYGK2uT/edit?usp=sharing&rtpof=true&sd=true)

* **MassIVE Repository:**
  - [**http:**  MSV000090383](https://massive.ucsd.edu/ProteoSAFe/dataset.jsp?task=76188b5c13714a6da059d2845fca1c64)
  - [**ftp:** &nbsp; MSV000090383](ftp://massive.ucsd.edu/MSV000090383/)

<!-- * **MassIVE Repository 2:**
  - [**http:**  MSV000084660](https://massive.ucsd.edu/ProteoSAFe/dataset.jsp?accession=MSV000084660)
  - [**ftp:** &nbsp; MSV000084660](ftp://massive.ucsd.edu/MSV000084660) -->



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

&nbsp;

&nbsp;

&nbsp;
