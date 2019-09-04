---
title: "Parallel Methods for Verifying the Consistency of Weakly-Ordered Architectures"
date: 2015-01-01
publishDate: 2019-09-04T10:56:23.204432Z
authors: ["Adam McLaughlin", "Duane Merrill", "Michael Garland", "David A. Bader"]
publication_types: ["1"]
abstract: "Contemporary microprocessors use relaxed memory consistency models to allow for aggressive optimizations in hardware. This enhancement in performance comes at the cost of design complexity and verification effort. In particular, verifying an execution of a program against its system's memory consistency model is an NP-complete problem. Several graph-based approximations to this problem based on carefully constructed randomized test programs have been proposed in the literature, however, such approaches are sequential and execute slowly on large graphs of interest. Unfortunately, the ability to execute larger tests is tremendously important, since such tests enable one to expose bugs more quickly. Successfully executing more tests per unit time is also desirable, since it allows for one to check for a greater variety of errors in the memory subsystem by utilizing a more diverse set of tests. This paper improves upon existing work by introducing an algorithm that not only reduces the time complexity of the verification process, but also facilitates the development of parallel algorithms for solving these problems. We first show performance improvements from a sequential approach and gain further performance from parallel implementations in OpenMP and CUDA. For large tests of interest, our GPU implementation achieves an average application speedup of 26.36x over existing techniques in use at NVIDIA."
featured: false
publication: "*2015 International Conference on Parallel Architectures and Compilation, PACT 2015, San Francisco, CA, USA, October 18-21, 2015*"
url_pdf: "https://doi.org/10.1109/PACT.2015.18"
doi: "10.1109/PACT.2015.18"
---

