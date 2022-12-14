---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "Truss Analytics Algorithms and Integration in Arkouda"
authors: ["Zhihui Du", "Joseph Patchett", "Oliver Alvarado Rodriguez", "David Bader"]
date: 2022-06-10T20:46:27-05:00
doi: ""

# Schedule page publish date (NOT publication's date).

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "The 9th Annual Chapel Implementers and Users Workshop"
publication_short: "CHIUW"

abstract: "The K-Truss of a graph is a cohesive subgraph that has been
widely used for community detection in applications such as social
networks and security analysis. In this paper, we first propose one
optimized triangle search kernel with a few operations that can be
used in both triangle counting and triangle search to replace the
existing list intersection method. Based on the optimized kernel,
three truss analytics algorithms, an optimized K-Truss parallel
algorithm, a maximal K-Truss parallel algorithm, and a Truss
decomposition parallel algorithm, are developed to enable different
kinds of graph analysis efficiently. Moreover, all proposed parallel
algorithms have been implemented in the highly-productive parallel
language Chapel and integrated into the opensource framework
Arkouda. Experimental results compared with the existing list
intersection-based method show that for both synthetic and real-world
graphs, the proposed method can significantly improve the performance
of truss analysis on large graphs. The implemented method is publicly
available from GitHub (https://github.com/Bears-R-Us/arkouda-njit)."

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
