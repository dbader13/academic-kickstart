---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "Interactive Data Science at Scale"
event: "Big Data Analytics Workshop (BigDAW), co-located with the ACM International Conference on Computing Frontiers 2021"
event_url: "https://hpc.pnl.gov/bigdaw/"
location: "virtual"
address:
  street:
  city:
  region:
  postcode:
  country:
summary:

abstract: "A real-world challenge in data science is to develop
interactive methods for quickly analyzing new and novel data sets that
are potentially of massive scale. In this talk, we discuss our
development of suffix array and graph algorithms in the context of
Arkouda, a NumPy-like replacement for interactive data science on tens
of terabytes of data. Many real-world applications in bioinformatics,
web information search and analysis, and lossless compression can be
abstracted as string analysis. Suffix arrays are a very efficient data
structure to support quick search of any string patterns. We have
integrated the suffix array data structure (including its enhanced
Longest Common Prefix (LCP) array) and the corresponding construction
algorithm into Arkouda, thus providing Python users with a powerful
method to support different types of string analysis.  Our novel
approach integrates a suffix array algorithm library into Arkouda so
that the Arkouda runtime can select the large suffix array
construction algorithm dynamically based on the dataset
properties. Two of the implemented methods on the back-end of Arkouda
include our novel O(n) time complexity skew algorithm in Chapel, and
the DivSufSoft suffix array construction algorithm in C, which has
higher time complexity but often is faster in practice.  Experimental
results show that, supported by Arkouda, Python users can build a
large scale string’s suffix array and LCP array in a Jupyter notebook
easily without losing any performance compared with the directly
back-end operation. Our future work is extending our self-developed
algorithm to support multi-locale parallel execution, so that our
algorithm can handle large strings on distributed systems. Graphs are
widely used to abstract problems in domains such as social sciences,
biological systems, and information systems.  To support real-world
large graph analysis in Arkouda, we first developed the array-based
graph data structure which can be used like an adjacency matrix or
incidence matrix but with much less memory. At the same time, it
naturally works well with Arkouda’s array operators. Based on this
succinct graph data structure, we have developed two typical graph
algorithms, breadth-first search (BFS) and triangle counting. Both
algorithms have been successfully integrated into Arkouda. Both are
multi-locale algorithms so they can handle a very large graph on
distributed systems. Experimental results of BFS on a 32-node cluster
system show that our method can build large graphs into distributed
memory and execute the parallel BFS algorithm on typical sparse graph
benchmarks and R- MAT generator-based graphs successfully. The
performance results show that the distributed graph building time and
BFS time will increase linearly with the total number of edges. For
future work, we will further optimize these graph algorithms and
investigate the streaming versions in Arkouda. We acknowledge Mike
Merrill and Bill Reus, the founding developers of the open-source
Arkouda framework. This is joint work with research scientist
Dr. Zhihui Du, and doctoral student Oliver Alvarado Rodriguez.  Bader
is supported in part by the National Science Foundation award
CCF-2109988."

# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
date: 2021-05-13T12:30:00-04:00
date_end: 2021-05-13T13:15:00-04:00
all_day: false

# Schedule page publish date (NOT event date).
publishDate: 2021-05-13T12:35:05-04:00

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
