---
title: "A Randomized Parallel Sorting Algorithm with an Experimental Study"
date: 1998-01-01
publishDate: 2019-09-10T12:18:38.203626Z
authors: ["David R. Helman", "David A. Bader", "Joseph JáJá"]
publication_types: ["2"]
abstract: "Previous schemes for sorting on general-purpose parallel machines have had to choose between poor load balancing and irregular communication or multiple rounds of all-to-all personalized communication. In this paper, we introduce a novel variation on sample sort which uses only two rounds of regular all-to-all personalized communication in a scheme that yields very good load balancing with virtually no overhead. Moreover, unlike previous variations, our algorithm efficiently handles the presence of duplicate values without the overhead of tagging each element with a unique identifier. This algorithm was implemented in Split-C and run on a variety of platforms, including the Thinking Machines CM-5, the IBM SP-2, and the Cray Research T3D. We ran our code using widely different benchmarks to examine the dependence of our algorithm on the input distribution. Our experimental results illustrate the efficiency and scalability of our algorithm across different platforms. In fact, it seems to outperform all similar algorithms known to the authors on these platforms, and its performance is invariant over the set of input distributions unlike previous efficient algorithms. Our results also compare favorably with those reported for the simpler ranking problem posed by the NAS Integer Sorting (IS) Benchmark."
featured: false
publication: "*Journal of Parallel and Distributed Computing*"
url_pdf: "10.1006/jpdc.1998.1462"
doi: "10.1006/jpdc.1998.1462"
---

