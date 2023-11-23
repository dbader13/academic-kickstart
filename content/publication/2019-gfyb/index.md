---
title: "Performance Impact of Memory Channels on Sparse and Irregular Algorithms"
date: 2019-11-18
publishDate: 2019-10-03T01:10:40.295069Z
authors: ["Oded Green", "James Fox", "Jeff Young", "David Bader"]
publication_types: ["paper-conference"]
abstract: "Graph processing is typically considered to be a memory-bound rather than compute-bound problem. One common line of thought is that more available memory bandwidth corresponds to better graph processing performance. However, in this work we show that this is not necessarily the case. We demonstrate that the key factor in the utilization of the memory system for graph algorithms is not the raw bandwidth, or even latency of memory requests, but instead is the number of memory channels available to handle small data transfers with low locality. Using several widely used graph frameworks, including Gunrock (on the GPU) and GAPBS & Ligra (for CPUs), we characterize two very distinct memory hierarchies with respect to key graph analytics kernels. Our results show that the differences in peak bandwidths of several of the latest Pascal-generation GPU memory subsystems aren't reflected in the performance of various analytics. Furthermore, our experiments on CPU and Xeon Phi systems show that the number of memory channels utilized can be a decisive factor in performance across several different applications. For CPU systems with smaller thread counts, the memory channels can be underutilized while systems with high thread counts can oversaturate the memory subsystem, which leads to limited performance. Lastly, we model the performance of including more channels with narrower access widths than those found in existing memory subsystems, and we analyze the trade-offs in terms of the two most prominent types of memory accesses found in graph algorithms, streaming and random accesses."
featured: false
publication: "*9th IEEE/ACM Workshop on Irregular Applications: Architectures and Algorithms, IA3@SC 2019, Denver, CO, USA, November 18, 2019*"
url_pdf: ""
doi: "10.1109/IA349570.2019.00016"
---

