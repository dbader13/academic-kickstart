---
title: "Skip the Intersection: Quickly Counting Common Neighbors on Shared-Memory Systems"
date: 2019-01-01
publishDate: 2019-09-18T11:07:24.821235Z
authors: ["Kasimir Gabert", "James Fox", "Oded Green", "Xiaojing An", "David A. Bader"]
publication_types: ["1"]
abstract: "Counting common neighbors between all vertex pairs in a graph is a fundamental operation, with uses in similarity measures, link prediction, graph compression, community detection, and more. Current shared-memory approaches either rely on set intersections or are not readily parallelizable. We introduce a new efficient and parallelizable algorithm to count common neighbors: starting at a wedge endpoint, we iterate through all wedges in the graph, and increment the common neighbor count for each endpoint pair. This exactly counts the common neighbors between all pairs without using set intersections, and as such attains an asymptotic improvement in runtime. Furthermore, our algorithm is simple to implement and only slight modifications are required for existing implementations to use our results. We provide an OpenMP implementation and evaluate it on real-world and synthetic graphs, demonstrating no loss of scalability and an asymptotic improvement. We show intersections are neither necessary nor helpful for computing all pairs common neighbor counts."
featured: false
publication: "*The 23rd Annual IEEE High Performance Extreme Computing Conference (HPEC), Waltham, MA, September 24-26, 2019*"
doi: 10.1109/HPEC.2019.8916307
url_pdf: http://ieeexplore.ieee.org.libdb.njit.edu:8888/stamp/stamp.jsp?tp=&arnumber=8916307&isnumber=8916214
---

