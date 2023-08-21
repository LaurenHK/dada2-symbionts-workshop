# dada2-symbionts-workshop

This hands-on workshop hosted by researchers from Minderoo Foundation’s Ocean’s Program (Research and Infrastructure and OceanOmics), will discuss considerations for assessing Symbiodiniaceae assemblages with amplicon sequencing and walk-through analysis of sequence data using the DADA2 pipeline.

## Primary workshop components
* Overview of coral-algal symbioses; marker genes; challenges and opportunities with ITS2.
* Step-by-step overview, from receiving fastq files and pre-processing up to production of a counts table using the DADA2 pipeline. 
Note: we will not be handling the analysis of sequences per-se. There is a lot of documentation online on how to visualize and statistically analyze these data types.

## Before the workshop:
* Download bbduk and test installation, instructions here: https://jgi.doe.gov/data-and-tools/software-tools/bbtools/bb-tools-user-guide/installation-guide/
  * Identify the path to bbuk on your local system, have this handy
* Make sure R and R studio are downloaded
* Fork and clone this repository (you can also click the top right green 'code' button and download a zip of all files).
* Install R packages: tidyverse (collection of packages), dada2 (instructions at the start of the Rmarkdown file)
  
## Workshop materials:
* Test sequences
    * test-set-ITS2seqs: these are raw fastq files from the sequencing provider, we will use these for pre-dada2 processing steps
    * pre-filtered: backup, in case challenges arise with bbduk pre-processing, these files are ready to use with dada2 in R
* R markdown file: contains all code used in workshop

## Context and recommend reading:
The internal transcribed spacer 2 (ITS2) rDNA region is the most frequently used marker gene among reef researchers to identify Symbiodiniaceae lineages. This workshop will cover one processing approach (using the DADA2 pipeline) and discuss considerations for analyzing this type of data. 

* Building consensus around the assessment and interpretation of Symbiodiniaceae diversity | PeerJ

* Deep-Sequencing Method for Quantifying Background Abundances of Symbiodinium Types: Exploring the Rare Symbiodinium Biosphere in Reef-Building Corals | PLOS ONE

* Transgenerational inheritance of shuffled symbiont communities in the coral Montipora digitata | Scientific Reports (nature.com)

* DADA2: High-resolution sample inference from Illumina amplicon data | Nature Methods



