---
title: "When Good Enough Is Better: Energy-Aware Scheduling for Multicore Servers"
date: 2017-01-01
publishDate: 2019-09-04T10:56:23.024057Z
authors: ["Xinning Hui", "Zhihui Du", "Jason Liu", "Hongyang Sun", "Yuxiong He", "David A. Bader"]
publication_types: ["1"]
abstract: "Power is a primary concern for mobile, cloud, and high-performance computing applications. Approximate computing refers to running applications to obtain results with tolerable errors under resource constraints, and it can be applied to balance energy consumption with service quality. In this paper, we propose a \"Good Enough (GE)\" scheduling algorithm that uses approximate computing to provide satisfactory QoS (Quality of Service) for interactive applications with significant energy savings. Given a user-specified quality level, the GE algorithm works in the AES (Aggressive Energy Saving) mode for the majority of the time, neglecting the low-quality portions of the workload. When the perceived quality falls below the required level, the algorithm switches to the BQ (Best Quality) mode with a compensation policy. To avoid core speed thrashing between the two modes, GE employs a hybrid power distribution scheme that uses the Equal-Sharing (ES) policy to distribute power among the cores when the workload is light (to save energy) and the Water-Filling (WF) policy when the workload is high (to improve quality). We conduct simulations to compare the performance of GE with existing scheduling algorithms. Results show that the proposed algorithm can provide large energy savings with satisfactory user experience."
featured: false
publication: "*2017 IEEE International Parallel and Distributed Processing Symposium Workshops, IPDPS Workshops 2017, Orlando / Buena Vista, FL, USA, May 29 - June 2, 2017*"
url_pdf: "https://doi.org/10.1109/IPDPSW.2017.38"
doi: "10.1109/IPDPSW.2017.38"
---

