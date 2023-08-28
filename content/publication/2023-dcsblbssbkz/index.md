---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "End-to-end resource analysis for quantum interior point methods and portfolio optimization"
authors: ["Alexander M. Dalzell", "B. David Clader", "Grant Salton", "Mario Berta", "Cedric Yen-Yu Lin", "David Bader", "Nikitas Stamatopoulos", "Martin J. A. Schuetz", "Fernando G. S. L. Brandão", "Helmut G. Katzgraber", "William J. Zeng"]
date: 2023-08-28T13:40:21-05:00
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: 2023-08-25T13:40:21-05:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "PRX Quantum: a Physics Review Journal"
publication_short: "PRX Quantum"

abstract: "We study quantum interior point methods (QIPMs) for second-order cone programming (SOCP), guided by the example use case of portfolio optimization (PO). We provide a complete quantum circuit-level description of the algorithm from problem input to problem output, making several improvements to the implementation of the QIPM. We report the number of logical qubits and the quantity/depth of non-Clifford T-gates needed to run the algorithm, including constant factors. The resource counts we find depend on instance-specific parameters, such as the condition number of certain linear systems within the problem. To determine the size of these parameters, we perform numerical simulations of small PO instances, which lead to concrete resource estimates for the PO use case. Our numerical results do not probe large enough instance sizes to make conclusive statements about the asymptotic scaling of the algorithm. However, already at small instance sizes, our analysis suggests that, due primarily to large constant pre-factors, poorly conditioned linear systems, and a fundamental reliance on costly quantum state tomography, fundamental improvements to the QIPM are required for it to lead to practical quantum advantage."

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
