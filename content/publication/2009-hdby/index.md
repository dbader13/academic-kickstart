---
title: "A Partition-Merge Based Cache-Conscious Parallel Sorting Algorithm for CMP with Shared Cache"
date: 2009-01-01
publishDate: 2019-09-10T12:18:35.217937Z
authors: ["Song Hao", "Zhihui Du", "David A. Bader", "Yin Ye"]
publication_types: ["1"]
abstract: "To explore chip-level parallelism, the PSC (Parallel Shared Cache) model is provided in this paper to describe high performance shared cache of Chip Multi-Processors (CMP). Then for a specific application, parallel sorting, a cache-conscious parallel algorithm, PMCC (Partition-Merge based Cache-Conscious) is designed based on the PSC model. The PMCC algorithm consists of two steps: the partition-based in-cache sorting and merge-based k-way merge sorting. In the first stage, PMCC first divides the input dataset into multiple blocks so that each block can fit into the shared L2 cache, and then employs multiple cores to perform parallel cache sorting to generate sorted blocks. In the second stage, PMCC first selects an optimized parameter k which can not only improve the parallelism but also reduce the cache missing rate, then performs a k-way merge sorting to merge all the sorted blocks. The I/O complexity of the in-cache sorting step and k-way merge step are analyzed in detail. The simulation results show that the PSC based PMCC algorithm can out-performance the latest PEM based cache-conscious algorithm and the scalability of PMCC is also discussed. The low I/O complexity, high parallelism and the high scalability of PMCC can take advantage of CMP to improve its performance significantly and deal with large scale problem efficiently."
featured: false
publication: "*ICPP 2009, International Conference on Parallel Processing, Vienna, Austria, 22-25 September 2009*"
url_pdf: "https://doi.org/10.1109/ICPP.2009.26"
doi: "10.1109/ICPP.2009.26"
---

