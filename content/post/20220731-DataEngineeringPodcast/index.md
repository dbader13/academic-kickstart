---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "Data Engineering Podcast: Interactive Exploratory Data Analysis On Petabyte Scale Data Sets With Arkouda"
subtitle: ""
summary: ""
authors: []
tags: []
categories: []
date: 2022-07-31T19:44:02-04:00
lastmod: 2022-07-31T19:44:02-04:00
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

{{<audio src="Episode-311-Arkouda.mp3">}}

Exploratory data analysis works best when the feedback loop is fast and iterative. This is easy to achieve when you are working on small datasets, but as they scale up beyond what can fit on a single machine those short iterations quickly become long and tedious. The Arkouda project is a Python interface built on top of the Chapel compiler to bring back those interactive speeds for exploratory analysis on horizontally scalable compute that parallelizes operations on large volumes of data. In this episode **David Bader** explains how the framework operates, the algorithms that are built into it to support complex analyses, and how you can start using it today.

*Host: Tobias Macey*

https://www.podchaser.com/podcasts/data-engineering-podcast-244123/episodes/interactive-exploratory-data-a-146056977