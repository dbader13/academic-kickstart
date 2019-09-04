---
title: "A faster parallel algorithm and efficient multithreaded implementations for evaluating betweenness centrality on massive datasets"
date: 2009-01-01
publishDate: 2019-09-04T10:56:24.579450Z
authors: ["Kamesh Madduri", "David Ediger", "Karl Jiang", "David A. Bader", "Daniel G. Chavarría-Miranda"]
publication_types: ["1"]
abstract: "We present a new lock-free parallel algorithm for computing betweenness centrality of massive complex networks that achieves better spatial locality compared with previous approaches. Betweenness centrality is a key kernel in analyzing the importance of vertices (or edges) in applications ranging from social networks, to power grids, to the influence of jazz musicians, and is also incorporated into the DARPA HPCS SSCA#2, a benchmark extensively used to evaluate the performance of emerging high-performance computing architectures for graph analytics. We design an optimized implementation of betweenness centrality for the massively multithreaded Cray XMT system with the Thread-storm processor. For a small-world network of 268 million vertices and 2.147 billion edges, the 16-processor XMT system achieves a TEPS rate (an algorithmic performance count for the number of edges traversed per second) of 160 million per second, which corresponds to more than a 2times performance improvement over the previous parallel implementation. We demonstrate the applicability of our implementation to analyze massive real-world datasets by computing approximate betweenness centrality for the large IMDb movie-actor network."
featured: false
publication: "*23rd IEEE International Symposium on Parallel and Distributed Processing, IPDPS 2009, Rome, Italy, May 23-29, 2009*"
url_pdf: "https://doi.org/10.1109/IPDPS.2009.5161100"
doi: "10.1109/IPDPS.2009.5161100"
---

