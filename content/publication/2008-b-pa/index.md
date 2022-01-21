---
title: "High performance MPEG-2 software decoder on the Cell Broadband Engine"
date: 2008-01-01
publishDate: 2019-09-10T12:18:35.512634Z
authors: ["David A. Bader", "Sulabh Patel"]
publication_types: ["1"]
abstract: "The Sony-Toshiba-IBM Cell Broadband Engine is a heterogeneous multicore architecture that consists of a traditional microprocessor (PPE) with eight SIMD co-processing units (SPEs) integrated on-chip. While the Cell/B.E. processor is designed with multimedia applications in mind, there are currently no open-source, optimized implementations of such applications available. In this paper, we present the design and implementation behind the creation of an optimized MPEG-2 software decoder for this unique parallel architecture, and demonstrate its performance through an experimental study. This is the first parallelization of an MPEG-2 decoder for a commodity heterogeneous multicore processor such as the IBM Cell/B.E. While Drake et al. have recently parallelized MPEG-2 using Streamlt for a streaming architecture, our algorithm is quite different and is the first to address the new challenges related to the optimization and tuning of a multicore algorithm with DMA transfers and local store memory. Our design and efficient implementation target the architectural features provided by the heterogeneous multicore processor. We give an experimental study on Sony PlayStation 3 and IBM QS20 dual-Cell Blade platforms. For instance, using 16 SPEs on the IBM QS20, our decoder runs 3.088 times faster than a 3.2 GHz Intel Xeon and achieves a speedup of over 10.545 compared with a PPE-only implementation. Our source code is freely- available through SourceForge under the CellBuzz project."
featured: false
publication: "*22nd IEEE International Symposium on Parallel and Distributed Processing, IPDPS 2008, Miami, Florida USA, April 14-18, 2008*"
url_pdf: "https://doi.org/10.1109/IPDPS.2008.4536234"
doi: "10.1109/IPDPS.2008.4536234"
---

