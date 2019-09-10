---
title: "Practical Parallel Algorithms for Personalized Communication and Integer Sorting"
date: 1996-01-01
publishDate: 2019-09-10T12:18:38.224080Z
authors: ["David A. Bader", "David R. Helman", "Joseph JáJá"]
publication_types: ["2"]
abstract: "A fundamental challenge for parallel computing is to obtain high-level, architecture independent, algorithms which efficiently execute on general-purpose parallel machines. With the emergence of message passing standards such as MPI, it has become easier to design efficient and portable parallel algorithms by making use of these communication primitives. While existing primitives allow an assortment of collective communication routines, they do not handle an important communication event when most or all processors have non-uniformly sized personalized messages to exchange with each other. We focus in this paper on the h-relation personalized communication whose efficient implementation will allow high performance implementations of a large class of algorithms. While most previous h-relation algorithms use randomization, this paper presents a new deterministic approach for h-relation personalized communication with asymptotically optimal complexity for h>p2. As an application, we present an efficient algorithm for stable integer sorting. The algorithms presented in this paper have been coded in Split-C and run on a variety of platforms, including the Thinking Machines CM-5, IBM SP-1 and SP-2, Cray Research T3D, Meiko Scientific CS-2, and the Intel Paragon. Our experimental results are consistent with the theoretical analysis and illustrate the scalability and efficiency of our algorithms across different platforms. In fact, they seem to outperform all similar algorithms known to the authors on these platforms."
featured: false
publication: "*ACM Journal of Experimental Algorithmics*"
url_pdf: "https://doi.org/10.1145/235141.235148"
doi: "10.1145/235141.235148"
---

