---
title: "On accelerating iterative algorithms with CUDA: A case study on Conditional Random Fields training algorithm for biological sequence alignment"
date: 2010-01-01
publishDate: 2019-09-10T12:18:35.028758Z
authors: ["Z. Du", "Z. Yin", "W. Liu", "D. Bader"]
publication_types: ["1"]
abstract: "The accuracy of Conditional Random Fields (CRF) is achieved at the cost of huge amount of computation to train model. In this paper we designed the parallelized algorithm for the Gradient Ascent based CRF training methods for biological sequence alignment. Our contribution is mainly on two aspects: 1) We flexibly parallelized the different iterative computation patterns, and the according optimization methods are presented. 2) As for the Gibbs Sampling based training method, we designed a way to automatically predict the iteration round, so that the parallel algorithm could be run in a more efficient manner. In the experiment, these parallel algorithms achieved valuable accelerations comparing to the serial version."
featured: false
publication: "*2010 IEEE International Conference on Bioinformatics and Biomedicine Workshops (BIBMW)*"
url_pdf: "https://doi.org/10.1109/BIBMW.2010.5703859"
doi: "10.1109/BIBMW.2010.5703859"
---

