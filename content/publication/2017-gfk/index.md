---
title: "Quickly finding a truss in a haystack"
date: 2017-01-01
publishDate: 2019-09-10T12:18:33.879185Z
authors: ["Oded Green", "James Fox", "Euna Kim", "Federico Busato", "Nicola Bombieri", "Kartik Lakhotia", "Shijie Zhou", "Shreyas G. Singapura", "Hanqing Zeng", "Rajgopal Kannan", "Viktor K. Prasanna", "David A. Bader"]
publication_types: ["paper-conference"]
abstract: "The k-truss of a graph is a subgraph such that each edge is tightly connected to the remaining elements in the k-truss. The k-truss of a graph can also represent an important community in the graph. Finding the k-truss of a graph can be done in a polynomial amount of time, in contrast finding other subgraphs such as cliques. While there are numerous formulations and algorithms for finding the maximal k-truss of a graph, many of these tend to be computationally expensive and do not scale well. Many algorithms are iterative and use static graph triangle counting in each iteration of the graph. In this work we present a novel algorithm for finding both the k-truss of the graph (for a given k), as well as the maximal k-truss using a dynamic graph formulation. Our algorithm has two main benefits. 1) Unlike many algorithms that rerun the static graph triangle counting after the removal of non-conforming edges, we use a new dynamic graph formulation that only requires updating the edges affected by the removal. As our updates are local, we only do a fraction of the work compared to the other algorithms. 2) Our algorithm is extremely scalable and is able to concurrently detect deleted triangles in contrast to past sequential approaches. While our algorithm is architecture independent, we show a CUDA based implementation for NVIDIA GPUs. In numerous instances, our new algorithm is anywhere from 100X-10000X faster than the Graph Challenge benchmark. Furthermore, our algorithm shows significant speedups, in some cases over 70X, over a recently developed sequential and highly optimized algorithm."
featured: false
publication: "*The 21st Annual IEEE High Performance Extreme Computing Conference, HPEC 2017, Waltham, MA, USA, September 12-14, 2017*"
url_pdf: "https://doi.org/10.1109/HPEC.2017.8091038"
doi: "10.1109/HPEC.2017.8091038"
---

{{<figure src="certificate.jpg">}}
