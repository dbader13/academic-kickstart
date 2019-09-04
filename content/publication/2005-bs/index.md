---
title: "A Cache-Aware Parallel Implementation of the Push-Relabel Network Flow Algorithm and Experimental Evaluation of the Gap Relabeling Heuristic"
date: 2005-01-01
publishDate: 2019-09-04T10:56:25.213275Z
authors: ["David A. Bader", "Vipin Sachdeva"]
publication_types: ["1"]
abstract: "The maximum flow problem is a combinatorial problem of significant importance in a wide variety of research and commercial applications. It has been extensively studied and implemented over the past 40 years. The push-relabel method has been shown to be superior to other methods, both in theoretical bounds and in experimental implementations. Our study discusses the implementation of the push-relabel network flow algorithm on present-day symmetric multiprocessors (SMP's) with large shared memories. The maximum flow problem is an irregular graph problem and requires frequent fine-grained locking of edges and vertices. Over a decade ago, Anderson and Setubal implemented Goldberg's push-relabel algorithm for shared memory parallel computers; however, modern systems differ significantly from those targeted by their implementation in that SMP's today have deep memory hierarchies and different performance costs for synchronization and fine-grained locking. Besides our new cache-aware implementation of Goldberg's parallel algorithm for modern shared-memory parallel computers, our main new contribution is the first parallel implementation and analysis of the gap relabeling heuristic that runs from 2.1 to 4.3 times faster for sparse graphs."
featured: false
publication: "*Proceedings of the ISCA 18th International Conference on Parallel and Distributed Computing Systems, September 12-14, 2005 Imperial Palace Hotel, Las Vegas, Nevada, USA*"
url_pdf: "http://hdl.handle.net/1853/14384"
---

