---
title: "Parallel Community Detection for Massive Graphs"
date: 2013-01-01
publishDate: 2019-09-18T11:07:24.324308Z
authors: ["E. Jason Riedy", "Henning Meyerhenke", "David Ediger", "David A. Bader"]
publication_types: ["chapter"]
abstract: "Tackling the current volume of graph-structured data requires parallel tools. We extend our work on analyzing such massive graph data with a massively parallel algorithm for community detection that scales to current data sizes, clustering a real-world graph of over 100 million vertices and over 3 billion edges in under 500 seconds on a four-processor Intel E7-8870-based server. Our algorithm achieves moderate parallel scalability without sacrificing sequential operational complexity. Community detection partitions a graph into subgraphs more densely connected within the subgraph than to the rest of the graph. We take an agglomerative approach similar to Clauset, Newman, and Moore’s sequential algorithm, merging pairs of connected intermediate subgraphs to optimize different graph properties. Working in parallel opens new approaches to high performance. We improve performance of our parallel community detection algorithm on both the Cray XMT2 and OpenMP platforms and adapt our algorithm to the DIMACS Implementation Challenge data set."
featured: false
publication: "*Graph Partitioning and Graph Clustering*"
url_pdf: "https://dx.doi.org/10.1090/conm/588/11703"
doi: "10.1090/conm/588/11703"
---

