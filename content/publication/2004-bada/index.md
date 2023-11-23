---
title: "An improved, randomized algorithm for parallel selection with an experimental study"
date: 2004-01-01
publishDate: 2019-09-10T12:18:38.046695Z
authors: ["David A. Bader"]
publication_types: ["article-journal"]
abstract: "A common statistical problem is that of finding the median element in a set of data. This paper presents an efficient randomized high-level parallel algorithm for finding the median given a set of elements distributed across a parallel machine. In fact, our algorithm solves the general selection problem that requires the determination of the element of rank k, for an arbitrarily given integer k. Our general framework is an SPMD distributed-memory programming model that is enhanced by a set of communication primitives. We use efficient techniques for distributing and coalescing data as well as efficient combinations of task and data parallelism. The algorithms have been coded in the message-passing standard MPI, and our experimental results from the IBM SP-2 illustrate the scalability and efficiency of our algorithm and improve upon all the related experimental results known to the author. The main contributions of this paper are:  (1) New techniques for speeding the performance of certain randomized algorithms, such as selection, which are efficient with likely probability. (2) A new, practical randomized selection algorithm (UltraFast) with significantly improved convergence."
featured: false
publication: "*Journal of Parallel and Distributed Computing*"
url_pdf: "https://doi.org/10.1016/j.jpdc.2004.06.010"
doi: "10.1016/j.jpdc.2004.06.010"
---

