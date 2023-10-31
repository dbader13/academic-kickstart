---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "IBM Invited Talk: Designing High Performance Algorithms for Clusters of SMPs"
event: "IBM Hyper Cluster Computing Workshop, Albuquerque High Performance Computing Center, The University of New Mexico"
event_url:
location:
address:
  street:
  city:
  region:
  postcode:
  country:
summary:
abstract: "With the cost of commercial off-the-shelf (COTS) high performance interconnects falling and the respective performance of microprocessors increasing, workstation clusters have become an attractive computing platform offering potentially a superior cost effective performance. In recent years, we have seen the maturing of Symmetric Multiprocessors (SMPs) technology, and the heavy reliance upon SMPs as the work-intensive servers for client/server applications. There are already several examples of clusters of SMPs, such as clusters of DEC AlphaServer, SGI Origin, Sun Ultra HPC machines, and the IBM SP system with SMP 'High' nodes; moreover, the Department of Energy's Accelerated Strategic Computing Initiative (ASCI) program relies on the success of computational clusters such as Option White, a 512-node IBM SP-2 with 16-way SMP nodes. With the acceptance of message passing standards such as MPI, it has become easier to design portable parallel algorithms making use of these primitives. However, the focus of MPI is a standard for communicating between shared-nothing processors, and although MPI programs run on clusters of SMPs, this is not necessarily the optimal methodology for these platforms.

In this talk, we will describe a hybrid methodology for programming clusters of SMP nodes which aids in the design and implementation of efficient high performance parallel algorithms. We call this approach SIMPLE, referring to the joining of SMP and MPI-like message passing paradisms and the _simple_ programming approach. Our complexity model captures the performance of shared memory access on SMP nodes combined with message passing between the nodes. We illustrate the power of our methodology by presenting experimental results for sorting integers, two-dimensional fast Fourier transforms (FFT) and constraint-satisfied searching."


# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
date: 2000-04-19T15:00:00-06:00
date_end: 2000-04-19T16:00:00-06:00
all_day: false

# Schedule page publish date (NOT event date).
publishDate: 2021-09-07T14:24:52-04:00

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


