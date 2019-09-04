---
title: "Scalable Graph Exploration on Multicore Processors"
date: 2010-01-01
publishDate: 2019-09-04T10:56:24.408542Z
authors: ["Virat Agarwal", "Fabrizio Petrini", "Davide Pasetto", "David A. Bader"]
publication_types: ["1"]
abstract: "Many important problems in computational sciences, social network analysis, security, and business analytics, are data-intensive and lend themselves to graph-theoretical analyses. In this paper we investigate the challenges involved in exploring very large graphs by designing a breadth-first search (BFS) algorithm for advanced multi-core processors that are likely to become the building blocks of future exascale systems. Our new methodology for large-scale graph analytics combines a highlevel algorithmic design that captures the machine-independent aspects, to guarantee portability with performance to future processors, with an implementation that embeds processorspecific optimizations. We present an experimental study that uses state-of-the-art Intel Nehalem EP and EX processors and up to 64 threads in a single system. Our performance on several benchmark problems representative of the power-law graphs found in real-world problems reaches processing rates that are competitive with supercomputing results in the recent literature. In the experimental evaluation we prove that our graph exploration algorithm running on a 4-socket Nehalem EX is (1) 2.4 times faster than a Cray XMT with 128 processors when exploring a random graph with 64 million vertices and 512 millions edges, (2) capable of processing 550 million edges per second with an R-MAT graph with 200 million vertices and 1 billion edges, comparable to the performance of a similar graph on a Cray MTA-2 with 40 processors and (3) 5 times faster than 256 BlueGene/L processors on a graph with average degree 50."
featured: false
publication: "*Conference on High Performance Computing Networking, Storage and Analysis, SC 2010, New Orleans, LA, USA, November 13-19, 2010*"
url_pdf: "https://doi.org/10.1109/SC.2010.46"
doi: "10.1109/SC.2010.46"
---

