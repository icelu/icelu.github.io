---
title: "CNETML: Maximum likelihood inference of phylogeny from copy number profiles of spatio-temporal samples"
collection: publications
permalink: /publications/2022-cnetml
date: 2022-03-20
venue: 'bioRxiv'
paperurl: 'https://www.biorxiv.org/content/10.1101/2022.03.18.484889v1'
citation: 'Bingxin Lu, Kit Curtius, Trevor A. Graham, Ziheng Yang, Chris P. Barnes (2022). CNETML: Maximum likelihood inference of phylogeny from copy number profiles of spatio-temporal samples. bioRxiv: 2022.03.18.484889.'
---

# Abstract
Phylogenetic trees based on copy number alterations (CNAs) for multi-region samples of a single cancer patient are helpful to understand the spatio-temporal evolution of cancers, especially in tumours driven by chromosomal instability. Due to the high cost of deep sequencing data, low-coverage data are more accessible in practice, which only allow the calling of (relative) total copy numbers due to the lower resolution. However, methods to reconstruct sample phylogenies from CNAs often use allele-specific copy numbers and those using total copy number are mostly distance matrix or maximum parsimony methods which do not handle temporal data or estimate mutation rates. In this work, we developed a new maximum likelihood method based on a novel evolutionary model of CNAs, CNETML, to infer phylogenies from spatio-temporal samples taken within a single patient. CNETML is the first program to jointly infer the tree topology, node ages, and mutation rates from total copy numbers when samples were taken at different time points. Our extensive simulations suggest CNETML performed well even on relative copy numbers with subclonal whole genome doubling events and under slight violation of model assumptions. The application of CNETML to real data from Barrett’s esophagus patients also generated consistent results with previous discoveries and novel early CNAs for further investigations.
