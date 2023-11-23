---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "Scalable Katz Ranking Computation in Large Static and Dynamic Graphs"
authors: ["Alexander van der Grinten", "Elisabetta Bergamini", "Oded Green", "David Bader", "Henning Meyerhenke"]
date: 2022-03-23T10:42:09-04:00
doi: "10.1145/3524615"

# Schedule page publish date (NOT publication's date).
publishDate: 2022-03-23T10:42:09-04:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["article-journal"]

# Publication name and optional abbreviated publication name.
publication: "ACM Journal on Experimental Algorithmics"
publication_short: "ACM JEA"

abstract: "Network analysis defines a number of centrality measures to
identify the most central nodes in a network. Fast computation of
those measures is a major challenge in algorithmic network
analysis. Aside from closeness and betweenness, Katz centrality is one
of the established centrality measures. In this paper, we consider the
problem of computing rankings for Katz centrality. In particular, we
propose upper and lower bounds on the Katz score of a given
node. While previous approaches relied on numerical approximation or
heuristics to compute Katz centrality rankings, we construct an
algorithm that iteratively improves those upper and lower bounds until
a correct Katz ranking is obtained. We extend our algorithm to dynamic
graphs while maintaining its correctness guarantees.  Experiments
demonstrate that our static graph algorithm outperforms both numerical
approaches and heuristics with speedups between 1.5× and 3.5×,
depending on the desired quality guarantees. Our dynamic graph
algorithm improves upon the static algorithm for update batches of
less than 10000 edges. We provide efficient parallel CPU and GPU
implementations of our algorithms that enable near real-time Katz
centrality computation for graphs with hundreds of millions of edges
in fractions of seconds."

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
