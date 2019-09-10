---
title: "Fast shared-memory algorithms for computing the minimum spanning forest of sparse graphs"
date: 2006-01-01
publishDate: 2019-09-10T12:18:37.921909Z
authors: ["David A. Bader", "Guojing Cong"]
publication_types: ["2"]
abstract: "Minimum spanning tree (MST) is one of the most studied combinatorial problems with practical applications in VLSI layout, wireless communication, and distributed networks, recent problems in biology and medicine such as cancer detection, medical imaging, and proteomics, and national security and bioterrorism such as detecting the spread of toxins through populations in the case of biological/chemical warfare. Most of the previous attempts for improving the speed of MST using parallel computing are too complicated to implement or perform well only on special graphs with regular structure. In this paper we design and implement four parallel MST algorithms (three variations of Borůvka plus our new approach) for arbitrary sparse graphs that for the first time give speedup when compared with the best sequential algorithm. In fact, our algorithms also solve the minimum spanning forest problem. We provide an experimental study of our algorithms on symmetric multiprocessors such as IBMs pSeries and Sun's Enterprise servers. Our new implementation achieves good speedups over a wide range of input graphs with regular and irregular structures, including the graphs used by previous parallel MST studies. For example, on an arbitrary random graph with 1M vertices and 20M  edges, our new approach achieves a speedup of 5 using 8 processors. The source code for these algorithms is freely available from our web site."
featured: false
publication: "*Journal of Parallel and Distributed Computing*"
url_pdf: "https://doi.org/10.1016/j.jpdc.2006.06.001"
doi: "10.1016/j.jpdc.2006.06.001"
---

