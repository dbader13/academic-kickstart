---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "Arachne: An Arkouda Package for Large-Scale Graph Analytics"
authors: ["Oliver Alvarado Rodriguez", "Zhihui Du", "Joseph Patchett", "Fuhuan Li", "David Bader"]
date: 2022-09-02T15:15:56-04:00
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: 2022-09-02T15:15:56-04:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "The 26th Annual IEEE High Performance Extreme Computing Conference"
publication_short: "IEEE HPEC"

abstract: "Due to the emergence of massive real-world graphs,
whose sizes may extend to terabytes, new tools must be developed
to enable data scientists to handle such graphs efficiently. These
graphs may include social networks, computer networks, and
genomes. In this paper, we propose a novel graph package,
Arachne, to make large-scale graph analytics more effortless
and efficient based on the open-source Arkouda framework.
Arkouda has been developed to allow users to perform massively
parallel computations on distributed data with an interface
similar to NumPy. In this package, we developed a fundamental
sparse graph data structure and then built several useful graph
algorithms around our data structure to form a basic algorithmic
library. Benchmarks and tools were also developed to evaluate
and demonstrate the use of our graph algorithms. The graph
algorithms we have implemented thus far include breadth-first
search (BFS), connected components (CC), k-Truss (KT), Jaccard
coefficients (JC), triangle counting (TC), and triangle centrality
(TCE). Their corresponding experimental results based on realworld
and synthetic graphs are presented. Arachne is organized
as an Arkouda extension package and is publicly available on
GitHub (https://github.com/Bears-R-Us/arkouda-njit)."

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
