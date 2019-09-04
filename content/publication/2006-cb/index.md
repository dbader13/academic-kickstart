---
title: "Designing irregular parallel algorithms with mutual exclusion and lock-free protocols"
date: 2006-01-01
publishDate: 2019-09-04T10:56:26.546491Z
authors: ["Guojing Cong", "David A. Bader"]
publication_types: ["2"]
abstract: "Irregular parallel algorithms pose a significant challenge for achieving high performance because of the difficulty predicting memory access patterns or execution paths. Within an irregular application, fine-grained synchronization is one technique for managing the coordination of work; but in practice the actual performance for irregular problems depends on the input, the access pattern to shared data structures, the relative speed of processors, and the hardware support of synchronization primitives. In this paper, we focus on lock-free and mutual exclusion protocols for handling fine-grained synchronization. Mutual exclusion and lock-free protocols have received a fair amount of attention in coordinating accesses to shared data structures from concurrent processes. Mutual exclusion offers a simple programming abstraction, while lock-free data structures provide better fault tolerance and eliminate problems associated with critical sections such as priority inversion and deadlock. These synchronization protocols, however, are seldom used in parallel algorithm designs, especially for algorithms under the SPMD paradigm, as their implementations are highly hardware dependent and their costs are hard to characterize. Using graph-theoretic algorithms for illustrative purposes, we show experimental results on two shared-memory multiprocessors, the IBM pSeries 570 and the Sun Enterprise 4500, that irregular parallel algorithms with efficient fine-grained synchronization may yield good performance."
featured: false
publication: "*Journal of Parallel and Distributed Computing*"
url_pdf: "https://doi.org/10.1016/j.jpdc.2005.12.004"
doi: "10.1016/j.jpdc.2005.12.004"
---

