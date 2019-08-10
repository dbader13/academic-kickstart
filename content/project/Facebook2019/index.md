---
title: "Facebook Research"
date: 2019-08-05T10:24:25-04:00
draft: false
---
Facebook AI Systems Hardware/Software Co-Design research award on Scalable Graph Learning Algorithms
---
https://research.fb.com/blog/2019/05/announcing-the-winners-of-the-ai-system-hardware-software-co-design-research-awards/
---
Deep learning has boosted the machine learning field at large and created significant increases in the performance of
tasks including speech recognition, image classification, object detection, and recommendation. It has opened the door
to complex tasks, such as self-driving and super-human image recognition. However, the important techniques used in
deep learning, e.g. convolutional neural networks, are designed for Euclidean data type and do not directly apply on
graphs. This problem is solved by embedding graphs into a lower dimensional Euclidean space, generating a regular
structure. There is also prior work on applying convolutions directly on graphs and using sampling to choose
neighbor elements. Systems that use this technique are called graph convolution networks (GCNs). GCNs have proven
to be successful at graph learning tasks like link prediction and graph classification. Recent work has pushed the
scale of GCNs to billions of edges but significant work remains to extend learned graph systems beyond
recommendation systems with specific structure and to support big data models such as streaming graphs.

This project will focus on developing scalable graph learning algorithms and implementations that open the door for
learned graph models on massive graphs. We plan to approach this problem in two ways. First, developing a scalable
high performance graph learning system based on existing GCNs algorithms, like GraphSage, by improving the
workflow on shared-memory NUMA machines, balancing computation between threads, optimizing data movement,
and improving memory locality. Second, we will investigate graph learning algorithm-specific decompositions and
develop new strategies for graph learning that can inherently scale well while maintaining high accuracy. This includes
traditional partitioning, however in general we consider breaking the problem into smaller pieces, which, when solved
will result in a solution to the bigger problem. We will explore decomposition results from graph theory, for example,
forbidden graphs and the Embedding Lemma, and determine how to apply such results into the field of graph learning.
We will investigate whether these decompositions could assist in a dynamic graph setting.


