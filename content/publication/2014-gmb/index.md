---
title: "Load balanced clustering coefficients"
date: 2014-01-01
publishDate: 2019-09-10T12:18:34.399992Z
authors: ["Oded Green", "Lluís-Miquel Munguía", "David A. Bader"]
publication_types: ["paper-conference"]
abstract: "Clustering coefficients is a building block in network sciences that offers insights on how tightly bound vertices are in a network. Effective and scalable parallelization of clustering coefficients requires load balancing amongst the cores. This property is not easy to achieve since many real world networks are scale free, which leads to some vertices requiring more attention than others. In this work we show two scalable approaches that load balance clustering coefficients. The first method achieves optimal load balancing with an Ο(|E|) storage requirement. The second method has a lower storage requirement of Ο(|V|) at the cost of some imbalance. While both methods have a similar time complexity, they represent a tradeoff between maintaining a balanced workload and memory complexity. Using a 40-core system we show that our load balancing techniques outperform the widely used and simple parallel approach by a factor of 3X-7.5X for real graphs and 1.5X-4X for random graphs. Further, we achieve 25X-35X speedup over the sequential algorithm for most of the graphs."
featured: false
publication: "*Proceedings of the first workshop on Parallel programming for analytics applications, PPAA 2014, Orlando, Florida, USA, February 16, 2014*"
url_pdf: "https://doi.org/10.1145/2567634.2567635"
doi: "10.1145/2567634.2567635"
---

