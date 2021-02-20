---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "SPAA 2018 Keynote Talk: Massive-Scale Streaming Analytics: Models, Parallelsim, and Real-World Applications"
event: "30th ACM Symposium on Parallelism in Algorithms and Architectures"
event_url: "https://spaa.acm.org/2018/index.html"
location: "Vienna, Austria"
summary: ""
abstract: "Emerging real-world graph problems include: detecting and preventing disease in human populations; revealing community structure in large social networks; and improving the resilience of the electric power grid. Unlike traditional applications in computational science and engineering, solving these social problems at scale often raises new challenges because of the sparsity and lack of locality in the data, the need for research on scalable algorithms and development of frameworks for solving these real-world problems on high performance computers, and for improved models that capture the noise and bias inherent in the torrential data streams. Highlighting this keynote talk, Bader will discuss the opportunities and challenges in massive data-intensive computing for applications in social sciences, physical sciences, and engineering. Focusing on parallel algorithm design and implementation, Bader formalizes a practical model for graph analysis on streaming data. In this model, a massive graph undergoes changes from an input stream of edge insertions and removals. The model supports concurrent updating of the graph while algorithms execute concurrently on the dynamic data structure. The talk introduces a concept of validity: an algorithm is valid if the output is correct for a graph consisting of the initial graph with some subset of concurrent changes. Practical examples of this model are given for valid implementations of breadth first search, connected components, PageRank, and triangle counting, all useful graph kernels in real-world applications. This is joint work with E. Jason Riedy and Chunxing Yin."

# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
date: 2018-07-17T11:30:00+02:00
date_end: 2018-07-17T12:30:00+02:00
all_day: false

# Schedule page publish date (NOT talk date).
publishDate: 2019-08-22T16:50:27-04:00

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
