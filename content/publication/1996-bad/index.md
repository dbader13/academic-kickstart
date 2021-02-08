---
title: "On the Design and Analysis of Practical Parallel Algorithms for Combinatorial Problems with Applications to Image Processing"
date: 1996-01-01
publishDate: 2019-09-18T11:07:24.618371Z
authors: ["David A. Bader"]
publication_types: ["7"]
abstract: "A fundamental challenge for parallel computing is to obtain high-level, architecture independent, algorithms which efficiently execute on general-purpose parallel machines. With the emergence of message passing standards such as MPI, it has become easier to design portable parallel algorithms making use of these primitives. We introduce a number of techniques that allow us to derive scalable and efficient algorithms for data communication, solving combinatorial problems, and image processing applications. These algorithms have been coded in SPLIT-C, a parallel extension of the C programming language which follows the SPMD (single program multiple data) paradigm, and run on a variety of parallel machines, such as, the Cray Research T3D, IBM SP-2, TMC CM-5, Intel Paragon, Meiko Scientific CS-2, and clusters of workstations. Our experimental results are consistent with the theoretical analyses and illustrate the scalability and efficiency of our algorithms across different platforms. The code is portable; that is, it is written independently of low-level primitives reflecting machine architecture or size. In addition, our implementations seem to outperform all similar known algorithms, both native or portable, on these same platforms. This dissertation presents a range of efficient parallel algorithms with experimental studies. The data communication primitives addressed include the MPI-like primitives such as transpose, broadcast, reduce, combine, gather, and scatter, as well as more general communication algorithms such as dynamic data redistribution and personalized communication. Building on these primitives, we develop efficient parallel algorithms for combinatorial problems such as selection, median finding, and sorting. We also discuss image processing applications including histogramming, connected components, enhancement, and segmentation."
featured: false
publication: ""
url_pdf: "https://dl.acm.org/citation.cfm?id=923668"
---

