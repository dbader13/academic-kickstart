---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Supercomputing: New Processor Architecture Holds Promise for Protein, Gene Studies"
subtitle: ""
summary: ""
authors: []
tags: []
categories: []
date: 2008-09-01T07:18:13-04:00
lastmod: 2008-09-01T07:18:13-04:00
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

A supercomputing architecture that first
appeared in prototype
form more than 10 years
ago has been given a
new lease on life, thanks in part to
a recent $4 million Department of
Defense grant issued to seed the
new Center for Adaptive Supercomputing Software. The joint project
teams up Pacific Northwest
National Laboratory and supercomputer maker Cray, as well as
several institutions including
Georgia Institute of Technology
and Sandia National Laboratories.

The initiative aims to develop
software that takes advantage of
the multithreaded processing
capabilities of Cray’s XMT supercomputer. Unlike traditional
supercomputer processing architecture, where each processor gets
a portion of memory for each calculation in a piece-by-piece fashion, the new processors are each
capable of multiple, simultaneous
data crunching and use a much
larger pool of memory per processing core. This design means
that many disparate sets
of complex data can be
digested at once, instead
of each portion of data
being handled piece by
piece.

**David Bader**, a computer scientist at Georgia
Tech, demonstrated the
architecture’s application
to biology by identifying proteins
that, when knocked out, disrupt
the cancer-causing networks in a
particular cell. Bader and his team
used a social networking algorithm to mine a huge collection of
publicly available human proteome datasets. “This is similar to
finding important people in a
social network, sometimes called
‘connectors,’” Bader says. “Looking
for these proteins is like looking
for a needle in a haystack — and it
is usually computationally intensive that won’t work well on
current [high-performance]
machines, but this new architecture is really designed for this type
of problem.”

Normally, multiple database
searches of this kind would take
hours and hours to complete on a
typical cluster or supercomputer.
But with an algorithm specially
ported to this multithreaded processing architecture, the same job
takes mere seconds to complete,
says Bader. “These sorts
of problems have overwhelmed modest size
clusters, and if you start
adding processors to a
cluster, it takes longer
and longer to run
because the communication costs dominate,” he
says. “This is really the
first architecture where you can
pose a biological hypothesis, test it
out, and run it in short seconds or
minutes versus hours to days, or
maybe never.”

Bader and his colleagues believe
the concept could offer a lot to largescale life science computing problems. “I think as we gather more
genomics data we can use such a
system to make scientific discoveries,” he says. “I would hope, looking
at three to five years, that we keep
investing in these novel types of
architecture and looking at the scientific results we can achieve, especially in the areas of solving
genomic problems and understanding of the genome.”

*— Matthew Dublin*