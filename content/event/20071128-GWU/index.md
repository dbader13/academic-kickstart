---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "GWU Invited Talk: Petascale Phylogenetic Reconstruction of Evolutionary Histories"
event: "George Washington University"
event_url:
location: "Washington, DC"
address:
  street:
  city:
  region:
  postcode:
  country:
summary:
abstract: "Computational science enables us to investigate phenomena where economics or constraints preclude experimentation, evaluate complex models and manage massive data volumes, model processes across interdisciplinary boundaries, and transform business and engineering practices. Increasingly, cyberinfrastructure including petascale computers is required to address our national and global priorities, such as sustainability of our natural environment by reducing our carbon footprint and by decreasing our dependencies on fossil fuels, improving human health and living conditions, understanding the mechanisms of life from molecules and systems to organisms and populations, preventing the spread of disease, predicting and tracking severe weather, recovering from natural and human-caused disasters, maintaining national security, and mastering nanotechnologies. Several of our most fundamental intellectual questions also require computation, such as the formation of the universe, the the evolution of life, and the properties of matter. 

In this talk, we focus on the grand challenge to reconstruct the tree of life. Phylogenies derived from gene order data may prove crucial in answering some fundamental questions in biomolecular evolution. Yet very few techniques are available for phylogenetic reconstruction based upon gene order and content, and these are (for the most part) computationally expensive. High-performance algorithm engineering offers a battery of tools that can reduce, sometimes spectacularly, the running time of existing approaches. We discuss one such such application, in which we started with the method known as *breakpoint analysis* (developed by Sankoff and his colleagues) and produced a software suite, GRAPPA, that demonstrated over a billion-fold speedup in running time (on a variety of real and simulated datasets), by combining low-level algorithmic improvements, cache-aware programming, careful performance tuning, and massive parallelism. The phylogeny reconstruction now can be performed in parallel and attain a linear speedup with the number of processors. We show how these techniques are directly applicable to a large variety of problems in computational biology."

# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
date: 2007-11-28T11:00:00-04:00
date_end: 2007-11-28T12:00:00-04:00
all_day: false

# Schedule page publish date (NOT event date).
publishDate: 2023-11-04T11:38:59-04:00

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
