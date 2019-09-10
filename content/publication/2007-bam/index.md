---
title: "On the Design and Analysis of Irregular Algorithms on the Cell Processor: A Case Study of List Ranking"
date: 2007-01-01
publishDate: 2019-09-10T12:18:35.640062Z
authors: ["David A. Bader", "Virat Agarwal", "Kamesh Madduri"]
publication_types: ["1"]
abstract: "The Sony-Toshiba-IBM Cell Broadband Engine is a heterogeneous multicore architecture that consists of a traditional microprocessor (PPE), with eight SIMD coprocessing units (SPEs) integrated on-chip. We present a complexity model for designing algorithms on the Cell processor, along with a systematic procedure for algorithm analysis. To estimate the execution time of the algorithm, we consider the computational complexity, memory access patterns (DMA transfer sizes and latency), and the complexity of branching instructions. This model, coupled with the analysis procedure, simplifies algorithm design on the Cell and enables quick identification of potential implementation bottlenecks. Using the model, we design an efficient implementation of list ranking, a representative problem from the class of combinatorial and graph-theoretic applications. Due to its highly irregular memory patterns, list ranking is a particularly challenging problem to parallelize on current cache-based and distributed memory architectures. We describe a generic work-partitioning technique on the Cell to hide memory access latency, and apply this to efficiently implement list ranking. We run our algorithm on a 3.2 GHz Cell processor using an IBM QS20 Cell Blade and demonstrate a substantial speedup for list ranking on the Cell in comparison to traditional cache-based microprocessors. For a random linked list of 1 million nodes, we achieve an an overall speedup of 8.34 over a PPE-only implementation."
featured: false
publication: "*21th International Parallel and Distributed Processing Symposium (IPDPS 2007), Proceedings, 26-30 March 2007, Long Beach, California, USA*"
url_pdf: "https://doi.org/10.1109/IPDPS.2007.370266"
doi: "10.1109/IPDPS.2007.370266"
---

