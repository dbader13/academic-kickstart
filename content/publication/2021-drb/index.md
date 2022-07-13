---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "Enabling Exploratory Large Scale Graph Analytics through Arkouda"
authors: ["Zhihui Du", "Oliver Alvarado Rodriguez", "David Bader"]
date: 2021-09-21T11:37:49-04:00
doi: "10.1109/HPEC49654.2021.9622860"

# Schedule page publish date (NOT publication's date).
publishDate: 2021-09-21T11:37:49-04:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "The 25th Annual IEEE High Performance Extreme Computing Conference"
publication_short: "IEEE HPEC"

abstract: "Exploratory graph analytics helps maximize the informational value from a graph. However, the increasing graph size makes it impossible for existing popular exploratory data analysis tools to handle dozens-of-terabytes or even larger data sets in the memory of a common laptop/personal computer. Arkouda is a framework under early-development that brings together the productivity of Python at the user side with the high-performance of Chapel at the server side. In this paper, we present preliminary work on overcoming the memory limit and high performance computing coding roadblock for high level Python users to perform large graph analysis. A simple and succinct graph data structure design and implementation at both the Python front-end and the Chapel back-end in the Arkouda framework are provided. A typical graph algorithm, Breadth-First Search (BFS), is used to show how we can use Chapel to develop high performance parallel graph algorithm productively. Two Chapel-based parallel Breadth-First Search (BFS) algorithms, one high level version and one corresponding low level version, have been implemented in Arkouda to support analyzing large graphs. Multiple graph benchmarks are used to evaluate the performance of the provided graph algorithms. Experimental results show that we can optimize the performance by tuning the selection of different Chapel high level data structures and parallel constructs. Our code is open source and available from GitHub (https://github.com/Bader-Research/arkouda)."

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
