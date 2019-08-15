---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "DARPA Sets Ubiquitous HPC Program in Motion"
subtitle: ""
summary: ""
authors: []
tags: []
categories: []
date: 2010-08-10T11:30:47-04:00
lastmod: 2010-08-10T11:30:47-04:00
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

*By Michael Feldman*

The US Defense Advanced Research Projects Agency (DARPA) has selected four “performers” to develop prototype systems for its Ubiquitous High Performance Computing (UHPC) program. According to a [press release](http://www.darpa.mil/news/2010/UHPCNewsRelease.pdf) issued on August 6, the organizations include Intel, NVIDIA, MIT, and Sandia National Laboratory. **Georgia Tech** was also tapped to head up an evaluation team for the systems under development. The first UHPC prototype systems are slated to be completed in 2018.

The overarching goal of UHPC is, in the words of the program’s mission, “to reinvent computing.” Of course, nearly every DARPA computing program purports to do that, to one extent or another. So this is just business as usual for the DoD’s premier research agency.

DARPA has dubbed the intended architecture “ExtremeScale” supercomputing, and one of the principle goals of the program is to develop dense, energy-efficient petascale and exascale architectures. Specifically, UHPC systems will need to deliver a petaflop of High Performance Linpack (HPL) in a single cabinet and achieve an energy efficiency of at least 50 gigaflops/watt. By comparison, the most efficient supercomputers today, according to the Green500 list, are based on IBM’s Cell processor technology, and offer well under 1 gigaflop/watt. So these ExtremeScale machines will need to be on the order of 100 times more efficient than today’s supercomputers.

Oh, and the machines have to be easy to program. That is, the system design and accompanying software should make it possible for application developers to be freed from managing low-level hardware features or explicitly programming for data locality and concurrency. In fact, the programmer should even be able to implement parallelism without using MPI, or any other communication-based mechanism. In addition, the operating system for these machines has to be “self-aware,” such that it can dynamically manage performance, dependability and system resources.

Since this is under DARPA, the applications UHPC is concerned with are all DoD-type HPC workloads. These include processing massive amounts of streaming sensor data, handling large graph-based, informatics problems, and solving decision class problems. Two other types of target problems, drawn from other DoD applications, are to be selected later. Obviously, such systems will also be applicable to many HPC-type applications in research and industry.

The DARPA announcement last Friday (August 6) was rather brief, only specifying the five organizations that have been selected. As of this writing, only NVIDIA has come out with a public announcement acknowledging the DARPA win. It is unclear whether additional awardees will be named at a later date.

For its part, NVIDIA is teaming with Cray, Oak Ridge National Laboratory and six unnamed universities to design its ExtremeScale prototype. The NVIDIA-Cray-ORNL troika is a natural for this project. When the Fermi GPU was unveiled last September, Oak Ridge announced plans for a multi-petaflop supercomputer based on NVIDIA’s latest GPU. Although not explicitly stated, the ORNL machine will likely be a Cray system, given the DOE lab’s propensity to buy supercomputing gear from them. Of course, when the first ExtremeScale prototype system is produced, NVIDIA is presumably going to be a few generations beyond its Fermi-class GPUs, and by 2018 may even be offering some sort of integrated CPU-GPU processor, a la AMD’s Fusion architecture. NVIDIA’s CUDA software development environment will also have gone through several iterations of enhancements by then.

As the only other commercial firm awarded under UHPC, Intel has a few options to exercise as far as processor architecture is concerned. But with the recent revival of Larrabee, now known as the Many Integrated Core (MIC) processor, Intel will almost certainly be looking to this architecture to get the level of energy efficiency that the UHPC program demands. The chipmaker’s expertise with parallel programming development tools (Ct language, Threading Building Blocks, Parallel Studio, etc.) is also likely to help address the ease-of-programming aspect for these systems.

It’s noteworthy that the two companies awarded UHPC money were chip vendors with a good parallel software base. Contrast this with AMD (assuming they bid for the UHPC work), which has a decent performance/watt story with its CPU-GPU Fusion architecture, but no well-defined software infrastructure to back it up as yet. It’s even more interesting that NVIDIA is now garnering this kind of respect from the HPC research community. As recently as five years ago, no one would have though the GPU maker would be at the cutting-edge of supercomputing.

As one of the ExtremeScale system developers, NVIDIA will receive $25 million spread over the next four years (two 24-month research phases). That effort will produce a preliminary design. The two follow-on phases, when the actual prototypes are developed, will be initiated under a separate solicitation and may be awarded to different teams than were selected for the first two phases.

https://www.hpcwire.com/2010/08/10/darpa_sets_ubiquitous_hpc_program_in_motion/