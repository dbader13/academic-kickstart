---
title: "Exact and Parallel Triangle Counting in Dynamic Graphs"
date: 2017-01-01
publishDate: 2019-09-10T12:18:33.863983Z
authors: ["Devavret Makkar", "David A. Bader", "Oded Green"]
publication_types: ["1"]
abstract: "Triangle counting is an important building block for finding key players in a graph. It is an integral part of the popular clustering coefficient analytic and can be used for pattern matching in social networks. A triangle, which is also a 3-clique, represents a strong connection between three players that are all connected. While counting triangles is not overly expensive from a computational standpoint, especially in comparison to centrality metrics (such as betweenness centrality and closeness centrality), it can still prove to be prohibitive for large scale networks, especially for those with a power-law distribution. This problem only deepens for dynamic graphs where the network is constantly changing, requiring constant updating of the graph and the analytic. In this paper, we present a new dynamic graph algorithm for counting triangles that is based on an inclusion-exclusion formulation. While our algorithm is independent of the computing platform, we show performance results on an NVIDIA GPU. Our approach handles 32 million updates per second, or up to 11 million updates per second if the graph data structure is also updated. In past approaches, when a vertex was affected due to an edge insertion or deletion, it was necessary to find the triangles from scratch for that given vertex. Our new formulation does not need this and only requires considering the affected edges. As such our algorithm is typically several hundred times faster than the past approach - in some cases up to 819X faster."
featured: false
publication: "*24th IEEE International Conference on High Performance Computing, HiPC 2017, Jaipur, India, December 18-21, 2017*"
url_pdf: "https://doi.org/10.1109/HiPC.2017.00011"
doi: "10.1109/HiPC.2017.00011"
---

