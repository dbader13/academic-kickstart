---
title: "Fast and Adaptive List Intersections on the GPU"
date: 2018-01-01
publishDate: 2019-09-10T12:18:33.728429Z
authors: ["James Fox", "Oded Green", "Kasimir Gabert", "Xiaojing An", "David A. Bader"]
publication_types: ["paper-conference"]
abstract: "List intersections are ubiquitous and can be found in a wide range of applications, including triangle counting and finding the maximal k-truss, both of which are part of the HPEC Static Graph Challenge. For many graph based problems it is necessary to find intersections for a very large number of lists-these lists tend to vary greatly in size and are difficult to efficiently load-balance. Numerous parallel algorithms on list intersections for triangle counting have been proposed, but load-balancing decisions are typically made at a global level. In this paper we present an efficient and adaptive approach to load-balancing at a finer granularity. Our approach assigns a different number of threads for different intersections in order to effectively utilize the resources of the GPU. We show the applicability of our load-balancing method to two different intersection methods, one search-based and one merge-based. Our algorithm outperforms several recent triangle counting algorithms, including recent HPEC Graph Challenge Champions."
featured: false
publication: "*2018 IEEE High Performance Extreme Computing Conference, HPEC 2018, Waltham, MA, USA, September 25-27, 2018*"
url_pdf: "https://doi.org/10.1109/HPEC.2018.8547759"
doi: "10.1109/HPEC.2018.8547759"
---

