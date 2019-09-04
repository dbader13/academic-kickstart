---
title: "An Experimental Study of Parallel Biconnected Components Algorithms on Symmetric Multiprocessors (SMPs)"
date: 2005-01-01
publishDate: 2019-09-04T10:56:25.281802Z
authors: ["Guojing Cong", "David A. Bader"]
publication_types: ["1"]
abstract: "We present an experimental study of parallel biconnected components algorithms employing several fundamental parallel primitives, e.g., prefix sum, list ranking, sorting, connectivity, spanning tree, and tree computations. Previous experimental studies of these primitives demonstrate reasonable parallel speedups. However, when these algorithms are used as subroutines to solve higher-level problems, there are two factors that hinder fast parallel implementations. One is parallel overhead, i.e., the large constant factors hidden in the asymptotic bounds; the other is the discrepancy among the data structures used in the primitives that brings non-negligible conversion cost. We present various optimization techniques and a new parallel algorithm that significantly improve the performance of finding biconnected components of a graph on symmetric multiprocessors (SMPs). Finding biconnected components has application in fault-tolerant network design, and is also used in graph planarity testing. Our parallel implementation achieves speedups up to 4 using 12 processors on a Sun E4500 for large, sparse graphs, and the source code is freely-available at our Web site."
featured: false
publication: "*19th International Parallel and Distributed Processing Symposium (IPDPS 2005), 4-8 April 2005, Denver, CO, USA*"
url_pdf: "https://doi.org/10.1109/IPDPS.2005.100"
doi: "10.1109/IPDPS.2005.100"
---

