---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "How researchers are letting us uncover secrets in social data"
subtitle: ""
summary: ""
authors: []
tags: []
categories: []
date: 2012-09-07T07:23:24-04:00
lastmod: 2012-09-07T07:23:24-04:00
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

*By Derrick Harris*

It’s not easy work turning the Mayberry Police Department into the team from *C.S.I.*, or turning an idea for a new type of social network analysis into something like Klout on steroids, but those types of transformations are becoming increasingly more possible. The world’s universities and research institutions are hard at work figuring out ways to make the mountains of social data generated every day more useful and, hopefully, to make us realize there’s more to social data than [just figuring out whose digital voice is the loudest](http://gigaom.com/cloud/why-klout-really-matters-money-money-money/).

Aspiring heirs to the Klout throne, for example, might look to a project called [STINGER](http://www.cc.gatech.edu/stinger/index.php) currently under development at Georgia Tech University. STINGER, which stands for Spatio-Temporal Interaction Networks and Graphs Extensible Representation, is a graph-processing engine that project lead **David Bader** says is bigger, faster and more flexible than anything currently in use for analyzing social media connections. You provide a shared-memory computing system, and it provides an open-source tool that can help detect relationships between billions of people, places and things as those relationships change over time — even in real time.

Someone using Facebook data, for example, might write an algorithm using where people or pages would be the vertices and actions (likes, shares, wall posts, etc.) would be the graph’s edges. One relatively easy application, Bader explained, would be to analyze how activity around particular people is increasing, decreasing or changing, therefore indicating changes in their importance or the growth of new communities.

### We’ll do the hard work ###

Writing an algorithm to perform that kind of analysis isn’t really the problem, though — it’s writing one that can scale into the billions of vertices and edges and [still perform quickly enough to be useful](http://highscalability.com/blog/2010/3/30/running-large-graph-algorithms-evaluation-of-current-state-o.html). An algorithm that generates one false positive in a million isn’t so bad when you’re dealing with tens of thousands of items, Bader explained, but it gets to be a big problem when you’re talking about billions of items against which it’s running.

There are [dozens of open source graph databases available](http://en.wikipedia.org/wiki/Graph_database), including popular offerings [such as Neo4j](http://gigaom.com/cloud/springsource-links-up-with-neo-technology-on-nosql/) and [InfiniteGraph](http://gigaom.com/cloud/twitters-success-pulls-23-year-old-objectivity-into-nosql/), but he said, “Our lab focuses on algorithms that run fast on massive data sets and that are more accurate than what is traditionally done in social media.”

{{<figure src="dbader2007-small.jpg" caption="David Bader">}}

Bader’s team recently presented a paper detailing a social media algorithm running atop STINGER that ran 100 times faster than some previous approaches because the system stores the graph’s previous state and only performs the minimal amount of processing necessary as new edges are inserted. This is in contrast to traditional approaches that re-process the entire graph every time there’s a change.

That being said, Georgia Tech isn’t entirely alone analyzing massive amounts of social data with graph databases. Google’s (s goog) Pregel had [already scaled to billions of vertices and edges](http://googleresearch.blogspot.com/2009/06/large-scale-graph-computing-at-google.html) as of 2009, and Facebook (s fb) is currently [analyzing more than a billion edges](http://www.slideshare.net/Hadoop_Summit/processing-edges-on-apache-giraph) using [Apache Giraph](http://incubator.apache.org/giraph/) (an open source, Hadoop-based Pregel implementation). But those cases — both companies are loaded with smart engineers, data scientists and powerful infrastructure — just underscore the importance of what researchers like Bader are building and releasing as open source.

### Forget social media, solve real problems ###

But social data isn’t just useful for figuring out who’s influential on Twitter or Facebook — it also can be used to solve some real problems. Bader said he’s already used graph processing with Twitter data to determine who was leading resistance units during Egypt’s recent revolution. “Anywhere I can look at connections between entities,” he said, “these approaches are available.”

Indeed. On Wednesday afternoon, for example, a group of researchers from the University of Alberta, University of Connecticut and University of California-Merced unveiled a new data-based method that could make it faster, easier and less expensive to root out culprits in fraud cases.

The technique uses a method called the Steiner tree to analyze the connections –social, business, familial, etc. — between the people involved in a given case of fraud. The algorithm is able to determine the shortest path between two objects, which the researchers posit is especially applicable to fraud investigations — the person with the shortest path between himself and the crime is probably the culprit (or at least a solid suspect).

The fraud researchers’ paper follows the publication in August of a [method for determining the source of everything](http://gigaom.com/data/an-algorithm-for-tracking-viruses-and-twitter-rumors-to-their-source/) from a disease outbreak to a Twitter rumor by tracking its spread across a complex network over time. Their algorithm, the paper’s authors claim, could be particularly effective for combating cybercrime by tracking computer viruses back to their sources. The more connections (in the case of social data), or observers, a particular point has, the fewer that are needed to track down the source point.

However, all the algorithms and data frameworks in the world probably won’t make too big a difference until they’re turned into products that actually work on real-world situations. As the University of Alberta’s Ray Patterson pointed out in a [press release detailing the fraudster-detection algorithm](http://www.news.ualberta.ca/article.aspx?id=598C1DAC742446ED84B477CB8FA05324), “It might take several years or many years before anyone picks it up. But it’s a good thing if we can point people towards what’s useful.”

Georgia Tech’s Bader said DARPA, Intel (s intc), Sandia National Laboratory and other research institutions have already used STINGER to tackle some complex data sets, and he suspects a strong commercial interest, as well. If a company is willing to take STINGER from a project into a product, it could bring the project’s scale and speed to everything from analyzing customer interactions to monitoring the changing nature of criminal networks, Bader said. Considering the desire from companies of all types to extract some meaning from social data, I have to think someone will give it a shot.

https://gigaom.com/2012/09/07/as-social-data-grows-researchers-want-to-uncover-its-secrets/
