---
title: "Revisiting Edge and Node Parallelism for Dynamic GPU Graph Analytics"
date: 2014-01-01
publishDate: 2019-09-10T12:18:34.384573Z
authors: ["Adam McLaughlin", "David A. Bader"]
publication_types: ["1"]
abstract: "Betweenness Centrality is a widely used graph analytic that has applications such as finding influential people in social networks, analyzing power grids, and studying protein interactions. However, its complexity makes its exact computation infeasible for large graphs of interest. Furthermore, networks tend to change over time, invalidating previously calculated results and encouraging new analyses regarding how centrality metrics vary with time. While GPUs have dominated regular, structured application domains, their high memory throughput and massive parallelism has made them a suitable target architecture for irregular, unstructured applications as well. In this paper we compare and contrast two GPU implementations of an algorithm for dynamic betweenness centrality. We show that typical network updates affect the centrality scores of a surprisingly small subset of the total number of vertices in the graph. By efficiently mapping threads to units of work we achieve up to a 110x speedup over a CPU implementation of the algorithm and can update the analytic 45x faster on average than a static recomputation on the GPU."
featured: false
publication: "*2014 IEEE International Parallel & Distributed Processing Symposium Workshops, Phoenix, AZ, USA, May 19-23, 2014*"
url_pdf: "https://doi.org/10.1109/IPDPSW.2014.157"
doi: "10.1109/IPDPSW.2014.157"
---

