---
title: "Numerically approximating centrality for graph ranking guarantees"
date: 2018-01-01
publishDate: 2019-09-10T12:18:36.636993Z
authors: ["Eisha Nathan", "Geoffrey Sanders", "Van Emden Henson", "David A. Bader"]
publication_types: ["article-journal"]
abstract: "Many real-world datasets can be represented as graphs. Using iterative solvers to approximate graph centrality measures allows us to obtain a ranking vector on the nodes of the graph, consisting of a number for each vertex in the graph identifying its relative importance. In this work the centrality measures we use are Katz Centrality and PageRank. Given an approximate solution, we use the residual to accurately estimate how much of the ranking matches the ranking given by the exact solution. Using probabilistic matrix norms, we obtain bounds on the accuracy of the approximation compared to the exact solution with respect to the highly ranked nodes and apply numerical analysis to the computation of centrality with iterative methods. This relates the numerical accuracy of the linear solver to the data analysis accuracy of finding the correct ranking. In particular, we answer the question of which pairwise rankings are reliable given an approximate solution to the linear system. Experiments on many real-world undirected and directed networks up to several million vertices and several hundred million edges validate our theory and show that we are able to accurately estimate large portions of the approximation. We also analyze the difference between global centrality scores and personalized scores (w.r.t. specific seed vertices). By analyzing convergence error, we develop confidence in the ranking schemes of data mining. We show we are able to accurately guarantee ranking of vertices with an approximation to centrality metrics faster than current methods."
featured: false
publication: "*Journal of Computational Science*"
url_pdf: "https://doi.org/10.1016/j.jocs.2018.02.010"
doi: "10.1016/j.jocs.2018.02.010"
---

