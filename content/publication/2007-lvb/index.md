---
title: "On the design of high-performance algorithms for aligning multiple protein sequences on mesh-based multiprocessor architectures"
date: 2007-01-01
publishDate: 2019-09-10T12:18:37.741804Z
authors: ["Diana H. P. Low", "Bharadwaj Veeravalli", "David A. Bader"]
publication_types: ["article-journal"]
abstract: "In this paper, we address the problem of multiple sequence alignment (MSA) for handling very large number of proteins sequences on mesh-based multiprocessor architectures. As the problem has been conclusively shown to be computationally complex, we employ divisible load paradigm (also, referred to as divisible load theory, DLT) to handle such large number of sequences. We design an efficient computational engine that is capable of conducting MSAs by exploiting the underlying parallelism embedded in the computational steps of multiple sequence algorithms. Specifically, we consider the standard Smith–Waterman (SW) algorithm in our implementation, however, our approach is by no means restrictive to SW class of algorithms alone. The treatment used in this paper is generic to a class of similar dynamic programming problems. Our approach is recursive in the sense that the quality of solutions can be refined continuously till an acceptable level of quality is achieved. After first phase of computation, we design a heuristic scheme that renders the final solution for MSA. We conduct rigorous simulation experiments using several hundreds of homologous protein sequences derived from the Rattus Norvegicus and Mus Musculus databases of olfactory receptors. We quantify the performance based on speed-up metric. We compare our algorithms to serial or single machine processing approaches. We testify our findings by comparing with conventional equal load partitioning (ELP) strategy that is commonly used in the parallel processing literature. Based on our extensive simulation study, we observe that DLT paradigm offers an excellent speed-up characteristics and provides avenues for its use in several other biological sequence processing related problem. This study is a first time attempt in using the DLT paradigm to devise efficient strategies to handle large scale multiple protein sequence alignment problem on mesh-based multiprocessor systems."
featured: false
publication: "*Journal of Parallel and Distributed Computing*"
url_pdf: "https://doi.org/10.1016/j.jpdc.2007.03.007"
doi: "10.1016/j.jpdc.2007.03.007"
---

