---
title: "Using statistical profiling to decipher hidden chromatin contacts resulting from repeated sequences"
collection: talks
type: "Talk"
permalink: /talks/talk-inception-2024
venue: "Institut Pasteur"
date: 2024-11-26
location: "Paris, France"
---
During their evolution, the genomes of micro-organisms can acquire quantities of different repeated elements such as retrotransposons, duplicated genes or tandem repeats. This type of sequence within genomes cannot be processed directly using high throughput sequencing technologies because they generate short sequences that cannot be located unambiguously on reference genomes. This type of data is filtered by most current standard pipelines, resulting in a significant loss of information on biological functions, processes and genomic structures involving repeated elements. We developed [*Hicberg*](https://github.com/sebgra/hicberg), an algorithm that uses statistical inference and pseudo-random generators to predict the positions of repeated sequence reads from different omics paired-end data (including contact technologies like Hi-C, nucleosomes or proteins positioning technologies like Mnase-seq or ChIP-seq). After developing the method and calibrating it on a test bench, we explored during this PhD project how it improves genomic data interpretability of various species, starting with microbial ones such as *Saccharomyces cerevisiae*. 

We show that [*Hicberg*](https://github.com/sebgra/hicberg) is capable of reconstructing fine genomic architecture signals such as chromosome loops or the compartmental bi-partition signal. Reconstruction of Hi-C and ChIP-seq genomic tracks with [*Hicberg*](https://github.com/sebgra/hicberg) revealed how certain retrotransposons in this model organism can contribute in the positioning of cohesin, a molecular motor involved in the formation of chromosomal loops. A new role for retrotransposons sequences as contact hotspots for the 2-micron yeast parasitic plasmid is also identified. Overall, these results underline the power of the approach to discover new novel molecular relationships, and the interest in applying this tool more widely to larger genomes with greater quantities of repeats. The proposed method can therefore provide an alternative processing of genomic signals in a wide variety of biological contexts and allow a more comprehensive view of genome organization and plasticity.

[More information here](https://www.inception-program.fr/events-trainings/inception-symposium-2024)

[Material here](../files/Inception_26_11_2024_slides.pdf)

