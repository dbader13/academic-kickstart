---
title: "Faster Betweenness Centrality Based on Data Structure Experimentation"
date: 2013-01-01
publishDate: 2019-09-04T10:56:23.646755Z
authors: ["Oded Green", "David A. Bader"]
publication_types: ["2"]
abstract: "Betweenness centrality is a graph analytic that states the importance of a vertex based on the number of shortest paths that it is on. As such, betweenness centrality is a building block for graph analysis tools and is used by many applications, including finding bottlenecks in communication networks and community detection. Computing betweenness centrality is computation- ally demanding, O(V2 + V · E) (for the best known algorithm), which motivates the use of parallelism. Parallelism is especially needed for large graphs with millions of vertices and billions of edges. While the the memory requirements for computing be- tweenness are not as demanding, O(V + E) (for the best known sequential algorithm), these bound increase for different parallel algorithms. We show that is possible to reduce the memory requirements for computing betweenness centrality from O(V + E) to O(V) at the expense of doing additional traversals. We show that not only does this not hurt performance it actually improves performance for coarse grain parallelism. Further, we show that using the new approach allows parallel scaling that previously was not possible. One example is that the new approach is able to scale to 40 x86 cores for a graph with 32M vertices and 2B edges, whereas the previous approach is only able to scale upto 6 cores because of memory requirements. We also do analysis of fine-grain parallel betweenness centrality on both the x86 and the Cray XMT."
featured: false
publication: "*Procedia Computer Science*"
tags: ["Parallel algorithms", "Graph algorithms", "Betweenness Centrality", "Optimizations", "Experimental algorithms"]
url_pdf: "http://www.sciencedirect.com/science/article/pii/S1877050913003463"
doi: "https://doi.org/10.1016/j.procs.2013.05.203"
---

