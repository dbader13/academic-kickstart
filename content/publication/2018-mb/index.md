---
title: "Accelerating GPU betweenness centrality"
date: 2018-01-01
publishDate: 2019-09-04T10:56:25.673038Z
authors: ["Adam McLaughlin", "David A. Bader"]
publication_types: ["2"]
abstract: "Graphs that model social networks, numerical simulations, and the structure of the Internet are enormous and cannot be manually inspected. A popular metric used to analyze these networks is Betweenness Centrality (BC), which has applications in community detection, power grid contingency analysis, and the study of the human brain. However, these analyses come with a high computational cost that prevents the examination of large graphs of interest. Recently, the use of Graphics Processing Units (GPUs) has been promising for efficient processing of unstructured data sets. Prior GPU implementations of BC suffer from large local data structures and inefficient graph traversals that limit scalability and performance. Here we present a hybrid GPU implementation that provides good performance on graphs of arbitrary structure rather than just scale-free graphs as was done previously. Our methods achieve up to 13× speedup on high-diameter graphs and an average of 2.71× speedup overall compared to the best existing GPU algorithm. We also observe near linear speedup when running BC on 192 GPUs."
featured: false
publication: "*Communications of the ACM*"
url_pdf: "https://doi.org/10.1145/3230485"
doi: "10.1145/3230485"
---

