---
title: "A fast, energy-efficient abstraction for simultaneous breadth-first searches"
date: 2015-01-01
publishDate: 2019-09-04T10:56:23.241976Z
authors: ["Adam McLaughlin", "E. Jason Riedy", "David A. Bader"]
publication_types: ["1"]
abstract: "Optimized GPU kernels are sufficiently complicated to write that they often are specialized to input data, target architectures, or applications. This paper presents a multi-search abstraction for computing multiple breadth-first searches in parallel and demonstrates a high-performance, general implementation. Our abstraction removes the burden of orchestrating graph traversal from the user while providing high performance and low energy usage, an often overlooked component of algorithm design. Energy consumption has become a first-class hardware design constraint for both massive and embedded computing platforms. Our abstraction can be applied to such problems as the all-pairs shortest-path problem, community detection, reachability querying, and others. To map graph traversal efficiently to the GPU, our hybrid implementation chooses between processing active vertices with a single thread or an entire warp based on vertex outdegree. For a set of twelve varied graphs, the implementation of our abstraction saves 42% time and 62% energy on average compared to representative implementations of specific applications from existing literature."
featured: false
publication: "*The 19th Annual IEEE High Performance Extreme Computing Conference, HPEC 2015, Waltham, MA, USA, September 15-17, 2015*"
url_pdf: "https://doi.org/10.1109/HPEC.2015.7322466"
doi: "10.1109/HPEC.2015.7322466"
---

