---
title: "Parallel Algorithms for Evaluating Centrality Indices in Real-world Networks"
date: 2006-01-01
publishDate: 2019-09-04T10:56:25.141806Z
authors: ["David A. Bader", "Kamesh Madduri"]
publication_types: ["1"]
abstract: "This paper discusses fast parallel algorithms for evaluating several centrality indices frequently used in complex network analysis. These algorithms have been optimized to exploit properties typically observed in real-world large scale networks, such as the low average distance, high local density, and heavy-tailed power law degree distributions. We test our implementations on real datasets such as the Web graph, protein-interaction networks, movie-actor and citation networks, and report impressive parallel performance for evaluation of the computationally intensive centrality metrics (betweenness and closeness centrality) on high-end shared memory symmetric multiprocessor and multithreaded architectures. To our knowledge, these are the first parallel implementations of these widely-used social network analysis metrics. We demonstrate that it is possible to rigorously analyze networks three orders of magnitude larger than instances that can be handled by existing network analysis (SNA) software packages. For instance, we compute the exact betweenness centrality value for each vertex in a large US patent citation network (3 million patents, 16 million citations) in 42 minutes on 16 processors, utilizing 20GB RAM of the IBM p5 570. SNA packages on the other hand cannot handle graphs with more than hundred thousand edges"
featured: false
publication: "*2006 International Conference on Parallel Processing (ICPP 2006), 14-18 August 2006, Columbus, Ohio, USA*"
url_pdf: "https://doi.org/10.1109/ICPP.2006.57"
doi: "10.1109/ICPP.2006.57"
---

