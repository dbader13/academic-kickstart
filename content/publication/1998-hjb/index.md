---
title: "A New Deterministic Parallel Sorting Algorithm with an Experimental Evaluation"
date: 1998-01-01
publishDate: 2019-09-10T12:18:38.187813Z
authors: ["David R. Helman", "Joseph JáJá", "David A. Bader"]
publication_types: ["2"]
abstract: "We introduce a new deterministic parallel sorting algorithm for distributed memory machines based on the regular sampling approach. The algorithm uses only two rounds of regular all-to-all personalized communication in a scheme that yields very good load balancing with virtually no overhead. Moreover, unlike previous variations, our algorithm efficiently handles the presence of duplicate values without the overhead of tagging each element with a unique identifier. This algorithm was implemented in SPLIT-C and run on a variety of platforms, including the Thinking Machines CM-5, the IBM SP-2-WN, and the Cray Research T3D. We ran our code using widely different benchmarks to examine the dependence of our algorithm on the input distribution. Our experimental results illustrate the efficiency and scalability of our algorithm across different platforms. In fact, the performance compares closely to that of our random sample sort algorithm, which seems to outperform all similar algorithms known to the authors on these platforms. Together, their performance is nearly invariant over the set of input distributions, unlike previous efficient algorithms. However, unlike our randomized sorting algorithm, the performance and memory requirements of our regular sorting algorithm can be deterministically guaranteed."
featured: false
publication: "*ACM Journal of Experimental Algorithmics*"
url_pdf: "https://doi.org/10.1145/297096.297128"
doi: "10.1145/297096.297128"
---

