n---
# Documentation: https://hugoblox.com/docs/managing-content/

title: "Designing Parallel Algorithms for Community Detection using Arachne"
authors: ["Fuhuan Li", "Zhihui Du", "David Bader"]
date: 2025-09-01T10:27:03-04:00
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: 2025-09-01T10:27:03-04:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["paper-conference"]

# Publication name and optional abbreviated publication name.
publication: "29th Annual IEEE High Performance Extreme Computing Conference"
publication_short: "IEEE HPEC 2025"

abstract: "The rise of graph data in various fields calls for efficient and scalable community detection algorithms. In this paper, we present parallel implementations of two widely used algorithms: Label Propagation and Louvain, specifically designed to leverage the capabilities of Arachne, which is a Python-accessible open-source framework for large-scale graph analysis. Our implementations achieve substantial speedups over existing Python-based tools like NetworkX and igraph, which lack efficient parallelization, and are competitive with parallel frameworks such as NetworKit. Experimental results show that Arachne-based methods outperform these baselines, achieving speedups of up to 710x over NetworkX, 75x over igraph, and 12x over NetworKit. Additionally, we analyze the scalability of our implementation under varying thread counts, demonstrating how different phases contribute to overall performance gains of the parallel Louvain algorithm. Arachne, including our community detection implementation, is open-source and available at https://github.com/Bears-R-Us/arkouda-njit ."

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
