---
title: "Scalable Katz Ranking Computation in Large Static and Dynamic Graphs"
date: 2018-01-01
publishDate: 2019-09-10T12:18:33.666766Z
authors: ["Alexander van der Grinten", "Elisabetta Bergamini", "Oded Green", "David A. Bader", "Henning Meyerhenke"]
publication_types: ["paper-conference"]
abstract: "Network analysis defines a number of centrality measures to identify the most central nodes in a network. Fast computation of those measures is a major challenge in algorithmic network analysis. Aside from closeness and betweenness, Katz centrality is one of the established centrality measures. In this paper, we consider the problem of computing rankings for Katz centrality. In particular, we propose upper and lower bounds on the Katz score of a given node. While previous approaches relied on numerical approximation or heuristics to compute Katz centrality rankings, we construct an algorithm that iteratively improves those upper and lower bounds until a correct Katz ranking is obtained. We extend our algorithm to dynamic graphs while maintaining its correctness guarantees. Experiments demonstrate that our static graph algorithm outperforms both numerical approaches and heuristics with speedups between 1.5 x and 3.5 x, depending on the desired quality guarantees. Our dynamic graph algorithm improves upon the static algorithm for update batches of less than 10000 edges. We provide efficient parallel CPU and GPU implementations of our algorithms that enable near real-time Katz centrality computation for graphs with hundreds of millions of nodes in fractions of seconds."
featured: false
publication: "*26th Annual European Symposium on Algorithms, ESA 2018, August 20-22, 2018, Helsinki, Finland*"
url_pdf: "https://doi.org/10.4230/LIPIcs.ESA.2018.42"
doi: "10.4230/LIPIcs.ESA.2018.42"
---

