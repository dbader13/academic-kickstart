---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Data Analysts Seek to Make Social Media More Useful"
subtitle: ""
summary: ""
authors: []
tags: []
categories: []
date: 2012-09-07T07:25:00-04:00
lastmod: 2012-09-07T07:25:00-04:00
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

It’s not easy turning the Mayberry Police Department into the team from CSI, or turning an idea for a new type of social network analysis into something like Klout on steroids, but those types of transformations are becoming ever more realistic. The world’s universities and research institutions are hard at work figuring out ways to make the mountains of social data generated every day more useful and, hopefully, make us realize there’s more to social data than just figuring out whose digital voice is the loudest. Aspiring heirs to the Klout throne, for example, might look to a project called Stinger now under development at Georgia Institute of Technology. Stinger, which stands for Spatio-Temporal Interaction Networks and Graphs Extensible Representation, is a graph-processing engine that project lead **David Bader** says is bigger, faster, and more flexible than anything currently in use for analyzing social media connections. You provide a shared-memory computing system, and it provides an open-source tool that can help detect relationships between billions of people, places, and things as those relationships change over time—even in real time. Someone using Facebook (FB) data, for example, might write an algorithm where people or pages would be the vertices and actions (likes, shares, wall posts, etc.) would be the graph’s edges. One relatively easy application, Bader explains, would be to analyze how activity around particular people is increasing, decreasing, or changing, therefore indicating changes in their importance or the growth of new communities. Writing an algorithm to perform that kind of analysis isn’t really the problem, though—it’s writing one that can scale into the billions of vertices and edges and still perform quickly enough to be useful. An algorithm that generates one false positive in a million isn’t so bad when you’re dealing with tens of thousands of items, Bader says, but it gets to be a big problem when you’re talking about billions of items against which it’s running. There are dozens of open-source graph databasesavailable, including popular offerings such as Neo4j andInfiniteGraph. But, Bader says, “our lab focuses on algorithms that run fast on massive data sets and that are more accurate than what is traditionally done in social media.” Bader’s team recently presented a paper detailing a social media algorithm running atop Stinger that ran 100 times faster than some previous approaches because the system stores the graph’s previous state and performs only the minimal amount of processing necessary as new edges are inserted. This is in contrast to traditional approaches that reprocess the entire graph every time there’s a change.
 That being said, Georgia Tech isn’t alone in analyzing massive amounts of social data with graph databases.Google’s (GOOG) Pregel had already scaled to billions of vertices and edges as of 2009, and Facebook is currently analyzing more than a billion edges using Apache Giraph(an open-source, Hadoop-based Pregel implementation). But those cases—both companies are loaded with smart engineers, data scientists, and powerful infrastructure—just underscore the importance of what researchers like Bader are building and releasing as open source.
 
https://neo4j.com/news/data-analysts-seek-to-make-social-media-more-useful/