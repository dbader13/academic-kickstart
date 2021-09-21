---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "Large Scale String Analytics In Arkouda"
authors: ["Zhihui Du", "Oliver Alvarado Rodriguez", "David Bader"]
date: 2021-09-21T11:38:01-04:00
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: 2021-09-21T11:38:01-04:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "The 25th Annual IEEE High Performance Extreme Computing Conference"
publication_short: "IEEE HPEC"

abstract: "Large scale data sets from the web, social networks, and bioinformatics are widely available and can often be represented by strings and suffix arrays are highly efficient data structures enabling string analysis.  But, our personal devices and corresponding exploratory data analysis (EDA) tools cannot handle big data sets beyond the local memory. Arkouda is a framework under early development that brings together the productivity of Python at the user side with the high-performance of Chapel at the server-side. In this paper, an efficient suffix array data structure design and integration method are given first. A suffix array algorithm library integration method instead of one single suffix algorithm is presented to enable runtime performance optimization in Arkouda since different suffix array algorithms may have very different practical performances for strings in various applications. A parallel suffix array construction algorithm framework is given to further exploit hierarchical parallelism on multiple locales in Chapel.  A corresponding benchmark is developed to evaluate the feasibility of the provided suffix array integration method and measure the end-to-end performance. Experimental results show that the proposed solution can provide data scientists an easy and efficient method to build suffix arrays with high performance in Python. All our codes are open source and available from GitHub (https://github.com/Bader-Research/arkouda/tree/string-suffix-array-functionality)."

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
