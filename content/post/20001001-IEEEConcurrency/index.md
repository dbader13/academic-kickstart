---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Solving the mystery of life with sixfold speedup"
subtitle: ""
summary: ""
authors: []
tags: []
categories: []
date: 2000-10-01T22:35:05-04:00
lastmod: 2000-10-01T22:35:05-04:00
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

To understand the evolutionary
process from the beginning of life
itself to present-day species, we must
first determine the “tree of life.” In this
tree, called a *phylogeny*, known species
reside at the tree’s leaves, while conjectured
ancestor (extinct) species
reside where the tree’s branches split.
We follow this process down to the
tree’s base, normally represented by
the three major limbs for plants, animals,
and single-celled organisms.

In recent years, geneticists have
made wondrous progress in determining
genetic sequences from generation
to generation; they have now mapped
complete genomes for several species.
Evolutionary models are approximations
at best, but nevertheless provide
the best guidance for determining the
interrelation between species. Biologists
are often concerned with a small
portion of the phylogeny (a subtree)
containing a family of related species.
They believe that Nature follows
a path of minimizing evolutionary
processes, but even computing the
minimum evolutionary tree (called
phylogeny reconstruction) for a handful
of species is intractable on several
levels.

At the University of New Mexico’s
Albuquerque High Performance
Computing Center (www.ahpcc.unm.
edu), **David Bader**, Bernard Moret,
and Tandy Warnow have achieved a
nearly one-million-fold speedup on
the UNM/Alliance LosLobos supercluster
in solving the phylogeny reconstruction
problem for the family of
twelve Bluebell species. The problem
size includes a thirteenth plant, tobacco,
used as a distantly related outgroup.
The LosLobos supercluster has
512 733-MHz Pentium III processors,
interconnected with four 64-way
Myrinet 2000 switches and running
the Linux 2.2 operating system. The
parallelization uses MPI and includes
techniques for concurrently evaluating
candidate trees and sharing
improved upper and lower bounds by
the processors.

The LosLobos supercluster executed
the problem in about one hour
and 40 minutes using the new phylogeny
reconstruction code, Grappa
(freely available as open source from
www.cs.unm.edu/~moret/GRAPPA/).
Run on a single processor, Grappa
performs 2,500 times faster than previous
methods but takes full advantage
of parallel processing for additional
speedups. Hence, the total speedup
for the new solution is one million—
equivalent to going from an estimated
200 years down to 100 minutes. Phylogenies
derived from gene-order data
might prove crucial in answering fundamental
open questions in biomolecular
evolution