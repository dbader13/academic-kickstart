---
title: "SNAP, Small-world Network Analysis and Partitioning: An open-source parallel graph framework for the exploration of large-scale networks"
date: 2008-01-01
publishDate: 2019-09-10T12:18:35.473355Z
authors: ["David A. Bader", "Kamesh Madduri"]
publication_types: ["paper-conference"]
abstract: "We present SNAP (small-world network analysis and partitioning), an open-source graph framework for exploratory study and partitioning of large-scale networks. To illustrate the capability of SNAP, we discuss the design, implementation, and performance of three novel parallel community detection algorithms that optimize modularity, a popular measure for clustering quality in social network analysis. In order to achieve scalable parallel performance, we exploit typical network characteristics of small-world networks, such as the low graph diameter, sparse connectivity, and skewed degree distribution. We conduct an extensive experimental study on real-world graph instances and demonstrate that our parallel schemes, coupled with aggressive algorithm engineering for small-world networks, give significant running time improvements over existing modularity-based clustering heuristics, with little or no loss in clustering quality. For instance, our divisive clustering approach based on approximate edge betweenness centrality is more than two orders of magnitude faster than a competing greedy approach, for a variety of large graph instances on the Sun Fire T2000 multicore system. SNAP also contains parallel implementations of fundamental graph-theoretic kernels and topological analysis metrics (e.g., breadth-first search, connected components, vertex and edge centrality) that are optimized for small- world networks. The SNAP framework is extensible; the graph kernels are modular, portable across shared memory multicore and symmetric multiprocessor systems, and simplify the design of high-level domain-specific applications."
featured: false
publication: "*22nd IEEE International Symposium on Parallel and Distributed Processing, IPDPS 2008, Miami, Florida USA, April 14-18, 2008*"
url_pdf: "https://doi.org/10.1109/IPDPS.2008.4536261"
doi: "10.1109/IPDPS.2008.4536261"
---

