---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "Interactive Graph Stream Analytics in Arkouda"
authors: ["Zhihui Du", "Oliver Alvarado Rodriguez", "Joseph Patchett", "David Bader"]
date: 2021-07-21T11:50:49-04:00
doi: "10.3390/a14080221"

# Schedule page publish date (NOT publication's date).
publishDate: 2021-07-21T11:50:49-04:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "Algorithms"
publication_short: ""

abstract: "Data from emerging applications, such as cybersecurity and
social networking, can be abstracted as graphs whose edges are updated
sequentially in the form of a stream. The challenging problem of
interactive graph stream analytics is the quick response of the
queries on terabyte and beyond graph stream data from end users. In
this paper, a succinct and efficient double index data structure is
designed to build the sketch of a graph stream to meet general
queries. A single pass stream model, which includes general sketch
building, distributed sketch based analysis algorithms and regression
based approximation solution generation, is developed, and a typical
graph algorithm—triangle counting—is implemented to evaluate the
proposed method. Experimental results on power law and normal
distribution graph streams show that our method can generate accurate
results (mean relative error less than 4%) with a high
performance. All our methods and code have been implemented in an open
source framework, Arkouda, and are available from our GitHub
repository, Bader-Research. This work provides the large and rapidly
growing Python community with a powerful way to handle terabyte and
beyond graph stream data using their laptops."

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
