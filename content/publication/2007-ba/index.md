---
title: "FFTC: Fastest Fourier Transform for the IBM Cell Broadband Engine"
date: 2007-01-01
publishDate: 2019-09-04T10:56:24.894794Z
authors: ["David A. Bader", "Virat Agarwal"]
publication_types: ["1"]
abstract: "The Fast Fourier Transform (FFT) is of primary importance and a fundamental kernel in many computationally intensive scientific applications. In this paper we investigate its performance on the Sony-Toshiba-IBM Cell Broadband Engine, a heterogeneous multicore chip architected for intensive gaming applications and high performance computing. The Cell processor consists of a traditional microprocessor (called the PPE) that controls eight SIMD co-processing units called synergistic processor elements (SPEs). We exploit the architectural features of the Cell processor to design an efficient parallel implementation of Fast Fourier Transform (FFT). While there have been several attempts to develop a fast implementation of FFT on the Cell, none have been able to achieve high performance for input series with several thousand complex points. We use an iterative out-of-place approach to design our parallel implementation of FFT with 1K to 16K complex input samples and attain a single precision performance of 18.6 GFLOP/s on the Cell. Our implementation beats FFTW on Cell by several GFLOP/s for these input sizes and outperforms Intel Duo Core (Woodcrest) for inputs of greater than 2K samples. To our knowledge we have the fastest FFT for this range of complex inputs."
featured: false
publication: "*High Performance Computing - HiPC 2007, 14th International Conference, Goa, India, December 18-21, 2007, Proceedings*"
url_pdf: "https://doi.org/10.1007/978-3-540-77220-0_19"
doi: "10.1007/978-3-540-77220-0_19"
---

