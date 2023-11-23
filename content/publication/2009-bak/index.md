---
title: "Computing discrete transforms on the Cell Broadband Engine"
date: 2009-01-01
publishDate: 2019-09-10T12:18:37.675763Z
authors: ["David A. Bader", "Virat Agarwal", "Seunghwa Kang"]
publication_types: ["article-journal"]
abstract: "Discrete transforms are of primary importance and fundamental kernels in many computationally intensive scientific applications. In this paper, we investigate the performance of two such algorithms; Fast Fourier Transform (FFT) and Discrete Wavelet Transform (DWT), on the Sony–Toshiba–IBM Cell Broadband Engine (Cell/B.E.), a heterogeneous multicore chip architected for intensive gaming applications and high performance computing.  We design an efficient parallel implementation of Fast Fourier Transform (FFT) to fully exploit the architectural features of the Cell/B.E. Our FFT algorithm uses an iterative out-of-place approach and for 1K to 16K complex input samples outperforms all other parallel implementations of FFT on the Cell/B.E. including FFTW. Our FFT implementation obtains a single-precision performance of 18.6 GFLOP/s on the Cell/B.E., outperforming Intel Duo Core (Woodcrest) for inputs of greater than 2K samples. We also optimize Discrete Wavelet Transform (DWT) in the context of JPEG2000 for the Cell/B.E. DWT has an abundant parallelism, however, due to the low temporal locality of the algorithm, memory bandwidth becomes a significant bottleneck in achieving high performance. We introduce a novel data decomposition scheme to achieve highly efficient DMA data transfer and vectorization with low programming complexity. Also, we merge the multiple steps in the algorithm to reduce the bandwidth requirement. This leads to a significant enhancement in the scalability of the implementation. Our optimized implementation of DWT demonstrates 34 and 56 times speedup using one Cell/B.E. chip to the baseline code for the lossless and lossy transforms, respectively. We also provide the performance comparison with the AMD Barcelona (Quad-core Opteron) processor, and the Cell/B.E. excels the AMD Barcelona processor. This highlights the advantage of the Cell/B.E. over general purpose multicore processors in processing regular and bandwidth intensive scientific applications."
featured: false
publication: "*Parallel Computing*"
url_pdf: "https://doi.org/10.1016/j.parco.2008.12.007"
doi: "10.1016/j.parco.2008.12.007"
---

