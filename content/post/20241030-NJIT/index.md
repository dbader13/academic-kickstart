---
# Documentation: https://hugoblox.com/docs/managing-content/

title: "NJIT Research Team Innovates in Princeton FlyWire Codex Challenge"
subtitle: ""
summary: ""
authors: []
tags: []
categories: []
date: 2024-10-30T11:04:17-04:00
lastmod: 2024-10-30T11:04:17-04:00
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

{{<figure src="PXL_20241028_180405267.jpg" caption="NJIT’s team — Zhihui Du, David Bader, Harinarayan Sriram and Srijith Chinthalapudi — is advancing computational neuroscience">}}

An NJIT computational research team made impressive strides at the Princeton FlyWire Codex Data Challenge. Teams were tasked to solve a highly complex problem: analyzing the intricate network of neurons in the brain of a *Drosophila melanogaster* — commonly known as the fruit fly. Teams had to treat this neural network as a massive, interconnected graph and work to determine the best possible ordering of neurons. The goal was to maximize the efficiency of the brain's neural pathways, creating an optimal flow of information within this tiny but surprisingly complex system.

NJIT’s team was led by Distinguished Professor David Bader, and included NJIT’s Institute for Data Science principal research scientist Dr. Zhihui Du, and high school student interns Harinarayan Asoori Sriram and Srijith Chinthalapudi from Edison Academy Magnet School. By the competition's deadline, they achieved a score of 35,231,406 — dramatically improving on the 29 million baseline using the well-known greedy method, which prioritizes the locally optimal choice at each stage. 

However, teams were allowed to continue to refine their algorithm. NJIT’s team improved to first place with a score of 35,459,212 in time for the awards ceremony held Oct. 28 at the Princeton Neuroscience Institute (PNI). Princeton research scientist Arie Matsliah ran the competition and NJIT’s results are directly applicable to the neuroscience research community, including for Mala Murthy, director of PNI, and H. Sebastian Seung, the Evnin Professor in Neuroscience at Princeton.

## Optimizing neural pathways reveals insights for neuroscience and advanced AI systems ##

“The significance of this event lies in its ability to test our advanced data science and optimization techniques in a real-world setting with a challenging dataset of the Drosophila brain connectome,” Bader said. Supported by the National Science Foundation, the NJIT team applied innovative techniques like parallelized simulated annealing and integer programming to yield high-level results.

“Working with the Drosophila brain is significant because its neural architecture provides insights that could translate to more complex systems.” This model offers an ideal testing ground for fundamental studies in neural connectivity, with implications for understanding human brain function and neurological conditions. Beyond the competition, NJIT’s approach to analyzing the connectome graph of the Drosophila brain has potential applications across various fields, from AI systems inspired by neural networks to bioinformatics and logistics.

This challenge also highlights the pursuit for more efficient algorithms that require less power. Training AI large language models, like ChatGPT, can require several megawatts to train — which is roughly the same power as a small town uses in a day. The human brain requires about 20 watts of power to function, which is roughly the energy needed to power a dim light bulb.

## Innovative strategies introduce controlled algorithmic chaos ##

Achieving such a high score required a combination of strategies, including a novel technique dubbed toposhuffling. When running complex simulations, the algorithm might get “stuck” in a suboptimal path, referred to as local maxima in this case. Toposhuffling effectively jolts the algorithm out of this groove through controlled disorder to escape the undesired pathways, which will ultimately score higher.

“Simulated annealing helps to minimize a quantity called energy, and in this challenge, we targeted the weighted sum of forward edges,” Bader explained. “Our team parallelized this approach, running multiple simulations to improve performance, but once progress slowed, we introduced toposhuffling—a method inspired by topological sorting that increased disorder while maintaining solution integrity. This helped us overcome local maxima.” 

For the high school student participants, the challenge provided transformative educational value. They gained hands-on experience in optimization techniques and teamwork, applying theoretical knowledge to solve high-impact problems. “The experience prepared them for future STEM careers, deepening their understanding of data analysis and programming,” said Bader. “The students also performed impressively, I viewed them more like colleagues in this challenge — they were fantastic.”

The event also aligned with NJIT’s broader institutional goals, emphasizing the university’s commitment to data science and interdisciplinary problem-solving. “Our use of techniques like parallelized simulated annealing and integer programming underscores NJIT’s mission to address complex problems,” Bader remarked. “This accomplishment not only strengthens our position in computational research but inspires future applications in neuroscience and AI.”

https://news.njit.edu/njit-research-team-innovates-princeton-flywire-codex-challenge