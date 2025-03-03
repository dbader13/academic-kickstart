---
# Documentation: https://hugoblox.com/docs/managing-content/

title: "Fruit Fly Research Led NJIT Scientists and Edison Teens to Better AI Habits on Supercomputers"
subtitle: ""
summary: ""
authors: []
tags: []
categories: []
date: 2025-03-03T11:07:35-05:00
lastmod: 2025-03-03T11:07:35-05:00
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

*Written by: Evan Koblentz*

{{<figure src="In_the_garden_(5039054744).jpg" caption="Fruit fly image by Wikimedia Commons user 'Jean and Fred'">}}

A competition to compare the brains of male vs. female fruit flies led New Jersey Institute of Technology researchers and two high school students to a second-place finish in the latest edition of the FlyWire Data Challenge, but more importantly the team learned new lessons about using artificial intelligence for setting up research with supercomputers.

In the challenge, hosted earlier this year by Princeton University’s Neuroscience Institute, teams had to create efficient maps of the 19,000 synapse connections between neurons in tiny insect brains. The maps take the form of graphs, and the information they convey represents part of the fly brain called a ventral nerve cord connectome.

Distinguished professor David Bader, who directs NJIT’s Institute for Data Science, led NJIT Principal Research Scientist Zhihui Du along with Edison Magnet School students Srijith Chinthalapudi and Harinarayan Asoori Sriram.

The team decided to create algorithms that could run on [NJIT’s Wulver supercomputer](https://news.njit.edu/njit-and-databank-launch-high-performance-computing-environment). To start, they selected Anthropic Claude as their AI system. Claude is a research-focused alternative to generic systems such as OpenAI’s ChatGPT.

“The massive scale of matching two 19,000-node graphs required efficient parallel processing,” Bader explained. “Using Claude 3.5 Sonnet for rapid prototyping helped us quickly iterate through different matching strategies, but we needed to ensure the generated code would scale effectively on Wulver, including multiple parallel programming paradigms like multicore CPU, GPU acceleration and message passing. The challenge wasn't just computational — we needed to maintain solution quality, while handling the complexity of weighted directed edges representing synaptic connections.”

In using AI, “It served as an evaluation engine for new ideas. Claude could effectively evaluate proposed approaches against nearly every published paper in real-time, compressing what would typically be weeks of literature review into minutes of interactive discussion,” Bader observed.

“Claude excelled at transforming these validated ideas into high-performance code with remarkable speed and accuracy. Rather than spending hours implementing each new approach, we could quickly generate optimized, HPC-ready code for multiple algorithmic variations.”

“This dramatic acceleration of the prototyping cycle allowed for much more rapid iteration and experimentation than traditional development approaches. The combination of these capabilities created a powerful new research workflow: generate new algorithmic ideas, have them instantly evaluated against existing literature, get them implemented in efficient code, and rapidly test and iterate. This suggests a new paradigm for computational research where AI serves not merely as a coding assistant but as a comprehensive research partner.”

The broader lesson is that researchers and students of any age should evaluate AI tools based on how the tools are tailored to technical requirements, not just on popularity or general capabilities, Bader noted.

In 2023 the team participated in [a single-brain version](https://news.njit.edu/njit-research-team-innovates-princeton-flywire-codex-challenge) of the competition using consumer-grade AI. They’ll learn about their next challenge on March 6 at the FlyWire awards ceremony.

https://news.njit.edu/fruit-fly-research-led-njit-scientists-and-edison-teens-better-ai-habits-supercomputers
