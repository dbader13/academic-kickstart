---
title: "Optimizing JPEG2000 Still Image Encoding on the Cell Broadband Engine"
date: 2008-01-01
publishDate: 2019-09-04T10:56:24.651032Z
authors: ["Seunghwa Kang", "David A. Bader"]
publication_types: ["1"]
abstract: "JPEG2000 is the latest still image coding standard from the JPEG committee, which adopts new algorithms such as embedded block coding with optimized truncation (EBCOT) and discrete wavelet transform (DWT). These algorithms enable superior coding performance over JPEG and support various new features at the cost of the increased computational complexity. The Sony-Toshiba-IBM cell broadband engine (or the Cell/B.E.) is a heterogeneous multicore architecture with SIMD accelerators. In this work, we optimize the computationally intensive algorithmic kernels of JPEG2000 for the Cell/B.E. and also introduce a novel data decomposition scheme to achieve high performance with low programming complexity. We compare the Cell/B.E.'s performance to the performance of the Intel Pentium IV 3.2 GHz processor. The Cell/B.E. demonstrates 3.2 times higher performance for lossless encoding and 2.7 times higher performance for lossy encoding. For the DWT, the Cell/B.E. outperforms the Pentium IV processor by 9.1 times for the lossless case and 15 times for the lossy case. We also provide the experimental results on one IBM QS20 blade with two Cell/B.E. chips and the performance comparison with the existing JPEG2000 encoder for the Cell/B.E."
featured: false
publication: "*2008 International Conference on Parallel Processing, ICPP 2008, September 8-12, 2008, Portland, Oregon, USA*"
url_pdf: "https://doi.org/10.1109/ICPP.2008.39"
doi: "10.1109/ICPP.2008.39"
---

