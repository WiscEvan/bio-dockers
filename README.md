# bio-dockers
### :whale: Dockerized bioinformatic tools.

[![Build Status](https://travis-ci.org/alexcoppe/bio-dockers.svg?branch=master)](https://travis-ci.org/wiscevan/bio-dockers)

A set of bioinformatics applications installed into a [Docker](https://www.docker.com) container, ready to be downloaded and used on any operating system
supported by [Docker](https://www.docker.com/).

All images are based on the [official Alpine Linux Docker image](https://hub.docker.com/_/alpine/)
which is only 5 MB of size. The main goal is to obtain decently small portable bioinformatics software, easy to install and run.

In order to use a container on your computer, [install](https://docs.docker.com/engine/installation/)
the Docker daemon and check the links in the table
below for instruction on how to pull the images from [Dockerhub](https://hub.docker.com/) and run them.

| Program        | Description| Version | Image size |
| ------------- |:-------------| :-------------| :-------------|
| [bamtools](https://github.com/alexcoppe/bio-dockers/tree/master/bamtools) |BamTools provides both a programmer's API and an end-user's toolkit for handling BAM files.| 2.5.1 | 161 MB |
| [bedtools](https://github.com/alexcoppe/bio-dockers/tree/master/bedtools) |A powerful toolset for genome arithmetic| 2.27.1 | 77.1 MB |
| [Burrows-Wheeler Aligner](https://github.com/alexcoppe/bio-dockers/tree/master/bwa) |BWA is a software package for mapping low-divergent sequences against a large reference genome| 0.7.17 | 8.9 MB |
| [CIRCOS](https://github.com/alexcoppe/bio-dockers/tree/master/circos) |A software package for visualizing data in a circular layout  | 0.69-6 | 176 MB |
| [FastQC](https://github.com/alexcoppe/bio-dockers/tree/master/fastqc) | A quality control tool for high throughput sequence data | 0.11.7 | 235 MB |
| [FASTX-Toolkit](https://github.com/alexcoppe/bio-dockers/tree/master/fastx-toolkit-lite) (lite) | A collection of command line tools for Short-Reads FASTA/FASTQ files preprocessing (lite version: no graphic commands) | 0.0.14 | 12.6 MB |
| [FASTX-Toolkit](https://github.com/alexcoppe/bio-dockers/tree/master/fastx-toolkit) | A collection of command line tools for Short-Reads FASTA/FASTQ files preprocessing | 0.0.14 | 77.2 MB |
| [gatk 3](https://github.com/alexcoppe/bio-dockers/tree/master/gatk) | A variety of tools with a primary focus on variant discovery and genotyping | 3.7 | 289 MB |
| [MuTect](https://github.com/alexcoppe/bio-dockers/tree/master/mutect) | A method for the reliable and accurate identification of somatic point mutations in next generation sequencing data of cancer genomes  | 1.1.5 | 134 MB |
| [Picard](https://github.com/alexcoppe/bio-dockers/tree/master/picard) | A set of command line tools for manipulating high-throughput sequencing (HTS) data and formats | 2.18.26 | 140 MB |
| [Samtools](https://github.com/alexcoppe/bio-dockers/tree/master/samtools) | A suite of programs for interacting with high-throughput sequencing data | 1.8 | 16.8 MB |
| [SnpEff](https://github.com/alexcoppe/bio-dockers/tree/master/snpeff) | Genetic variant annotation and effect prediction toolbox | 4.3T | 353 MB |
| [SnpSift](https://github.com/alexcoppe/bio-dockers/tree/master/snpsift) | A toolbox that allows you to filter and manipulate annotated files | 4.3T | 353 MB |
| [Trimmomatic](https://github.com/alexcoppe/bio-dockers/tree/master/trimmomatic) | A flexible read trimming tool for Illumina NGS data | 0.38 | 172 MB |
| [VarDictJava](https://github.com/alexcoppe/bio-dockers/tree/master/vardict) |  A variant discovery program written in Java and Perl. It is a partial Java port of VarDict variant caller | 1.5.1 | 631 MB |
| [VarScan](https://github.com/alexcoppe/bio-dockers/tree/master/varscan) | Variant detection in massively parallel sequencing data | 2.4.3 | 124 MB |
| [Pal2Nal](https://github.com/wiscevan/bio-dockers/tree/master/pal2nal) | Protein alignment to nucleotide alignment to calculate non-synonymous to synonymous codon usage | (v14) | 1.17 GB |
