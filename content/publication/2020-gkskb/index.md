---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Traversing Large Graphs on GPUs with Unified Memory"
authors: ["Prasun Gera", "Hyojong Kim", "Piyush Sao", "Hyesoon Kim", "David Bader"]
date: 2020-03-20T08:54:31-04:00
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: 2020-03-20T08:54:31-04:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "Proceedings of the VLDB Endowment, 13(7):1119-1133, 2020},"
publication_short: ""

abstract: "Due to the limited capacity of GPU memory, the majority of
prior work on graph applications on GPUs has been restricted to graphs
of modest sizes that fit in memory. Recent hardware and software
advances make it possible to address much larger host memory
transparently as a part of a feature known as unified virtual
memory. While accessing host memory over an interconnect is
understandably slower, the problem space has not been sufficiently
explored in the context of a challenging workload with low
computational intensity and an irregular data access pattern such as
graph traversal. We analyse the performance of breadth first search
(BFS) for several large graphs in the context of unified memory and
identify the key factors that contribute to slowdowns. Next, we
propose a lightweight offline graph reordering algorithm, HALO
(Harmonic Locality Ordering), that can be used as a pre-processing
step for static graphs.  HALO yields speedups of 1.5x-1.9x over
baseline in subsequent traversals. Our method specifically aims to
cover large directed real world graphs in addition to undirected
graphs whereas prior methods only account for the latter.
Additionally, we demonstrate ties between the locality ordering
problem and graph compression and show that prior methods from graph
compression such as recursive graph bisection can be suitably adapted
to this problem."

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
