---
# Documentation: https://hugoblox.com/docs/managing-content/

title: "Research from NJIT and Yale Leads to Trio of Computing Innovations"
subtitle: ""
summary: ""
authors: []
tags: []
categories: []
date: 2025-07-29T10:04:44-04:00
lastmod: 2025-07-29T10:04:44-04:00
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

{{<figure src="Firefly_Start over. Show an example of a graph neural network. 962626.jpg" caption="AI image of data patterns by Adobe Firefly">}}

New research from New Jersey Institute of Technology and Yale University, intended to help identify obscure patterns in overwhelmingly large and convoluted data, is producing novel side effects that advance the state of very old and very new technology.

**NJIT Distinguished Professor David Bader** said the inspiration for a joint $540,000 National Science Foundation grant, “Scalable Algorithmic and Software Foundations for Subgraph Counting and Enumeration," is that existing pattern-finding science is struggling to keep pace with modern data sets.

Applications such as anomaly detection in computer networks for cybersecurity purposes, protein interactions with human cells for evolving treatments and trending topic amplification in social media all begin when algorithms explore subgraphs, which can be as small as just a few interconnected data points.

“Subgraph analysis has been a core part of my research for years,” Bader explained. “But what's driving urgency now is the explosion in dynamic graph sizes — we're seeing networks with billions of edges changing hundreds of millions of times per day. Traditional algorithms simply can't keep up with this scale and dynamism.”

Bader, along with Yale Assistant Professor Quanquan Liu and their team of students and researchers, are developing new algorithms that are provably efficient at counting and listing subgraphs. The team is also making new programming frameworks and they’re looking to perform real-world validation — currently the research is only theoretically optimized. Another goal is to make their software work well on local servers and cloud networks, which are different technical challenges. Liu is focused on the algorithm work, while Bader leads the systems research.

## Challenges and side effects ##

It’s not officially decided, but the new frameworks will likely integrate with Arkouda and Arachne. Arkouda is an open-source data science library for the Python programming language, and Arachne is an Arkouda extension led by Bader which adds features for working with large data.

“Integration into Arachne is definitely the right approach. The major pro is that Arachne already has the distributed computing infrastructure … plus a Python API that data scientists are comfortable with. We'd be building on a proven foundation rather than starting from scratch. The challenge is that Arachne currently doesn't handle dynamic graphs — it's designed for static analysis. We need to carefully architect the batch-dynamic capabilities without breaking existing functionality. But this is much more tractable than building an entirely new system.”

There are two novel side effects of this subgraph research. One is in batch processing, which is the concept that software will ingest all of the data before acting upon it. That’s been common since the dawn of industrial computing in the 1950s. Batch techniques are being implemented to make the new subgraph research possible, because the data being studied are too dynamic for software to examine one step at a time. The research team developed a new way to take a virtual snapshot of the data and work from that information, since real-world full graphs change too quickly to be analyzed in real-time.

The other side effect is on the artificial intelligence frontier — Bader said faster subgraph counting could speed up AI applications that use a common research technique in data science called graph neural networks.

“What excites me most is that we're not just making algorithms faster — we're making breakthrough analysis possible. When you can analyze billion-edge networks that change millions of times per day, you unlock insights that were previously impossible to capture.”

https://news.njit.edu/research-njit-and-yale-leads-trio-computing-innovations
