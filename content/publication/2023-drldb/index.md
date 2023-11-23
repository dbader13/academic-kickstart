---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "Minimum-Mapping based Connected Components Algorithm"
authors: ["Zhihui Du", "Oliver Alvarado Rodriguez", "Fuhuan Li", "Mohammad Dindoost", "David Bader"]
date: 2023-05-24T12:38:41-04:00
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: 2023-05-24T12:38:41-04:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["paper-conference"]

# Publication name and optional abbreviated publication name.
publication: "The 10th Annual Chapel Implementers and Users Workshop"
publication_short: "CHIUW"

abstract: "Finding connected components is a fundamental problem in graph analysis. We develop a novel minimum-
mapping based Contour algorithm to solve the connectivity problem. The Contour algorithm can identify
all connected components of an undirected graph within O (log 𝑑𝑚𝑎𝑥 ) iterations on 𝑚 parallel processors,
where 𝑑𝑚𝑎𝑥 is the largest diameter of all components in a given graph and 𝑚 is the total number of edges
of the given graph. Furthermore, each iteration can easily be parallelized by employing the highly efficient
minimum-mapping operator on all edges. To improve performance, the Contour algorithm is further optimized
through asynchronous updates and simplified atomic operations. Our algorithm has been integrated into an
open-source framework, Arachne, that extends Arkouda for large-scale interactive graph analytics with a
Python API powered by the high-productivity parallel language Chapel. Experimental results on real-world and
synthetic graphs show that the proposed Contour algorithm needs less number of iterations and can achieve
5.26 folds of speedup on average compared with the state-of-the-art connected component method FastSV
implemented in Chapel. All code is publicly available on GitHub (https://github.com/Bears-R-Us/arkouda-njit)."

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
