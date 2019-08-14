---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "David Bader on the Challenges of Linux Clusters"
subtitle: ""
summary: ""
authors: []
tags: []
categories: []
date: 2003-07-30T07:57:02-04:00
lastmod: 2003-07-30T07:57:02-04:00
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

*CIO Insight* reporter Debra D'Agostino spoke with **Dr. David A. Bader**, a professor in the Electrical and Computer Engineering Department and researcher at the Center for High Performance Computing at the University of New Mexico, about the differences between Linux clusters and supercomputers, and the challenges CIOs can expect to face when evaluating the two strategies."

**CIO Insight: Why are we seeing more and more companies choose Linux clusters rather than supercomputers?**

**Bader**: Initially, the attractive part about Linux clusters was just the price vs. performance. Linux clusters are much cheaper to acquire than supercomputers. And with the Linux cluster, the OS essentially is free. You could buy PCs, commodity PCs, get a fast network and put it together. That's why a lot of companies, big and small, moved toward Linux clusters, although most of the commercial vendors now are offering their own versions of Linux clusters.

**And is the advantage to using a Linux cluster instead of a supercomputer still mainly a matter of cost?**

Well, in addition, while a supercomputer traditionally would have perhaps a very well engineered system, the processor might be a generation out of date. Meanwhile, a Linux cluster typically looks like a collection of the fastest PCs you can currently buy. And so you may be getting a newer generation of processors or the current generation as opposed to a previous generation, and so you're able to buy a commodity network. A supercomputer or a Linux cluster has maybe a three-year life span as it is, so the faster you can get [current] technology into place, the greater the competitive advantage. If you're using a technology that's a year or two out of date and your machine has only a three-year life span, that doesn't make a lot of sense.

At this point, a Linux cluster and a supercomputer are probably very close to each other. In fact, Linux clusters are now some of the largest and fastest computers, and most of the traditional supercomputing companies, such as IBM and Sun, are modifying their operating systems so that they run Linux applications as well. Furthermore, in many of the large systems that are being delivered, the failure rate of nodes in a large Linux cluster is very similar to a supercomputer. So the distinctions between a Linux cluster and a supercomputer are really blurred at this point, and becoming more so by the day.

**So is this the end of supercomputers?**

While I think the two are blending together, at the high end, for instance, you may find you need a more tightly coupled machine or better architected machine to scale some problems to the larger sizes. And at the very high end you typically have data-intensive problems. You need to be able to have memory bandwidths on a very high scale that you may not find in commodity products.

So while typical Linux clusters are often very good if you have tens or maybe hundreds of nodes, if you're talking thousands of nodes or more, you may need a very sophisticated interconnection network, a modified operating system, a scalable scheduler to put the jobs onto the machine, and checkpoint restartability.

**What are some of the challenges facing CIOs who start looking to this technology?**

They're very similar to the challenges of acquiring a supercomputer. Machine rooms need to be upgraded—the cooling, the power requirements, etc. As you go to cheaper commodities, cheaper nodes and larger clusters, you'll start requiring more power and more cooling. That's one challenge.

Another concern is the total cost of ownership. As we have machines with lots and lots of nodes, big concerns include actually finding all the faults, making sure that everything is operating correctly, the system administration, making sure that versions are consistent across machines, security issues. While an academic or a group of enthusiasts can put together a Linux cluster themselves, really there's a significant amount of effort that needs to take place to have a large installation. The operating system has some limitations, the networks, maintaining software across that many computers, and so forth. You need to be able to service faults in the machines, for instance; if one machine goes down, you have to be able to figure out which one it is and replace it. And if you have a long-running application, you don't want that to hurt what you're doing. You also need to be able to get your jobs running on the cluster. Your code has to be willing to take advantage of that and so forth.

Another challenge is that applications that normally would run on a PC, for instance, may not be straightforward on a cluster. If it's a database application, chances are there's a port to a multiprocessor system. But if you have an internal computation, you would have to find some way to make sure that it would work on a cluster. However, if you do have applications that already have implementations that could run in parallel, then it makes the computing even more accessible. Some of the machines today have orders of magnitude more computing power than what we had just three to five years ago. And so the amount of computation is just astonishing.

https://www.cioinsight.com/print/c/a/Past-News/Web-Extra-David-Bader-on-the-Challenges-of-Linux-Clusters