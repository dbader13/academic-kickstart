---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "Linux and Supercomputing: How my passion for building COTS systems led to an HPC revolution"
subtitle: ""
summary: ""
authors: []
tags: []
categories: []
date: 2021-04-26T21:11:08-04:00
lastmod: 2021-04-26T21:11:08-04:00
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


Back in the early 1990s when I was a graduate student in electrical and computer engineering at the University of Maryland, the term “supercomputer” meant Single Instruction, Multiple Data (SIMD) vector processor machines (the Cray-1 was the most popular), or massively parallel multiprocessor systems, such as Thinking Machine CM-5. These systems were bulky—a Cray-1 measured 8 ½ feet by 6 ½ feet and contained 60 miles of wires[^1] —expensive (costing between $1.5 and $5 million) and required significant expertise to program and operate. Supercomputing at this point in time was mainly a function of the U.S. Department of Defense, large government and academic labs, and large industrial users. Each system used its own proprietary software and none was compatible with another.

But something new was on the horizon—a revolution in supercomputing technology was beginning and would bring scalable, less expensive systems to a much wider audience. That revolution involved using a new open-source operating system called Linux and collections of commodity off-the shelf (COTS) servers to obtain the performance of a more traditional supercomputer. I was deeply involved with that revolution from the start. In 1989, as an undergraduate computer engineering student at Lehigh University, I had my first chance to build a parallel computer, using several Commodore Amiga 1000 personal computers that had been donated to Lehigh by Commodore Business Machines. The computers had been collecting dust in a closet when I teamed up with a friend to create a parallel computer by networking them together. The Amiga 1000 ran the AmigaOS operating system, used a Motorola 68000 processor, and targeted multimedia applications.  In 1990, I designed parallel algorithms on a 128-processor nCUBE hypercube parallel computer donated to Lehigh University by AT&T Bell Laboratories.  In 1992 while pursuing my doctorate at the University of Maryland, I won a NASA Graduate Students Researchers Program Fellowship from Goddard Space Flight Center and in 1993, I assembled my first cluster of Intel-based PCs running the freely-available FreeBSD operating system. This early work building parallel systems led me to understand that the development of powerful parallel machines required a simultaneous development of scalable, high performance algorithms and services. Otherwise, application developers would be forced to develop algorithms from scratch every time vendors introduced a newer, faster hardware platform. 

By the late 1990s, the term “cluster computing” was common among computer science researchers and several of these systems had received significant publicity. One of the first to attract interest was Beowulf, which cost from a tenth to a third of the price of a traditional supercomputer, according to Beowulf.org. A typical setup consisted of server nodes, with each one controlling a set of client nodes connected by Ethernet and running the Linux operating system. In the Spring of 1998, Los Alamos National Laboratory introduced a larger, more powerful version of Beowulf called Avalon, composed of 68 cores of DEC Alpha computers powered by 531MHz EV56 CPUs[^2].  However, neither the Beowulf cluster nor Avalon were genuine supercomputers. 

The Beowulf project was not about developing a supercomputer per se, but rather aimed to "explore the potential of ‘Pile-of-PCs’” at the lowest possible cost and develop methodologies for applying these systems to NASA Earth and space science problems[^3].   Beowulf clusters were limited to solving problems that could be neatly divided into independent tasks, because the communication among processors required to run massively parallel applications on supercomputers was still a dream. As Thomas Sterling, creator of the first Beowulf cluster said, "Basically, you can order most of Beowulf's components from the back pages of Computer Shopper or get them for free over the 'Net."[^4]  While Beowulf clusters could run several applications, performance was disappointing because of the latency and bandwidth limitations. These first Beowulf clusters never could tackle the broad range of supercomputing applications used by the scientific community.

Avalon was powerful enough to make it onto the “Top500 List” of supercomputers in 1998, but although the system was fast, it was not truly a supercomputer.  Avalon’s nodes were connected via Ethernet and utilized message passing over TCP, which meant relatively low bandwidth, high latency, and serious performance issues when executing parallel programs. While Avalon made the Top500 list based on its ability to run the LINPACK benchmark, its limited connectivity meant it could only run applications with a minimal need for communication as well as some domain decomposition methods, where performance is based almost entirely on processor speed alone.

## From Experimental Clusters to the First Bona-fide Linux Supercomputer ##

Less attention has been focused on  systems running Linux and built with COTS components that were developed even before Avalon and Beowulf. In fact, building these systems was my professional passion by this time. In 1996 and 1997, I was an electrical and computer engineering postdoc at the University of Maryland and a National Science Foundation research associate at the University of Maryland’s Institute for Advanced Computer Studies (UMIACS). In this role, I was able to build an experimental computing cluster comprising 10 DEC AlphaServer 2100 4/275 nodes, each with four DEC 21064A Alpha RISC processors and a DEC (OC-3c) 155.52 Mbps PCI card connected to a DEC Gigaswitch ATM switch. The system used either my own communication library or a freely-available MPI implementation. In fact, this DEC system was more advanced  than LANL’s Avalon cluster, which used Fast Ethernet for interconnection rather than a high-performance ATM network with lower latency and higher throughput. From Maryland and my NSF research associate position, I moved to a position in electrical and computer engineering at the University of New Mexico and had the opportunity to build and deploy the first bona-fide Linux supercomputer.

## The National Computational Science Alliance and Roadrunner ##

In January 1998, I joined the University of New Mexico and the Albuquerque High Performance Computing Center (AHPCC) and continued to work on developing clusters of COTS processors into systems with the speed, performance, and services of a more traditional supercomputer. I came to UNM with the idea of building the first x86 Linux supercomputer as a teaching tool for advanced computer design. I became the Principal Investigator for the AHPCC’s SMP Cluster Computing Project and, by spring 1998, had built the first working Intel/Linux supercomputer using an Alta Technologies “AltaCluster,” consisting of 8 dual Intel Pentium II, 333 MHz nodes. My work included a partnership with Myricom to incorporate the first Myrinet interconnection network for Intel/Linux. I also added a job scheduler to the system and installed the “ExtremeLinux” RedHat Linux distribution even before its widespread distribution in May 1998.[^5] 
Around this time, I also became a PI with the new National Computational Science Alliance, a National Science Foundation-supported effort to integrate computational, visualization and information resources into a national-scale "Grid."[^6]   With funding from the Alliance, I was able to put together a team, and we used this 16-processor Linux machine as a prototype for Roadrunner, the first actual Linux supercomputer for production use. Roadrunner entered production mode in April 1999. One of its main improvements over previous Linux systems such as Beowulf and Avalon was its use of an interconnection network called Myrinet from Myricom. The new Myrinet System Area Network (Myrinet/SAN) was twice as fast as Myrinet/LAN and about five times faster than Ethernet, with much lower latency in the 10s of microseconds. Roadrunner’s hardware was fully configured workstations with Intel Pentium II processors and its system software included the Redhat Linux 5.2 operating system, sets of compilers from both the GNU Compiler Collection and the Portland Group, the Portable Batch System (PBS) job scheduler originally designed for NASA’s supercomputers, and features to enable parallel programming, such as software-based distributed shared memory and Message Passing Interface (MPI), a standardized means of exchanging information between multiple computer nodes running a parallel program across distributed memory. 

Roadrunner also included MPICH, a high performance open-source MPI implementation from Argonne National Laboratory, Myricom GM network drivers, and MPICH GM, Myricom’s MPI implementation. The system consisted of 128 dual 450 MHz Intel Pentium II processors, a 512 KB cache, 512 MB, Error Correction Code (ECC), synchronous dynamic random access memory (SDRAM), 6.4 GB IDE hard drive and, to achieve fast networking and low latency, Myrinet network interface cards. Built at a cost of about $400,000, Roadrunner was among the 100 fastest supercomputers in the world at the time it went online and  featured services that were lacking in the first Linux clusters but essential for supercomputing, such as node-based resource allocation, job monitoring and auditing, and resource reservations.[^7]  At the time, Roadrunner was dubbed a supercluster, combining the low cost and accessibility of Linux clusters with the services, fast networking, and low latency of a supercomputer. It was also one of the Alliance’s first hardware deployments designed with the intention of bringing supercomputing to the desktop. Roadrunner would become a node on the evolving National Technology Grid. 

{{<figure src="Picture1.png" caption="Larry Smarr (left), UNM President William Gordon, and U.S. Sen. Pete Domenici turn on the Roadrunner supercomputer in April 1999.">}}

The Grid was envisioned as a way to give researchers access to supercomputers for large-scale problem solving from their desktops, no matter their location, through the nation’s fastest high-performance research networks. Alliance Director Larry Smarr saw the National Technology Grid as another version of the power grid, where users could plug in and get the compute resources they needed, without having to worry about where those resources came from or their own location. 

Within the Alliance, computer scientists and software and hardware engineers worked closely with domain scientists to ensure that the systems being developed would meet the requirements of scientists needing supercomputers to solve complicated scientific problems. Scientific software that ran on Roadrunner included: AZTEC, algorithms for solving sparse systems of linear equations; BEAVIS, (Boundary Element Analysis of Viscous Suspension), used for 3-D analysis of multiphase flows; Cactus, a numerical relativity toolkit for solving astrophysics problems; HEAT, a diffusion partial differential equation using conjugate gradient solver methods; HYDRO, a Langranian hydrodynamics code; and MILC, a set of codes developed by the MIMD Lattice Computation (MILC) collaboration used to study quantum chromodynamics (QCD). 

Roadrunner’s performance on the Cactus application benchmark showed near perfect scalability compared to other systems, such as the NASA Beowulf cluster, the Microsoft Windows NT cluster computer at the National Center for Supercomputing Applications (NCSA),  and the SGI Origin2000, a family of high-end server computers developed by Silicon Graphics. Several scientists who became the pioneer users of the Roadrunner system recently shared with me their memories about those days:

> *“It was a very exciting time; Linux clusters were emerging as a huge force to democratize supercomputing and software frameworks providing community toolkits to solve broad classes of science and engineering problems were also taking shape. The collaboration we had between the Cactus team at the Albert Einstein Institute in Germany and David Bader’s team with the Roadrunner supercluster was a pioneering effort that helped these movements gain traction around the world. The collaboration helped advance the goals of the Cactus team, led by Gabrielle Allen, whose efforts continue to this day as the underlying framework of the Einstein Toolkit. That toolkit now powers many efforts globally to address complex problems in multi-messenger astrophysics.”*
>
>  — Edward Seidel, Ph.D.
>      President, University of Wyoming
>     Former Head of the Numerical Relativity and 
>    E-Science Research Groups, Albert Einstein Institute

&nbsp;

> *“We tested our large weather prediction codes on Roadrunner and found it to be a powerful platform for code development and application, with the move to COTS hardware and software opening the doors to non-proprietary clusters for many researchers who until then only did their work on workstations and laptops. The Roadrunner network (Message Passing Interface) results were superior to those from previous clusters’ Ethernets in moving data from one processor to another during a weather forecast, thus enhancing the forecast turnaround time or forecast quality by allowing for more grid points to be used and a correspondingly more resolved weather feature prediction. We also used Roadrunner to produce detailed simulations of thunderstorms and turbulence generated at commercial airline flight levels.”*
> 
> —Dan Weber
>   Retired Research Meteorologist
>             
> and
> 
> —Kelvin Droegemeier, Ph.D.
> OU Regents Professor of Meteorology
> Weathernews Chair Emeritus
> Roger and Sherry Teigen Presidential Professor
> Former Director, White House Office of Science and Technology Policy
 
&nbsp;

> *“Roadrunner, to my knowledge, was the first Linux cluster-based supercomputer available to the research community. It was a forerunner of what has become a dominant approach in supercomputing.  In 1999, while just starting at MIT, I was able to obtain access to Roadrunner to test and scale a number of key parallel software technologies, which formed the basis of establishing our supercomputing center at MIT.  This early work pioneered on Roadrunner impacts thousands of researchers across MIT.”*
> 
> —Jeremy Kepner, Ph.D.
> Head and Founder, MIT Lincoln Laboratory Supercomputing Center

But the development of the first Linux supercomputer had an impact far beyond the needs of Alliance scientists—it permanently changed supercomputing and its impacts are still felt today.

## The Continuing Linux Supercomputing Revolution ##

As leader of the Alliance/UNM Roadrunner project, I presented my team’s work on advances being made in this “next wave” of supercomputing at various professional events, such as the Alliance Chautauquas held at UNM, the University of Kentucky, and Boston  University in 1999.[^8][^9]    After Roadrunner, I embarked on another Alliance project, this time working with IBM on development of LosLobos, IBM’s first ever Linux production system that was assembled and operated at the University of New Mexico. LosLobos, which premiered on the Top500 list at number 24, consisted of 256 dual-processor IBM Intel-based servers with high-speed Myrinet connections, creating a 512-processor machine capable of 375 gigaflops (375 billion floating point operations per second). 

LosLobos entered production in summer 2000. The Linux supercomputing movement was now well underway, thanks to the proliferation of commodity components, the development of high-speed COTS networks such as Myrinet, the rapid expansion of the open software movement, and the ability of researchers, myself included, to leverage all these developments to move the field forward. For the first time, supercomputers could be built at a relatively low cost. While LosLobos was used primarily by scientists to model and solve complicated problems in physics, biology, and other fields, IBM’s move toward the open-source framework was a sign of the times. Within a year, IBM had used the knowledge gained by working with my Alliance research group on LosLobos to create the first pre-assembled and pre-configured Linux server clusters for business.[^10]

 My focus on Linux supercomputing continued. I worked with IBM to accelerate a different supercomputer, also called Roadrunner, located at LANL, into the first supercomputer to break the petaflop barrier (1 quadrillion FLOPS per second).  I helped develop the Cell Broadband Engine Processor, the multi-core microprocessor that accelerated this supercomputer and was also used in the Sony PlayStation 3. That work was done at the Sony-Toshiba-IBM Center of Competence that I led at Georgia Tech.[^11]   I developed high-performance software libraries for the Cell B.E. for fast Fourier transform, JPEG image encoding, MPEG-2 decoding, data encryption and decryption, and data compression, and grew the ecosystem for accelerated computing.  The Sony PlayStation 3 supported the Linux operating system, and I launched one of the first Cell/B.E. Linux clusters, named CellBuzz, with 14 IBM QS20 blades and 28 Cell/B.E. processors.[^12]

Today, 100 percent of the systems on the Top500 list are Linux systems. As an open-source operating system, Linux can be easily customized for different uses—unlike supercomputers based on vendor-specific Unix systems. Linux, running on commodity  microprocessors, such as x86 or ARM, networked with high-speed commodity interconnects and offering the services of more traditional supercomputers, offers users speed, high-end services, and unprecedented flexibility, all at a lower cost. 

Simply put, because of the creation of supercomputers built from COTS components and running Linux, modern supercomputers are no longer purpose-built monoliths. Instead, they are built from hardware that can be purchased and integrated into any datacenter, making it feasible for organizations to use enterprise systems that are similar to those breaking scientific barriers. The ease of use of Linux supercomputers has had a profound impact on how scientists conduct their research and on the most pressing issues of our time, and I am proud of my role in this revolution in computing and discovery. From simulating astrophysical phenomena, the impacts of climate change, or biological functions at the cellular level, Linux supercomputers are today’s primary tool of knowledge discovery.

Today, researchers are building a new generation of exascale computing systems – machines capable of calculating at least 1018 floating point operations per second (1 exaFLOPS). The Linux operating system is tightly linked to this effort because it provides the scale and flexibility to support high-performance computing at the exascale level. The framework that I developed in the 1990s remains the foundational infrastructure of today’s Linux supercomputers, including the fastest machines in the world. 

For me, this is both thrilling and gratifying. My interest in parallel computing dates way back to 1981, when I read an article in IEEE Transactions on Computers by HJ Siegel et al. on a SIMD/MIMD parallel computing system for image processing and pattern recognition.  I’ve spent my entire career working to make COTS systems running Linux a viable and more affordable alternative to more traditional supercomputers. I’ve incorporated popular compilers, job schedulers, and MPICH to COTS Linux deployments, and those innovations are still used today on Linux supercomputers and have allowed Linux to become the OS of choice on high performance machines. 

Exascale supercomputers will provide unprecedented capability to integrate data analytics, AI, and simulation for advanced 3-D modeling. They will  tackle problems related to neuroscience, clean fusion, the biology of cancer, and will give the U.S. a competitive edge in energy R&D and national security. It is my hope that somewhere a young computer scientist is reading my published work and it is sparking the same inspiration in him or her as Siegel’s work inspired in me. My work has become one of the building blocks of 21st-century computing technologies, and I look forward to how others will continue to build on my innovations with their own.


[^1]: History of Cray Supercomputers. Hewlett Packard Enterprise, https://www.hpe.com/us/en/compute/hpc/cray.html

[^2]: Linux and Supercomputers. Linux Journal, November 29, 2018, https://www.linuxjournal.com/content/linux-and-supercomputers#:~:text=In%20June%201998%2C%20that%20change,comparatively)%20tiny%20cost%20of%20%24152%2C000

[^3]: D. Ridge, D. Becker, P. Merkey and T. Sterling, "Beowulf: harnessing the power of parallelism in a pile-of-PCs," 1997 IEEE Aerospace Conference, Snowmass, CO, USA, 1997, pp. 79-91 vol.2, doi: 10.1109/AERO.1997.577619.

[^4]: Supercomputing gets a new hero, Communications News, August 1, 1998, https://www.thefreelibrary.com/Supercomputing+gets+a+new+hero-a021071072

[^5]: “Announcing Extreme Linux,” May 13, 1998. https://www.redhat.com/en/about/press-releases/press-extremelinux

[^6]: The Grid links the Alliance together and provides access to its wide variety of resources to the national scientific research community. Using high performance networking the Grid will link the highest performing systems to mid-range versions of these architectures, and then to the end-users' workstations, thereby creating a national Power-Grid. NSF Award #9619019, https://www.nsf.gov/awardsearch/showAward?AWD_ID=9619019

[^7]: D. A. Bader, A. B. Maccabe, J. R. Mastaler, J. K. McIver and P. A. Kovatch, "Design and analysis of the Alliance/University of New Mexico Roadrunner Linux SMP SuperCluster," IEEE Computer Society International Workshop on Cluster Computing (IWCC), Melbourne, Victoria, Australia, 1999, pp. 9-18, doi: 10.1109/IWCC.1999.810804.

[^8]: D.A. Bader, “CLUSTERS - The Most Rapidly Growing Architecture of High-End Computing, https://web.archive.org/web/20000203101440/http://chautauqua.ahpcc.unm.edu/agenda.html

[^9]: “Chautauquas Revive an American Forum for a New Era,” Aug. 4, 1999. https://davidbader.net/post/19990804-internet2/

[^10]: IBM unveils pre-packaged Linux clusters. Nov. 14, 2001, ComputerWeekly.com, https://www.computerweekly.com/news/2240043115/IBM-unveils-pre-packaged-Linux-clusters

[^11]: Georgia, not Austin, gets chip center. Nov. 14, 2006, Austin American-Statesman, https://davidbader.net/post/20061114-austinamericanstatesman/

[^12]: Georgia Tech ‘CellBuzz’ Cluster in Production Use. July 11, 2007, HPCWire, https://web.archive.org/web/20070715054621/https://www.hpcwire.com/hpc/1657877.html


### About the Author: ###

***David A. Bader** is a distinguished professor in the department of computer science in the Ying Wu College of Computing and Director of the Institute for Data Science at the New Jersey Institute of Technology. Prior to this, he served as founding professor and chair of the School of Computational Science and Engineering, College of Computing, at the Georgia Institute of Technology. He is a Fellow of the IEEE, AAAS, and SIAM.*

