---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "A Simple and Efficient Algorithm for Finding Minimum Spanning Tree Replacement Edges"
authors: ["David Bader", "Paul Burkhardt"]
date: 2022-12-20T10:51:51+05:30
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: 2022-12-20T10:51:51+05:30

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "Journal of Graph Algorithms and Applications"
publication_short: "JGAA"

abstract: "Given an undirected, weighted graph, the minimum spanning tree (MST)is a tree that connects all of the vertices of the graph with minimum sum of edge weights. In real world applications, network designers often seek to quickly find a replacement edge for each edge in the MST. For example, when a traffic accident closes a road in a transportation network, or a line goes down in a communication network, the replacement edge may reconnect the MST at lowest cost. In the paper, we consider the case of finding the lowest cost replacement edge for each edge of the MST. A previous algorithm by Tarjan takes O{m \alpha(m, n)} time and space, where $\alpha(m, n)$ is the inverse Ackermann's function. Given the MST and sorted non-tree edges, our algorithm is the first practical algorithm that runs in O(m+n) time and O(m+n) space to find all replacement edges. Additionally, since the most vital edge is the tree edge whose removal causes the highest cost, our algorithm finds it in linear time."

# Summary. An optional shortened abstract.
summary: ""

tags: []
categories: []
featured: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_pdf:
url_code:
url_dataset:
url_poster:
url_project:
url_slides:
url_source:
url_video:

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ""
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---
