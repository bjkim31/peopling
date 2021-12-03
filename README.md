# Peopling

## Introduction

* This repository is an archive of code and protocol for reproducibility of my research

## DATA source

- Genotype and metadata used in the analysis were downloaded from (I) section of [Reich lab's Simons Genome project Repository](https://reichdata.hms.harvard.edu/pub/datasets/sgdp/)<sup>1</sup> and [1000 genome project phase 3 data]() of the the International Genome Sample Resource<sup>2</sup>.

- for g1k data, only Biallelic sites were extracted.

## code and softwares

- [plink]() 
- [R]()
  - [tidyverse]()
  - [ggplot2]()
  - [leaflet]()
- [vcf2fasta]() this script extract genotypes from vcf files to construct 10-letter fasta file based on following hash table which denotes IUPAC nucleotide code.
  |   | A | C | G | T |
  | - | - | - | - | - | 
  | A | A | M | R | W |
  | C | M | C | S | Y |
  | G | R | S | G | K |
  | T | W | Y | K | T |
  


## References

