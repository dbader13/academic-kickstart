---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "Why Do Super Computers Use Linux?"
subtitle: ""
summary: ""
authors: []
tags: []
categories: []
date: 2012-11-05T14:42:47-05:00
lastmod: 2012-11-05T14:42:47-05:00
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

In our last few posts we discussed the fact that [over 90% supercomputers (94.2% to be precise)](https://www.unixmen.com/linux-share-in-supercomputer-os/) employ Linux as their operating system. In this post, a sequel to our last posts, we shall attempt to investigate the potentials of Linux which make it suitable and perhaps the best choice for supercomputers OS.

{{<figure src="THUMB-150x150.jpg">}}

Indeed no one can highlight the capability of Linux as a supercomputer OS better than the team responsible for deploying and maintaining supercomputers. Before we enlist and discuss notable features of Linux, let’s have a look at what key persons in supercomputer domain say about Linux; and what reasons they give when they are asked about selecting Linux as their supercomputer OS.

Mark Seager serves as the assistant department head for advanced technologies at the Lawrence Livermore National Laboratory in Livermore, Calif. The site (Lawrence Livermore National Laboratory) operates ten machines on the Top 500 list, including Blue Gene/L, the world’s most powerful supercomputer, and Thunder, which ranks fifth. The supercomputers, of course, use Linux as an OS. Mark Seager says “Linux has dominated the marketplace for **high-performance** computing”. High-performance Linux clustering is a two-part series providing background on high-performance computing that is only possible with Linux.

Scott Gnau is the chief development officer at Teradata Corporation. The corporation handles several mission critical tasks and deploys supercomputers for computation intensive tasks. The supercomputers run on Linux. Scott says “Our solutions are designed to drive powerful business intelligence and real-time decisioning applications, including fraud detection and prevention, customer segmentation, human resources and forecasting. Our solutions run on SUSE Linux Enterprise Server from Novell, which, thanks to its extreme **scalability**, **reliability**, **flexibility** and **ease of use**, is the optimal Linux operating system for our customers’ businesses. We selected Novell and its SUSE Linux Enterprise platform because of its full range of industry-leading Linux services to support large-scale, mission-critical enterprises”.

Eddie Epstein on System Administration of the Watson Supercomputer when asked about their choice of Linux for the supercomputer said “the project started with x86-based blades, and the researchers responsible for admin were very familiar with Linux.” Indicating **Linux is already famous with researchers**.

Alejandro Ramirez was the leader of the team at the Barcelona Supercomputing Center (BSC) developing the world’s first ARM-based supercomputer. He says about the choice of Linux for supercomputers “the **support** of the Linux operating system is one of the fundamental elements” He further added “**ARM supports Linux well…**”

Irene Qualters is SGI senior vice president of software at SGI. Irene says about their selection of Linux for their , “At SGI, our focus is on **high-performance computing** and **robust scalability**, and SUSE Linux Enterprise Server is the operating system of choice for many of our Altix and Altix XE customers”

Back in 2000, **University of New Mexico** built a virtual supercomputer Los Lobos employing Red Hat Linux with the initial investment of 1.5 Million dollars (then). Dr. Frank Gilfeather was appointed as the executive director of high-performance computing at the University of New Mexico then. Gilfeather said: “We have several customers that would benefit from high-end computing on a Linux cluster. Down the road, we believe that this will be important for e-business as well–as more and more customers deploy middleware and message queueing, they’ll need the kind of power you’ll find in a Linux cluster: indicating the high performance provide by Linux OS. He further says “the evolution of large Linux superclusters emerges from the proliferation of commodity components such as PCs, the development of high-speed COTS networks, such as Myrinet, and rapid expansion of the open software movement,”…. “Thus, true supercomputers can be created at an extremely **reasonable cost** in comparison to traditional supercomputers.”

Stephen Scott a research scientist at Oak Ridge National Lab’s computer-science division (2000) was among the early users/researchers of Linux supercomputer. He says “The scientific world likes Linux because **it’s close to standard Unix**,” Scott added. “Most high-performance environments are Unix, but all of the free GNU tools make it much easier and cheaper to deploy Linux

Having looked at the expert view lets elaborate features of Linux that makes Linux the best choice for supercomputers:

## 1- Modular nature of Linux ##

A layman can think of typical Linux as being made up of small building blocks or modules. Each module performs distinct dedicated utilities. These building blocks work together to make the OS running. This modular nature of Linux facilitates anyone, may they be average Linux users or Supercomputer administrators to modify the OS to suit their requirements. No other operating system, specifically Windows gives freedom of customization to this extent. As a consequence Linux can be modified to be used on supercomputers and archive dedicated goals, particularly enhance performance or energy efficiency etc. Today most supercomputers employ a modified Linux kernel.

## 2-Generic Nature of Linux Kernel ##

Linux kernel is generic, as much as possible. This implies that single source code can be written to run on large supercomputers and also on small even hand-held gadgets; this is entirely upto user how one uses Linux, either on giant systems or smaller systems. There is no need to add fundamental and large changes to the kernel in order to run on larger or smaller systems. Typically Linux kernel can be configured to be as small as 2Mb or as large as 1G or 1T without impending time and effort.

## 3-Scalability ##

Scalability can be defined as the ability of the server to adapt to larger loads. Scalability can be directly thought of as a measure of efficiency, performance. System must be such that addition of new server should be painless. Linux has tremendous scalability as it can accommodate the new and higher loads rather easily. This why you can find Linux run supercomputers and Android (using Linux kernel) on mobile phones, refrigerators and even microwaveovens!

## 4-Open Source Nature ##

Linux is entirely Open source and free software with complete source code available. This implies that supercomputer administrators can customize the OS to any level. Additionally, in case of performance glitches, security loopholes etc. found on supercomputers administrators can alter the code anytime to attain max performance and security (or for that matter any goal); rather than waiting for security updates from proprietary companies.

Supercomputers seek to maximize performance. Usually supercomputers are assigned with jobs that require computation at a very high speed. When compared to Windows, Windows has number of extraneous processes that are unnecessary and only degrade the supercomputer performance  However as Windows is proprietary the code cannot be altered to cut off unnecessary processes. With Linux it is certainly possible which gives a performance boost to computers.

## 5- Community Support ##

Linux being Open source has immense community support that is unparalleled on any other operating system.

## 6- Cost ##

Cost can be of major concern when it comes to huge devices, one like supercomputers. Deploying Linux on supercomputers is cost effective as Linux is completely royalty free.

Other reasons of using Linux as OS is Linux nice networking support. It is relatively easier to add or remove any experimental networking device. No reboots required! Linux is reliable and stable OS that can be run on large costly servers and computers without having to worry alot. Finally, Linux is more secure.

What do you think are factors that make Linux as most suitable choice for Supercomputers? Add your expert comments to make the content richer!

https://www.unixmen.com/why-do-super-computers-use-linux/
