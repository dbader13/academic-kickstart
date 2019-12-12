---
title: "A Linear Time Algorithm for Finding Minimum Spanning Tree Replacement Edges"
date: 2019-01-01
publishDate: 2019-09-10T12:18:36.583089Z
authors: ["David A. Bader", "Paul Burkhardt"]
publication_types: ["2"]
abstract: "Given an undirected, weighted graph, the minimum spanning tree (MST) is a tree that connects all of the vertices of the graph with minimum sum of edge weights. In real world applications, network designers often seek to quickly find a replacement edge for each edge in the MST. For example, when a traffic accident closes a road in a transportation network, or a line goes down in a communication network, the replacement edge may reconnect the MST at lowest cost. In the paper, we consider the case of finding the lowest cost replacement edge for each edge of the MST. A previous algorithm by Tarjan takes $O(m \alpha(n, m))$ time, where $\alpha(n, m)$ is the inverse Ackermann's function. Our algorithm is the first that runs in $O(n + m)$ time and $O(n + m)$ space. Moreover, it is easy to implement and our experimental study demonstrates fast performance on several types of graphs. The most vital edge is the graph edge whose removal causes the largest increase in weight of the minimum spanning tree. Our algorithm also finds the most vital edge in linear time."
featured: false
publication: "*arXiv e-prints*"
url_preprint: "http://arxiv.org/abs/1908.03473"

---

