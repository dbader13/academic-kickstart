---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "1st Algorithmic Breakthrough in 40 years for solving the Minimum Spanning Tree (MST) Replacement Edges problem"
subtitle: ""
summary: ""
authors: []
tags: []
categories: []
date: 2020-08-19T21:12:59-04:00
lastmod: 2020-08-19T21:12:59-04:00
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

One of the most studied algorithms in computer science is called
"[Minimum Spanning
Tree](https://www.wikipedia.org/wiki/Minimum_spanning_tree)" or
MST. In this problem, one is given a graph comprised of vertices and
weighted edges, and asked to find a subset of edges that connects all
of the vertices, and the total sum of their weights is as small as
possible. Many real-world optimization problems are solved by finding
a minumum spanning tree, such as lowest cost for distribution on road
networks where intersections are vertices and weights could be length
of the road or time to drive that segment. In 1926, Czech scientist
Otakar Borůvka was the first to design an MST algorithm. Other famous
approaches to solving MST are often given by the name of the scientist
who designed MST algorithm in the late 1950's such as Prim, Kruskal,
and Dijkstra.

Several important variations of MST are also used in real
applications, including the replacement problem. Imagine a use case
when an edge in the MST degrades and either has a significanly
increased cost or is removed entirely. One must quickly find the
lowest cost "replacement edge" that reconnects the spanning
tree. Several algorithms are known for this MST replacement edge
problem. The first algorithm, due to Spira and Pan in 1975, took cubic
time in the number of vertices. They presented an $O(n^2)$ algorithm
to update the MST when new vertices are added, and could find all
replacement edges in $O(n^3)$ time, where $n$ is the number of
vertices in the graph. This was improved by Chin and Houck in 1978 to
a quadratic time algorithm, or $O(n^2)$, using a more efficient
approach to insert and delete vertices from the graph.  The best
approach to date is due to Tarjan in 1979, who gave an $O(m \alpha(n,
m))$ time algorithm using path compression, where $m$ is the number of
edges in the graph and $\alpha(n, m)$ is the inverse Ackermann's
function. $\alpha()$ is a very slow growing function, usually a number
around 3 or 4 in practice, but still a gap has remained if a better
approach exists.

**For the first time in 40 years, progress has been made on this
important graph algorithm.** With Paul Burkhardt, we've designed a
simple algorithm that runs very fast in linear time and space, or
$O(n+m)$ where $n$ and $m$ are the number of vertices and edges,
respectively, in the graph. The paper entitled [A Linear Time
Algorithm for Finding Minimum Spanning Tree Replacement
Edges](https://arxiv.org/abs/1908.03473) is now available in Arxiv.
The main result of this paper is **the first linear-time algorithm for
finding all replacement edges in the minimum spanning tree.** Our
linear time and space algorithm is an asymptotic improvement from all
prior algorithms, uses only simple arrays and Gabow-Tarjan disjoint
set union data structures, alleviates the need to use least common
ancestor (LCA) algorithms, and is easy to implement.

Other important graph algorithms need to find replacement edges, a
step often considered their bottleneck in performance. For example,
**the most vital edge** of a connected, weighted graph $G$ is the edge
whose removal causes the largest increase in the weight of the minimum
spanning tree.  When the graph contains bridges, the most vital edge
is undefined. Several algorithms were designed in the early 1990's for
the most vital edge, including $O(m \log m)$ and $O(n^2)$ time from
Hsu et al. in 1991, and improvements to this approach by Iwano and
Katoh in 1993 with $O(m+n \log n)$ and $O(m \alpha(m,n))$ time
algorithms. When using our new MST replacement edge algorithm, we now
can find the most vital edge in linear time (or $O(n)$) by simply
finding the tree edge with maximum difference in weight from its
replacement edge.  Thus, our approach is the first linear algorithm
for finding the most vital edge of the minimum spanning tree.

