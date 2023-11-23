---
title: "GTfold: a scalable multicore code for RNA secondary structure prediction"
date: 2009-01-01
publishDate: 2019-09-10T12:18:35.364679Z
authors: ["Amrita Mathuriya", "David A. Bader", "Christine E. Heitsch", "Stephen C. Harvey"]
publication_types: ["paper-conference"]
abstract: "The prediction of the correct secondary structures of large RNAs is one of the unsolved challenges of computational molecular biology. Among the major obstacles is the fact that accurate calculations scale as O(n4), so the computational requirements become prohibitive as the length increases. Existing folding programs implement heuristics and approximations to overcome these limitations. We present a new parallel multicore and scalable program called GTfold, which is one to two orders of magnitude faster than the de facto standard programs and achieves comparable accuracy of prediction. Development of GTfold opens up a new path for the algorithmic improvements and application of an improved thermodynamic model to increase the prediction accuracy.  In this paper we analyze the algorithm's concurrency and describe the parallelism for a shared memory environment such as a symmetric multiprocessor or multicore chip. In a remarkable demonstration, GTfold now optimally folds 11 picornaviral RNA sequences ranging from 7100 to 8200 nucleotides in 8 minutes, compared with the two months it took in a previous study. We are seeing a paradigm shift to multicore chips and parallelism must be explicitly addressed to continue gaining performance with each new generation of systems. We also show that the exact algorithms like internal loop speedup can be implemented with our method in an affordable amount of time. GTfold is freely available as open source from our website."
featured: false
publication: "*Proceedings of the 2009 ACM Symposium on Applied Computing (SAC), Honolulu, Hawaii, USA, March 9-12, 2009*"
url_pdf: "https://doi.org/10.1145/1529282.1529497"
doi: "10.1145/1529282.1529497"
---

