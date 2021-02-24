---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "WMPP 2002 Keynote Talk: Massively Parallel Processing for Computational Genomics: Reconstructing Evolutionary Trees from Gene-Order Data"
event: "2nd Workshop on Massively Parallel Processing"
event_url: "http://www.cs.kent.edu/~parallel/workshops/ipdps02-mpp/index.html"
location: "Fort Lauderdale, FL"
address:
  street:
  city:
  region:
  postcode:
  country:

summary:
abstract: "Phylogenies derived from gene order data may prove crucial in answering some fundamental questions in biomolecular evolution. Yet very few techniques are available for phylogenetic reconstruction based upon gene order and content, and these are (for the most part) computationally expensive. High-performance algorithm engineering offers a battery of tools that can reduce, sometimes spectacularly, the running time of existing approaches. We discuss one such such application, in which we started with the method known as ``breakpoint analysis'' (developed by Sankoff and his colleagues) and produced a software suite, GRAPPA, that demonstrated a million-fold speedup in running time (on a variety of real and simulated datasets), by combining low-level algorithmic improvements, cache-aware programming, careful performance tuning, and massive parallelism. The phylogeny reconstruction now can be performed in parallel and attain a linear speedup with the number of processors. We show how these techniques are directly applicable to a large variety of problems in computational biology. (Supported in part by NSF Grants CAREER 00-93039, ITR 00-81404 and DEB 99-10123.)"

# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
date: 2002-04-19T08:30:00-04:00
date_end: 2002-04-19T09:30:00-04:00
all_day: false

# Schedule page publish date (NOT talk date).
publishDate: 2019-09-30T22:17:01-04:00

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

## Speaker Biography ##

David A. Bader is an Assistant Professor and Regents' Lecturer in the Electrical & Computer Engineering Department at The University of New Mexico. He received his Ph.D. in Electrical Engineering in 1996 from The University of Maryland, and held an NSF CISE Postdoctoral Research Associate in Experimental Computer Science before joining the University of New Mexico. David is an NSF CAREER Award recipient, and his research focuses on developing high-performance algorithms for uniform-memory-access shared-memory machines and SMP clusters with applications in the areas of computational biology, genomics, and ecology.
