---
title: "Parallel Shortest Path Algorithms for Solving Large-Scale Instances"
date: 2006-01-01
publishDate: 2019-09-10T12:18:35.809849Z
authors: ["Kamesh Madduri", "David A. Bader", "Jonathan W. Berry", "Joseph R. Crobak"]
publication_types: ["1"]
abstract: "We present an experimental study of parallel algorithms for solving the single source shortest path problem with non-negative edge weights (NSSP) on large-scale graphs. We implement Meyer and Sander’s ∆-stepping algorithm and report performance results on the Cray MTA-2, a multithreaded parallel architecture. The MTA-2 is a high-end shared memory system offering two unique features that aid the efficient implementation of irregular parallel graph algorithms: the ability to exploit fine-grained parallelism, and low-overhead synchronization primitives. Our implementation exhibits remarkable parallel speedup when compared with a competitive sequential algorithm, for low-diameter sparse graphs. For instance, ∆-stepping on a directed scale-free graph of 100 million vertices and 1 billion edges takes less than ten seconds on 40 processors of the MTA-2, with a relative speedup of close to 30. To our knowledge, these are the first performance results of a shortest path problem on realistic graph instances in the order of billions of vertices and edges."
featured: false
publication: "*The Shortest Path Problem: Ninth DIMACS Implementation Challenge*"
url_pdf: "https://doi.org/10.1090/dimacs/074/10"
doi: "10.1090/dimacs/074/10"
---

