---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Accelerating and Expanding End-to-End Data Science Workflows with DL/ML Interoperability Using RAPIDS"
authors: ["Bartley Richardson", "Bradley Rees", "Tom Drabas", "Even Oldridge", "David Bader", "Rachel Allen"]
date: 2020-08-23T16:31:45-04:00
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: 2020-07-18T16:31:45-04:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "ACM SIGKDD International Conference on Knowledge Discovery and Data Mining"
publication_short: "KDD"

abstract: "The lines between data science (DS), machine learning (ML),
deep learning (DL), and data mining continue to be blurred and
removed. This is great as it ushers in vast amounts of
capabilities, but it brings increased complexity and a vast
number of tools/techniques. It’s not uncommon for DL engineers
to use one set of tools for data extraction/cleaning and then pivot
to another library for training their models. After training and
inference, it’s common to then move data yet again by another
set of tools for post-processing. The RAPIDS suite of open source
libraries not only provides a method to execute and accelerate
these tasks using GPUs with familiar APIs, but it also provides
interoperability with the broader open source community and
DL tools while removing unnecessary serializations that slow
down workflows. GPUs provide massive parallelization that DL
has leveraged for some time, and RAPIDS provides the missing
pieces that extend this computing power to more traditional yet
important DS and ML tasks (e.g., ETL, modeling). Complete
pipelines can be built that encompass everything, including ETL,
feature engineering, ML/DL modeling, inference, and
visualization, all while removing typical serialization costs and
affording seamless interoperability between libraries. All
experiments using RAPIDS can effortlessly be scheduled, logged
and reviewed using existing public cloud options. Join our
engineers and data scientists as they walk through a collection of
DS and ML/DL engineering problems that show how RAPIDS
running on Azure ML can be used for end-to-end, entirely GPU
pipelines. This tutorial includes specifics on how to use RAPIDS
for feature engineering, interoperability with common ML/DL
packages, and creating GPU native visualizations using cuxfilter.
The use cases presented here give attendees a hands-on approach
to using RAPIDS components as part of a larger workflow,
seamlessly integrating with other libraries (e.g., TensorFlow) and
visualization packages."

# Summary. An optional shortened abstract.
summary: ""

tags: []
categories: []
featured: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_pdf:
url_code:
url_dataset:
url_poster:
url_project:
url_slides:
url_source:
url_video:

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ""
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---
