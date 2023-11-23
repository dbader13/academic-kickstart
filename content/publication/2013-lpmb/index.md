---
title: "PASQUAL: Parallel Techniques for Next Generation Genome Sequence Assembly"
date: 2013-01-01
publishDate: 2019-09-10T12:18:37.442797Z
authors: ["Xing Liu", "Pushkar R. Pande", "Henning Meyerhenke", "David A. Bader"]
publication_types: ["article-journal"]
abstract: "The study of genomes has been revolutionized by sequencing machines that output many short overlapping substrings (called reads). The task of sequence assembly in practice is to reconstruct long contiguous genome subsequences from the reads. With Next Generation Sequencing (NGS) technologies, assembly software needs to be more accurate, faster, and more memory-efficient due to the problem complexity and the size of the data sets. In this paper, we develop parallel algorithms and compressed data structures to address several computational challenges of NGS assembly. We demonstrate how commonly available multicore architectures can be efficiently utilized for sequence assembly. In all stages (indexing input strings, string graph construction and simplification, extraction of contiguous subsequences) of our software Pasqual, we use shared-memory parallelism to speed up the assembly process. In our experiments with data of up to 6.8 billion base pairs, we demonstrate that Pasqual generally delivers the best tradeoff between speed, memory consumption, and solution quality. On synthetic and real data sets Pasqual scales well on our test machine with 40 CPU cores with increasing number of threads. Given enough cores, Pasqual is fastest in our comparison."
featured: false
publication: "*IEEE Transactions on Parallel & Distributed Systems*"
url_pdf: "https://doi.org/10.1109/TPDS.2012.190"
doi: "10.1109/TPDS.2012.190"
---

