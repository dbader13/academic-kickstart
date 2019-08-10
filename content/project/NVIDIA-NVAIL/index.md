---
title: "NVIDIA AI Lab (NVAIL) for Scalable Graph Algorithms"
date: 2019-08-05T10:39:06-04:00
draft: false
---
## Research Directions

Graph algorithms represent some of the most challenging known problems in computer science for modern processors.  These algorithms contain far more memory access per unit of computation than traditional scientific computing.  Access patterns are not known until execution time and are heavily dependent on the input data set.  Graph algorithms vary widely in the volume of spatial and temporal locality that is usable my modern architectures. In today's rapidly evolving world, graph algorithms are used to make sense of large volumes of data from news reports, distributed sensors, and lab test equipment, among other sources connected to worldwide networks.  As data is created and collected, dynamic graph algorithms make it possible to compute highly specialized and complex relationship metrics over the entire web of data in near-real time, reducing the latency between data collection and the capability to take action.

With this partnership with NVIDIA, we collaborate on the design and implementation of scalable graph algorithms and graph primitives that will bring new capabilities to the broader community of data scientists.  Leveraging existing open frameworks, this effort will improve the experience of graph data analysis using GPUs by improving tools for analyzing graph data, speeding up graph traversal using optimized data structures, and accelerating computations with better runtime support for dynamic work stealing and load balancing.

## Selected Projects:

### cuGraph

***Problem***: With the rapid advance of AI and Machine Learning, demand has surged for expertise at all levels in the workforce.  Through our educational mission, we may accelerate the development of AI frameworks such as [RAPIDS AI cuGraph](https://github.com/rapidsai/cugraph) that builds upon our Hornet streaming graph framework for accelerators such as NVIDIA GPUs.

***Our approach***: The focus of our collaboration will design and implement scalable graph algorithms and primitives that will enable the broader data science community to make broadly accessible high-performance graph analytics. This includes faster loading of data onto the GPU, improving the performance of the underlying data structure of cuGraph, and creating better loading balancing mechanisms for graph traversals.

### Accelerators

***Problem***: There are a wide variety of accelerators available today including quantum annealers, TPUs, and GPUs. These accelerators are considered key to opening the door to new applications that cannot run in a reasonable time on CPUs. However, these accelerators come with some large pitfalls: they have larger latencies, lower bandwidth, and reduced memory capacity compared to CPU main memory. This is challenging for memory-intensive applications, especially graph processing, which severely limits the impact of these accelerators for graph applications.

***Our approach***: We will investigate algorithm-specific graph decomposition. This could include partitioning in some cases, but would extend in general to breaking a graph into smaller graphs, which may not be subgraphs (induced or otherwise) but which, when solved, will result in a solution to the original graph problem. We will investigate decomposition approaches for NVIDIA GPUs in which large graphs (greater than 20 billion edges) are unexpected to fit into GPU memory for some time. We will leverage decomposition results from graph theory, for example applications such as the Embedding Lemma due to the Szemeredi Regularity Lemma, and apply them to graph problems which are currently, at scale, intractable on CPUs and will not fit on today's accelerators.

### Exploiting Graph Structure

***Problem***: Some graph problems are exceedingly difficult on general graphs and some heuristics or approximations are too expensive to run on graphs at large scale. One of the issues is that generappl graphs are one of the most challenging data structures to leverage for performance due to the limited locality of data access and reuse. They introduce arbitrary memory access patterns, have limited or no bounds on traversals, do not partition well, etc. The lack of structure is a significant challenge and a large amount of computational science research is done to mitigate many of these issues. In some cases this work is successful, but there are entire areas where graph analysis does not have both effective and mathematically understood approaches for solving, such as the approximate graph matching problem.

***Our approach***: We will investigate structure in existing real-world graphs and design new approaches to exploit these features for performance on accelerators. If this structure is designed well enough, then the algorithm can run approximately if the structure does not exist and exactly if it does exist, with an approximation factor based on some distance that the graph has to the structure. We can apply structural methods toward hard problems such as approximate graph matching.