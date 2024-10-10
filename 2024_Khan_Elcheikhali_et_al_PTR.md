---
layout: default
title: Khan et al, 2024
nav_order: 11
permalink: Khan_Elcheikhali_et_al_2024
description: "Inferring post-transcriptional regulation within and across cell types in human testis | Slavov Laboratory"
parent: Single-cell protein data
---

### Article: [Khan, Elcheikhali et al, 2024][BayesPG_Preprint]

&nbsp;

* **Preprint**:  Khan S & Elcheikhali M, Leduc A, Huffman R, Derks J, Franks A & Slavov N, [Inferring post-transcriptional regulation within and across cell types in human testis][BayesPG_Preprint], *bioRxiv*, 2024
* Code available at: [github.com/SlavovLab/BayesPG](https://github.com/SlavovLab/BayesPG/)

&nbsp;

### Methods used:
* Single-cell proteomics: [SCoPE2](SCoPE2), [pSCoPE](pSCoPE), [plexDIA](plexDIA)
* Sample preparation: [nPOP](nPOP)
* Data analysis package: [BayesPG](BayesPG), [QuantQC](QuantQC)


### Model system: human testes


&nbsp;

## Summary
Single-cell tissue atlases commonly use RNA abundances as surrogates for protein abundances. Yet, protein abundance also depends on the regulation of protein synthesis and degradation rates. To estimate the contributions of such post transcriptional regulation, we quantified the proteomes of 5,883 single cells from human testis using 3 distinct mass spectrometry methods (SCoPE2, pSCoPE, and plexDIA). To distinguish between biological and technical factors contributing to differences between protein and RNA levels, we developed BayesPG, a Bayesian model of transcript and protein abundance that systematically accounts for technical variation and infers biological differences. We use BayesPG to jointly model RNA and protein data collected from 29,709 single cells across different methods and datasets. BayesPG estimated consensus mRNA and protein levels for 3,861 gene products and quantified the relative protein-to-mRNA ratio (rPTR) for each gene across six distinct cell types in samples from human testis. About 28 % of the gene products exhibited significant differences at protein and RNA levels and contributed to about 1,500 significant GO groups. We observe that specialized and context specific functions, such as those related to spermatogenesis are regulated after transcription. Among hundreds of detected post translationally modified peptides, many show significant abundance differences across cell types. Furthermore, some phosphorylated peptides covary with kinases in a cell-type dependent manner, suggesting cell-type specific regulation. Our results demonstrate the potential of inferring protein regulation in complex tissues from single-cell proteogenomic data and provide a generalizable model, BayesPG, for performing such analyses.



&nbsp;


<h2 style="letter-spacing: 2px; font-size: 26px;" id="raw_data" > Raw Data </h2>


Raw files with acquired mass spectra are available via [MassIVE](https://massive.ucsd.edu/ProteoSAFe/dataset.jsp?accession=MSV000096034)


  &nbsp;

<h2 style="letter-spacing: 2px; font-size: 26px;" id="proc_data" >Processed Data</h2>

The processed data is available within a Google Drive  *[folder](https://drive.google.com/drive/folders/1oMaW74bjDPPPjyPTqocPD_SjMnHy7UeM?usp=sharing)*   

The folder is organized as follows:



- **001-MSData**: search outputs from raw mass specgtrometry data and associated files to process to single cell matrices
  - **001-searchedFiles**: output tables from Maxquant (including variable modification PTM search) and DIA-NN
  - **002-AuxiliaryFiles**: metadata and cellenOne files to process search data into single cell matrices,   configurations for DART-ID, inclusion lists and methods for pSCoPE and FASTA's used and complex groupings used.



- **002-SingleCellMatrices**: processed single cell matrices
  - **001-mRNA**: contains data from both studies used, one in the standard 10x output folder (Sohni et al) and the other as a digital gene expression matrix (Shami et al)
  - **002-Protein**: cell x protein matrices for each sample preparation batch (unimputed: protein and peptide level ; BayesPG uses peptide level) and a single batch corrected matrix with all sample preparation batches
  - **003-alignmentOutputs**: tables that contain RNA and protein cell type labels as assigned after dataset alignment via LIGER, as well as list of gene products that form feature space as selected by correlation vector analysis.



- **003-BayesPGOutput**: tables output from various testing prcoedures for signifant rPTR at gene product, GO and complex level as well similar tables for the correlation tests
  - **001-unfiltered**: all the datums
  - **002-filtered**: important note, the filtered data will not be a complete (at the level of cell types); gene products/grouping significance is cell type specific for the rPTR tests.

   &nbsp;

   &nbsp;

   [BayesPG_Preprint]: https://www.biorxiv.org/content/10.1101/2023.11.27.568927v1 "Bayesian software for modeling single-cell RNA and protein abundance that systematically accounts for technical variation and infers biological differences"
