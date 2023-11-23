---
title: "WEC: Improving Durability of SSD Cache Drives by Caching Write-Efficient Data"
date: 2015-01-01
publishDate: 2019-09-10T12:18:37.226572Z
authors: ["Yunpeng Chai", "Zhihui Du", "Xiao Qin", "David A. Bader"]
publication_types: ["article-journal"]
abstract: "Serving as cache disks, flash-based solid-state drives (SSDs) can significantly boost the performance of read-intensive applications. However, frequent data updating, the necessary condition for classical replacement algorithms (e.g., LRU, MQ, LIRS, and ARC) to achieve a high hit rate, makes SSDs wear out quickly. To address this problem, we propose a new approach-write-efficient caching (WEC)-to greatly improve the write durability of SSD cache. WEC is conducive to reducing the total number of writes issued to SSDs while achieving high hit rates. WEC takes two steps to improve write durability and performance of SSD cache. First, WEC discovers write-efficient data, which tend to be active for a long time period and to be frequently accessed. Second, WEC keeps the write-efficient data in SSDs long enough to avoid excessive number of unnecessary updates. Our findings based on a wide range of popular real-world traces show that write-efficient data does exist in a wide range of popular read-intensive applications. Our experimental results indicate that compared with the classical algorithms, WEC judiciously improves the mean hits of each written block by approximately two orders of magnitude while exhibiting similar or even higher hit rates."
featured: false
publication: "*IEEE Transactions on Computers*"
url_pdf: "https://doi.org/10.1109/TC.2015.2401029"
doi: "10.1109/TC.2015.2401029"
---

