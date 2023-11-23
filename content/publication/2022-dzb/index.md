---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "Parallel Suffix Sorting for Large String Analytics"
authors: ["Zhihui Du", "Sen Zhang", "David Bader"]
date: 2022-09-13T18:48:25-04:00
doi: "10.1007/978-3-031-30442-2_6"

# Schedule page publish date (NOT publication's date).
publishDate: 2022-09-13T18:48:25-04:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["paper-conference"]

# Publication name and optional abbreviated publication name.
publication: "14th International Conference on Parallel Processing and Applied Mathematics, Gdansk, Poland. In R. Wyrzykowski et al. (Eds.): PPAM 2022, LNCS 13826, pp. 71–82, 2023."
publication_short: "PPAM 2022"

abstract: "The suffix array is a fundamental data structure to support string analysis efficiently. It took about 26 years for the sequential suffix array construction algorithm to achieve O(n) time complexity and inplace sorting. In this paper, we develop the DLP I (D Limited Parallel Induce) algorithm, the first O( n/p ) time parallel suffix array construction algorithm. The basic idea of DLPI includes two aspects: dividing the O(n) size problem into p reduced sub-problems with size O( n/p ) so we can handle them on p processors in parallel; developing an efficient parallel induce sorting method to achieve correct order for all the reduced sub-problems. The complete algorithm description is given to show the implementation method of the proposed idea. The time and space complexity analysis and proof are also given to show the correctness and efficiency of the proposed algorithm. The proposed DLP I algorithm can handle large strings with scalable performance."

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
