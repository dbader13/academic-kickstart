---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "Billion-scale Detection of Isomorphic Nodes"
authors: ["Luca Cappelletti", "Tommaso Fontana", "Justin Reese", "David Bader"]
date: 2023-05-15T00:00:00-04:00
doi: "10.1109/IPDPSW59300.2023.00046"

# Schedule page publish date (NOT publication's date).
publishDate: 2023-05-13T00:00:00-04:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["paper-conference"]

# Publication name and optional abbreviated publication name.
publication: "Workshop on Graphs, Architectures, Programming, and Learning, IEEE International Parallel and Distributed Processing Symposium (IPDPS)"
publication_short: "IEEE GrAPL"

abstract: "This paper presents an algorithm for detecting attributed
high-degree node isomorphism. High-degree isomorphic
nodes seldom happen by chance and often represent duplicated
entities or data processing errors. By definition, isomorphic nodes
are topologically indistinguishable and can be problematic in
graph ML tasks. The algorithm employs a parallel, “degreebounded”
approach that fingerprints each node’s local properties
through a hash, which constrains the search to nodes within hashdefined
buckets, thus minimising the number of comparisons.
This method scales on graphs with billions of nodes and edges.
Finally, we provide isomorphic node oddities identified in realworld
data."

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
