---
title: "Faster Clustering Coefficient Using Vertex Covers"
date: 2013-01-01
publishDate: 2019-09-10T12:18:34.684118Z
authors: ["Oded Green", "David A. Bader"]
publication_types: ["paper-conference"]
abstract: "Clustering coefficients, also called triangle counting, is a widely-used graph analytic for measuring the closeness in which vertices cluster together. Intuitively, clustering coefficients can be thought of as the ratio of common friends versus all possible connections a person might have in a social network. The best known time complexity for computing clustering coefficients uses adjacency list intersection and is O(V · d max 2 ), where d max is the size of the largest adjacency list of all the vertices in the graph. In this work, we show a novel approach for computing the clustering coefficients in an undirected and unweighted graphs by exploiting the use of a vertex cover, V̂ ⊆ V. This new approach reduces the number of times that a triangle is counted by as many as 3 times per triangle. The complexity of the new algorithm is O(V̂ · ĥ max 2 + t VC ) where d̂ max is the size of the largest adjacency list in the vertex cover and t VC is the time needed for finding the vertex cover. Even for a simple vertex cover algorithm this can reduce the execution time 10-30% while counting the exact number of triangles (3-circuits). We extend the use of the vertex cover to support counting squares (4-circuits) and clustering coefficients for dynamic graphs."
featured: false
publication: "*International Conference on Social Computing, SocialCom, Washington, DC, USA, 8-14 September, 2013*"
url_pdf: "https://doi.org/10.1109/SocialCom.2013.51"
doi: "10.1109/SocialCom.2013.51"
---

