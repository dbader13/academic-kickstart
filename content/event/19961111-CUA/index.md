---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "Catholic University of America (CUA) Talk: Practical Parallel Algorithms for Combiantorial Problems, Data Communication, and Image Processing Applications"
event: "Department of Electrical Engineering, The Catholic University of America"
event_url:
location:
address:
  street:
  city:
  region:
  postcode:
  country:
summary:
abstract: "A fundamental challenge for parallel computing is to obtain high-level, architecture independet, algorithms which efficiently execute on general-purpose parallel machines. With the emergence of message passing standards such as MPI, it has become easier to design portable parallel algorithms making use of these primitives. We introduce our model for parallel computation and a number of techniques that allow us to derive scalable and efficient algorithms for data communication, solving combinatorial problems, and image processing applications.

While existing communication primitives allow an assortment of collective communication routines, they do not handle an important communication event when most or all processors have non-uniformly sized personalized messages to exchange with each other. This talk will focus on this event, called an 'h-relation', whose efficient implementation will allow high performance implementations of a large class of algorithms. While most previous h-relation algorithms use randomization, this talk presents a new deterministic approach for h-relation personalized communciation with asymptotically optimal complexity (for h >= p^2). As an application, we present an efficient algorithm for stable integer sorting.

These algorithms have been coded in a parallel-C programming language which follows the SPMD (single program mulitple data) paradigm, and run on a variety of parallel machines, such as, the Cray Research T3D, IBM SP-2, TMC CM-5, Intel Paragon, Meiko Scientific CS-2, and clusters of workstations. Our experimental results are consistent with the theoretical analyses and illustrate the scalability and efficiency of our algorithms across different platforms. In fact, they seem to outperform all similar algorithms known to the authors on these platforms."

# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
date: 1996-11-11T10:10:00-04:00
date_end: 1996-11-11T12:00:00-04:00
all_day: false

# Schedule page publish date (NOT event date).
publishDate: 2021-09-07T10:34:41-04:00

authors: []
tags: []

# Is this a featured event? (true/false)
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

# Optional filename of your slides within your event's folder or a URL.
url_slides:

url_code:
url_pdf:
url_video:

# Markdown Slides (optional).
#   Associate this event with Markdown slides.
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

{{<figure src="flyer.jpg">}}
