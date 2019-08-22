---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Nuke labs show the future of hybrid computing"
subtitle: ""
summary: ""
authors: []
tags: []
categories: []
date: 2009-11-19T08:32:24-04:00
lastmod: 2009-11-19T08:32:24-04:00
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

*By Timothy Prickett Morgan*

The Hybrid Multicore Consortium is on a mission that perhaps all of computing - on the desktop and in the data center - will one day embark on: making hybrid computing architectures as easy to program and use as monolithic platforms have been.

There is a growing consensus - but by no means a complete one - that the future of energy-efficient and yet powerful systems will be based on the coupling of general purpose, multicore CPUs with various kinds of co-processors that also have hundreds of cores to do specific kinds of accelerations needed by particular applications. The trouble with these hybrid computing architectures, which can bring a lot of flops to bear, is that even the smartest people in the world complain about how hard it is to program them.

That is why the Oak Ridge, Lawrence Berkeley, and Los Alamos national laboratories and the **Georgia Institute of Technology** in the United States and the Swiss Federal Institute of Technology in Zurich have banded together to create the Hybrid Multicore Consortium, which is open to members of the HPC, server, accelerator, and software development communities.

According to Jeff Nichols, who runs the Oak Ridge lab, the idea behind the consortium is to mimic the sharing of ideas that the HPC community did in the wake of IBM's BlueGene massively parallel Linux-on-Power systems, which required a different kind of programming model from earlier federated RISC/Unix machines or x64/Linux clusters to squeeze the most performance out of them.

"We believe that the development of code for these hybrid architectures will need a lift, and we cannot do it by ourselves," Nichols said in announcing the consortium at SC09 supercomputer conference in Portland, Oregon, and referring to the massive amount of brainpower that the propellerheads in the major supercomputing centers of the world have.

"Roadrunner is the first hybrid multicore system of any significant size," Nichols said, referring to the hybrid Opteron-Cell blade cluster rated at just above 1 petaflops built by IBM that is installed at the Los Alamos lab. "The challenge is significant, and the programming model to get performance on these machines is going to have to be different."

Andy White, who heads up Los Alamos and who babysits Roadrunner, nodded his head and smiled wryly at that sentiment. "When we began thinking about this in 2002, this was something of a bold vision," White explained. "We are excited about helping mainstream this technology."

White said that he and Horst Simon, the director of the Berkeley Lab, have a running bet about when all of 50 machines at the top of the Top 500 supercomputer rankings will be hybrid architectures like the one embodied in Roadrunner (but certainly based on different technologies). Simon says it will happen in 2014, White in 2018. All of the players in the Hybrid Multicore Consortium are betting that the ramp to exaflops of computing power - that's 1,000 times the oomph of Roadrunner - is going to require hybrid architectures.

Maybe the real bet is when all HPC gear (and quite possibly all servers and all PCs) will be sold with a variety of co-processors, whether they are embedded on CPU chips or on off-chip co-processors. With the advance of Moore's Law, it will be possible to embed all kinds of co-processors as well as memory and switching onto chips. While that electronic integration will solve plenty of signaling and thermal issues, the programming nightmares will remain.

Nichols said that the Hybrid Multicore Consortium will wield a kind of soft power. It is not funding a specific set of technologies, and indeed, it will not be directly involved with any kind of funding. But the expectation is that hybrid architectures will come into being through the normal government and industry budgeting process and that the consortium can be a kind of clearinghouse for the ideas that work and the ideas that don't. What they are looking to establish is what Nichols called "evolutionary co-design."

"We are all doing this, and we are all dealing with a half dozen different design approaches," said Simon. "We need to work as a group and communicate to the vendors what we like and what we don't like."

In addition to the supercomputing labs mentioned above, Advanced Micro Devices, Cray, Convey, Hewlett-Packard, Intel, Micron, Nvidia, Tilera, and Xilinx have all expressed interest in joining the consortium.

While the Hybrid Multicore Consortium is clearly something that the HPC community needs, perhaps a more rigorous approach to standards and some direct government funding for the development of hybrid computing architectures is in order. Uncle Sam ponied up big cash in the 1980s to keep the semiconductor industry alive and indigenous and has pumped huge sums of money into supercomputing centers in the 1990s and 2000s to keep HPC a national priority.

The consortium needs hard power rather than soft power to compel specific investments to discover the hybrid hardware and software technologies that work and to support these in the market. We all stand to benefit from the innovation or at least that is theme of all the talk about exascale computing here at SC09.


https://www.theregister.co.uk/2009/11/19/nuke_lab_hybrid_consortium/
