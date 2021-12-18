---
title: "Streaming Breakpoint Graph Analytics for Accelerating and Parallelizing the Computation of DCJ Median of Three Genomes"
date: 2013-01-01
publishDate: 2019-09-10T12:18:34.529100Z
authors: ["Zhaoming Yin", "Jijun Tang", "Stephen W. Schaeffer", "David A. Bader"]
publication_types: ["2"]
abstract: "The problem of finding the median of three genomes is the key process in building the most parsimonious phylogenetic trees from genome rearrangement data. The median problem using Double-Cut-and-Join (DCJ) distance is NP-hard and the best exact algorithm is based on a branch-and-bound best-first search strategy to explore sub-graph patterns in Multiple BreakPoint Graph (MBG). In this paper, by taking advantage of the “streaming” property of MBG, we introduce the “footprint-based” data structure to reduce the space requirement of a single search nodes from O(v2) to O(v); minimize the redundant computation in counting cycles/paths to update bounds, which leads to dramatically decrease of workload of a single search node. Additional heuristic of branching strategy is introduced to help reducing the searching space. Last but not least, the introduction of a multi-thread shared memory parallel algorithm with two load balancing strategies bring in additional benefit by distributing search work efficiently among different processors. We conduct extensive experiments on simulated datasets and our results show significant improvement on all datasets. And we test our DCJ median algorithm with GASTS, a state of the art software phylogenetic tree construction package. On the real high resolution Drosophila data set, our exact algorithm run as fast as the heuristic algorithm and help construct a better phylogenetic tree."
featured: false
publication: "*Procedia Computer Science*"
tags: ["Genome Rearrangement", "Double-cut-and-joining Median", "Parallel Programming"]
url_pdf: "http://www.sciencedirect.com/science/article/pii/S1877050913003633"
doi: "10.1016/j.procs.2013.05.220"
---

