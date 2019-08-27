---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Supercomputer Digests Twitter in Real-Time"
subtitle: "Specialized hardware and software could provide new insights into the social Web."
summary: ""
authors: []
tags: []
categories: []
date: 2010-10-20T20:28:23-04:00
lastmod: 2010-10-20T20:28:23-04:00
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

*By Christopher Mims*

Determining the most influential users of Twitter is probably not what the creators of the Cray XMT supercomputer had in mind when they designed their machine. But when you’re packing this much computational heat, you go where the hard problems are. Twitter, Facebook and the rest of the social Web have become the modern-day equivalent of the water cooler, albeit with an automatic transcriptionist present. And processing all the data that conversation generates turns out to be a very hard problem.

{{<figure src="cray_xmt.jpg" caption="Cray XMT supercomputer courtesy Cray">}}

For example, as of February 2010, Facebook included 400 million active users with an average of 120 “friend” connections each, all of whom collectively shared 5 billion pieces of information in a single month.

Figuring out who the “influencers” are in such a massive social networks requires creating a gigantic social graph, where each user is a vertex and the connections between them are lines. Ranking users within such a graph requires a determination of their “centrality”. That is, how many other people are connected to them, and how many people are connected to them, and so on, until you get to the trunk of the tree structure underlying connectedness on a service like Twitter.

It turns out this is not the sort of problem that is readily handled even by the usual go-to workstations of the scientific supercomputing world – the GPGPU-powered supercomputers that leverage the graphics chips usually used to render lush 3D environments in videogames. These GPGPU workstations simply don’t allow enough control over how many processes are running in parallel to efficiently churn through social graphs as big as the one represented by Twitter or Facebook.

That’s why David Ediger of Georgia Tech, [with the help of a long list of collaborators](https://web.archive.org/web/20101025140234/http://www.cc.gatech.edu/~bader/papers/MassiveTwitter.html), turned to the 128-CPU Cray XMT housed at the Pacific Northwest National Laboratory. The XMT is a favorite of supercomputing hot-rodders and uber-geeks who appreciate its fine-grained massively multithreaded tunability. This machine is usually pressed into service for solving problems like “Hierarchical Bayesian Modeling for Text Analysis” or [analyzing the stability of America’s power grid](http://www.cray.com/Products/XMT/Product/Resources.aspx), but Ediger had it cogitating on every stray thought from a single day’s worth of the [Twitter firehose](http://mashable.com/2010/03/01/twitter-opens-up-the-firehose-to-startups/).

The Cray made short work of Twitter, disposing of an entire day’s worth of connections in under an hour. The results will surprise no one – on Twitter, a tiny fraction of sources are retweeted widely, mostly government and media, while the rest of the service is either people talking in small groups or literally talking to themselves.

The point, though, is that throwing a finely-tuned Cray running Ediger’s custom software – GraphCT – at Twitter allowed the researchers to digest the service in something like real time. Which is exactly the sort of capability that intelligence agencies, marketers and perhaps even Twitter itself might want to have.


https://www.technologyreview.com/s/421274/supercomputer-digests-twitter-in-real-time/
