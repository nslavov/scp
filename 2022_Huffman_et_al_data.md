---
layout: default
title: Huffman et al, 2022
nav_order: 5
permalink: Huffman_et_al_2022
description: "Single-cell proteomics by data from prioritized SCoPE, pSCoPE | Slavov Laboratory"
parent: Data
---
{% include social-media-links.html %}


## Article: [Huffman et al, 2022](https://www.biorxiv.org/content/10.1101/2022.03.16.484655v1)
<!-- **Peer reviewed article:** -->

### Single-cell proteomics method: [pSCoPE](pSCoPE)
**Sample preparation method: [nPOP](nPOP)**

### Model systems:  Primary murine bone marrow derived macrophages and a pancreatic ductal adenocarcinoma (PDAC) cell line.




&nbsp;


&nbsp;

[Processed pSCoPE Data]({{site.baseurl}}#processed-single-cell-protein-data){: .btn .fs-5 .mb-4 .mb-md-0 .mr-2 }
[RAW pSCoPE Data]({{site.baseurl}}#RAW-single-cell-protein-data){: .btn .fs-5 .mb-4 .mb-md-0 .mr-2 }
<!--[10x Genomics Data]({{site.baseurl}}#single-cell-RNA-data){: .btn .fs-5 .mb-4 .mb-md-0 .mr-2 }-->

&nbsp;

<h2 style="letter-spacing: 2px; font-size: 26px;" id="processed-single-cell-protein-data" >pSCoPE data processed to ASCII text matrices</h2>
<h3 style="letter-spacing: 2px; font-size: 26px;" id="processed-single-cell-protein-data" >Benchmarking experiments: Figure 1b/e data</h3>

* [Peptides-raw.csv](https://drive.google.com/file/d/1gbbn_SgwaPYAYG3iiQqpEHSw34hpKp5M/view?usp=sharing)
  - `Peptides` **x** `single cells` at 1% FDR.  The first 2 columns list the corresponding protein identifiers and peptide sequences and each subsequent column corresponds to a single cell. Peptide identification is based on spectra analyzed by [MaxQuant](https://www.maxquant.org/).
  <!-- See [Specht et al., 2019](https://www.biorxiv.org/content/10.1101/665307v3) for details. -->  

&nbsp;

* [Proteins-processed.csv](https://drive.google.com/file/d/1l1DvtdYrfj6rjq1TZKcsWqG4iYBOtpKq/view?usp=sharing)
   - `Proteins` **x** `single cells` at 1% FDR, imputed and batch corrected.

&nbsp;

* [Cells.csv](https://drive.google.com/file/d/1J7sBHYwo5669w8igY4ldojPcLwuqX7I-/view?usp=sharing)
   - `Annotation` **x**  `single cells`. Each row corresponds to a single cell annotated with relevant metadata, such as, cell type if known, measurements from the isolation of the cell, and derivative quantities, i.e., rRI, CVs, reliability.

&nbsp;

<!--* [sdrf_meta_data.tsv](https://drive.google.com/file/d/1T8BTfNDlYQkBTs8La6YRSCyD1RwNTvqk/view?usp=sharing)
   -  Meta data following the [Sample to Data file format (SDRF) for Proteomics project guidelines](https://github.com/bigbio/proteomics-metadata-standard) for  for all single cells used in analysis constituting all figures.-->

&nbsp;

<!--* [Joint protein-RNA data](https://drive.google.com/file/d/130FWc-s-Pd-mx3ymg22bI1qH5fiT7Ktv/view?usp=sharing)
   - `Gene` **x**  `single cells`. Both sets imputed and batch-corrected separately then combined, taking only genes common to both data sets. Uniprot accession numbers used to denote gene.-->

<!--&nbsp;-->

<!--* [Signal-to-noise data](https://drive.google.com/file/d/16dmI7qNdpJlPOn83dOZFhHfXv0du5Dip/view?usp=sharing)
  - `Peptides` and `Proteins` **x** `single cells` at 1% FDR.  The first 2 columns list the corresponding protein identifiers and peptide sequences and each subsequent column corresponds to a single cell. The quantitation is the Signal-to-noise (S/N) ratio for each single cell's corresponding reporter ion extracted from the RAW file. The single cell identification numbers are [mapped](https://drive.google.com/file/d/1PUfiGhmInYP3JW5Xoul7Tikl9RSHyQcN/view?usp=sharing) to cell type and RAW file. Complete extracted S/N for each RAW file can be found [here](https://drive.google.com/drive/folders/18_BQ15_JQKzbDt1JZo36MaJuOhN3tJCX?usp=sharing).  -->

<h3 style="letter-spacing: 2px; font-size: 26px;" id="processed-single-cell-protein-data" >Benchmarking experiments: Figure 1c/d data</h3>

* [Peptides-raw.csv](https://drive.google.com/file/d/1VS-ko7rDsy0t2V5JNfB049txTLpzGPr0/view?usp=sharing)
  - `Peptides` **x** `single cells` at 1% FDR.  The first 2 columns list the corresponding protein identifiers and peptide sequences and each subsequent column corresponds to a single cell. Peptide identification is based on spectra analyzed by [MaxQuant](https://www.maxquant.org/).
  <!-- See [Specht et al., 2019](https://www.biorxiv.org/content/10.1101/665307v3) for details. -->

&nbsp;

* [Proteins-processed.csv](https://drive.google.com/file/d/1PSg-FA5eqYeLEekVZ8Yr_nx902K4Aink/view?usp=sharing)
   - `Proteins` **x** `single cells` at 1% FDR, imputed and batch corrected.

&nbsp;

* [Cells.csv](https://drive.google.com/file/d/1z6vah8XfzqxEM62oFMmGP7q7UDYhfS6D/view?usp=sharing)
   - `Annotation` **x**  `single cells`. Each row corresponds to a single cell annotated with relevant metadata, such as, cell type if known, measurements from the isolation of the cell, and derivative quantities, i.e., rRI, CVs, reliability.

&nbsp;

<!-- * [sdrf_meta_data.tsv](https://drive.google.com/file/d/1T8BTfNDlYQkBTs8La6YRSCyD1RwNTvqk/view?usp=sharing)
   -  Meta data following the [Sample to Data file format (SDRF) for Proteomics project guidelines](https://github.com/bigbio/proteomics-metadata-standard) for  for all single cells used in analysis constituting all figures. -->  

<h3 style="letter-spacing: 2px; font-size: 26px;" id="processed-single-cell-protein-data" >Bone-marrow-derived macrophage experiments: Figures 2, 3, and 4</h3>

* [Peptides-raw.csv](https://drive.google.com/file/d/1mCNeDcxUT5eWKwSruC-aThnKM9PNtEcO/view?usp=sharing)
  - `Peptides` **x** `single cells` at 1% FDR.  The first 2 columns list the corresponding protein identifiers and peptide sequences and each subsequent column corresponds to a single cell. Peptide identification is based on spectra analyzed by [MaxQuant](https://www.maxquant.org/)  and is enhanced by using [DART-ID](https://dart-id.slavovlab.net/) to incorporate retention time information.
  <!-- See [Specht et al., 2019](https://www.biorxiv.org/content/10.1101/665307v3) for details. -->  

&nbsp;

* [Proteins-processed.csv](https://drive.google.com/file/d/1qHU5wtXoKxBcZ73QPWSUavOeO2xk1zvR/view?usp=sharing)
   - `Proteins` **x** `single cells` at 1% FDR, imputed and batch corrected.

&nbsp;

* [Cells.csv](https://drive.google.com/file/d/1OHEf8PQ7REerh0kFlnxj3bHFQ2HTmRKL/view?usp=sharing)
   - `Annotation` **x**  `single cells`. Each row corresponds to a single cell annotated with relevant metadata, such as, cell type if known, measurements from the isolation of the cell, and derivative quantities, i.e., rRI, CVs, reliability.

&nbsp;

<!-- * [sdrf_meta_data.tsv](https://drive.google.com/file/d/1T8BTfNDlYQkBTs8La6YRSCyD1RwNTvqk/view?usp=sharing)
   -  Meta data following the [Sample to Data file format (SDRF) for Proteomics project guidelines](https://github.com/bigbio/proteomics-metadata-standard) for  for all single cells used in analysis constituting all figures. -->


&nbsp;
<!-- * [DART-ID input](https://drive.google.com/drive/folders/1ohLco5KHX95jyXIZUAZDvrrbip1RzZ_1?usp=sharing) -->


&nbsp;
<!-- * [GSEA: GOrilla output](https://drive.google.com/drive/folders/1DCp_euY0Cj_NWWG5xQsx7CTN3ju5LI_O?usp=sharing)
&nbsp; -->

<!-- * [Minimal data files](https://drive.google.com/drive/folders/10pOMMlxHsFIyPa9X2auq6xKJssqFgo-D?usp=sharing) necessary for generating Peptides-raw.csv and Proteins-processed.csv -->

<h2 style="letter-spacing: 2px; font-size: 26px;" id="processed-single-cell-protein-data" >Files needed to regenerate preprint figures</h2>

&nbsp;

* [Additional data files](https://drive.google.com/file/d/1WRVpDCJPxYjfOX-QWvoq86RqfKbmVfGc/view?usp=sharing) necessary for generating figures from the pSCoPE preprint.
<!-- [SCoPE2 article](https://doi.org/10.1101/665307). -->


&nbsp;





&nbsp;


<h2 style="letter-spacing: 2px; font-size: 26px;" id="RAW-single-cell-protein-data" >pSCoPE RAW data and search results from MaxQuant</h2>
The Massive repository below contains RAW mass-spectrometry data files generated by a Q exactive instrument as well as the search results from analyzing the RAW files by [MaxQuant](https://www.maxquant.org/)  and by [DART-ID](https://dart-id.slavovlab.net/). Please consult the linked files for more information on the included files:

<!--* [MaxQuant results descriptions](https://drive.google.com/open?id=1qXThKpGPx1tBcxvYFvNM0zCSeyILDzE6) -->

* [Raw file descriptions](https://docs.google.com/spreadsheets/d/1EoBFPIgXXSYqP5khTAp7LMG75HYGK2uT/edit?usp=sharing&ouid=109814487119977139380&rtpof=true&sd=true)

* **MassIVE Repository:**
  - [**http:**  MSV000089055](https://massive.ucsd.edu/ProteoSAFe/dataset.jsp?task=b15cafc7489147e99b93bd7c718388b2)
  - [**ftp:** &nbsp; MSV000089055](ftp://massive.ucsd.edu/MSV000089055/)

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
