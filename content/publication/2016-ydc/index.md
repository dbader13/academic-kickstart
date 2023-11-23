---
title: "A New Parallel Method for Binary Black Hole Simulations"
date: 2016-01-01
publishDate: 2019-09-10T12:18:36.974042Z
authors: ["Quan Yang", "Zhihui Du", "Zhou-Jian Cao", "Jian Tao", "David A. Bader"]
publication_types: ["article-journal"]
abstract: "Simulating binary black hole (BBH) systems are a computationally intensive problem and it can lead to great scientific discovery. How to explore more parallelism to take advantage of the large number of computing resources of modern supercomputers is the key to achieve high performance for BBH simulations. In this paper, we propose a scalable MPM (Mesh based Parallel Method) which can explore both the inter- and intramesh level parallelism to improve the performance of BBH simulation. At the same time, we also leverage GPU to accelerate the performance. Different kinds of performance tests are conducted on Blue Waters. Compared with the existing method, our MPM can improve the performance from 5x speedup (compared with the normalized speed of 32 MPI processes) to 8x speedup. For the GPU accelerated version, our MPM can improve the performance from 12x speedup to 28x speedup. Experimental results also show that when only enough CPU computing resource or limited GPU computing resource is available, our MPM can employ two special scheduling mechanisms to achieve better performance. Furthermore, our scalable GPU acceleration MPM can achieve almost ideal weak scaling up to 2048 GPU computing nodes which enables our software to handle even larger BBH simulations efficiently."
featured: false
publication: "*Scientific Programming*"
url_pdf: "https://doi.org/10.1155/2016/2360492"
doi: "10.1155/2016/2360492"
---

