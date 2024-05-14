---
# Documentation: https://hugoblox.com/docs/managing-content/

title: "Quantum interior point method (US20240144066A1)"
authors: ["Alexander M. Dalzell", "B. David Clader", "Grant Salton", "Mario Berta", "Cedrick Yen-Yu Lin", "David Bader", "William J. Zeng"]
date: 2024-05-02T09:21:08+02:00
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: 2024-05-14T09:21:08+02:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["8"]

# Publication name and optional abbreviated publication name.
publication: "United States Patent and Trademark Office"
publication_short: "USPTO"

abstract: "In some aspects, the techniques described herein relate to a quantum method for solving a second-order cone program (SOCP) instance, the method including: defining a Newton system for the SOCP instance by constructing matrix G and vector h based on the SOCP instance; preconditioning matrix G and vector h via row normalization to reduce a condition number of matrix G; iteratively determining u until a predetermined iteration condition is met, the iterations including: causing a quantum computing system to apply matrix G and vector h to a quantum linear system solver (QLSS) to generate a quantum state; causing the quantum computing system to perform quantum state tomography on the quantum state; and updating a value of u based on a current value of u and the output of the quantum state tomography; and determining a solution to the SOCP instance based on the updated value of u."

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

https://patents.google.com/patent/US20240144066A1/en
