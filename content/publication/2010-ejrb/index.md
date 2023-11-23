---
title: "Massive streaming data analytics: A case study with clustering coefficients"
date: 2010-01-01
publishDate: 2019-09-10T12:18:35.049107Z
authors: ["David Ediger", "Karl Jiang", "E. Jason Riedy", "David A. Bader"]
publication_types: ["paper-conference"]
abstract: "We present a new approach for parallel massive graph analysis of streaming, temporal data with a dynamic and extensible representation. Handling the constant stream of new data from health care, security, business, and social network applications requires new algorithms and data structures. We examine data structure and algorithm trade-offs that extract the parallelism necessary for high-performance updating analysis of massive graphs. Static analysis kernels often rely on storing input data in a specific structure. Maintaining these structures for each possible kernel with high data rates incurs a significant performance cost. A case study computing clustering coefficients on a general-purpose data structure demonstrates incremental updates can be more efficient than global recomputation. Within this kernel, we compare three methods for dynamically updating local clustering coefficients: a brute-force local recalculation, a sorting algorithm, and our new approximation method using a Bloom filter. On 32 processors of a Cray XMT with a synthetic scale-free graph of 2 24 ≈ 16 million vertices and 2 29 ≈ 537 million edges, the brute-force method processes a mean of over 50 000 updates per second and our Bloom filter approaches 200 000 updates per second."
featured: false
publication: "*24th IEEE International Symposium on Parallel and Distributed Processing, IPDPS 2010, Atlanta, Georgia, USA, 19-23 April 2010 - Workshop Proceedings*"
url_pdf: "https://doi.org/10.1109/IPDPSW.2010.5470687"
doi: "10.1109/IPDPSW.2010.5470687"
---

