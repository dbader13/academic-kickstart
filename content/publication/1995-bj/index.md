---
title: "Parallel Algorithms for Image Histogramming and Connected Components with an Experimental Study"
date: 1995-01-01
publishDate: 2019-09-10T12:18:36.548132Z
authors: ["David A. Bader", "Joseph JáJá"]
publication_types: ["1"]
abstract: "This paper presents efficient and portable implementations of two useful primitives in image processing algorithms, histogramming and connected components. Our general framework is a single-address space, distributed memory programming model. We use efficient techniques for distributing and coalescing data as well as efficient combinations of task and data parallelism. Our connected components algorithm uses a novel approach for parallel merging which performs drastically limited updating during iterative steps, and concludes with a total consistency update at the final step. The algorithms have been coded in Split-C and run on a variety of platforms. Our experimental results are consistent with the theoretical analysis and provide the best known execution times for these two primitives, even when compared with machine-specific implementations. More efficient implementations of Split-C will likely result in even faster execution times."
featured: false
publication: "*Proceedings of the Fifth ACM SIGPLAN Symposium on Principles & Practice of Parallel Programming (PPOPP), Santa Barbara, CA, July 19--21, 1995*"
url_pdf: "https://doi.org/10.1145/209936.209950"
doi: "10.1145/209936.209950"
---

