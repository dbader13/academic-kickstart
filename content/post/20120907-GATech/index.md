---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Who’s the Most Influential in a Social Graph?"
subtitle: "New Georgia Tech Software Recognizes Key Influencers Faster Than Ever"
summary: ""
authors: []
tags: []
categories: []
date: 2012-09-07T08:11:03-04:00
lastmod: 2012-09-07T08:11:03-04:00
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

At an airport, many people are essential for planes to take off. Gate staffs, refueling crews, flight attendants and pilots are in constant communication with each other as they perform required tasks. But it’s the air traffic controller who talks with every plane, coordinating departures and runways. Communication must run through her in order for an airport to run smoothly and safely.

In computational terms, the air traffic controller is the “betweenness centrality,” the most connected person in the system. In this example, finding the key influencer is easy because each departure process is nearly the same.

Determining the most influential person on a social media network (or, in computer terms, a graph) is more complex. Thousands of users are interacting about a single subject at the same time. New people (known computationally as edges) are constantly joining the streaming conversation. 

Georgia Tech has developed a new algorithm that quickly determines betweenness centrality for streaming graphs. The algorithm can identify influencers as information changes within a network. The first-of-its-kind streaming tool was presented this week by Computational Science and Engineering Ph.D. candidate Oded Green at the Social Computing Conference in Amsterdam.

“Unlike existing algorithms, our system doesn’t restart the computational process from scratch each time a new edge is inserted into a graph,” said College of Computing Professor **David Bader**, the project’s leader. “Rather than starting over, our algorithm stores the graph’s prior centrality data and only does the bare minimal computations affected by the inserted edges.”

In some cases, betweenness centrality can be computed more than 100 times faster using the Georgia Tech software. The open source software will soon be available to businesses.

Bader, the Institute’s executive director for high performance computing, says the technology has wide-ranging applications. For instance, advertisers could use the software to identify which celebrities are most influential on Twitter or Facebook, or both, during product launches.

“Despite a fragmented social media landscape, data analysts would be able to use the algorithm to look at each social media network and mark inferences about a single influencer across these different platforms,” said Bader.

As another example, the algorithm could be used for traffic patterns during a wreck or traffic jam. Transportation officials could quickly determine the best new routes based on gradual side-street congestion.

The accepted paper was co-authored by Electrical and Computer Engineering Ph.D. candidate Rob McColl.

*This project is supported by the National Science Foundation (NSF) (Award Number CNS-0708307). The content is solely the responsibility of the principal investigators and does not necessarily represent the official views of the NSF.*

https://www.news.gatech.edu/2012/09/07/who%E2%80%99s-most-influential-social-graph
