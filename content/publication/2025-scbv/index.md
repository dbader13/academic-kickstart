---
# Documentation: https://hugoblox.com/docs/managing-content/

title: "Wedge-Parallel Triangle Counting for GPUs (Best Paper Award Finalist)"
authors: ["Jeffrey Spaan", "Kuan-Hsun Chen", "David Bader", "Ana-Lucia Varbanescu"]
date: 2025-06-28T15:35:33-04:00
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: 2025-06-28T15:35:33-04:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["paper-conference"]

# Publication name and optional abbreviated publication name.
publication: "The 31st International European Conference on Parallel
and Distributed Computing, Dresden, Germany, August 25-29, 2025."
publication_short: "Euro-Par 2025"

abstract: "For fast processing of increasingly large graphs, triangle counting - a common building block of graph processing algorithms, is often performed on GPUs. However, applying massive parallelism to triangle counting is challenging due to the algorithm’s inherent irregular access patterns and workload imbalance. In this work, we propose WeTriC, a novel wedge-parallel triangle counting algorithm for GPUs, which, using fine(r)-grained parallelism through a lightweight static mapping of wedges to threads, improves load balancing and efficiency. Our theoretical analysis compares different parallelization granularities, while optimizations enhance caching, reduce work-per-intersection, and minimize overhead. Performance experiments indicate that WeTriC yields 5.63x and 4.69x speedup over optimized vertex-parallel and edge-parallel binary search triangle counting algorithms, respectively. Furthermore, we show that WeTriC consistently outperforms the state-of-the-art (i.e., on avg. 2.86x faster than Trust and 2.32x faster than GroupTC)."

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
