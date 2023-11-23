---
title: "A parallel local search framework for the Fixed-Charge Multicommodity Network Flow problem"
date: 2017-01-01
publishDate: 2019-09-10T12:18:36.715572Z
authors: ["Lluís-Miquel Munguía", "Shabbir Ahmed", "David A. Bader", "George L. Nemhauser", "Vikas Goel", "Yufen Shao"]
publication_types: ["article-journal"]
abstract: "We present a parallel local search approach for obtaining high quality solutions to the Fixed Charge Multicommodity Network Flow problem (FCMNF). The approach proceeds by improving a given feasible solution by solving restricted instances of the problem where flows of certain commodities are fixed to those in the solution while the other commodities are locally optimized. We derive multiple independent local search neighborhoods from an arc-based mixed integer programming (MIP) formulation of the problem which are explored in parallel. Our scalable parallel implementation takes advantage of the hybrid memory architecture in modern platforms and the effectiveness of MIP solvers in solving small problems instances. Computational experiments on FCMNF instances from the literature demonstrate the competitiveness of our approach against state of the art MIP solvers and other heuristic methods."
featured: false
publication: "*Computers & Optimization Research*"
url_pdf: "https://doi.org/10.1016/j.cor.2016.07.016"
doi: "10.1016/j.cor.2016.07.016"
---

