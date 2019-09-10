---
title: "Generalizing k-Betweenness Centrality Using Short Paths and a Parallel Multithreaded Implementation"
date: 2009-01-01
publishDate: 2019-09-10T12:18:35.239931Z
authors: ["Karl Jiang", "David Ediger", "David A. Bader"]
publication_types: ["1"]
abstract: "We present a new parallel algorithm that extends and generalizes the traditional graph analysis metric of betweenness centrality to include additional non-shortest paths according to an input parameter k. Betweenness centrality is a useful kernel for analyzing the importance of vertices or edges in a graph and has found uses in social networks, biological networks, and power grids, among others. k-betweenness centrality captures the additional information provided by paths whose length is within k units of the shortest path length. These additional paths provide robustness that is not captured in traditional betweenness centrality computations, and they may become important shortest paths if key edges are missing in the data. We implement our parallel algorithm using lock-free methods on a massively multithreaded Cray XMT. We apply this implementation to a real-world data set of pages on the World Wide Web and show the importance of the additional data incorporated by our algorithm."
featured: false
publication: "*ICPP 2009, International Conference on Parallel Processing, Vienna, Austria, 22-25 September 2009*"
url_pdf: "https://doi.org/10.1109/ICPP.2009.76"
doi: "10.1109/ICPP.2009.76"
---

