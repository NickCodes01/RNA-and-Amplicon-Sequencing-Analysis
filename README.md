# RNA-and-Amplicon-Sequencing-Analysis
This repository contains the analysis pipeline, results, and summaries for two distinct sequencing projects: RNA Sequencing and Amplicon Sequencing. These projects were conducted to explore gene expression level analysis and variant calling analysis, respectively.

Projects Overview:
1. RNA-Seq Analysis
This project involves processing RNA sequencing data to quantify gene expression levels. The workflow includes:
Aligning RNA-Seq reads to the human reference genome using HISAT2.
Converting alignment files from SAM to BAM format and sorting for downstream analyses.
Generating a gene expression count matrix using featureCounts.
Calculating RPKM (Reads Per Kilobase per Million mapped reads) and TPM (Transcripts Per Million) for normalized expression levels.
Quality assessment of input data using FastQC.
Key Results:
Gene expression levels quantified in TPM and RPKM.
High-quality alignment and minimal errors in preprocessing.
Top expressed genes and summary statistics highlight expected biological patterns.


2. Amplicon Sequencing Analysis
This project focuses on variant detection from targeted genomic loci using amplicon sequencing data. The workflow includes:
Alignment of reads to the human reference genome using BWA-MEM2.
Variant calling using FreeBayes to identify single nucleotide polymorphisms (SNPs) and small insertions/deletions (indels).
High-quality variant filtration based on QUAL and DP metrics.
Quality assessment of input data using FastQC.
Key Results:
Top 10 high-quality genetic variants identified with confidence metrics (QUAL scores).
Comprehensive statistical overview of detected variants.
Insights into targeted genomic loci with potential biological significance.


Contents:
Scripts: Python and command-line scripts for alignment, feature counting, and variant filtration.
FastQC Reports: Quality assessment reports for both RNA-Seq and Amplicon projects.
Results: Processed data including gene counts, TPM/RPKM matrices, and high-confidence variant calls.
Documentation: Step-by-step explanation of the workflows and results interpretation.

