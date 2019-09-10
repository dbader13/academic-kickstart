---
title: "Advanced Shortest Paths Algorithms on a Massively-Multithreaded Architecture"
date: 2007-01-01
publishDate: 2019-09-10T12:18:35.715275Z
authors: ["Joseph R. Crobak", "Jonathan W. Berry", "Kamesh Madduri", "David A. Bader"]
publication_types: ["1"]
abstract: "We present a study of multithreaded implementations of Thorup's algorithm for solving the single source shortest path (SSSP) problem for undirected graphs. Our implementations leverage the fledgling multithreaded graph library (MTGL) to perform operations such as finding connected components and extracting induced subgraphs. To achieve good parallel performance from this algorithm, we deviate from several theoretically optimal algorithmic steps. In this paper, we present simplifications that perform better in practice, and we describe details of the multithreaded implementation that were necessary for scalability. We study synthetic graphs that model unstructured networks, such as social networks and economic transaction networks. Most of the recent progress in shortest path algorithms relies on structure that these networks do not have. In this work, we take a step back and explore the synergy between an elegant theoretical algorithm and an elegant computer architecture. Finally, we conclude with a prediction that this work will become relevant to shortest path computation on structured networks."
featured: false
publication: "*21th International Parallel and Distributed Processing Symposium (IPDPS 2007), Proceedings, 26-30 March 2007, Long Beach, California, USA*"
url_pdf: "https://doi.org/10.1109/IPDPS.2007.370687"
doi: "10.1109/IPDPS.2007.370687"
---

