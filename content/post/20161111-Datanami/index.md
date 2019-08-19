---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "New Approach Seeks to Automate Parallel Programming"
subtitle: ""
summary: ""
authors: []
tags: []
categories: []
date: 2016-11-11T23:30:06-04:00
lastmod: 2016-11-11T23:30:06-04:00
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

*by George Leopold*

Artificial intelligence researchers are leveraging an emerging divide-and-conquer computing approach called “dynamic programming” to greatly accelerate the process of solving problems ranging from genomic analysis to cyber security.

Engineers at Researchers from MIT’s Computer Science and Artificial Intelligence Laboratory (CSAIL) and Stony Brook University in New York reported at a computing conference earlier this month that their approach can be used to “parallelize” algorithms that leverage dynamic programming. The resulting programs running on multicore chips were said to operate up to 11 times faster than previous parallel processing techniques.

Just as important, AI-based dynamic programming approached the efficiency of parallel processing programs develop by computer scientists.

The CSAIL researchers dubbed the new approach “Bellmania,” after Richard Bellman, the applied mathematician who pioneered dynamic programming. That approach is based on a parallel processing strategy called recursive divide-and-conquer.

For certain classes of problems such as computational biology, the researchers said          dynamic programming offers much faster processing by storing the results of previous computations. In a form of computing compression, the scheme reuses those computations rather than re-computing them each time they are needed.

The approach also seeks to address lingering memory management issues that have been complicated by the steady shift to multicore processing architectures. The researchers noted that a “hand-optimized” parallel version of a dynamic-programming algorithm is typically 10 times longer as a single-core version. Complicating matters further, individual lines of code also are more complex.

Using traditional approaches requires “more memory, because you store the results of intermediate computations,” noted CSAIL researcher Shachar Itzhaky, an associate professor of electrical engineering and computer science at MIT. “When you come to implement it, you realize that you don’t get as much speedup as you thought you would, because the memory is slow.”

The recursive divide-and-conquer approach breaks computing tasks in “subproblems” that lend themselves to parallelization. Applying the Bellmania framework, a user can describe the initial step in the computational process and the platform continues divvying a problem to maximize memory efficiency to speed up processing on a multicore platform.

“The goal is to arrange the memory accesses such that when you read a cell [of the matrix], you do as much computation as you can with it, so that you will not have to read it again later,” Itzhaky explained.

The work is seen as enabling new applications running on multicore and parallel processors. “One challenge has been to enable high-level writing of programs that work on our current multicore processors, and up to now doing that requires heroic, low-level manual coding to get performance,” said **David Bader**, a professor of computational science and engineering at Georgia Tech.

Dynamic programming “is a much simpler, high-level technique for some classes of programs that makes it very easy to write the program and have their system automatically figure out how to divide up the work to create codes that are competitive with hand-tuned, low-level coding,” Bader added.

https://www.datanami.com/2016/11/11/new-approach-automate-parallel-programming/
