---
layout: paper
title: An Integrated Model of Multiple-Condition ChIP-Seq Data Reveals Predeterminants of Cdx2 Binding
image: /images/papers/mahony_ploscompbiol_2014.gif
authors: Mahony S, Edwards MD, Mazzoni EO, Sherwood RI, <b>Kakumanu A</b>, Morrison CA, Wichterle H and Gifford DK
year: 2014
bigref: Mahony S, Edwards MD, Mazzoni EO, Sherwood RI, <b>Kakumanu A</b>, Morrison CA, Wichterle H and Gifford DK. 2014. PLoS Comput Biol.
ref: Mahony et al. 2014. PLoS Comput Biol.
journal: "PLoS Comput Biol 10(3): e1003501"
pdf: /pdfs/papers/mahony_ploscompbiol_2014.pdf
doi: 10.1371/journal.pcbi.1003501
---

# Abstract

Regulatory proteins can bind to different sets of genomic targets in various cell types or conditions. To reliably characterize such condition-specific regulatory binding we introduce MultiGPS, an integrated machine learning approach for the analysis of multiple related ChIP-seq experiments. MultiGPS is based on a generalized Expectation Maximization framework that shares information across multiple experiments for binding event discovery. We demonstrate that our framework enables the simultaneous modeling of sparse condition-specific binding changes, sequence dependence, and replicate-specific noise sources. MultiGPS encourages consistency in reported binding event locations across multiple-condition ChIP-seq datasets and provides accurate estimation of ChIP enrichment levels at each event. MultiGPS's multi-experiment modeling approach thus provides a reliable platform for detecting differential binding enrichment across experimental conditions. We demonstrate the advantages of MultiGPS with an analysis of Cdx2 binding in three distinct developmental contexts. By accurately characterizing condition-specific Cdx2 binding, MultiGPS enables novel insight into the mechanistic basis of Cdx2 site selectivity. Specifically, the condition-specific Cdx2 sites characterized by MultiGPS are highly associated with pre-existing genomic context, suggesting that such sites are pre-determined by cell-specific regulatory architecture. However, MultiGPS-defined condition-independent sites are not predicted by pre-existing regulatory signals, suggesting that Cdx2 can bind to a subset of locations regardless of genomic environment. A summary of this paper appears in the proceedings of the RECOMB 2014 conference, April 2–5