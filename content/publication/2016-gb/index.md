---
title: "cuSTINGER: Supporting dynamic graph algorithms for GPUs"
date: 2016-01-01
publishDate: 2019-09-10T12:18:34.044331Z
authors: ["Oded Green", "David A. Bader"]
publication_types: ["1"]
abstract: "cuSTINGER, a new graph data structure targeting NVIDIA GPUs is designed for streaming graphs that evolve over time. cuSTINGER enables algorithm designers greater productivity and efficiency for implementing GPU-based analytics, relieving programmers of managing memory and data placement. In comparison with static graph data structures, which may require transferring the entire graph back and forth between the device and the host memories for each update or require reconstruction on the device, cuSTINGER only requires transferring the updates themselves; reducing the total amount of data transferred. cuSTINGER gives users the flexibility, based on application needs, to update the graph one edge at a time or through batch updates. cuSTINGER supports extremely high update rates, over 1 million updates per second for mid-size batched with 10k updates and 10 million updates per second for large batches with millions of updates."
featured: false
publication: "*2016 IEEE High Performance Extreme Computing Conference, HPEC 2016, Waltham, MA, USA, September 13-15, 2016*"
url_pdf: "https://doi.org/10.1109/HPEC.2016.7761622"
doi: "10.1109/HPEC.2016.7761622"
---

