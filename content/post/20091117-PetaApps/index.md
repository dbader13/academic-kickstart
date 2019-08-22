---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "NSF Funds Genomics Petascale Project"
subtitle: ""
summary: ""
authors: []
tags: []
categories: []
date: 2009-11-17T22:24:21-04:00
lastmod: 2009-11-17T22:24:21-04:00
featured: false
draft: false

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ""
  focal_point: ""
  preview_only: false

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects: []
---

*By Matthew Dublin*

A team of researchers led by Georgia Tech's **David Bader** are poised to bring genomic
evolution to petascale heights. Equipped with a four-year $1M grant courtesy of the
National Science Foundation's PetaApps program, Bader and his team are setting their
sights on developing algorithms to take advantage of petascale computing platforms for
studying genome rearrangement events. Bader says that they will be writing their own
open source software development framework from scratch and eventually releasing it
through the GNU GPU license on Sourceforge. The team says they will start off the peta
project by ramping up GRAPPA, an open-source application that reconstructs the
evolutionary relatedness among species first released by Bader in 2000, to take
advantage of petascale computers. "GRAPPA is currently the most accurate method for
determining genome rearrangement, but it has only been applied to small genomes with
simple events because of the limitation of the algorithms and the lack of computational
power," stated Bader in an announcement. The teamed used the latest version GRAPPA
to analyze a dataset of a dozen bellflower genomes to determin the flower's evolutionary
relatedness one billion times faster than the original, non-parallelized version.

Worth checking out is Bader's 2007 book entitled "_Petascale Computing: Algorithms and
Applications_," which covers possible applications for petascale systems, including
molecular dynamics and biomolecules, as well as multithreaded algorithm design,
performance analysis, Charm++, and the Cactus framework.

https://www.genomeweb.com/informatics/nsf-funds-petascale-algorithms-genomic-relatedness-research#.XV3-huhKjIU
