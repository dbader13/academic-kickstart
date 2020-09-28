---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "GTC 2020 Invited Talk: New High Performance Graph Analytics Technique and a GPU Implementation"
event: "NVIDIA GPU Technology Conference (GTC) 2020"
event_url: "https://www.nvidia.com/en-us/gtc/"
location:
address:
  street:
  city:
  region:
  postcode:
  country:
summary:
abstract: "We'll introduce a new algorithm called anti-section transitive closure (ATC) for finding the transitive closure of a graph, including a new technique, called anti-sections, for finding reachable vertices. ATC works on both sparse and large networks. ATC scales naturally to massively multi-threaded systems such as GPUs. Finding the transitive closure of a graph is computationally expensive and has required a large memory footprint. Prior approaches assume dense graphs, however, real-world networks like cyber networks are extremely sparse, and the existing methods do not scale on large, sparse networks. By leveraging anti-sections and the Hornet dynamic graph data structure, we're able to reduce the memory footprint required and show that ATC significantly outperforms common CPU and prior GPU implementations. ATC can outperform NetworkX by several orders of magnitude, and it outperforms a highly-tuned GraphBLAS CPU solution by 400x on a single NVIDIA GPU."

# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
date: 2020-10-07T10:00:00-04:00
date_end: 2020-10-07T10:50:00-04:00
all_day: false

# Schedule page publish date (NOT talk date).
publishDate: 2020-09-28T14:11:02-04:00

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
