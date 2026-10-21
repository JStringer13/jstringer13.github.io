# Unix and Analysis of Large Genomic Datasets

## Introduction and overview

Analysed short- and long-read sequencing data from fire ants and *Plasmodium falciparum*, developing practical skills in Linux, bioinformatics and genomic data interpretation.

The practicals followed the workflow from read cleaning and assembly to gene annotation, variant discovery and population genetics, alongside genomic and cancer database exercises.

## Skills developed

- **Linux and Bash:** Built scripting skills by organising projects and automating repeated steps across samples.
- **Sequencing analysis:** Developed quality-control and assembly skills by cleaning reads and evaluating reconstructed sequences.
- **Gene annotation:** Assessed predicted gene models through sequence similarity searches and comparison with reference proteins.
- **Variant interpretation:** Evaluated SNPs and structural variants using alignment evidence, filtering and genomic context.
- **R and population genetics:** Applied visualisation and comparative analysis to genotype data using R-based workflows.
- **Database research:** Investigated gene and cancer datasets while considering reference versions, transcript differences and cohort context.
- **Reproducibility and troubleshooting:** Managed Conda environments, recorded commands and software versions, and resolved dependency issues.

## Practical work

### 1. Unix and read quality control

- Worked on remote Linux systems, organised project files and recorded commands in analysis logs.
- Assessed read quality with FastQC and cleaned paired-end Illumina reads with Trimmomatic, KMC and Cutadapt.

### 2. Genome assembly

- Assembled cleaned reads using SPAdes and evaluated assembly length, GC content and contiguity with QUAST.

### 3. Gene prediction and annotation

- Predicted genes with MAKER and Augustus, and assessed protein predictions using BLASTP, UniProtKB/Swiss-Prot and GeneValidator.

### 4. Read mapping and variant calling

- Aligned reads with Bowtie2, processed alignment files with SAMtools, and called and filtered SNPs with BCFtools.
- Inspected alignments and variants in IGV to evaluate read support and potential artefacts.

### 5. Population genetics

- Used R Markdown, adegenet and PopGenome to visualise genetic variation and compare population structure, diversity and differentiation.

### 6. Long-read analysis on the teaching cluster

- Processed Oxford Nanopore reads using NanoPlot and Chopper, and mapped them to a reference with minimap2.
- Identified candidate structural variants with Sniffles and used Bash scripts to apply analysis steps across samples.

### 7. Genomic databases

- Queried NCBI, RefSeq, CCDS and UCSC to investigate gene locations, transcripts, annotations and reference assemblies.

### 8. Cancer genomics databases

- Used COSMIC and cBioPortal to study cancer mutation profiles, transcript isoforms, mutation hotspots and copy-number variation.