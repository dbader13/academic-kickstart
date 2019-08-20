---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Your Laptop Can Now Analyze Big Data"
subtitle: "New software makes it possible to do in minutes on a small computer what used to be done by large clusters of computers."
summary: ""
authors: []
tags: []
categories: []
date: 2012-07-17T17:42:50-04:00
lastmod: 2012-07-17T17:42:50-04:00
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

*By John Pavlus*

**Computer scientists from Carnegie Mellon University** have devised a framework for running large-scale computations for tasks such as social network or Web search analysis efficiently on a single personal computer.

The software could help developers working on many modern tasks: for example, designing a new recommendation engine using social network connections. In order to make effective recommendations—“your friends liked this movie, so here is another movie that you haven’t seen yet, but you will probably like”—the software has to be able to analyze the connections between the members of a social network. This type of task is called graph computation, and it is increasingly common. But working with large-scale data sets (such as online social networks) usually requires the processing horsepower of many computers clustered together, such as those offered by Amazon’s cloud-based EC2 service.

The new software, called GraphChi, exploits the capacious hard drives that are becoming ever more common in personal computers. A graph would normally be stored in temporary memory (RAM) for analysis. With GraphChi, the hard drive performs this task instead.

“PCs don’t have enough RAM to hold an entire Web graph, but they do have hard drives, which can hold a lot of information,” says Carlos Guestrin, codirector of Carnegie Mellon’s Select Lab, where GraphChi was developed. But hard drives are slow compared to RAM for reading and writing data, which tends to slow down computation. So Guestrin’s student Aapo Kyrola designed a faster, less random method of accessing the hard drive.

According to Guestrin, a Mac Mini running GraphChi can analyze Twitter’s social graph from 2010—which contains 40 million users and 1.2 billion connections—in 59 minutes. “The previous published result on this problem took 400 minutes using a cluster of about 1,000 computers,” Guestrin says.

As technology gets more networked, and data sets get larger, graph computation is becoming more and more relevant in many domains, says **David A. Bader**, a graph computation expert at Georgia Tech. “Trying to understand how the human brain works or trying to make sense of medical patient records involve graph computing,” he says.

Graph analysis also drives the development of new web products, says Jeremy Kepner, a researcher at MIT. “Document search, ad placement, route planning, travel reservations, and cyber security all rely on graph analysis,” he says. “Enabling web developers to construct these analyses on their desktop computers catalyzes these industries and accelerates product development.”

Guestrin adds that GraphChi can handle “streaming graphs,” which more accurately model large networks by showing how relationships change over time. Bader and others at Georgia Tech have created a graph computation framework, called Stinger, that’s optimized for supercomputers working with massive streaming graphs.

“The scales of these problems will obviously keep growing,” says Guestrin. But he says GraphChi is capable of effectively handling many large-scale graph-computing problems without resorting to cloud-based solutions or supercomputers.

“A researcher in computational biology could do large-scale computations on their PC; a developer working on a data-center algorithm can test it on their laptop before pushing it to the cloud,” Guestrin says. “Big data is everywhere now, but some big data isn’t as big as it once was, relatively speaking. Tools like GraphChi will let many companies and startups solve all their graph-computing needs on a single machine. It’s cost effective, and it drives innovation, too.”

https://www.technologyreview.com/s/428497/your-laptop-can-now-analyze-big-data/
