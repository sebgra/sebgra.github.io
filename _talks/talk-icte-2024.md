---
title: "Hicberg – Hi-C Biological Estimation of Reapeated elements in Genomes"
collection: talks
type: "Poster"
permalink: /talks/talk-icte-2024
venue: "Palais des Congrès"
date: 2024-04-22
location: "Saint-Malo, France"
---

During their evolution, the genomes of micro-organisms can acquire quantities of different repeated elements such as retrotransposons, duplicated genes or tandem repeats. This type of sequence within genomes cannot be processed directly by NGS technologies because they generate short reads that cannot be located unambiguously on reference genomes. This information is filtered out by most current pipelines, leading to incomplete genomic tracks resulting in a significant loss of information on biological functions, processes and genomic structures involving repeated elements. We developed [*Hicberg*](https://github.com/sebgra/hicberg), an algorithm that uses statistical inference and pseudo-random generators to predict the positions of repeated sequence reads from different omics paired-end data (including Hi-C, Mnase-seq or ChIP-seq). After developing the method and calibrating it on a test bench, we explored during this PhD project how it improves genomic data interpretability of various species, starting with microbial ones such as *Saccharomyces cerevisiae*. Reconstruction of Hi-C and ChIP-seq genomic tracks with [*Hicberg*](https://github.com/sebgra/hicberg) revealed how some retrotransposons in this model organism contribute in the positioning of cohesin, a molecular motor involved in the formation of chromatin loops. A new role for retrotransposons sequences as contact points for the elusive yeast 2 micron episomal molecule was also identified. Overall, these results underline the power of the approach to discover new novel molecular relationships, and the interest in applying this tool more widely to larger genomes with greater quantities of repeats. The proposed method can therefore provide an alternative visualization of genomic signals in a wide variety of biological conditions and allow a more comprehensive view of genome organization and plasticity. Importantly, existing datasets can be
revisited using the approach to unveil overlook features.

[Poster here](../files/ICTE_2024_poster.pdf)


[More information here](https://icte2024.sciencesconf.org/browse/author?authorid=1210060)
