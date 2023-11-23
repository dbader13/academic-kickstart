---
title: "Logarithmic Radix Binning and Vectorized Triangle Counting"
date: 2018-01-01
publishDate: 2019-09-10T12:18:33.751024Z
authors: ["Oded Green", "James Fox", "Alex Watkins", "Alok Tripathy", "Kasimir Gabert", "Euna Kim", "Xiaojing An", "Kumar Aatish", "David A. Bader"]
publication_types: ["paper-conference"]
abstract: "Triangle counting is a building block for numerous graph applications and given the fact that graphs continue to grow in size, its scalability is important. As such, numerous algorithms have been designed for triangle counting - some of which are compute-bound rather than memory bound. Even for compute-bound algorithms, one of the key challenges is the limited control flow available on the processor. This is in-part due to the high dependency between the control flow, input data, and limited utilization of vector instructions. Not surprising, compilers are not always able to detect these data dependencies and vectorize the algorithms. Using the branch-avoiding model we show to remove control flow restrictions by replacing branches with an equivalent set of arithmetic operations. More so, we show how these can be vectorized using Intel's AVX-512 instruction set and that our new vectorized algorithms are 2×-5× faster than scalar counterparts. We also present a new load balancing method, Logarithmic Radix Binning (LRB) that ensures that threads and the vector data lanes execute a near equal amount of work at any given time. Altogether, our algorithm outperforms several 2017 HPEC Graph Challenge Champions such as the KOKKOS framework and a GPU based algorithm by anywhere from 1.5× and up to 14×."
featured: false
publication: "*The 22nd Annual IEEE High Performance Extreme Computing Conference, HPEC 2018, Waltham, MA, USA, September 25-27, 2018*"
url_pdf: "https://doi.org/10.1109/HPEC.2018.8547581"
doi: "10.1109/HPEC.2018.8547581"
---

