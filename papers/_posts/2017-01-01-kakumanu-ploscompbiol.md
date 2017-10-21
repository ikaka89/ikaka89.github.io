---
layout: paper
title: Deconvolving sequence features that discriminate between overlapping regulatory annotations.
image: /assets/images/papers/journal.pcbi.1005795.g001.PNG
authors: <b>Kakumanu A</b>, Velasco S, Mazzoni EO and Mahony S
year: 2017
bigref: <b>Kakumanu A</b>, Velasco S, Mazzoni EO and Mahony S. 2017. PLoS Comput Biol.
ref: Kakumanu et al. 2017. PLoS Comput Biol.
journal: "PLoS Comput Biol"
pdf: /assets/pdfs/kakumanu_ploscompbiol_2017.pdf
doi: https://doi.org/10.1371/journal.pcbi.1005795
github : https://github.com/seqcode/sequnwinder
---

# Abstract

Transcription factor proteins control gene expression by recognizing and interacting with short DNA sequence patterns in regulatory regions on the genome. Current genomics experiments allow us to find regulatory regions associated with a particular biochemical activity over the entire genome; for example, all regions where a particular transcription factor interacts with the genome in a given cell type. Given a collection of regulatory regions, we often aim to discover short DNA sequence patterns that are more common in the collection than in other regions. Performing such “DNA motif-finding” analysis can give us hints about the patterns that determine gene regulation in the analyzed cell type.

Here we describe a new method for DNA motif-finding called SeqUnwinder. Our approach analyzes collections of regulatory regions where each has been labeled according to various biological properties. For example, the labels could correspond to various cell types in which the regulatory region is active. SeqUnwinder then performs machine-learning analysis to unravel DNA sequence features that are characteristic of each label (e.g. features that distinguish regulatory regions in each cell type from other cell types). SeqUnwinder is the first method to enable analysis of regulatory region collections that contain several overlapping labels.