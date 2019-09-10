---
title: "Multithreaded Community Monitoring for Massive Streaming Graph Data"
date: 2013-01-01
publishDate: 2019-09-10T12:18:34.603904Z
authors: ["E. Jason Riedy", "David A. Bader"]
publication_types: ["1"]
abstract: "Analyzing static snapshots of massive, graph-structured data cannot keep pace with the growth of social networks, financial transactions, and other valuable data sources. Current state-of-the-art industrial methods analyze these streaming sources using only simple, aggregate metrics. There are few existing scalable algorithms for monitoring complex global quantities like decomposition into community structure. Using our framework STING, we present the first known parallel algorithm specifically for monitoring communities in this massive, streaming, graph-structured data. Our algorithm performs incremental re-agglomeration rather than starting from scratch after each batch of changes, reducing the problem's size to that of the change rather than the entire graph. We analyze our initial implementation's performance on multithreaded platforms for execution time and latency. On an Intel-based multithreaded platform, our algorithm handles up to 100 million updates per second on social networks with one to 30 million edges, providing a speed-up from 4x to 3700x over statically recomputing the decomposition after each batch of changes. Possibly because of our artificial graph generator, resulting communities' modularity varies little from the initial graph."
featured: false
publication: "*2013 IEEE International Symposium on Parallel & Distributed Processing, Workshops and Phd Forum, Cambridge, MA, USA, May 20-24, 2013*"
url_pdf: "https://doi.org/10.1109/IPDPSW.2013.229"
doi: "10.1109/IPDPSW.2013.229"
---

