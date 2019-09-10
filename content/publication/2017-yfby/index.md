---
title: "Designing and implementing a heuristic cross-architecture combination for graph traversal"
date: 2017-01-01
publishDate: 2019-09-10T12:18:36.743855Z
authors: ["Yang You", "Haohuan Fu", "David A. Bader", "Guangwen Yang"]
publication_types: ["2"]
abstract: "Breadth-First Search (BFS) is widely used in real-world applications including computational biology, social networks, and electronic design automation. The most effective BFS approach has been shown to be a combination of top-down and bottom-up approaches. Such hybrid techniques need to identify a switching point which is conventionally found through expensive trial-and-error and exhaustive search routines. We present an adaptive method based on regression analysis that enables dynamic switching at runtime with little overhead. We improve the performance of our method by exploiting popular heterogeneous platforms and efficiently design the approach for a given architecture. A 155x speedup is achieved over the standard top-down approach on GPUs. Our approach is the first to combine top-down and bottom-up across different architectures. Unlike combination on a single architecture, a mistuned switching point may significantly decrease the performance of cross-architecture combination. Our adaptive method can predict the switching point with high accuracy, leading to 7x speedup compared to the switching point in average case (1000 switching points)."
featured: false
publication: "*Journal of Parallel and Distributed Computing*"
url_pdf: "https://doi.org/10.1016/j.jpdc.2016.05.007"
doi: "10.1016/j.jpdc.2016.05.007"
---

