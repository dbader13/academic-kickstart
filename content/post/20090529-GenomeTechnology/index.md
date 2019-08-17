---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Petascale Coming Down the Pike"
subtitle: "Supercomputing is on the cusp of a new era, offering researchers processing power never seen before. Here’s a look at machines poised to help the life sciences community chip away at the building blocks of biology"
summary: ""
authors: []
tags: []
categories: []
date: 2009-05-29T07:41:07-04:00
lastmod: 2009-05-29T07:41:07-04:00
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

Given the combination of the everincreasing power of
compute hardware
and researchers’ desire to unlock the mysteries of life, it’s
no surprise that high-performance
computing in the early 21st century
is now talking in terms of a whole
new scale of computation. While the
life sciences community has for some
time now been concerned with terrifying amounts of data in terabytescale proportions — that’s 1,024 gigabytes — there is an even larger
scale on the computational horizon:
petascale computing. One petabyte
is 1,024 terabytes, and to provide
some perspective, Google processes
an average of about 20 petabytes of
data per day.

Gee-whiz factor aside, should petascale and near-petascale systems
even be on the radar screen of the
life sciences community? So far, there
is a resounding yes from many in the
molecular simulation research community. “With petaflop-scale performance, [molecular] simulations
will reach the time scale of a submillisecond,” says Makoto Taiji, a
team leader at the RIKEN Yokohama
Institute. “This time scale will cover
various interesting biological events,
including large fluctuations in proteins. … Petascale computing will
provide scientific breakthroughs.”

Taiji and his team use RIKEN’s petaflop-capable supercomputer called
MDGRAPE-3 to conduct a range of
molecular dynamic simulations, including “post-docking” — a protocol he uses to choose drug candiate
compunds with more precision after
using the normal molecular docking
technique. “We have already found a
few successful seed compounds for
real drug targets confirmed by the experimental assays,” says Taiji. “Their
optimization is [underway], and we
are trying to use our machine also
for the optimizations of the seeds.”
In the case of MDGRAPE-3, which is
not really a programmable machine,
porting popular molecular dynamics
software to run on its architecture is
not that difficult, but it does require
a deep knowledge of the software and
people power. So far, Taiji says, they
do not have enough researchers and
programmers to study that many molecular dynamics software packages,
although they have managed to port
Amber and CHARMM, two popular
simulation applications.

On the other side of the globe, Nick
Grishin, a professor of biophysics
at the University of Texas Southwest Medical Center and a Howard
Hughes Medical Institute investigator, recently used Ranger, the sixth
most powerful supercomputer in the
world according to the Top500 list,
to solve some very difficult threedimensional protein folding problems. Housed at the Texas Advanced
Computing Center, Ranger came online in February 2008 and Grishin
got to use its roughly 62,976 processing cores to help secure top honors in
the most recent Critical Assessment
of Techniques for Protein Structure
Prediction competition, a worldwide
contest to predict the structures of a
select number of unknown proteins.

“It’s embarrassing to say, but because our algorithms are stochastic,
they are not particularly fast to run,
and protein chains are very long so
it just takes an incredible amount
of computer resource to compute
those energies,” Grishin says. Without Ranger, Grishin says he never
would have been able to accomplish
the task. “A typical cluster is just too
small; it needs to be many more processors. A hundred or 200 processors
is clearly not enough for this kind of
job. … And the more computations
we make, the more likelihood there
is that we will hit the right energy
function and have something with
some medical importance,” he says.

### Still a rarity ###

Despite the growing number of
petascale machines, it’s not as if just
anyone can waltz down the hallway
of an institute and find one to use.
These systems are still relatively rare;
there are only two supercomputer
sites currently capable of achieving
one petaflop peak performance in
the US. Los Alamos National Laboratory unveiled its Roadrunner supercomputer only last year, which is
listed on the Top500 supercomputing
sites list as the world’s most powerful supercomputer with a whopping
129,600 processing cores. In late
January of this year, the Oak Ridge
National Laboratory announced that
its Cray XT supercomputer, known
as Jaguar, is now capable of a peak
performance of 1.6 petaflops. “Highperformance computing affects all
areas of computational science, including biological research … [and]
more and more petascale systems
will be coming online,” says Jack
Dongarra, a professor of electrical
engineering and computer science at
the University of Tennessee. Dongarra is one of the developers of the LINPACK Benchmark, a series of dense
linear equations used
to measure a compute
system’s processing
capacity. Dongarra
helps run the Top500
list, a semiannual listing of the most powerful computing sites
in the world compiled
by computer scientists in the US and
Germany. According to Dongarra, all
high-performance systems will reach
petascale in the very near future.
“The projections say that all of the
Top500 fastest computers will be at
petascale in 2015,” he says.

More petaflop machines are already
on the way. The National Center for
Supercomputing Applications has
teamed up with IBM to create Blue
Waters, a beast of a machine that
contains more than 200,000 processing cores and is capable of sustained
multi-petaflop performance. Although
exact performance figures are still being kept confidential by IBM, all involved claim that Blue Waters will far
exceed the performance capabilities of
the two formerly mentioned machines
by a long shot when it comes online in
the summer of 2011.

“I think petascale computing comes
at a very good time for biology, especially genomics, which has to deal
with … increasingly large data sets
trying to do a lot of correlation between the data that’s held in several
massive datasets,” says Thomas Dunning, director of the NCSA at University of Illinois, Urbana-Champaign.
“This is the time that biology is now
going to need this kind of computing
capability — and the good thing is
that it’s going to be here.”

**David Bader**, a professor of computer science at the Georgia Institute of Technology, has been heavily involved in promoting awareness
of petascale computing. In 2006,
he co-chaired a workshop that attempted both to lay out a roadmap of
recommendations for making petascale computing a reality for the life
sciences and also to address its many
challenges, the biggest of which is
scaling algorithms to run on these
mega architectures.

“First and foremost, this is a scale
of system that has not been seen
before,” Bader says. “Just in June, we
saw Roadrunner using accelerators
like the Cell processor and now we
see the Cray XT-5 system at Oak
Ridge, so I think that can lead to
more experience on how to scale
algorithms that can run on all those
processors.”

In addition to scalability, reliability is
another major hurdle. When a system
crash causes you to lose a few hundred
gigabytes on a simulation or analysis job, that really hurts — but just
think of the gnashing of teeth when
you’re talking terabytes or petabytes
of data gone haywire. Efforts such as
the Berkeley Lab Checkpoint/Restart
project have focused on how to ensure a high level of reliability in these
monolithic systems. At the start of the
year, the group released a new and
improved version of its software, an
open-source solution that uses checkpointing to take hourly snapshots of
MPI-enabled applications running
jobs on large-scale compute systems.
The software “works transparently
and users do not need to make source
code changes to their applications to
work with BLCR,” says Eric Roman,
a member of the Future Technologies
Group at Lawrence Berkeley National
Laboratory. “On a petascale system
with possibly thousands of users and
applications, this feature should not
be overlooked.”

### Planning for peta ###

Given that eco-consciousness now
pervades the computing world, supercomputing sites are following suit
and are continuing to make moves
toward more environmentally friendly infrastructure. For Blue Waters,
energy-efficient design is not so much
a choice as a necessity. “I think we’ve
gotten to a point where that has to be
a priority — where if you don’t pay
careful attention to that, the power
budget can just become overwhelming, so in fact we’re at the point right
now where that has to be part of the
consideration,” says NCSA’s Dunning.
“For example, Blue Waters will be a
water-cooled, not air-cooled, machine
and the simple reason for that is that
it’s 40 percent more efficient.” NCSA
also brought in a specialized team to
look at ways to minimize the footprint
of the building itself so that most of
the power coming into the building
is actually used to run the computer
rather than all the ancillary things
needed for the facility.

Bader also hopes to see petascale
computing assisting with big ideas in
genomics. “When I think of petascale
machines, I think of doing complex
operations. So once I can assemble
whole genomes and sequence whole
genomes and get much richer data
sets and combine that with microarray data and other data sources,
what I want to be able to do is understand the evolution of whole genomes
and compare both the organisms and
genes across whole and entire genomes,” he says. “And that’s a problem
that needs both an army of data and
also the computational requirements
of a petascale system. So rather than
just taking our current techniques
and running them a bit faster, I think
that developing new algorithms ... is
really where we’re headed.”

And Bader reminds researchers
that this isn’t something only computer scientists should be thinking
about. “Biologists will need to be
aware of this technology because
if you push out the road map 10
years, these are the capability class
machines that they’ll have in their
laboratories,” Bader says. “There are
a lot of biological problems that are
still in their infancy and we [now
understand] to solve those problems
we’ll have to bring in a lot of data
collected from a lot of sites and a
lot of laboratories. … [There will]
be a growing number [of biologists]
who need access to massive volumes
of data and the computational capabilities to solve their particular
scientific inquiry.” 

https://www.genomeweb.com/informatics/petascale-coming-down-pike