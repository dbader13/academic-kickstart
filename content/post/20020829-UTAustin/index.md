---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Large-Scale Phylogenetic Analysis"
subtitle: ""
summary: ""
authors: []
tags: []
categories: []
date: 2002-08-29T21:20:43-04:00
lastmod: 2002-08-29T21:20:43-04:00
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

The goal of phylogenetic analysis is to reconstruct the evolutionary
history of different taxa (e.g., species, genera). Recent
advances in molecular biology and genomics have provided
biologists with molecular data at an unprecedented
rate and scale. New approaches are necessary because the
most accurate analyses are obtained through solving (or attempting
to solve) NP-hard optimization problems. Furthermore,
any such analysis can return hundreds or thousands
of trees. Finally, some taxa evolve down networks rather
than down trees. Our research uses discrete algorithms, graph
theory, probability theory, and experimental performance
analyses. Below we describe just three of several ongoing
projects in the group.

## 1. Genome Rearrangement Phylogeny: ##

Whole genomes evolve via events, such as inversions, transpositions,
deletions, and duplications, that change the order
and content of genes within genomes. Such events are relatively
rare, compared to nucleotide substitutions, and thus
contain significantly stronger phylogenetic “signal”. Our
group works on developing new methods for reconstructing
phylogenies on whole genomes. The software suite
GRAPPA, a result of collaboration with Bernard Moret and
**David Bader** at the University of New Mexico, is several
orders of magnitude faster than the previous best software
for this kind of problem.

## 2. Absolute Fast Converging Methods: ##

Statisticians are interested in the sequence lengths needed
by methods to reconstruct trees under Markov models of
evolution. Our new “absolute fast converging methods” are
methods that recover the true tree from polynomial lengths.
Our experimental performance analyses show that our new
methods greatly out perform other polynomial time methods
with respect to topological accuracy, especially on big
trees.

## 3. Visualization and Clustering of Sets of Phylogenetic Trees: ##

When a phylogenetic analysis of a dataset produces thousands
of equally good trees, biologists summarize the information
in the analysis with a consensus tree. We replace the
traditional one-consensus approach with multi-consensus
methods using clustering of trees, and develop tools for visualizing
the distributions of trees in tree space.
Large-Scale Phylogenetic Analysis

## Faculty ##

### Computer Science ###

Tandy Warnow    
Nina Amenta    
Bernard Moret (U. New Mexico)    
**David Bader** (U. New Mexico)    
Katherine St. John (CUNY)    
Tamara Munzner (Compaq)    

### Biology ###

Robert Jansen    
Randy Linder    
Linda Raubeson (Central Wash. U)    

http://www.cs.utexas.edu/users/phylo