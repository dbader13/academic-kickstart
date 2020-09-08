---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "GPU Accelerated Anomaly Detection of Large Scale Light Curves"
authors: ["Austin Chase Minor", "Zhihui Du", "Yankui Sun", "David Bader", "Chao Wu", "Jianyan Wei"]
date: 2020-09-08T15:29:35-04:00
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: 2020-09-08T15:29:35-04:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "2020 IEEE High Performance Extreme Computing Conference"
publication_short: "HPEC"

abstract: "Identifying anomalies in millions of stars in real time
is a great challenge. In this paper, we develop a matched filtering
based algorithm to detect a typical anomaly, microlensing. The
algorithm can detect short timescale microlensing events with
high accuracy at their early stage with a very low false-positive
rate. Furthermore, a GPU accelerated scalable computational
framework, which can enable real time follow-up observation,
is designed. This framework efficiently divides the algorithm
between CPU and GPU, accelerating large scale light curve
processing to meet low latency requirements. Experimental
results show that the proposed method can process 200,000
stars (the maximum number of stars processed by a single
GWAC telescope) in approximately 3.34 seconds with current
commodity hardware while achieving an accuracy of 92% and an
average detection occurring approximately 14% before the peak
of the anomaly with zero false alarm. Working together with the
proposed sharding mechanism, the framework is positioned to be
extendable to multiple GPUs to improve the performance further
for the higher data throughput requirements of next-generation
telescopes."

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
