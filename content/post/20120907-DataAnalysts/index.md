---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Data Analysts Seek to Make Social Media More Useful"
subtitle: ""
summary: ""
authors: []
tags: []
categories: []
date: 2012-09-07T07:15:17-04:00
lastmod: 2012-09-07T07:15:17-04:00
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

It’s not easy turning the Mayberry Police Department into the team from CSI, or turning an idea for a
new type of social network analysis into something like Klout on steroids, but those types of
transformations are becoming ever more realistic. The world’s universities and research institutions
are hard at work figuring out ways to make the mountains of social data generated every day more
useful and, hopefully, make us realize there’s more to social data than just figuring out whose digital
voice is the loudest.

Aspiring heirs to the Klout throne, for example, might look to a project called Stinger now under
development at Georgia Institute of Technology. Stinger, which stands for Spatio-Temporal
Interaction Networks and Graphs Extensible Representation, is a graph-processing engine that project
lead **David Bader** says is bigger, faster, and more flexible than anything currently in use for analyzing
social media connections. You provide a shared-memory computing system, and it provides an opensource
tool that can help detect relationships between billions of people, places, and things as those
relationships change over time—even in real time.

Someone using Facebook (FB) data, for example, might write an algorithm where people or pages
would be the vertices and actions (likes, shares, wall posts, etc.) would be the graph’s edges. One
relatively easy application, Bader explains, would be to analyze how activity around particular people
is increasing, decreasing, or changing, therefore indicating changes in their importance or the growth
of new communities.

Writing an algorithm to perform that kind of analysis isn’t really the problem, though—it’s writing
one that can scale into the billions of vertices and edges and still perform quickly enough to be useful.
An algorithm that generates one false positive in a million isn’t so bad when you’re dealing with tens
of thousands of items, Bader says, but it gets to be a big problem when you’re talking about billions
of items against which it’s running.

There are dozens of open-source graph databases available, including popular offerings such as Neo4j
and InfiniteGraph. But, Bader says, “our lab focuses on algorithms that run fast on massive data sets
and that are more accurate than what is traditionally done in social media.”

Bader’s team recently presented a paper detailing a social media algorithm running atop Stinger that
ran 100 times faster than some previous approaches because the system stores the graph’s previous
state and performs only the minimal amount of processing necessary as new edges are inserted. This
is in contrast to traditional approaches that reprocess the entire graph every time there’s a change.

That being said, Georgia Tech isn’t alone in analyzing massive amounts of social data with graph
databases. Google’s (GOOG) Pregel had already scaled to billions of vertices and edges as of 2009,
and Facebook is currently analyzing more than a billion edges using Apache Giraph (an open-source,
Hadoop-based Pregel implementation). But those cases—both companies are loaded with smart
engineers, data scientists, and powerful infrastructure—just underscore the importance of what
researchers like Bader are building and releasing as open source.

But social data isn’t just useful for figuring out who’s influential on Twitter or Facebook—it also can
be used to solve some real problems. Bader says he’s already used graph processing with Twitter data
to determine who was leading resistance units during Egypt’s recent revolution. “Anywhere I can
look at connections between entities,” he says, “these approaches are available.”

Indeed. On Wednesday afternoon, for example, a group of researchers from the University of Alberta,
University of Connecticut, and University of California at Merced unveiled a new data-based method
that could make it faster, easier, and less expensive to root out culprits in fraud cases.

The technique uses a method called the Steiner tree to analyze the connections—social, business,
familial, etc.—between the people involved in a given case of fraud. The algorithm is able to
determine the shortest path between two objects, which the researchers posit is especially applicable
to fraud investigations—the person with the shortest path between himself and the crime is probably
the culprit (or at least a solid suspect).

The fraud researchers’ paper follows the publication in August of a method for determining the source
of everything from a disease outbreak to a Twitter rumor by tracking its spread across a complex
network over time. Their algorithm, the paper’s authors claim, could be particularly effective for
combating cybercrime by tracking computer viruses back to their sources. The more connections (in
the case of social data), or observers, a particular point has, the fewer that are needed to track down
the source point.

All the algorithms and data frameworks in the world, however, probably won’t make too big a
difference until they’re turned into products that actually work in real-world situations. As the
University of Alberta’s Ray Patterson pointed out in a press release detailing the fraudster-detection
algorithm: “It might take several years or many years before anyone picks it up. But it’s a good thing
if we can point people towards what’s useful.”

Georgia Tech’s Bader says Darpa, Intel (INTC), Sandia National Laboratories, and other research
institutions have already used Stinger to tackle some complex data sets, and he suspects the project
has a strong commercial interest, as well. If a company is willing to take Stinger from a project into a
product, it could bring the project’s scale and speed to everything from analyzing customer
interactions to monitoring the changing nature of criminal networks, Bader says.

Considering the desire from companies of all types to extract some meaning from social data, I have
to think someone will give it a shot.

https://www.bloomberg.com/news/articles/2012-09-07/data-analysts-seek-to-make-social-media-more-useful
