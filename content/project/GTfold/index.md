---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "GTfold"
summary: "Scalable Multicore Code for RNA Secondary Structure Prediction"
authors: []
tags: []
categories: []
date: 2015-01-01T07:47:41-04:00

# Optional external URL for project (replaces project detail page).
external_link: "http://gtfold.sourceforge.net/"

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ""
  focal_point: ""
  preview_only: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_code: ""
url_pdf: ""
url_slides: ""
url_video: ""

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: ""
---

The GTfold package includes fast, scalable multicore code for predicting RNA secondary structure that is one to two orders of magnitude faster than the de facto standard programs and achieves comparable accuracy of prediction.

We are seeing a paradigm shift to multicore chips and parallelism must be explicitly addressed to continue gaining performance with each new generation of systems. GTfold, which is implemented in C/C++ and uses OpenMP primitives for parallelization of the algorithm, opens up a new path for the algorithmic improvements and the application of improved thermodynamic models to increase prediction accuracy.

GTfold now includes related programs such as RNAStructProfiling, RNAStructViz, and NNTMParameterEditor. The details of these additional programs can be found on the Github page; details for compiling and running RNA profiling can be found on the Related page.

If you wish to download and compile GTfold from the latest source code, please visit the Develop page or the Github page.
