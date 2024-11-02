---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "Supercomputing Research Center Colloquium Talk: Scalable and Portable Parallel Algorithms for Image Processing"
event: "Supercomputing Research Center Colloquium Series"
event_url:
location: "Supercomputing Research Center, Bowie, MD"
address:
  street:
  city:
  region:
  postcode:
  country:
summary:
abstract: "This talk presents efficient and portable implementations for several useful primitives in image processing algorithms, such as histogramming, noise estimation, and connected components. An image segmentation process which makes use of these primitives, an enhancement filter called the Symmetric Neighborhood Filter, and a variant of the conventional connected components algorithm, which we call Delta-Connected Components, will also be presented. 

Our general framework is a single-address space, distributed memory programming model. We use efficient techniques for distributing and coalescing data as well as efficient combinations of task and data parallelism. Our connected components algorithm uses a novel approach for parallel merging which performance drastically limited updating during iterative steps, and concludes with a total consistency update at the final step. This algorithms have been coded in Split-C and run on a variety of platforms, including the TMC CM-5, IBM SP-1 and SP-2, Intel Paragon, Cray T3D, Meiko CS-2, and workstation clusters. Our experimental results are consistent with the theoretical analysis and provide the best known execution times for several of these operations, even when compared with machine specific implementations. More efficient implementations of Split-C will likely result in even faster execution times. 

The suppoert by NASA Graduate Student Researcher Fellowship No. NGT-50951 is gratefully acknowledged."

# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
date: 1995-03-31T13:30:00-04:00
date_end: 1995-03-31T14:30:00-04:00
all_day: false

# Schedule page publish date (NOT event date).
publishDate: 2021-09-07T08:53:11-04:00

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
{{<figure src="letter.jpg">}}
