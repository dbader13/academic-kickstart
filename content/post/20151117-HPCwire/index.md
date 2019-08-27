---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Georgia Tech Students Named Finalists for Best Student Research Paper at SC15"
subtitle: ""
summary: ""
authors: []
tags: []
categories: []
date: 2015-11-17T14:54:28-04:00
lastmod: 2015-11-17T14:54:28-04:00
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

Four doctoral students comprising two research projects in the School of Computational Science & Engineering at the Georgia Institute of Technology are finalists for “Best Student Research Paper” at Supercomputing ’15, the International Conference for High Performance Computing, Networking, Storage and Analysis.

For the first project, the finalists developed a fast algorithm; in the second, they created a GPU-based framework that can process large graphs exceeding a device’s internal memory capacity. Each demonstrably outperforms other common approaches in high-performance computing today. A winner will be announced at the conference in Austin, Texas.

“Both of these are outstanding projects and evidence of the future leaders who are already keeping pace with and solving the most challenging problems in science, engineering, health and the social domain,” says **David A. Bader**, professor and chair of the School of Computational Science & Engineering.

### New Human Genome Indexing Algorithm for Parallel Distributed Memory ###

In his work, “Parallel Distributed Memory Construction of Suffix and Longest Common Prefix Arrays,” PhD Candidate Patrick Flick, working with Professor Srinivas Aluru, created parallel algorithms for distributed-memory construction that are 110x times faster than the best method running on a sequential, single computer. Flick, using the human genome as a racetrack to test his speed, indexed it in only 7.3 seconds using his distributed-memory algorithm running on 1024 Intel Xeon cores.

“Bioinformatics is an example of a scientific field that is extremely data intensive; speed matters and speed helps,” he says. “We are not aware of any other parallel suffix array or suffix tree construction algorithms which achieve speedups this high.”

It is believed to be the first algorithm and implementation that uses this approach for distributed-memory parallel systems.

“At this stage the code is offered as an open-source library that can be used within parallel applications,” Fick adds. “We hope that it finds adaptation within bioinformatics research. We are now working on a user-friendly interface that can be used by bioinformaticians to replace older (and slower) tools.”

Next, Flick is working on a journal paper that includes some more improvements and additional techniques, and further showcases their algorithms on real applications. Patrick also authored another paper at Supercomputing 2015 with fellow students Chirag Jain and Tony Pan about how to partition large graphs that arise in metagenomics, another data-intensive application area.

### Processing Large-Scale Graphs ###

In their paper titled “GraphReduce: Processing Large-Scale Graphs on Accelerator-Based Systems,” PhD Candidates Dipanjan Sengupta, and Kapil Agarwal developed a scalable framework (dubbed “GraphReduce”) to process large graphs that exceed a device’s GPU memory.

“GraphReduce can accelerate the analysis of graphs with billions of edges, operating at speeds much faster than similar operations on CPUs, and programmed in ways that are accessible to those who are not typically experts in GPU programming,” Sengupta says.

It provides a logic for processing “shard stores” based on choice of interval, number and sizes of shards, and how to order the edges in each shard. A “graph layout engine” then defines the layout of the data by sorting in-edges by their destination and out-edges by their source.

“One of the interesting results is that saturating the available bandwidth and overlapping data transfer with computation was able to hide a large amount of overhead, resulting in huge performance benefits,” Agarwal adds.

Most methods process dynamic graphs (like those of a social network which are continually changing over time) by storing static versions of the graph and then repeatedly running analysis on them. To address this, Sengupta next is working on an open-source framework with a Fortune 500 company to boost processing.

### About the Georgia Tech College of Computing ###

The Georgia Tech College of Computing is a national leader in the creation of real-world computing breakthroughs that drive social and scientific progress. With its graduate program ranked 9th nationally by U.S. News and World Report, the College’s unconventional approach to education is expanding the horizons of traditional computer science students through interdisciplinary collaboration and a focus on human-centered solutions. For more information about the Georgia Tech College of Computing, its academic divisions and research centers, please visit http://www.cc.gatech.edu

https://www.hpcwire.com/off-the-wire/georgia-tech-students-named-finalists-for-best-student-research-paper-at-sc15/
