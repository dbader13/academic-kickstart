---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "Anomaly Detection in Catalog Streams"
authors: ["Chen Yang", "Zhihui Du", "Xiaofeng Meng", "Xukang Zhang", "Xinli Hao", "David Bader"]
date: 2022-03-23T10:37:37-04:00
doi: "10.1109/TBDATA.2022.3161925"

# Schedule page publish date (NOT publication's date).
publishDate: 2022-03-23T10:37:37-04:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["article-journal"]

# Publication name and optional abbreviated publication name.
publication: "IEEE Transactions on Big Data"
publication_short: "IEEE TBDATA"

abstract: "Detecting anomalies with high accuracy and real time from
large amounts of streaming data is a challenge for many real-world
applications, such as smart city, astronomical observations, and
remote sensing. This article focuses on a special kind of stream,
catalog stream, whose high-level catalog structure can be used to
analyze the stream effectively. We first formulate the anomaly
detection in catalog streams as a constrained optimization problem
based on a catalog stream matrix. Then, a novel filtering-identifying
based anomaly detection algorithm (FIAD) is proposed, which includes
two complementary strategies, true event identifying and false alarm
filtering, data oriented general method and domain oriented specific
method together, to detect truly valuable anomalies.  Furthermore,
different kinds of attention windows are developed to provide
corresponding data for various algorithm components. A scalable and
lightweight catalog stream processing framework CSPF is designed to
support and implement the proposed method efficiently. A prototype
system is developed to evaluate the proposed algorithm. Extensive
experiments are conducted on the catalog stream data sets from an
operational super large field-of-view high-cadence astronomy
observation. The experimental results show that the proposed method
can achieve a false-positive rate as low as 0.04%, reduces the false
alarms by 98.6% compared with the existing methods, and the latency to
handle each catalog is 2.1 seconds (much less than the required 15
seconds). Furthermore, a total of 36 transient candidates, including
seven microlensing events, 27 superflares, and two dual-superflares,
are detected from 21.67 million stars (involving 1.09 million
catalogs) from one observation season."

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
