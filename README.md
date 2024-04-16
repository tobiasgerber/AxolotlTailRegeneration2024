This repository contains the scripts necessary to reproduce the single-cell RNA-seq analyses published in Somite-independent regeneration of the axolotl primary body axis (https://doi.org/10.1101/2024.01.31.577464)

Following scripts describe the basic prefiltering and cell type annotation/isolation:

01_ViralBarcodes_scRNAseqQuantification.sh (should be executed on shell
02_scRNAseqProcessing_Rep1.r (should be exectued on R)
03_scRNAseqProcessing_Rep2.r (should be exectued on R)
04_BarcodeExtraction.nf (executed on nextflow per replicate fq.gz file)
05_CloneCalling.r (executed on R)
