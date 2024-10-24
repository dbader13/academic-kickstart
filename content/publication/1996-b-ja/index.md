---
title: "Parallel Algorithms for Image Histogramming and Connected Components with an Experimental Study"
date: 1996-01-01
publishDate: 2019-09-10T12:18:38.246008Z
authors: ["David A. Bader", "Joseph JáJá"]
publication_types: ["article-journal"]
abstract: "This paper presents efficient and portable implementations of two useful primitives in image processing algorithms, histogramming and connected components. Our general framework is a single-address space, distributed memory programming model. We use efficient techniques for distributing and coalescing data as well as efficient combinations of task and data parallelism. Our connected components algorithm uses a novel approach for parallel merging which performs drastically limited updating during iterative steps, and concludes with a total consistency update at the final step. The algorithms have been coded in SPLIT-C and run on a variety of platforms. Our experimental results are consistent with the theoretical analysis and provide the best known execution times for these two primitives, even when compared with machine-specific implementations."
featured: false
publication: "*Journal of Parallel and Distributed Computing*"
url_pdf: "https://doi.org/10.1006/jpdc.1996.0079"
doi: "10.1006/jpdc.1996.0079"
---

