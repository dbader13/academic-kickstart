---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "Triangle Counting Through Cover-Edges (Graph Challenge Student Innovation Award)"
authors: ["David Bader", "Fuhuan Li", "Anya Ganeshan", "Ahmet Gundogdu", "Jason Lew", "Oliver Alvarado Rodriguez", "Zhihui Du"]
date: 2023-09-04T13:42:20-04:00
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: 2023-09-04T13:42:20-04:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "27th Annual IEEE High Performance Extreme Computing Conference"
publication_short: "IEEE HPEC 2023"

abstract: "Counting and finding triangles in graphs is often used in real-world analytics to characterize cohesiveness and identify communities in graphs. In this paper, we propose the novel concept of a cover-edge set that can be used to find triangles more efficiently. We use a breadth-first search (BFS) to quickly generate a compact cover-edge set. Novel sequential and parallel triangle counting algorithms are presented that employ cover-edge sets. The sequential algorithm avoids unnecessary triangle-checking operations, and the parallel algorithm is communication-efficient. The parallel algorithm can asymptotically reduce communication on massive graphs such as from real social networks and synthetic graphs from the Graph500 Benchmark. In our estimate from massive-scale Graph500 graphs, our new parallel algorithm can reduce the communication on a scale 36 graph by 1156x and  on a scale 42 graph by 2368x."

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
