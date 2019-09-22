---
title: "A Fast, Parallel Spanning Tree Algorithm for Symmetric Multiprocessors (SMPs)"
date: 2004-01-01
publishDate: 2019-09-10T12:18:36.283159Z
authors: ["David A. Bader", "Guojing Cong"]
publication_types: ["1"]
abstract: "We focus on implementing parallel spanning tree algorithms on SMPs. Spanning tree is an important problem in the sense that it is the building block for many other parallel graph algorithms and also because it is representative of a large class of irregular combinatorial problems that have simple and efficient sequential implementations and fast PRAM algorithms, but often have no known efficient parallel implementations. Experimental studies have been conducted on related problems (minimum spanning tree and connected components) using parallel computers, but only achieved reasonable speedup on regular graph topologies that can be implicitly partitioned with good locality features or on very dense graphs with limited numbers of vertices. We present a new randomized algorithm and implementation with superior performance that for the first-time achieves parallel speedup on arbitrary graphs (both regular and irregular topologies) when compared with the best sequential implementation for finding a spanning tree. This new algorithm uses several techniques to give an expected running time that scales linearly with the number p of processors for suitably large inputs (n>p/sup 2/). As the spanning tree problem is notoriously hard for any parallel implementation to achieve reasonable speedup, our study may shed new light on implementing PRAM algorithms for shared-memory parallel computers. The source code for these algorithms is freely-available from our Web site hpc.ece.unm.edu."
featured: false
publication: "*18th International Parallel and Distributed Processing Symposium (IPDPS 2004), 26-30 April 2004, Santa Fe, NM*"
url_pdf: "https://doi.org/10.1109/IPDPS.2004.1302951"
doi: "10.1109/IPDPS.2004.1302951"
---

