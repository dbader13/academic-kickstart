---
title: "A Linear-Time Algorithm for Computing Inversion Distance Between Two Signed Permutations with an Experimental Study"
date: 2001-01-01
publishDate: 2019-09-10T12:18:38.138439Z
authors: ["David A. Bader", "Bernard M. E. Moret", "Mi Yan"]
publication_types: ["article-journal"]
abstract: "Hannenhalli and Pevzner gave the first polynomial-time algorithm for computing the inversion distance between two signed permutations, as part of the larger task of determining the shortest sequence of inversions needed to transform one permutation into the other. Their algorithm (restricted to distance calculation) proceeds in two stages: in the first stage, the overlap graph induced by the permutation is decomposed into connected components, then in the second stage certain graph structures (hurdles and others) are identified. Berman and Hannenhalli avoided the explicit computation of the overlap graph and gavean O(na(n)) algorithm, based on a Union-Find structure, to find its connected components, where a is the inverse Ackerman function. Since for all practical purposes a(n) is a constant no larger than four, this algorithm has been the fastest practical algorithm to date. In this paper, we present a new linear-time algorithm for computing the connected components, which is more efficient than that of Berman and Hannenhalli in both theory and practice. Our algorithm uses only a stack and is very easy to implement. We give the results of computational experiments over a large range of permutation pairs produced through simulated evolution; our experiments show a speed-up by a factor of 2 to 5 in the computation of the connected components and by a factor of 1.3 to 2 in the overall distance computation."
featured: false
publication: "*Journal of Computational Biology*"
url_pdf: "https://doi.org/10.1089/106652701753216503"
doi: "10.1089/106652701753216503"
---

