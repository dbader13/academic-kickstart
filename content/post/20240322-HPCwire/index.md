---
# Documentation: https://hugoblox.com/docs/managing-content/

title: "Chapel 2.0 Released: Scalable and Productive Computing for All"
subtitle: ""
summary: ""
authors: []
tags: []
categories: []
date: 2024-03-22T13:40:30-04:00
lastmod: 2024-03-22T13:40:30-04:00
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

The Chapel team is excited to announce the release of Chapel version 2.0. After years of hard work and continuous improvements, Chapel shines as an enjoyable and productive programming language for distributed and parallel computing.

{{<figure src="chapel-logo-300x197.png">}}

Users with diverse application goals are leveraging Chapel to quickly develop fast and scalable software, including physical simulations, massive data and graph analytics, portions of machine learning pipelines, and more. The 2.0 release brings stability guarantees to Chapel’s battle-tested features, making it possible to write performant and elegant code for laptops, GPU workstations, and supercomputers with confidence and convenience.

In addition to numerous usability and performance improvements — [including many over the previous release candidate](https://www.hpcwire.com/off-the-wire/chapel-programming-language-moves-toward-2-0-with-significant-updates-and-stabilizations/) — the 2.0 release of Chapel is stable: the core language and library features are designed to be backwards-compatible from here on. As Chapel continues to grow and evolve, additions or changes to the language should not require adjusting any existing code.

Those new to Chapel might be wondering how the language came about. Chapel was pioneered by a small team at Cray Inc. who wanted to help anyone make full use of any parallel hardware available to them — from their multicore laptop to a large-scale supercomputer.

## What Are People Doing with Chapel? ##

Chapel is being used for a diverse set of production-grade applications; these applications have guided the language’s development, pushing it to grow and support real-world computing workloads.

### <span style="text-decoration:underline">Arkouda: Interactive Data Analysis at Scale</span> ###

Arkouda is one exciting application of the Chapel language. It is an open-source data science library for Python written in Chapel. Arkouda enables users to interactively analyze massive datasets. Using Chapel enables Arkouda to scale easily; as a concrete example, its `argsort` operation, written in around 100 lines of Chapel code, was able to sort 256 TiB of data in 31 seconds, a rate of 8500 GiB/s! That throughput was achieved by scaling Arkouda to 8192 compute nodes on an [HPE Cray EX](https://www.hpe.com/us/en/compute/hpc/supercomputing/cray-exascale-supercomputer.html) using its [Slingshot-11 network](https://www.hpe.com/us/en/compute/hpc/slingshot-interconnect.html). The scaling was made possible through Chapel’s built-in support for multi-node execution.

{{<figure src="arkouda-argsort-1024x532.png" caption="Scaling results from Arkouda’s argsort function">}}

Arkouda allows data scientists to iterate at the speed of thought, even with datasets spanning terabytes of data — scales that could never fit into the memory of a single machine. All the performance and scalability of Chapel does not come at the cost of convenience or ergonomics.

**David Bader**, the NJIT professor leading development of the [Arachne](https://github.com/Bears-R-Us/arkouda-njit) Arkouda module for scalable graph algorithms, has this to say about the language: “Chapel serves as a powerful tool for the rapid development of scalable graph analysis algorithms, standing alone in its capability to enable such advancements.”

Further examples can be found [here](https://chapel-lang.org/blog/posts/announcing-chapel-2.0/#:~:text=CHAMPS%3A%20A%20Framework%20for%20Computational%20Fluid%20Dynamics).

Chapel has supported developers with various computing needs in creating performant and maintainable software since 2015, a track record of nearly 10 years. The 2.0 release represents the culmination of a concerted, multi-year effort to refine Chapel’s core functionality based on these many years of experience.

Chapel is now stable, but it is not finished: the language will continue to see performance improvements, new features, and better tooling. Whether you are working with a personal machine or a multi-node cluster, there has been no better time to get started with Chapel to get the most out of your computing hardware.

*Source: Chapel Parallel Programming Language Development Team*

https://www.hpcwire.com/off-the-wire/chapel-2-0-released-scalable-and-productive-computing-for-all/
