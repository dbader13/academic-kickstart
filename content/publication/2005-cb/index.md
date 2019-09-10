---
title: "An Empirical Analysis of Parallel Random Permutation Algorithms on SMPs"
date: 2005-01-01
publishDate: 2019-09-10T12:18:35.917315Z
authors: ["Guojing Cong", "David A. Bader"]
publication_types: ["1"]
abstract: "We compare parallel algorithms for random permutation generation on symmetric multiprocessors (SMPs). Algorithms considered are the sorting-based algorithm, Anderson's shuffling algorithm, the dart-throwing algorithm, and Sanders' algorithm. We investigate the impact of synchronization method, memory access pattern, cost of generating random numbers and other parameters on the performance of the algorithms. Within the range of inputs used and processors employed, Anderson's algorithm is preferable due to its simplicity when random number generation is relatively costly, while Sanders' algorithm has superior performance due to good cache performance when a fast random number generator is available. There is no definite winner across all settings. In fact we predict our new dart-throwing algorithm performs best when synchronization among processors becomes costly and memory access is relatively fast. We also compare the performance of our parallel implementations with the sequential implementation. It is unclear without extensive experimental studies whether fast parallel algorithms beat efficient sequential algorithms due to mismatch between model and architecture. Our implementations achieve speedups up to 6 with 12 processors on the Sun E4500. This work was supported in part by NSF Grants CAREER ACI-00-93039, NSF DBI-0420513, ITR ACI-00- 81404, DEB-99-10123, ITR EIA-01-21377, Biocomplexity DEB-01-20709, and ITR EF/BIO 03-31654; and DARPA Contract NBCH30390004."
featured: false
publication: "*Proceedings of the ISCA 18th International Conference on Parallel and Distributed Computing Systems, September 12-14, 2005 Imperial Palace Hotel, Las Vegas, Nevada, USA*"
url_pdf: "http://hdl.handle.net/1853/14385"
---

