---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "Tunnel: Parallel-inducing sort for large string analytics"
authors: ["Zhihui Du", "Sen Zhang", "David Bader"]
date: 2023-08-11T12:37:19-04:00
doi: "10.1016/j.future.2023.08.009"

# Schedule page publish date (NOT publication's date).
publishDate: 2023-08-11T12:37:19-04:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "Future Generation Computer Systems (Elsevier)"
publication_short: "FGCS"

abstract: "The suffix array is a crucial data structure for efficient
 string analysis. Over the course of twenty-six years, sequential
 suffix array construction algorithms have achieved O(n) time
 complexity and in-place sorting. In this paper, we present the *Tunnel*
 algorithm, the first large-scale parallel suffix array construction
 algorithm with a time complexity of O(n/p) based on the parallel
 random access machine (PRAM) model. The *Tunnel* algorithm is built on
 three key ideas: dividing the problem of size O(n) into p
 sub-problems of reduced size O(n/p) by replacing long suffixes with
 shorter prefixes of size at most a constant D ; introducing a *Tunnel*
 mechanism to efficiently induce the order of a set of suffixes with
 long common prefixes; developing a strategy to transform a partially
 ordered suffix set into a total order relation by iteratively
 applying the *Tunnel* inducing method. We provide a detailed
 description of the algorithm, along with a thorough analysis of its
 time and space complexity, to demonstrate its correctness and
 efficiency. The proposed *Tunnel* algorithm exhibits scalable
 performance, making it suitable for large string analytics on
 large-scale parallel systems."

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
