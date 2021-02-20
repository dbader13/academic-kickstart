---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "HIPC 2001 Keynote Talk: Using PRAM Algorithms on a Uniform Memory Access Shared-Memory Architecture"
event: "6th International Workshop on High-Level Parallel Programming Models and Supportive Environments"
event_url: "https://arcb.csc.ncsu.edu/~mueller/hips01/"
location: "San Francisco, CA"
summary:
abstract: "Shared-memory architectures with uniform memory access come very close to the PRAM, the theoretical model of parallel computing, and stand in sharp contrast to the common cluster approach. While PRAM algorithms have been devised for a large variety of combinatorial problems in graphs, strings, and geometry, none has been run successfully on a conventional parallel machine -- the irregular nature of the computations cause a tremendous communication load and make the parallel machine run much more slowly than a simple workstation. Our preliminary results indicate that true shared-memory architectures, such as the Sun Enterprise 10000, run these same PRAM algorithms quite efficiently, showing effective speedups and thus opening up the possibility of leveraging over 20 years of research in PRAM algorithms for practical applications that require complex combinatorial optimization (such as sequence alignment and tree reconstruction problems that arise in genomics and bioinformatics)."

# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
date: 2001-04-23T13:15:00-07:00
date_end: 2001-04-23T14:15:00-07:00
all_day: false

# Schedule page publish date (NOT talk date).
publishDate: 2019-09-30T23:19:38-04:00

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

**David A. Bader** is an Assistant Professor of Electrical & Computer Engineering at The University of New Mexico, and received his Ph.D. in Electrical Engineering in 1996 from The University of Maryland. David's recent research experiences highlight his ability to bridge the gap between application and computer science. For example, while an NSF CISE Postdoctoral Research Associate in Experimental Computer Science, David worked closely with Earth scientists at NASA/GSFC and University of Maryland's Geography Department to develop a high-performance system for on-demand queries of terascale remotely-sensed Earth science data, such as 4km AVHRR global coverage, used for monitoring long-term global studies of the Earth. In addition to developing some of the fastest known portable, high-performance algorithms for image segmentation and classification applications, combinatorial problems such as sorting and selection, and data communication primitives, David's recent research has produced a new, preliminary methodology for programming UMA shared-memory machines and clusters of SMP nodes.
