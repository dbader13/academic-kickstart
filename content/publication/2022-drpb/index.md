---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "Interactive Graph Analytics at Scale in Arkouda"
authors: ["Zhihui Du", "Oliver Alvarado Rodriguez", "Joseph Patchett", "David Bader"]
date: 2022-07-20T10:12:39-05:00
doi: "10.1201/9781003033707"

# Schedule page publish date (NOT publication's date).
publishDate: 2022-07-20T10:12:39-05:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["6"]

# Publication name and optional abbreviated publication name.
publication: "Massive Graph Analytics"
publication_short: ""

abstract: "Data from many real-world applications often can be
abstracted as graphs. However, the increasing graph size makes it
impossible for existing popular exploratory data analysis tools to
handle large data sets in the memory of a common laptop/personal
computer. Arkouda is a framework under early development that brings
together the productivity of Python at the user side with the
high-performance of Chapel at the server side. In this work, a
succinct double-index data structure is designed to build a static
graph and the sketch of a graph stream with much less memory
footprint. Two typical graph algorithms, Breadth-First Search (BFS)
and triangle counting algorithms, are developed to evaluate the
efficiency of the proposed graph analytics workflow.  Experimental
results show that our method can take advantage of distributed
resources to handle large graphs. This work provides the large and
rapidly growing Python community a powerful way to handle terabyte and
beyond graph data using their laptops. All our methods and code have
been implemented in Arkouda and are available from GitHub
(https://github.com/Bader-Research/arkouda/tree/streaming)."

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
