---
# Documentation: https://wowchemy.com/docs/managing-content/

#
title: "Anti-Section Transitive Closure"
authors: ["Oded Green", "Zhihui Du", "Sanyamee Patel", "Zehui Xie", "Hang Liu", "David Bader"]
date: 2021-12-17T18:35:00-05:00
doi: "10.1109/HiPC53243.2021.00033"

# Schedule page publish date (NOT publication's date).
publishDate: 2021-12-17T18:35:00-05:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["paper-conference"]

# Publication name and optional abbreviated publication name.
publication: "The 28th IEEE International Conference on  High Performance Computing, Data, and Analytics"
publication_short: "HiPC 2021"

abstract: "The transitive closure of a graph is a new graph where
every vertex is directly connected to all vertices to which it had a
path in the original graph. Transitive closures are useful for
reachability and relationship querying. Finding the transitive closure
can be computationally expensive and requires a large memory footprint
as the output is typically larger than the input.  Some of the
original research on transitive closures assumed that graphs were
dense and used dense adjacency matrices. We have since learned that
many real-world networks are extremely sparse, and the existing
methods do not scale. In this work, we introduce a new algorithm
called Anti-section Transitive Closure (ATC) for finding the
transitive closure of a graph. We present a new parallel edges
operation – anti-sections – for finding new edges to reachable
vertices. ATC scales to massively multithreaded systems such as
NVIDIA’s GPU with tens of thousands of threads. We show that the
anti-section operation shares some traits with the triangle counting
intersection operation in graph analysis. Lastly, we view the
transitive closure problem as a dynamic graph problem requiring edge
insertions. By doing this, our memory footprint is smaller. We also
show a method for creating the batches in parallel using two different
techniques: dual-round and hash. Using these techniques and the Hornet
dynamic graph data structure, we show our new algorithm on an NVIDIA
Titan V GPU. We compare with other packages such as NetworkX,
SEI-GBTL, SuiteSparse, and cuSparse."

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
