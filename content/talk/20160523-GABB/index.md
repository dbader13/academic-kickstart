---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "GABB 2016 Keynote Talk: Massive-scale Streaming Analytics"
event: "Graph Algorithms Building Blocks"
event_url: "http://graphanalysis.org/workshop2016.html"
location: "Chicago, IL"
summary: ""
abstract: "Emerging real-world graph problems include: detecting community structure in large social networks; improving the resilience of the electric power grid; and detecting and preventing disease in human populations. Unlike traditional applications in computational science and engineering, solving these problems at scale often raises new challenges because of the sparsity and lack of locality in the data, the need for additional research on scalable algorithms and development of frameworks for solving these problems on high performance computers, and the need for improved models that also capture the noise and bias inherent in the torrential data streams. In this talk, I will discuss opportunities and challenges in massive data-intensive computing for applications in computational science and engineering."

# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
date: 2016-05-23T13:30:00-04:00
date_end: 2016-05-23T14:30:00-04:00
all_day: false

# Schedule page publish date (NOT talk date).
publishDate: 2019-08-23T12:49:12-04:00

authors: []
tags: []

# Is this a featured talk? (true/false)
featured: false

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

# Optional filename of your slides within your talk's folder or a URL.
url_slides:

url_code:
url_pdf:
url_video:

# Markdown Slides (optional).
#   Associate this talk with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: ""

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects: []
---

The Basic Linear Algebra Subprograms, introduced over 30 years ago, had a transformative effect on software for linear algebra. With the BLAS, researchers spend less time mapping algorithms onto specific features of hardware platforms and more time on interesting new algorithms.

Would it be practical to define an analogous set of basic building blocks for graph algorithms?  Can we define a core set of mathematical primitives from which we can build most (if not all) important graph algorithms? If we can agree on the mathematical foundations, how would these interact with the data structures used in graph algorithms and result in an API the graph algorithms research community could support?

These questions will be the topic for the third “Graph Algorithms Building Blocks” workshop.  Our goal is an interactive workshop where the full range of issues behind “Graph Algorithms Building Blocks” will be explored.   We want an interactive “workshop” so papers that report preliminary results and unproven but interesting ideas will be considered.
