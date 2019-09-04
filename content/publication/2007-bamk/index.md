---
title: "High performance combinatorial algorithm design on the Cell Broadband Engine processor"
date: 2007-01-01
publishDate: 2019-09-04T10:56:26.474470Z
authors: ["David A. Bader", "Virat Agarwal", "Kamesh Madduri", "Seunghwa Kang"]
publication_types: ["2"]
abstract: "The Sony–Toshiba–IBM Cell Broadband Engine (Cell/B.E.) is a heterogeneous multicore architecture that consists of a traditional microprocessor (PPE) with eight SIMD co-processing units (SPEs) integrated on-chip. While the Cell/B.E. processor is architected for multimedia applications with regular processing requirements, we are interested in its performance on problems with non-uniform memory access patterns. In this article, we present two case studies to illustrate the design and implementation of parallel combinatorial algorithms on Cell/B.E.: we discuss list ranking, a fundamental kernel for graph problems, and zlib, a data compression and decompression library.  List ranking is a particularly challenging problem to parallelize on current cache-based and distributed memory architectures due to its low computational intensity and irregular memory access patterns. To tolerate memory latency on the Cell/B.E. processor, we decompose work into several independent tasks and coordinate computation using the novel idea of Software-Managed threads (SM-Threads). We apply this generic SPE work-partitioning technique to efficiently implement list ranking, and demonstrate substantial speedup in comparison to traditional cache-based microprocessors. For instance, on a 3.2 GHz IBM QS20 Cell/B.E. blade, for a random linked list of 1 million nodes, we achieve an overall speedup of 8.34 over a PPE-only implementation.  Our second case study, zlib, is a data compression/decompression library that is extensively used in both scientific as well as general purpose computing. The core kernels in the zlib library are the LZ77 longest subsequence matching algorithm and Huffman data encoding. We design efficient parallel algorithms for these combinatorial kernels, and exploit concurrency at multiple levels on the Cell/B.E. processor. We also present a Cell/B.E. optimized implementation of gzip, a popular file-compression application based on the zlib library. For our Cell/B.E. implementation of gzip, we achieve an average speedup of 2.9 in compression over current workstations."
featured: false
publication: "*Parallel Computing*"
url_pdf: "https://doi.org/10.1016/j.parco.2007.09.005"
doi: "10.1016/j.parco.2007.09.005"
---

