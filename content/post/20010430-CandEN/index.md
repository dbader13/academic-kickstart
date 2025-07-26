---
# Documentation: https://hugoblox.com/docs/managing-content/

title: "Supercomputing Strategies"
subtitle: "Chemists emerge as major players in developing tools for new computer architectures, including increasingly popular computer clusters"
summary: ""
authors: []
tags: []
categories: []
date: 2001-04-30T15:20:27-04:00
lastmod: 2001-04-30T15:20:27-04:00
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

*Elizabeth K. Wilson, C&EN West Coast News Bureau*

The parallel supercomputers of today come in a number of "flavors," and their different styles of crunching data have led to as many different varieties of hardware and software.

{{<figure src="7918photodimer.jpeg" caption="COMPUTER PROWESS. The highest occupied molecular orbital in the 9,10-dimethyleneanthracene photodimer was computed by Baldridge and imaged by Johnson of SDSC using volume graphics techniques.">}}

Garden-variety parallel architecture and problem-solving present numerous well-known networking and programming challenges. For example, many computational chemistry codes, be they for ab initio quantum calculations or for molecular dynamics simulations, were written decades ago for machines that process data sequentially. Over the years, chemists have undertaken the difficult task of modifying the codes to run on massively parallel machines with dozens, even hundreds, of processors.

But on top of that, some new architectures are complicating the picture. They include, most notably, the fantastically popular cluster-style computers--groups of small machines hooked together. Because they can be put together from off-the-shelf PCs, their cost is very low. Yet they can pack as much computational punch as more expensive Crays or IBMs. Chemists have a particular interest in clusters because of the increasing prevalence of modeling and simulations in everyday research ([C&EN, Jan. 10, 2000, page 27](http://cen.acs.org/isubscribe/journals/cen/78/i02/html/7802scit1.html)).

BUT MUCH MORE is involved in assembling a cluster than setting a few PCs next to each other and expecting them to talk. They require special communications tools and carry a number of complications in addition to those of traditional parallel computing. And recently, scientists have been experimenting with yet another new computer structure: clusters of clusters.

Surprisingly, chemists are contributing a good deal to the development of a field that one might expect to be populated exclusively by computer scientists. In addition to modifying chemistry software, they're designing general tools to make clusters and their ilk run better, and these accomplishments were outlined at a symposium on new computer architectures at the American Chemical Society meeting in San Diego earlier this month.

{{<figure src="7918sci1x.jpeg" caption="Jackman. *Photos by Elizabeth Wilson*">}}

{{<figure src="7918sci4x.jpeg" caption="Pineda. *Photos by Elizabeth Wilson*">}}

{{<figure src="7918sci3x.jpeg" caption="Baldridge. *Photos by Elizabeth Wilson*">}}

{{<figure src="7918sci2x.jpeg" caption="Gordon. *Photos by Elizabeth Wilson*">}}

Sponsored by the [Division of Computers in Chemistry](http://membership.acs.org/C/COMP/), the symposium also highlighted new research on ways to visualize data, new hardware designed to speed up lengthy calculations, and numerous tests of parallel versions of computational chemistry software on these new architectures.

Most of these complexities arise from the fundamental issue of how processors are grouped. For the past few years, supercomputers have fallen into two basic classes, explained Andrew C. Pineda, a chemist at the [University of New Mexico's Albuquerque High Performance Computing Center (AHPCC)](http://oaserv1.ahpcc.unm.edu/) and organizer of the symposium. The first, known as a distributed single processor, consists of individual processors with their own memory connected to other processors by a high-speed communications network.

THE SECOND TYPE is the shared-memory multiprocessor, where a number of processors sit on one board, sharing a bus and internal memory. The problem with this strategy, however, is that only so many processors can be used on a single motherboard before the computational returns begin to diminish. "You can only have eight to 16 processors on a board before they're all fighting over access to memory," Pineda said.

What's emerging now is a hybrid of those two, a strategy exemplified by clusters. As Pineda explained, a number of processors are put on a motherboard, into a unit known as a node, which is then hooked together with other such boards via high-speed communications networks.

Nodes can be hardwired into the supercomputers produced by companies like IBM and Compaq, or they can be composed of individual small PCs, as in the case of low-end clusters.

The lines between the two are blurring, however, as supercomputer companies are starting to make cluster-styled computers. For example, IBM's SP supercomputer line has now evolved from what was essentially a cluster of IBM RISC workstations into clusters of multiprocessor nodes, Pineda said.

Major supercomputer centers are adding huge "superclusters" to their inventories, behemoths that rank among some of the most powerful computers in the world. "Probably the next generation of machines that everyone's going to be buying--even at very high-end supercomputing sites--will be clusters, because of the huge price difference compared with big traditional supercomputers," Pineda said.

At AHPCC, scientists are working with IBM to test the capabilities of an even more exotic computer architecture, a group of clusters known as Vista Azul. It consists of a combination of an IBM SP2 cluster (Vista), a Linux-based cluster (Azul), and a graphics engine.

Such versatility would be useful to chemists, who have a variety of computing needs, noted Thomas M. Jackman, a chemist and computer scientist at [IBM T. J. Watson Research Center](http://www.research.ibm.com/about/ykt.shtml) in Yorktown Heights, N.Y. Ab initio problems are solved much differently than molecular dynamics simulations, for example. A common system with different computing architectures would allow chemists to select the portion that would best handle their particular problem, Jackman said.

The Vista Azul structure would also be useful for projects that are completed in stages. For example, the hope is that Vista Azul could do large calculations on one set of nodes, render the data on another cluster, then turn that data over to the graphics engine.

The group is still working out bugs in the new system. "The two pieces don't quite play together yet, but hopefully we'll iron that out soon," Pineda said.

This type of system would also be advantageous for those who have old IBM SPs, Pineda said. "Rather than take an old SP and throw it away, you could graft new Linux clusters on to the existing platform."

Because the processors of Linux-based clusters are not wired together internally for ultrafast communication like standalone supercomputers, a critical component is the communications network that connects the nodes. Communication has to happen fast. For low-end clusters, a network known as FastEthernet usually does the job. But if a cluster is to take its place alongside enormous standard supercomputers, it needs something more sophisticated, such as Gigabit Ethernet or Myrinet.

AN ALTERNATIVE to Gigabit Ethernet and Myrinet is the so-called Scalable Coherent Interface, or SCI. But there have been questions about its performance in a cluster environment, noted [Mark S. Gordon](http://www.msg.ameslab.gov/), theoretical chemistry professor at Iowa State University, Ames, and director of the Scalable Computing Laboratory (SCL) at the Department of Energy's Ames Laboratory.

{{<figure src="7918scit1.ce.jpeg">}}

Gordon's colleague David Halstead put SCI to the test. His particular concern was that SCI's communication through nodes is monodirectional. For example, to get from node 1 to node 8 requires going through several other nodes. "The question was, Does the communication from node 1 to node 8 degrade when the nodes in between talk to each other" Gordon said. Yes, but surprisingly little, was the answer.

Gordon's group has also developed a new version of crucial cluster networking software known as MPI (message-passing interface). All distributed-memory parallel computers need some message-passing software. MPI is a collection of routines that allow communication among the processors; it was developed to work on any platform and has become an industry standard.

Ames scientist David Turner has written a program called MP_LITE, a much smaller, more efficient piece of software that can either replace or run on top of standard MPI. The program should be useful not only for clusters, but also for supercomputers such as the Cray T3E, Gordon said.

To get the most out of a computer with multiple processors on different nodes, it's vital to keep the processors occupied. The number of nodes involved in a calculation is constantly changing, so a piece of software known as a scheduler is called in to help manage various tasks more efficiently. Gordon's group compared different schedulers on clusters, finding that a program known as the Maui Scheduler, developed at the [Maui High Performance Computing Center](http://www.mhpcc.edu/mhpcc.html), performed best.

Software is also coming onboard to make the task of assembling a cluster more user-friendly. In the past, putting together clusters has required a good deal of computer knowledge. But as Kim Baldridge, computational chemist at the [San Diego Supercomputer Center (SDSC)](http://www.sdsc.edu/), noted at the meeting, software known as Rocks put out by computer scientist Philip Papadopoulos' group at the [National Partnership for Advanced Computational Infrastructure](http://www.npaci.edu/) makes the task much easier for the nonexpert.

Of course, for these scientists, the ultimate purpose of all this activity is to enhance the capabilities of computational chemistry. And so they're testing the mettle of computational chemistry software on these new varieties of supercomputers.

REFORMULATING SOFTWARE to solve problems in parallel by delegating tasks to numerous processors is a particularly onerous undertaking in computational chemistry. The initial stages of many calculations, such as those that determine electronic structure, often involve integral evaluations, which don't require as much communication throughout the computing network. But the end of the calculation is dominated by large linear algebra problems that require a great deal of cross-checking on a parallel computer's communication network.

Therefore, it's not surprising that the performance of such codes depends on how fast processors and nodes can communicate with each other. "They're quite sensitive to how robust the software and hardware for the communication network is," Pineda said.

At the meeting, speakers reported their results of software performance on different computer architectures using so-called benchmark tests--standard calculations with known results. In particular, they focused on GAMESS, an open-source ab initio quantum chemistry software package cowritten by Gordon, Baldridge, and others. GAMESS is also one of the quantum chemistry programs that has been modified most extensively to run on parallel machines.

At SDSC, Baldridge and her colleagues studied how GAMESS ran on four different types of machines: the center's famous IBM Blue Horizon, a huge supercomputer with 144 eight-processor nodes; a shared-memory supercomputer from Sun; a large Compaq/IBM Linux-based cluster known as the Meteor cluster; and finally, a machine called Tera, possessing a unique architecture that includes structures known as threads, which make tasks within codes even more parallel.

Pineda and his colleagues are running a Department of Defense-sponsored project to study software performance on a number of clusters at AHPCC. They tested GAMESS on Los Lobos, a huge 512-processor Linux-based cluster, as well as on Azul and Vista separately. The bottom line: The cluster computers performed within a factor of two of their standard supercomputing counterparts. Not bad, considering that the price of clusters is about one-tenth that of comparable supercomputers, Pineda said.

Pineda notes that DOD recognizes that the future of supercomputing likely lies with clusters. "They're seeing the handwriting on the wall, in terms of where the next generation of supercomputers will come from: They'll probably be large Linux-based clusters," he said.

[Greg S. Johnson](http://www.sdsc.edu/~johnson/) and Allen Snavely, scientists at SDSC, have been exploring ways to run more than one task on the same set of resources at the same time, a strategy they call symbiosis. Not only could symbiosis allow chemists to solve more than one problem at once, it's also a potential boon for visualizing, or rendering, data. Usually, the huge data sets produced from a lengthy calculation are saved to disk. In order to turn the data into something visually meaningful--a protein structure, for instance--it has to be carted to a different system and manipulated by visualization software.

But with the strategy of symbiosis, graphic representations of the calculations could be churned out in real time, and scientists could watch their simulations as their calculations are running. Not only would this save time and reduce the amount of computer resources required, but errors can be spotted and corrected sooner, Johnson said.

Accomplishing symbiosis will require some work because the machines are not currently designed to schedule jobs that way. "Even to do test runs to show the benefit of symbiosis, we had to get a machine specially configured," Johnson said. Scientists will also need to change the way they view the computer resources they use.

Chemistry-computing performance is also getting a boost from new advances in computer hardware. IBM's Jackman noted a number of new devices coming down the pipeline, including the series of accelerator chips known as MD-GRAPE from IBM and the Institute of Chemical Research (RIKEN) in Tokyo. The chips operate on principles similar to graphics accelerators, except that they speed up dynamics calculations.

{{<figure src="7918triquinane.jpeg" caption="ON THE COVER. The graphic shown on the cover of this week's C&EN is a three-dimensional rendering of the transition state between two carbocation structures of the triquinane molecule. San Diego Supercomputing Center scientist Johnson used code called MPIRE to image data from GAMESS structure calculations performed by SDSC's Baldridge. Red and dark blue show regions of high orbital density, fading out to low-density greens. The group's goal is to run programs like these in tandem to directly visualize the results of calculations in a process they call symbiosis.">}}

{{<figure src="7918md2_boardgood3.jpeg" caption="FRUITFUL. MD-GRAPE chips speed up calculations. IBM WATSON RESEARCH CENTER">}}

{{<figure src="7918superCluster.jpeg" caption="ENCOUNTER GROUP. Several of the Albuquerque High Performance Computing Center's high-powered clusters.">}}

Nanotechnology C&EN Special Report, Science & Technology, 79(18):42, April 30, 2001.

https://pubsapp.acs.org/cen/coverstory/7918/7918supercomputer.html
