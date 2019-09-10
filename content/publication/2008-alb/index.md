---
title: "Financial modeling on the cell broadband engine"
date: 2008-01-01
publishDate: 2019-09-10T12:18:35.451712Z
authors: ["Virat Agarwal", "Lurng-Kuo Liu", "David A. Bader"]
publication_types: ["1"]
abstract: "High performance computing is critical for financial markets where analysts seek to accelerate complex optimizations such as pricing engines to maintain a competitive edge. In this paper we investigate the performance of financial workloads on the Sony-Toshiba- IBM Cell Broadband Engine, a heterogeneous multicore chip architected for intensive gaming applications and high performance computing. We analyze the use of Monte Carlo techniques for financial workloads and design efficient parallel implementations of different high performance pseudo and quasi random number generators as well as normalization techniques. Our implementation of the Mersenne Twister pseudo random number generator outperforms current Intel and AMD architectures by over an order of magnitude. Using these new routines, we optimize European option (EO) and collateralized debt obligation (CDO) pricing algorithms. Our Cell-optimized EO pricing achieves a speedup of over 2 in comparison with using RapidMind SDK for Cell, and comparing with GPU, a speedup of 1.26 as compared with using RapidMind SDK for GPU (NVIDIA GeForce 8800), and a speedup of 1.51 over NVIDIA GeForce 8800 (using CUDA). Our detailed analyses and performance results demonstrate that the Cell/B.E. processor is well suited for financial workloads and Monte Carlo simulation."
featured: false
publication: "*22nd IEEE International Symposium on Parallel and Distributed Processing, IPDPS 2008, Miami, Florida USA, April 14-18, 2008*"
url_pdf: "https://doi.org/10.1109/IPDPS.2008.4536320"
doi: "10.1109/IPDPS.2008.4536320"
---

