---
title: "A Fast Algorithm for Streaming Betweenness Centrality"
date: 2012-01-01
publishDate: 2019-09-04T10:56:23.949784Z
authors: ["Oded Green", "Robert McColl", "David A. Bader"]
publication_types: ["1"]
abstract: "Analysis of social networks is challenging due to the rapid changes of its members and their relationships. For many cases it impractical to recompute the metric of interest, therefore, streaming algorithms are used to reduce the total runtime following modifications to the graph. Centrality is often used for determining the relative importance of a vertex or edge in a graph. The vertex Betweenness Centrality is the fraction of shortest paths going through a vertex among all shortest paths in the graph. Vertices with a high betweenness centrality are usually key players in a social network or a bottleneck in a communication network. Evaluating the betweenness centrality for a graph G = (V, E) is computationally demanding and the best known algorithm for unweighted graphs has an upper bound time complexity of O(V 2 + VE). Consequently, it is desirable to find a way to avoid a full re-computation of betweenness centrality when a new edge is inserted into the graph. In this work, we give a novel algorithm that reduces computation for the insertion of an edge into the graph. This is the first algorithm for the computation of betweenness centrality in a streaming graph. While the upper bound time complexity of the new algorithm is the same as the upper bound for the static graph algorithm, we show significant speedups for both synthetic and real graphs. For synthetic graphs the speedup varies depending on the type of graph and the graph size. For synthetic graphs with 16384 vertices the average speedup is between 100X - 400X. For five different real world collaboration networks the average speedup per graph is in range of 36X - 148X."
featured: false
publication: "*2012 International Conference on Privacy, Security, Risk and Trust, PASSAT 2012, and 2012 International Confernece on Social Computing, SocialCom 2012, Amsterdam, Netherlands, September 3-5, 2012*"
url_pdf: "https://doi.org/10.1109/SocialCom-PASSAT.2012.37"
doi: "10.1109/SocialCom-PASSAT.2012.37"
---

