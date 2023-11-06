---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "Contour Algorithm for Connectivity"
authors: ["Zhihui Du", "Oliver Alvarado Rodriguez", "Fuhuan Li", "Mohammad Dindoost", "David Bader"]
date: 2023-11-05T20:06:53-05:00
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: 2023-11-05T20:06:53-05:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "The 30th IEEE International Conference on  High Performance Computing, Data, and Analytics"
publication_short: "HiPC 2023"

abstract: "Finding connected components in a graph is a fundamental problem in graph analysis. In this work, we present a novel minimum-mapping based *Contour* algorithm to efficiently solve the connectivity problem. We prove that  the *Contour* algorithm with two or higher order operators can identify all connected components of an undirected graph within O(log *d_max*) iterations, with each iteration involving O(*m*) work, where *d_max* represents the largest diameter among all components in the given graph, and *m* is the total number of edges in the graph. Importantly, each iteration is highly parallelizable, making use of the efficient minimum-mapping operator applied to all edges. To further enhance its practical performance, we optimize the *Contour* algorithm through asynchronous updates, early convergence checking, eliminating atomic operations, and choosing more efficient mapping operators. 
Our implementation of the *Contour* algorithm has been integrated into the open-source framework Arachne. Arachne extends Arkouda for large-scale interactive graph analytics, providing a Python API powered by the high-productivity parallel language Chapel. Experimental results on both real-world and synthetic graphs demonstrate the superior performance of our proposed *Contour* algorithm compared to state-of-the-art large-scale parallel algorithm FastSV and the fastest shared memory algorithm ConnectIt. On average, *Contour* achieves a speedup of 7.3x and 1.4x compared to FastSV and ConnectIt, respectively. All code for the *Contour* algorithm and the Arachne framework is publicly available on GitHub {https://github.com/Bears-R-Us/arkouda-njit), ensuring transparency and reproducibility of our work."

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
