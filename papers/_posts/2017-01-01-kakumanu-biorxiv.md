---
layout: paper
title: Characterizing regulatory sequence features that discriminate between overlapping annotation labels
image: /images/papers/kakumanu_biorxiv_2017.png
authors: <b>Kakumanu A</b>, Velasco S, Mazzoni EO and Mahony S
year: 2017
bigref: <b>Kakumanu A</b>, Velasco S, Mazzoni EO and Mahony S. 2017. bioRxiv.
ref: Kakumanu et al. 2017. bioRxiv.
journal: "bioRxiv"
pdf: /pdfs/papers/kakumanu_biorxiv_2017.pdf
doi: 10.1101/100511
github : https://github.com/seqcode/sequnwinder
---

# Abstract

Genomic loci with regulatory potential can be identified and annotated with various labels. For example, sites may be annotated as being bound or unbound by a transcription factor (TF) under particular cellular conditions, or as being proximal or distal to known transcription start sites. Given such a collection of labeled genomic sites, it is natural to ask what sequence features are associated with each annotation label. However, discovering such label-specific sequence features is often confounded by uneven overlaps between annotation labels. In order to meet this challenge, we developed SeqUnwinder, a principled approach to deconvolving interpretable discriminative sequence features associated with overlapping annotation labels. We demonstrate the novel analysis abilities of SeqUnwinder using three examples. Firstly, we show SeqUnwinder's ability to unravel sequence features associated with the dynamic binding behavior of TFs during motor neuron programming from features associated with chromatin state in the initial embryonic stem cells. Secondly, we demonstrate that multi-condition TF binding sites are typically characterized by better quality instances of the TF's cognate binding motifs. Finally, we demonstrate the scalability of SeqUnwinder to discover cell-specific sequence features from over one hundred thousand genomic loci that display DNase I hypersensitivity in one or more ENCODE cell lines. Availability: [SeqUnwinder](https://github.com/seqcode/sequnwinder)