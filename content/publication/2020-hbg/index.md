---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Using RAPIDS AI to Accelerate Graph Data Science Workflows"
authors: ["Todd Hricik", "David Bader", "Oded Green"]
date: 2020-09-08T15:29:20-04:00
doi: "10.1109/HPEC43674.2020.9286224"

# Schedule page publish date (NOT publication's date).
publishDate: 2020-09-08T15:29:20-04:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "2020 IEEE High Performance Extreme Computing Conference"
publication_short: "HPEC"

abstract: "This Scale free networks are abundant in many natural,
social, and engineering phenomena for which there exists a substantial
corpus of theory able to elucidate many of their underlying
properties. In this paper we study the scalability of some widely
available Python-based tools for the empirical investigation of scale
free network data in a typical early stage analysis pipeline. We
demonstrate how porting serial implementations of commonly used
pipeline data structures and methods to parallel hardware via the
NVIDIA RAPIDS AI API requires minimal rewriting of code. As a utility
for each pipeline we recorded the time required to complete the
analysis for both the serial and parallelized workflows on a task-wise
basis.  Furthermore, we review a statistically based methodology for
fitting a power-law to empirical data. Maximum likelihood estimations
for scale were inferred after using Kolmogorov- Smirnov based methods
to determine location estimates. Our serial implementation of a
typical early stage network analysis workflow uses a combination of
widely used data structures and algorithms provided by the NumPy,
Pandas and NetworkX frameworks. We then parallelized our workflow
using the APIs provided by NVIDIA’s RAPIDS AI open data science
libraries and measured the relative time to completion for the tasks
of ingesting raw data, creating a graph representation of the data and
finally fitting a power-law distribution to the empirical
observations. The results of our experiments, run on graphs ranging in
size from 1 million to 20 million edges, demonstrate that
significantly less time is required to complete the tasks of
generating a graph from an edge list, computing the degree of all
nodes in the graph and fitting the scale and location parameters to
the observed data."

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
