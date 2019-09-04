---
title: "Parallel algorithms for image enhancement and segmentation by region growing, with an experimental study"
date: 1996-01-01
publishDate: 2019-09-04T10:56:26.872232Z
authors: ["David A. Bader", "Joseph JáJá", "David Harwood", "Larry S. Davis"]
publication_types: ["2"]
abstract: "This paper presents efficient and portable implementations of a powerful image enhancement process, the Symmetric Neighborhood Filter (SNF), and an image segmentation technique that makes use of the SNF and a variant of the conventional connected components algorithm which we call δ-Connected Components. We use efficient techniques for distributing and coalescing data as well as efficient combinations of task and data parallelism. The image segmentation algorithm makes use of an efficient connected components algorithm based on a novel approach for parallel merging. The algorithms have been coded in Split-C and run on a variety of platforms, including the Thinking Machines CM-5, IBM SP-1 and SP-2, Cray Research T3D, Meiko Scientific CS-2, Intel Paragon, and workstation clusters. Our experimental results are consistent with the theoretical analysis (and provide the best known execution times for segmentation, even when compared with machine-specific implementations). Our test data include difficult images from the Landsat Thematic Mapper (TM) satellite data."
featured: false
publication: "*The Journal of Supercomputing*"
url_pdf: "https://doi.org/10.1007/BF00130707"
doi: "10.1007/BF00130707"
---

