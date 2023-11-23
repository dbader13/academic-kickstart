---
title: "Design and implementation of parallel PageRank on multicore platforms"
date: 2017-01-01
publishDate: 2019-09-10T12:18:33.902651Z
authors: ["Shijie Zhou", "Kartik Lakhotia", "Shreyas G. Singapura", "Hanqing Zeng", "Rajgopal Kannan", "Viktor K. Prasanna", "James Fox", "Euna Kim", "Oded Green", "David A. Bader"]
publication_types: ["paper-conference"]
abstract: "PageRank is a fundamental graph algorithm to evaluate the importance of vertices in a graph. In this paper, we present an efficient parallel PageRank design based on an edge-centric scatter-gather model. To overcome the poor locality of PageRank and optimize the memory performance, we develop a fast and efficient partitioning technique. We first partition all the vertices into non-overlapping vertex sets such that the data of each vertex set can fit in the cache; then we sort the outgoing edges of each vertex set based on the destination vertices to minimize random memory writes. The partitioning technique significantly reduces random accesses to main memory and improves the sustained memory bandwidth by 3×. It also enables efficient parallel execution on multicore platforms; we use distinct cores to execute the computations of distinct vertex sets in parallel to achieve speedup. We implement our design on a 16-core Intel Xeon processor and use various large-scale real-life and synthetic datasets for evaluation. Compared with the PageRank Pipeline Benchmark, our design achieves 12× to 19× speedup for all the datasets."
featured: false
publication: "*The 21st Annual IEEE High Performance Extreme Computing Conference, HPEC 2017, Waltham, MA, USA, September 12-14, 2017*"
url_pdf: "https://doi.org/10.1109/HPEC.2017.8091048"
doi: "10.1109/HPEC.2017.8091048"
---

{{<figure src="certificate.jpg">}}
