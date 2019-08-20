---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "World's Most Powerful Big Data Machines Charted on Graph 500"
subtitle: "IBM's BlueGene/Q dominates an emerging ranking of data processing supercomputers"
summary: ""
authors: []
tags: []
categories: []
date: 2012-11-16T09:05:03-04:00
lastmod: 2012-11-16T09:05:03-04:00
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

*By Joab Jackson, U.S. Correspondent, IDG News Service*

The [Top500](http://www.top500.org/) is no longer the only ranking game in town: make way for the [Graph 500](http://www.graph500.org/), which tracks how well supercomputers handle big-data-styled workloads.

So while a new Cray supercomputer took [first place on the Top500](https://www.computerworld.com/article/2493517/cray-bumps-ibm-from-top500-supercomputer-top-spot.html), it was another machine, Lawrence Livermore National Laboratory's Sequoia, that proved to be the most adept at processing data intensive workloads on the Graph 500.

Such differences in ranking between the two scales highlight the changing ways in which the world's most powerful supercomputers are being used. An increasing number of high performance computing (HPC) machines are being put to work on data analysis, rather than the traditional duties of modeling and simulation.

"I look around the exhibit floor [of the Supercomputing 2012 conference], and I'm hard-pressed to find a booth that is not doing big data or analytics. Everyone has recognized that data is a new workload for HPC," said **David Bader**, a computational science professor at the Georgia Institute of Technology who helps oversee the Graph 500.

The Graph 500 was created to chart how well the world's largest computers handle such data intensive workloads. The latest edition of the list was released at the SC12 supercomputing conference, being held this week in Salt Lake City.

In a nutshell, the Graph 500 benchmark looks at "how fast [a system] can trace through random memory addresses," Bader said. With data intensive workloads, "the bottleneck in the machine is often your memory bandwidth rather than your peak floating point processing rate," he added.

The approach is markedly different than Top500. The well-known Top500 list relies on the [Linpack](http://www.netlib.org/linpack/) benchmark, which was created in 1974. Linpack measures how effectively a supercomputer executes floating point operations, which are used for mathematically intensive computations such as weather modeling or other three dimensional simulations.

The Graph 500, in contrast, places greater emphasis on how well a computer can search through a large data set. "Big data has a lot of irregular and unstructured data sets, irregular accesses to memory, and much more reliance on memory bandwidth and memory transactions than on floating point performance," Bader said.

For the Graph 500 benchmark, the supercomputer is given a large set of data, called a graph. A graph is an interconnected set of data, such as a group of connected friends on a social network like Facebook. A graph consists of a set of vertices and edges, and in the social media context a vertex would be a person and the edge that person's connection to another person. Some vertices have many connections while many others have fewer. The computer is given a single vertex and is timed on how quickly it discovers all the other vertices in a graph, namely by following the edges.

Currently, IBM's BlueGene/Q systems dominate this edition of the Graph 500. Nine out of the top 10 systems on the list are BlueGene/Q models -- compared to four BlueGene/Q systems on the November 2011 compilation. For Bader, this is proof that IBM is becoming more sensitive to current data processing needs. IBM's previous BlueGene system, BlueGene/L, was geared more towards floating point operations, and does not score as highly on the list.

Like the Top500, each successive edition of the Graph 500 shows steady performance gains among its participants. The top machine on the new list, Sequoia, traversed 15,363 billion edges per second. In contrast, the top entrant of the first list, compiled in 2010, followed only 7 billion edges per second. This jump of four orders of magnitude is "staggering," Bader said.

The Graph500 list is compiled twice a year, and, like the Top500, the results are announced at the Supercomputing conference, usually held in November, or the International Supercomputing Conference, usually held in June. Participation is voluntary: entrants will run either the reference implementations, or their own implementations, of the benchmark and submit the results.

Despite its name, the Graph 500 has yet to attract 500 submissions, though the numbers are improving with each edition. The first contest garnered 9 participants, and this latest edition has 124 entrants.

Bader is quick to point out that the Graph 500 is not a replacement for the Top500 but rather a complementary benchmark. Still, the data intensive benchmark could help answer [some of the criticisms](http://www.computerworld.com/s/article/9197198/IBM_Intel_question_key_Top500_supercomputer_metric) around the Top500's use of the Linpack benchmark.

Jack Dongarra, who helped create Linpack and now maintains the Top500, admitted [during a discussion](http://www.computerworld.com/s/article/9233639/SC2012_Top500_expects_exascale_computing_by_2020) about the latest results of the Top500 at SC12 that Linpack does not measure all aspects of a computer's performance. He pointed to projects like Graph 500, the [Green500](http://www.green500.org/) and the HPC Challenge that measure other aspects of supercomputer performance.

At least one system, the [National Center for Supercomputing Applications' Blue Waters](http://www.ncsa.illinois.edu/BlueWaters/system.html), was not entered in the Top500, because its keepers did not feel Linpack would adequately convey the true power of the machine.

Supercomputers are built according to the jobs they will execute, not to an arbitrary benchmark, Bader pointed out.

"At the end of the day, you are going to want the machine that does best for your workload," Bader said.

*Joab Jackson covers enterprise software and general technology breaking news for The IDG News Service. Follow Joab on Twitter at @Joab_Jackson. Joab's e-mail address is Joab_Jackson@idg.com*

https://www.computerworld.com/article/2493162/world-s-most-powerful-big-data-machines-charted-on-graph-500.html
