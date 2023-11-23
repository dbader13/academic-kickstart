---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "An Efficient LP Rounding Scheme for Replica Placement"
authors: ["Zhihui Du", "Sen Zhang", "David Bader", "Jingkun Hu"]
date: 2020-09-08T15:29:50-04:00
doi: "10.1109/HPEC43674.2020.9286163"

# Schedule page publish date (NOT publication's date).
publishDate: 2020-09-08T15:29:50-04:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["paper-conference"]

# Publication name and optional abbreviated publication name.
publication: "2020 IEEE High Performance Extreme Computing Conference"
publication_short: "HPEC"

abstract: "Large fault-tolerant network systems with high Quality of Service (QoS) guarantee are critical in many real world applications and entail diverse replica placement problems. In this paper, the replica placement problem in terms of minimizing the replica placement cost subject to both QoS and fault-tolerant constraints is formulated as a binary integer linear programming problem first and then relaxed as a linear programming problem. Given the optimal fractional linear programming solution, we propose a two-step rounding algorithm to obtain its integer solution. In the first step, a half rounding algorithm is used to simplify the problem. In the second step, a cheapest amortized cost rounding algorithm uses a novel metric, named amortized cost, to make locally optimal rounding decision for the remaining vertices independently. Furthermore, a conflict resolution algorithm is presented to tackle the situations when different vertices make conflicting rounding decisions. Finally, we prove that the proposed two-step rounding algorithm has a 2-approximation ratio when the additional conflict cost meets a given constraint."

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
