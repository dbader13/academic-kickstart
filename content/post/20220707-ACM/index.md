---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "People of ACM - David A. Bader"
subtitle: ""
summary: ""
authors: []
tags: []
categories: []
date: 2022-07-07T16:29:01-04:00
lastmod: 2022-07-07T16:29:01-04:00
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

# {{< video src="bader.mp4" >}}

---


{{< youtube hd1APIbv8c0 >}}

***Why did you decide to pursue a career in computer engineering, and specifically in parallel computing?***

I first used a computer when I was three years old in 1972, when my father—a college chemistry professor and early computer scientist who developed numerical methods and plotting packages—let us enter programs into a Digital Equipment Corporation PDP 11/45 mainframe computer. In the college library, I browsed through computing journals and was inspired first by a 1981 paper by H.J. Siegel et al., focused on parallel computing architectures for image processing. This led me to pursuing degrees in electrical and computer engineering and my doctoral research under Joseph JaJa at University of Maryland, who had authored the leading textbook on parallel algorithms. Parallel computing was a path for me to pursue solutions to some of the most challenging real-world problems of global significance such as those in Earth sciences, biology and genomics, and national security. These problems require the use of parallel computing due to the data volumes, computational complexity, and time-to-solution requirements.

***You have been recognized as a pioneer in using the Linux operating system along with commodity parts in the development of high-performance computers. Will you tell us about your initial efforts in this area? Why has Linux been such an effective framework for supercomputers?***

Yes, last year I received the IEEE Sidney Fernbach Award for the development of Linux-based massively parallel production computers and for pioneering contributions to scalable discrete parallel algorithms for real-world applications. According to Hyperion Research’s HPC Qview tracking of servers and the broader HPC ecosystem, the total economic impact of my invention of Linux supercomputing has been over $100 trillion in the past 25 years. In the early 1980’s I was fascinated with parallel computing and passionate to build my own system. I recognized that to democratize supercomputers and improve their affordability, one needs to leverage commodity technologies and make programming and system software portable. In 1989, as an undergraduate student at Lehigh University, I built my first parallel computer, using several Commodore Amiga 1000 personal computers that the company had donated to Lehigh. They had been collecting dust in a closet when a friend and I networked them together. In January 1992, I joined the University of Maryland as an electrical and computer engineering doctoral student and visited the NASA Goddard Space Flight Center in search of fellowships in parallel computing. In August, I received the NASA Graduate Student Researcher Fellowship and built my first parallel computer using Ethernet-connected, Intel-based PCs and the FreeBSD operating system in 1993, prior to the Beowulf project. After receiving my PhD in May 1996, over the next eighteen months I was a postdoc at the university and a National Science Foundation (NSF) research associate at its Institute for Advanced Computer Studies (UMIACS). In this role, I built an experimental computing cluster comprising 10 DEC AlphaServer nodes, each with four DEC Alpha RISC processors and a DEC PCI card connected to a DEC Gigaswitch ATM switch.

In January 1998, I moved to the University of New Mexico and the Albuquerque High Performance Computing Center (AHPCC). There, I had the opportunity to build and deploy, to my knowledge, the first bona fide Linux supercomputer while continuing to develop clusters of COTS processors into systems with the speed, performance, and services of a traditional supercomputer. I came to UNM with the idea of building the first x86 Linux supercomputer as a teaching tool for advanced computer design. My system design took a revolutionary new direction that differed significantly from Beowulf and the HPC research community’s cluster efforts. From my experience with real applications, I knew that Beowulf did not have the capabilities to run the broad set of scientific computing tasks on contemporary supercomputers, and more engineering was necessary to create a Linux-based system that would displace traditional supercomputers. By spring 1998 I had built the first working Intel/Linux supercomputer with 8 dual-Intel Pentium II nodes and a Myrinet interconnection network. I pitched the idea of including a Linux supercomputer on the NSF-supported National Technology Grid. NCSA’s director Larry Smarr made a high risk/high payoff bet on my vision of the first Linux supercomputer widely available to national science communities by allocating $400,000. I assembled a team to build a 128-node dual-Intel Pentium II process system Roadrunner with Myrinet. Roadrunner was among the 100 fastest supercomputers in the world when it went online. More historical information can be found in: D.A. Bader, “[Linux and Supercomputing: How my passion for building COTS systems led to an HPC revolution](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9546947).”

***In December 2021, it was announced that you will be leading an [international project to develop streaming algorithms for graph data](https://davidbader.net/post/20211216-njit/). What are the goals of this project? How are new innovations in scalable graph analytics impacting areas including cybersecurity and healthcare?***

Graphs are an abstraction that are useful for solving real-world problems such as those in cybersecurity and healthcare, where the vertices of the graph represent the objects and the edges connecting vertices represent the relationships between these objects. Graphs require combinatorial algorithms that are particularly difficult to parallelize due to their irregular data structures, lack of locality, and unpredictable memory traces. In the over three decades since I designed and implemented my first parallel graph algorithm, I’ve produced multiple “firsts” in algorithm design and implementation, including the first evaluation of parallel single-source shortest path algorithms on large and real-world graphs, the first scalable parallel betweenness centrality calculation, the first scalable parallel community detection algorithm (winner of the 10th DIMACS Challenge's mix challenge), the first parallel streaming community maintenance algorithm, and many of the best-performing graph algorithms for GPUs. My open-source STINGER streaming graph analysis framework (winner of IEEE HPEC Best Paper) is the first of its kind, leading research and applications in graph analysis as the graph evolves. My recent NSF awards include support for open-source frameworks StreamWare (with D. Brooks, S.R. Kuppannagari, S. Basu Roy, V. Prasanna, X. Qian, and Z. Du) to enable users to develop streaming data-science applications, and Arkouda, which combines the productivity of Python with the performance of HPE/Cray Chapel for manipulation multi-terabyte data sets and graphs.

***Why are graph analytics effective in understanding the dynamics of large social networks? Where is research heading in this area?***

Graphs are of tremendous importance in understanding the dynamics of large social networks. The graph abstraction allows natural modeling of people, devices, social media posts (as vertices), and interactions and information flow (as edges). With the availability of new open-source tools, such as STINGER, StreamWare, and Arkouda, as mentioned earlier, we’re able to discover emerging trends, find new communities, identify campaigns of misinformation, and make social networks safer by removing malicious actors. I’m proud of my team of collaborators and students whose research and algorithms are used in practice today. While parallel graph algorithms and supercomputers have helped analyze massive data sets, they are often performing forensic analysis after an egregious event. With new algorithmic and architectural developments that enable high-performance streaming analytics, future research will solve predictive analytics—actionable intelligence that understands events as they unfold and allows for real-time actions within the network.

---

David A. Bader is a Distinguished Professor and a founder of the Department of Data Science and Director of the Institute for Data Science at New Jersey Institute of Technology. His research interests are at the intersection of high-performance computing and real-world applications, including cybersecurity, massive-scale analytics, and computational genomics. Bader has co-authored over 300 scholarly papers and received best paper awards at various conferences. He is the editor of the books *Massive Graph Analytics*, *Graph Partitioning and Graph Clustering*, *Scientific Computing with Multicore and Accelerators*, and *Petascale Computing*.

Bader serves as Editor-in-Chief of [*ACM Transactions on Parallel Computing*](https://dl.acm.org/journal/topc) (TOPC). Bader was selected as an ACM Fellow for contributions to high-performance computing systems, graph analytics, and technical leadership in parallel computing. He is also a Fellow of the Society of Industrial and Applied Mathematics (SIAM), the American Association for the Advancement of Science (AAAS), and the Institute of Electrical and Electronics Engineers (IEEE). Bader received the 2021 IEEE Sidney Fernbach Award for the development of Linux-based massively parallel production computers and for pioneering contributions to scalable discrete parallel algorithms for real-world applications.

{{< figure src="david-bader.jpg">}}

https://www.acm.org/articles/people-of-acm/2022/david-a-bader
