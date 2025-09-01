---
# Documentation: https://hugoblox.com/docs/managing-content/

title: "HiPerMotif: Novel Parallel Subgraph Isomorphism in Large-Scale Property Graphs"
authors: ["Mohammad Dindoost", "Oliver Alvarado Rodriguez", "Bartosz Bryg", "Ioannis Koutis", "David Bader"]
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

abstract: "Subgraph isomorphism algorithms face significant scalability bottlenecks on large-scale property graphs due to inefficient vertex-by-vertex search that requires extensive exploration of early search tree levels where pruning is minimal. We present HiPerMotif, a hybrid parallel algorithm that overcomes these limitations through edge-centric initialization. HiPerMotif first reorders pattern graphs to prioritize high-connectivity vertices, then systematically identifies and validates all possible first-edge mappings before injecting these pre-validated partial states directly at search depth 2. This approach eliminates costly early exploration while enabling natural parallelization over independent edge candidates. Comprehensive evaluation against state-of-the-art baselines (VF2-PS, VF3P, Glasgow) demonstrates up to 66x speedup on real-world networks and successful processing of massive datasets like the 150M-edge H01 human connectome that cause existing methods to fail due to memory constraints. Implemented in the open-source Arkouda/Arachne framework, HiPerMotif enables previously intractable large-scale network analysis in computational neuroscience and related domains."

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
