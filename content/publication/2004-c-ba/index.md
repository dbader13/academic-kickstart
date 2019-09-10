---
title: "The Euler Tour Technique and Parallel Rooted Spanning Tree"
date: 2004-01-01
publishDate: 2019-09-10T12:18:36.266327Z
authors: ["Guojing Cong", "David A. Bader"]
publication_types: ["1"]
abstract: "Many parallel algorithms for graph problems start with finding a spanning tree and rooting the tree to define some structural relationship on the vertices which can be used by following problem specific computations. The generic procedure is to find an unrooted spanning tree and then root the spanning tree using the Euler tour technique. With a randomized work-time optimal unrooted spanning tree algorithm and work-time optimal list ranking, finding rooted spanning trees can be done work-time optimally on EREW PRAM w.h.p. Yet the Euler tour technique assumes as \"given\" a circular adjacency list, it is not without implications though to construct the circular adjacency list for the spanning tree found on the fly by a spanning tree algorithm. In fact our experiments show that this \"hidden\" step of constructing a circular adjacency list could take as much time as both spanning tree and list ranking combined. We present new efficient algorithms that find rooted spanning trees without using the Euler tour technique and incur little or no overhead over the underlying spanning tree algorithms. We also present two new approaches that construct Euler tours efficiently when the circular adjacency list is not given. One is a deterministic PRAM algorithm and the other is a randomized algorithm in the symmetric multiprocessor (SMP) model. The randomized algorithm takes a novel approach for the problems of constructing the Euler tour and rooting a tree. It computes a rooted spanning tree first, then constructs an Euler tour directly for the tree using depth-first traversal. The tour constructed is cache-friendly with adjacent edges in the tour stored in consecutive locations of an array so that prefix-sum (scan) can be used for tree computations instead of the more expensive list-ranking."
featured: false
publication: "*33rd International Conference on Parallel Processing (ICPP 2004), 15-18 August 2004, Montreal, Quebec, Canada*"
url_pdf: "https://doi.org/10.1109/ICPP.2004.1327954"
doi: "10.1109/ICPP.2004.1327954"
---

