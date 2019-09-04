---
title: "A Memory and Time Scalable Parallelization of the Reptile Error-Correction Code"
date: 2016-01-01
publishDate: 2019-09-04T10:56:23.168734Z
authors: ["Vipin Sachdeva", "Srinivas Aluru", "David A. Bader"]
publication_types: ["1"]
abstract: "This paper details a distributed memory implementation of Reptile, a scalable and accurate spectrum based error-correction method. Reptile uses both k-mer and adjoining k-mers (called tiles) information along with the quality scores of bases to correct substitution-based errors from next generation sequencing machines. Previous approaches to parallelize Preptile have replicated the spectrums on each node which can be prohibitive in terms of memory needed for huge datasets. Our approach distributes both the k-mer and the tile spectrum amongst the processing ranks, relying on message passing for error correction. This allows hardware with any memory size per node to be employed for error-correction using Reptile's algorithm, irrespective of the size of the dataset. As part of our implementation, we have also implemented several heuristics which can be used to run the algorithm optimally based on the advantages of the hardware used. We present our results on IBM's BlueGene/Q architecture for the E.Coli, Drosophila and the human datasets showing excellent scalability with increasing number of nodes. Using 256 nodes of BlueGene/Q, we are able to error correct E.Coli and Drosphila datasets in less than 200 seconds and 600 seconds respectively. The human dataset consisting of 1.55 billion reads is corrected in a little more than two hours using 1024 nodes of BlueGene/Q. All three datasets are corrected with Reptile's memory intensive algorithm with less than 512 MB per process."
featured: false
publication: "*2016 IEEE International Parallel and Distributed Processing Symposium Workshops, IPDPS Workshops 2016, Chicago, IL, USA, May 23-27, 2016*"
url_pdf: "https://doi.org/10.1109/IPDPSW.2016.59"
doi: "10.1109/IPDPSW.2016.59"
---

