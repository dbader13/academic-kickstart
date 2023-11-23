---
title: "GPU Merge Path: A GPU Merging Algorithm"
date: 2012-01-01
publishDate: 2019-09-18T11:07:24.457598Z
authors: ["Oded Green", "Robert McColl", "David A. Bader"]
publication_types: ["paper-conference"]
abstract: "Graphics Processing Units (GPUs) have become ideal candidates for the development of fine-grain parallel algorithms as the number of processing elements per GPU increases. In addition to the increase in cores per system, new memory hierarchies and increased bandwidth have been developed that allow for significant performance improvement when computation is performed using certain types of memory access patterns.  Merging two sorted arrays is a useful primitive and is a basic building block for numerous applications such as joining database queries, merging adjacency lists in graphs, and set intersection. An efficient parallel merging algorithm partitions the sorted input arrays into sets of non-overlapping sub-arrays that can be independently merged on multiple cores. For optimal performance, the partitioning should be done in parallel and should divide the input arrays such that each core receives an equal size of data to merge.  In this paper, we present an algorithm that partitions the workload equally amongst the GPU Streaming Multi-processors (SM). Following this, we show how each SM performs a parallel merge and how to divide the work so that all the GPU's Streaming Processors (SP) are utilized. All stages in this algorithm are parallel. The new algorithm demonstrates good utilization of the GPU memory hierarchy. This approach demonstrates an average of 20X and 50X speedup over a sequential merge on the x86 platform for integer and floating point, respectively. Our implementation is 10X faster than the fast parallel merge supplied in the CUDA Thrust library."
featured: false
publication: "*Proceedings of the 26th ACM International Conference on Supercomputing*"
tags: ["graphics processors", "measurement of multiple-processor systems", "parallel algorithms", "parallel systems"]
url_pdf: "http://doi.acm.org/10.1145/2304576.2304621"
doi: "10.1145/2304576.2304621"
---

