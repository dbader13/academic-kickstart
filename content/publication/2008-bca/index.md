---
title: "On the Design of Fast Pseudo-Random Number Generators for the Cell Broadband Engine and an Application to Risk Analysis"
date: 2008-01-01
publishDate: 2019-09-10T12:18:35.433035Z
authors: ["David A. Bader", "Aparna Chandramowlishwaran", "Virat Agarwal"]
publication_types: ["1"]
abstract: "Numerical simulations in computational physics, biology, and finance, often require the use of high quality and efficient parallel random number generators. We design and optimize several parallel pseudo random number generators on the cell broadband engine, with minimal correlation between the parallel streams: the linear congruential generator (LCG) with 64-bit prime addend and the Mersenne Twister (MT) algorithm. As compared with current Intel and AMD microprocessors, our Cell/B.E. LCG and MT implementations achieve a speed up of 33 and 29, respectively. We also explore two normalization techniques, Gaussian averaging method and box Mueller polar/cartesian, that transform uniform random numbers to a Gaussian distribution. Using these fast generators we develop a parallel implementation of value at risk, a commonly used model for risk assessment in financial markets. To our knowledge we have designed and implemented the fastest parallel pseudo random number generators on the Cell/B.E."
featured: false
publication: "*2008 International Conference on Parallel Processing, ICPP 2008, September 8-12, 2008, Portland, Oregon, USA*"
url_pdf: "https://doi.org/10.1109/ICPP.2008.41"
doi: "10.1109/ICPP.2008.41"
---

