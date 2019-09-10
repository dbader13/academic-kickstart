---
title: "An efficient transactional memory algorithm for computing minimum spanning forest of sparse graphs"
date: 2009-01-01
publishDate: 2019-09-10T12:18:35.341821Z
authors: ["Seunghwa Kang", "David A. Bader"]
publication_types: ["1"]
abstract: "Due to power wall, memory wall, and ILP wall, we are facing the end of ever increasing single-threaded performance. For this reason, multicore and manycore processors are arising as a new paradigm to pursue. However, to fully exploit all the cores in a chip, parallel programming is often required, and the complexity of parallel programming raises a significant concern. Data synchronization is a major source of this programming complexity, and Transactional Memory is proposed to reduce the difficulty caused by data synchronization requirements, while providing high scalability and low performance overhead.  The previous literature on Transactional Memory mostly focuses on architectural designs. Its impact on algorithms and applications has not yet been studied thoroughly. In this paper, we investigate Transactional Memory from the algorithm designer's perspective. This paper presents an algorithmic model to assist in the design of efficient Transactional Memory algorithms and a novel Transactional Memory algorithm for computing a minimum spanning forest of sparse graphs. We emphasize multiple Transactional Memory related design issues in presenting our algorithm. We also provide experimental results on an existing software Transactional Memory system. Our algorithm demonstrates excellent scalability in the experiments, but at the same time, the experimental results reveal the clear limitation of software Transactional Memory due to its high performance overhead. Based on our experience, we highlight the necessity of efficient hardware support for Transactional Memory to realize the potential of the technology."
featured: false
publication: "*Proceedings of the 14th ACM SIGPLAN Symposium on Principles and Practice of Parallel Programming, PPOPP 2009, Raleigh, NC, USA, February 14-18, 2009*"
url_pdf: "https://doi.org/10.1145/1504176.1504182"
doi: "10.1145/1504176.1504182"
---

