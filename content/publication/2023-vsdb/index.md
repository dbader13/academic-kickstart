---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "Parallel Longest Common SubSequence Analysis In Chapel"
authors: ["Soroush Vahidi", "Baruch Schieber", "Zhihui Du", "David Bader"]
date: 2023-09-04T13:41:23-04:00
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: 2023-09-04T13:41:23-04:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "27th Annual IEEE High Performance Extreme Computing Conference"
publication_short: "IEEE HPEC 2023"

abstract: "One of the most critical problems in the field of string algorithms is the longest common subsequence problem (LCS). The problem is NP-hard for an arbitrary number of strings but can be solved in polynomial time for a fixed number of strings. In this paper, we select a typical parallel LCS algorithm and integrate it into our large-scale string analysis algorithm library to support different types of large string analysis. Specifically, we take advantage of the high-level parallel language, Chapel, to integrate Lu and Liu's parallel LCS algorithm into Arkouda, an open-source framework. Through Arkouda, data scientists can easily handle large string analytics on the back-end high-performance computing resources from the front-end Python interface. The Chapel-enabled parallel LCS algorithm can identify the longest common subsequences of two strings, and experimental results are given to show how the number of parallel resources and the length of input strings can affect the algorithm's performance."

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
