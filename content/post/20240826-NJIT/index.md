---
# Documentation: https://hugoblox.com/docs/managing-content/

title: "NJIT and Illinois Research on Data Analytics Will Measure Impact of Scientific Literature"
subtitle: ""
summary: ""
authors: []
tags: []
categories: []
date: 2024-08-26T11:37:00-04:00
lastmod: 2024-08-26T11:37:00-04:00
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

{{<figure src="DARPA_Big_Data.jpg" caption="U.S. government / public domain image, via Wikimedia Commons">}}

Three distinct problems in data science — trend identification in graphs, the quantitative study of scientific literature and evaluation of single-cell genomics — will all be addressed by new research in large-scale network analytics, jointly led by **Distinguished Professor David Bader** at New Jersey Institute of Technology.

The problems have a common challenge of finding patterns, known as community detection, from inside incredibly large datasets. Work is funded by a $648,000 National Science Foundation grant, [Cyber-Infrastructure for Community Detection, Extraction, and Search in Large Networks](https://www.nsf.gov/awardsearch/showAward?AWD_ID=2402560). Bader is a principal investigator, receiving $250,000 for research. He is working with George Chacko and Tandy Warnow, both of University of Illinois Urbana-Champaign.

What will happen now is the development of new algorithms to identify clusters within those graphs. Bader’s role is scalability and performance. He brings Arachne to the table, which is open-source software that he and colleagues have worked on since 2022, designed to organize graphs with trillions of vertices and edges while presenting a Python interface that almost anyone can learn. Chacko is working on project benchmarking and Warnow is developing new algorithms and interoperability with other methods.

They are planning to test the new method for various applications. In one field, single-cell genomics, it will involve “clustering very large networks whose vertices represent cells and where the weight of an edge between two vertices is computed based on gene expression profiles,” the team explained.

But it’s scientometrics that has Bader most excited. This is a meta-field where researchers study how to mathematically evaluate the impact of papers and citations.

“A lot of information can be learned by looking at the metadata of published literature,” said Bader, director of NJIT’s Institute for Data Science. “For instance, looking at which papers cite others, which authors co-published together, and so on. And when there are questions emerging, like who are the experts on the following topic, or what are the papers I need to read to really get an understanding of a particular field, that's where scientometrics comes into play.”

“Right now, the data sets for scientometrics are very, very large in size, and current tools, for instance, NetworkX in Python, or other such packages, don't scale to the size problems needed by the scientometrics community. So what this grant is enabling is new algorithms and new implementations that are scalable to be able to solve their problems. And so this is where we're going to pick up Arkouda and Arachne to work on them,” he noted, referring to [his own prior research](https://news.njit.edu/institute-data-science-aims-democratize-supercomputing-nsf-grant).

So far, “There are prototypes for some of the algorithms that [Warnow] has developed, and they work on small test cases. So the idea is, we essentially have a proof of concept, but there's sequential implementations, there's slow implementations and our challenge is going to be able to get them to scale to the problem sizes that the scientometrics community needs for their data sets, and to be able to make it run fast.”

https://news.njit.edu/njit-and-illinois-research-data-analytics-will-measure-impact-scientific-literature



