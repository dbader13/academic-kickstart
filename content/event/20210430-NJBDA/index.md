---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "NJBDA Talk: Large-Scale Graph Analytics in Arkouda"
event: "New Jersey Big Data Alliance 2021 Symposium: Smart State: Big Data for Community Impact"
event_url: "https://njbda.org/2021-symposium/"
location: "VIRTUAL"
address:
  street:
  city:
  region:
  postcode:
  country:
summary:
abstract:

# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
date: 2021-04-30T11:00:00-04:00
date_end: 2021-04-30T11:30:00-04:00
all_day: false

# Schedule page publish date (NOT event date).
publishDate: 2021-04-30T09:47:38-04:00

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

## Oliver Alvarado Rodriguez (presenter), Zhihui Du and **David Bader**; New Jersey Institute of Technology ##

Exploratory graph analytics is a much sought out approach to help extract useful information from graphs. One of its main challenges arises when the size of the graph expands outside of the memory capacity that a typical computer can handle. Solutions must then be developed to allow data scientists to efficiently handle and analyze large graphs in a short period of time, using machines that have the capacity to handle massive file sizes. Arkouda is a software package under early development created with the intent to bridge the gap between massive parallel computations and data scientists wishing to perform exploratory data analysis (EDA). The communication system between the Chapel back-end and the Python front-end helps to create an easy-to-use interface for data scientists that does not require knowledge of the underlying Chapel code and instead allows them to utilize the simple Python front-end to carry out all their large file and graph EDA needs. In this work, a graph data structure is designed and implemented into the Arkouda framework at both the Chapel back-end and the Python front-end. The main attraction of this data structure is its ability to occupy less memory space and perform efficient adjacency edge searching. A parallel breadth-first search (BFS) algorithm is also presented to help demonstrate how easily one can implement parallel algorithms in Arkouda to increase EDA productivity with graphs. Lastly, real-world graphs from different domains, such as biology and social networks, are utilized to evaluate the efficiency of the graph data structure and the BFS algorithm. The results obtained from this benchmarking help show that the Arkouda overhead is almost negligible, and data scientists can utilize Arkouda for large scale graph analytics. This work can help further bridge the gap between high-performance computing (HPC) software and data science to create a framework that is straightforward for all data scientists to use. All of the code in this project and in Arkouda is open source and can be found on GitHub. This is joint work with Mike Merrill and William Reus. We acknowledge the support of National Science Foundation grant award CCF- 2109988.
