# BIO-410-Final-Project
## Background
The data consist of six samples from the organism ________. This organism is a _____ which ______. (cite)

## Purpose
The purpose of this project was to create a phylogenic tree from 6 samples of Zaire ebolavirus in order to determine  the evolutionary relationships between the samples.

## Methods
include information about
- Next-Generation Sequencing (NGS): the samples were sequenceed using NGS to generate ___ sequence data. Raw sequencing reads for each sample are provided in the repository as .fq files. As they contain the original unprocessed reads.
- Assembly using MEGAHIT (provide link to megahit website): raw sequencied were assembled into contigs using MEGAHIT. This is designed for assembling large and complex datasets for each sample.
- Alignment using R package DECIPHER: multiple alignemnt was preformed un R using DECIPHER, the contig sequences generated from the assembly setp and imported into R and aligned. The alignment identified homologus regions among the seqences and prepares data for phylogenetic analysis.
- Tree using ML in R package DECIPHER: the phylogenetic relationships among the sequences used maximum likelihood (ML). The aligned sequences were generated during the DECIPHER alignment and used to construct the ML phylogenetic tree. This tree evaluates the evolutionary relationships and sequences similarity among the 6 samples. The assembles sequence dataset are provided in the repository as .fq file.

## Results
Here is the phylogenetic tree:
(insert image, see the markdown cheatsheet) 
	![alt text](Rplot.png)
explain
-which samples are closley relates 
-how many individuals did these 6 samples come from based in the phylogenetic tree
