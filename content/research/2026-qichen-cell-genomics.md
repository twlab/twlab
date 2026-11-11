---
title: "Leveraging human pangenome for improved somatic variant detection"
date: 2026-11-05
featured: true
draft: false
link: https://doi.org/10.1016/j.xgen.2026.101419
weight: 62
---

[Learn more](https://doi.org/10.1016/j.xgen.2026.101419)
{{< load-photoswipe >}}
{{< figure src = "https://wang.wustl.edu/img/2026-qichen-cell-genomics.png" >}}

# Abstract:
Somatic variant detection is technically challenging due to low variant allele fractions, the confounding presence of germline variation, and reference bias. Linear references, such as GRCh38, miss sample-specific variation, leading to misalignments and incorrect variant calls. Although telomere-to-telomere donor-specific assemblies (DSAs) accurately represent individual genomes, their application is limited by cost and technical barriers. Alternatively, the graph-based human pangenome provides a scalable framework to improve read alignment and perform genome inference. Here, we benchmarked somatic variant detection using GRCh38, graph-based pangenomes, and pangenome-inferred DSAs with a HapMap mixture dataset and the COLO829 melanoma cell line. Pangenome-guided alignment improves read mapping and somatic variant calling accuracy. Furthermore, personalized pangenomes partially reconstruct donor-specific genomic content, improving accuracy, reducing germline contamination, and enabling detection of events in loci absent or poorly represented in GRCh38. These findings demonstrate that graph-based and personalized pangenomes are effective strategies for enhancing somatic variant detection compared with GRCh38.
