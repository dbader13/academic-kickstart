---
title: "Scalable and High Performance Betweenness Centrality on the GPU (Best Student Paper Finalist)"
date: 2014-01-01
publishDate: 2019-09-10T12:18:34.433893Z
authors: ["Adam McLaughlin", "David A. Bader"]
publication_types: ["1"]
abstract: "Graphs that model social networks, numerical simulations, and the structure of the Internet are enormous and cannot be manually inspected. A popular metric used to analyze these networks is between ness centrality, which has applications in community detection, power grid contingency analysis, and the study of the human brain. However, these analyses come with a high computational cost that prevents the examination of large graphs of interest. Prior GPU implementations suffer from large local data structures and inefficient graph traversals that limit scalability and performance. Here we present several hybrid GPU implementations, providing good performance on graphs of arbitrary structure rather than just scale-free graphs as was done previously. We achieve up to 13x speedup on high-diameter graphs and an average of 2.71x speedup overall over the best existing GPU algorithm. We observe near linear speedup and performance exceeding tens of GTEPS when running between ness centrality on 192 GPUs."
featured: true
publication: "*International Conference for High Performance Computing, Networking, Storage and Analysis, SC 2014, New Orleans, LA, USA, November 16-21, 2014*"
url_pdf: "https://doi.org/10.1109/SC.2014.52"
doi: "10.1109/SC.2014.52"
---

