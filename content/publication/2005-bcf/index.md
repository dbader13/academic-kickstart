---
title: "On the Architectural Requirements for Efficient Execution of Graph Algorithms"
date: 2005-01-01
publishDate: 2019-09-10T12:18:36.079763Z
authors: ["David A. Bader", "Guojing Cong", "John Feo"]
publication_types: ["paper-conference"]
abstract: "Combinatorial problems such as those from graph theory pose serious challenges for parallel machines due to non-contiguous, concurrent accesses to global data structures with low degrees of locality. The hierarchical memory systems of symmetric multiprocessor (SMP) clusters optimize for local, contiguous memory accesses, and so are inefficient platforms for such algorithms. Few parallel graph algorithms outperform their best sequential implementation on SMP clusters due to long memory latencies and high synchronization costs. In this paper, we consider the performance and scalability of two graph algorithms, list ranking and connected components, on two classes of shared-memory computers: symmetric multiprocessors such as the Sun Enterprise servers and multithreaded architectures (MTA) such as the Cray MTA-2. While previous studies have shown that parallel graph algorithms can speedup on SMPs, the systems' reliance on cache microprocessors limits performance. The MTA's latency tolerant processors and hardware support for fine-grain synchronization makes performance a function of parallelism. Since parallel graph algorithms have an abundance of parallelism, they perform and scale significantly better on the MTA. We describe and give a performance model for each architecture. We analyze the performance of the two algorithms and discuss how the features of each architecture affects algorithm development, ease of programming, performance, and scalability."
featured: false
publication: "*34th International Conference on Parallel Processing (ICPP 2005), 14-17 June 2005, Oslo, Norway*"
url_pdf: "https://doi.org/10.1109/ICPP.2005.55"
doi: "10.1109/ICPP.2005.55"
---

