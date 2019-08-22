---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "GRAPPAling with evolutionary history"
subtitle: ""
summary: ""
authors: []
tags: []
categories: []
date: 2009-12-16T09:50:40-04:00
lastmod: 2009-12-16T09:50:40-04:00
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

*By Miriam Boon, iSGTW*

{{<figure src="NewIndex_front.jpg" caption="This figure illustrates how gene order changes among the eight species. Each thin line represents a single gene and its position in the different species. Most genes are conserved on the same chromosomal arm or Muller element, but gene order is shuffled between species. This figure appeared in the July 2008 issue of Genetics. *Image courtesy of Stephen Schaeffer.*">}}

We’ve known for several years
now that chimpanzees share 96
percent of our DNA. Our
technology tells us how closely
humans and chimps are related.
But it doesn’t tell us how we’re
related. We need new technology
for that.

Enter _GRAPPA_ – or Genome
Rearrangements Analysis under
Parsimony and other Phylogenetic
Algorithms if you want a
mouthful. GRAPPA has already
been used to analyze the
evolution of organelles such as
chloroplasts and mitochondria,
running on cluster computers with
upwards of 500 processors. To
analyze more complex organisms,
however, the team that develops
GRAPPA will have to take the code
to an entirely new level – the petascale level.

With the help of a $1 million grant from the National Science Foundation, computational science
researchers **David Bader** of Georgia Tech and Jijun Tang of the University of Southern Carolina
have joined forces with genetics researcher Stephen Schaeffer, from Pennsylvania State
University, to do just that.

“One of the first open science petascale systems will be the IBM BlueWaters resource
supercomputer,” Bader said. “Our goal is to scale GRAPPA up to use that magnificent
computer.”

The trick is in the algorithms, according to Bader. “As an example, our first version of GRAPPA
eight years ago took an hour and a half to run a problem involving the chloroplasts of a dozen
species of bluebell flowers on a 512 processor linux cluster,” Bader said.

{{<figure src="ISGTW-091216.jpg" caption="A \"Tree of Life\" diagram. *Courtesy of David Bader.*">}}

Since then, GRAPPA has
undergone a variety of
refinements. It shows. “Today
that same problem solved in a
more biologically meaningful
way takes less than five
minutes on my laptop,” Bader
said. “The biggest speed
improvement comes from
better algorithms.”

Refining GRAPPA will require a
better take on both the science
and the programming, which
makes the interdisciplinary
team a perfect fit.

Over the next four years, the
grant – which comes via the
American Recovery and
Reinvestment Act – will pay for
two graduate students at each
of the three participating
schools. Not only will they be creating invaluable tools for advancing science, but they’ll
also be learning very specialized skills in the process.

“I think we’re the pioneers in large-scale evolutionary or reconstruction of evolutionary
trees,” Bader said. “We’re breaking new ground with each new algorithm and
implementation, where no one has studied before.”

It isn’t clear how far these funds will take the team. Over the course of the grants
lifetime, they hope to continue to refine the code, doing test runs on prototypical
petascale systems. Perhaps they will be able to study fish. Or mammals. Or even
humans.

Either way, a new and improved GRAPPA will be valuable in innumerable ways. Already,
it has been used to develop biochemical products, identify target drug receptors, create
safer pesticides, and study how viruses evolve in order to make better vaccines.

“For instance, if you know that there’s a specific plant that has a property but that plant
is rare or difficult to find, you may be interested in what plants are phylogenetically
close or closely related in the family tree,” Bader said. “They may be more abundant or
easier to use to produce the right biochemical substance.”

It is clear that Bader believes this is only the beginning of a new era. “If I look at other
communities in scientific computing, they’ve matured their methods and techniques over
the course of decades to centuries,” Bader said. “We’ve only known about the structure
of DNA for fifty years, and we’ve only had the ability to sequence full genomes in the
last several years. So we’re really at the infancy of what we see in the area of
understanding biological sciences through computational methods.”


https://web.archive.org/web/20091218072926/http://www.isgtw.org/

https://sciencenode.org/feature/feature-grappaling-evolutionary-history.php
