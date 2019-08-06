---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "NVIDIA AI Laboratory (NVAIL)"
subtitle: ""
summary: ""
authors: []
tags: []
categories: []
date: 2019-04-07T09:33:26-04:00
lastmod: 2019-04-07T09:33:26-04:00
featured: false
draft: false

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ""
  focal_point: ""
  preview_only: false

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects: []
---

# [Georgia Tech, UC Davis, Texas A&M Join NVAIL Program with Focus on Graph Analytics](https://news.developer.nvidia.com/graph-technology-leaders-combine-forces-to-advance-graph-analytics/)

April 17, 2019

By Sandra Skaff

NVIDIA is partnering with three leading universities — Georgia Tech, the University of California, Davis, and Texas A&M — as part of our NVIDIA AI Labs program, to build the future of graph analytics on GPUs. 

NVIDIA’s work with these three new NVAIL partners aims to ultimately create a one-stop shop for customers to take advantage of accelerated graph analytics algorithms. 

This will enable users to iterate over different graph models to find the best one faster, to update models faster as the data changes or grows, and to extract better insights from their data and bring new offerings to customers.

The importance of [graph analytics](https://developer.nvidia.com/discover/graph-analytics) is increasing with the explosion of data, and especially data which can benefit from graph representations. Graph representations are ideal for representing data points along with the relationships between them using edges. Graph data is available in diverse applications, ranging from chemistry to computer science to sociology. As such, the opportunities for applying graph analytics algorithms are vast.

Leading the way, Georgia Tech, UC Davis and Texas A&M are working towards solving graph analytics problems within the [cuGRAPH](https://github.com/rapidsai/cugraph)framework inside [RAPIDS](https://github.com/rapidsai), an open source set of software libraries that speeds data science and analytics pipelines. 

{{< figure library="true" src="inception-visual-nvail-data-science-blog-image-976056-r3.jpg" title="" lightbox="true" >}}

## Building the Future of Graph Analytics with RAPIDS

RAPIDS was launched by NVIDIA last year with the goal of enabling end-to-end data analytics pipelines to run entirely on GPUs.  RAPIDS at its lowest level relies on the [CUDA-X AI](https://www.nvidia.com/en-us/technologies/cuda-x/) libraries for low-level optimization of GPU parallelism at the thread level, taking best advantage of the GPU’s high memory bandwidth, but then exposes these functionalities through simple and familiar python interfaces, making it highly suitable for running data science experiments.

By using RAPIDS, data can be loaded onto GPUs using a Pandas-like interface, and then used for various connected machine learning and graph analytics algorithms without ever leaving the GPU. This level of interoperability is made possible through libraries like Apache Arrow. 

To accelerate the Apache Arrow development, NVIDIA started collaborating with Ursa Labs through the NVAIL (NVIDIA AI Labs) program. Apache Arrow provides an interoperable columnar representation of tabular data commonly called a DataFrame, which bridges between CPU and GPU memory, and Arrow is the data format of the RAPIDS [cuDF](https://github.com/rapidsai/cudf) library. The data in cuDF format is fed to machine learning and graph analytics algorithms, which are housed in the [cuML](https://github.com/rapidsai/cuml) and [cuGRAPH](https://github.com/rapidsai/cugraph) libraries in RAPIDS. 

We are building cuGRAPH as a collection of GPU accelerated graph analytics algorithms that both consume and produce data in cuDF format. Graph algorithms are essential to making sense of large volumes of highly unstructured and sparse data. Reducing the latency between collecting that data and the capability to take action is critical for both expediting scientific progress as well as enabling new applications that rely on inferring from extremely large amounts of data.

With these new NVAIL universities, we will ensure we have state-of-the-art graph analytics approaches for static, dynamic, and property graph structures.  We will support both the frontier- and linear-algebra-based approaches for graph analytics algorithms.

## Texas A&M

[Prof. Tim Davis](http://faculty.cse.tamu.edu/davis/welcome.html) and his lab at Texas A&M are significant contributors to [SuiteSparse/GraphBLAS](http://faculty.cse.tamu.edu/davis/suitesparse.html), which provides linear algebra based building blocks for implementing graph algorithms. In the case of traversal, for example, instead of traversing the nodes through the edges of a graph one at a time, we can implement the algorithm using the equivalent of matrix operations for graphs, called semirings. Working with Prof. Davis and his lab, we aim to combine the strengths of SuiteSparse/GraphBLAS, [nvGraph](https://developer.nvidia.com/nvgraph), and [cuSPARSE](https://developer.nvidia.com/cusparse), into one library, which would be exposed to users through a [GraphBLAS](http://graphblas.org/) API. This combination will ensure the acceleration of numerous graph algorithms and scaling to multiple NVIDIA GPUs.

## UC Davis

[Prof. John Owens](https://www.ece.ucdavis.edu/~jowens/) and his lab at UC Davis are the creators of the open-source [Gunrock](https://github.com/gunrock) framework, which provides frontier-based building blocks for implementing graph algorithms on GPUs. We plan on working with UC Davis to improve on the design, development, and implementation of cuGRAPH in several ways, specifically on scalability and programmability aspects. These improvements leverage Gunrock, which provides a frontier-based programming model and a path to scalable and multi-GPU methods. On the scalability aspect, we will build upon UC Davis’s existing approach for multi-GPU processing for integration into cuGRAPH, and explore multi-node capabilities. On the programmability aspect, we will bring the frontier model into cuGRAPH, which would make it as easy as possible for developers to write new algorithms and applications.

## Georgia Tech

[Prof. David Bader](https://www.cse.gatech.edu/people/david-bader) and his lab at Georgia Tech are leaders in high performance computing algorithms, with a focus on both static and dynamic graph algorithms. With Prof. Bader and his lab, we will work on the design and implementation of scalable graph algorithms and graph primitives for integrating into cuGRAPH, leveraging their [Hornet](https://github.com/hornet-gt/hornet) framework. A few challenges we plan on tackling for both static and dynamic graph algorithms are improving tools for analyzing graph data, speeding up graph traversal using optimized data structures, and accelerating computations with better runtime support for dynamic work stealing and load balancing.

## Interaction with other GPU graph frameworks

While the landscape of graph frameworks designed for GPUs is sparse, we believe that leveraging a combination of  nvGraph from NVIDIA, Gunrock from UC Davis, Hornet from Georgia Tech, and the SuiteSparse work out of Texas A&M will help us address next generation graph challenges.  While there is overlap between the various frameworks, each excels in different areas. Rather than forcing the data scientist to choose a framework based on their needs, RAPIDS [cuGRAPH](https://medium.com/rapids-ai/rapids-cugraph-1ab2d9a39ec6) will help integrate with all four frameworks. You can learn more about the future of RAPIDS in this [post](https://medium.com/rapids-ai/the-road-to-1-0-building-for-the-long-haul-657ae1afdfd6).  

You can get started with RAPIDS cuGRAPH today: https://github.com/rapidsai/notebooks/tree/branch-0.6/cugraph



https://news.developer.nvidia.com/graph-technology-leaders-combine-forces-to-advance-graph-analytics/