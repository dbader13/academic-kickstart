---
title: "A Prediction Based CMP Cache Migration Policy"
date: 2008-01-01
publishDate: 2019-09-10T12:18:35.385181Z
authors: ["Song Hao", "Zhihui Du", "David A. Bader", "Man Wang"]
publication_types: ["1"]
abstract: "The large L2 cache's access latency, which is mainly caused by wire delay, is a critical problem to improve the performance of CMP (Chip Multi-Processor) in NUCA (Non-Uniform Cache Architecture). A CMP L2 cache accessing performance model is provided first to analyze and evaluate the L2 access efficiency in this paper. The total L2 cache access latency problem is formalized as an optimal problem and the lower bound of L2 cache access latency is given based on this model. A novel PBM (Prediction based L2 cache data Migration) algorithm, which employs the sequential prediction technology to identify the data to be accessed in the near future, is designed to migrate the data to be accessed toward their users in early and this method can enable the cores to perform their accesses to the L2 cache in close banks. The analysis results show that this active data migration algorithm can take advantage of the principle of locality to reduce the data access latency much more than the traditional lazy data migration policy. To evaluate the theoretic analysis results, the HMTT toolkit is used to capture the complete memory trace of the SPEC 2000 benchmark running on an SMP computer. The memory trace shows that our prediction technology can work well and at the same time, an L2 cache access simulator is developed to deal with the memory trace data. The simulation experiments show that both the shorter block transfer distance and the lower average access latency can be achieved in the PBM policy. The average block transfer distance can be reduced by up to 16.9%, and the average L2 access latency can be reduced by up to 8.4%."
featured: false
publication: "*10th IEEE International Conference on High Performance Computing and Communications, HPCC 2008, 25-27 Sept. 2008, Dalian, China*"
url_pdf: "https://doi.org/10.1109/HPCC.2008.83"
doi: "10.1109/HPCC.2008.83"
---

