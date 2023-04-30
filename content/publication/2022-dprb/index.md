---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "High-Performance Truss Analysis in Arkouda"
authors: ["Zhihui Du", "Joseph Patchett", "Oliver Alvarado Rodriguez", "Fuhuan Li", "David Bader"]
date: 2022-10-29T17:14:31-04:00
doi: "10.1109/HiPC56025.2022.00026"

# Schedule page publish date (NOT publication's date).
publishDate: 2022-10-29T17:14:31-04:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "The 29th IEEE International Conference on  High Performance Computing, Data, and Analytics"
publication_short: "HiPC 2022"

abstract: "In graph analytics, the Truss is a cohesive subgraph based on the number of triangles supporting each edge. It is widely used for community detection applications such as social networks and security analysis, and the performance of Truss analytics highly depends on its triangle counting method. This paper proposes a novel triangle counting kernel named Minimum Search (MS). Minimum Search can select two smaller adjacency lists out of three and uses fine-grained parallelism to improve the performance of triangle counting. Then, two basic algorithms, MS-based triangle counting and MS-based support updating are developed. Based on the novel kernel and two basic algorithms, three fundamental parallel truss analytics algorithms are designed and implemented to enable different kinds of graph truss analysis. These truss algorithms include an optimized K-Truss algorithm, a Max-Truss algorithm, and a Truss Decomposition algorithm. Moreover, all proposed algorithms have been implemented in the parallel language Chapel and integrated into an open-source framework, Arkouda. Through Arkouda, data scientists can efficiently conduct graph analysis through an easy-to-use Python interface and handle large-scale graph data in powerful back-end computing resources. Experimental results show that the proposed methods can significantly improve the performance of truss analysis on real-world graphs compared with the existing and widely adopted list intersection-based method. The implemented code is publicly available from GitHub: https://github.com/Bears-R-Us/arkouda-njit"

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
