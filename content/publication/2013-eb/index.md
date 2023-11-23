---
title: "Investigating Graph Algorithms in the BSP Model on the Cray XMT"
date: 2013-01-01
publishDate: 2019-09-10T12:18:34.583042Z
authors: ["David Ediger", "David A. Bader"]
publication_types: ["paper-conference"]
abstract: "Implementing parallel graph algorithms in large, shared memory machines, such as the Cray XMT, can be challenging for programmers. Synchronization, deadlock, hot spotting, and others can be barriers to obtaining linear scalability. Alternative programming models, such as the bulk synchronous parallel programming model used in Google's Pregel, have been proposed for large graph analytics. This model eases programmer complexity by eliminating deadlock and simplifying data sharing. We investigate the algorithmic effects of the BSP model for graph algorithms and compare performance and scalability with hand-tuned, open source software using GraphCT. We analyze the innermost iterations of these algorithms to understand the differences in scalability between BSP and shared memory algorithms. We show that scalable performance can be obtained with graph algorithms in the BSP model on the Cray XMT. These algorithms perform within a factor of 10 of hand-tuned C code."
featured: false
publication: "*2013 IEEE International Symposium on Parallel & Distributed Processing, Workshops and Phd Forum, Cambridge, MA, USA, May 20-24, 2013*"
url_pdf: "https://doi.org/10.1109/IPDPSW.2013.107"
doi: "10.1109/IPDPSW.2013.107"
---

