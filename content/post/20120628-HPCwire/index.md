---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Supercomputer Learns How to Recognize Cats"
subtitle: ""
summary: ""
authors: []
tags: []
categories: []
date: 2012-06-28T17:04:49-04:00
lastmod: 2012-06-28T17:04:49-04:00
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

*By Robert Gelber*

Search giant Google along with researchers from Stanford University have made an interesting discovery based on an X labs project. After being fed 10 million images from YouTube, a 16,000-core cluster learned how to recognize various objects, including cats. Earlier this week, the New York Times [detailed](https://www.nytimes.com/2012/06/26/technology/in-a-big-network-of-computers-evidence-of-machine-learning.html?pagewanted=1&_r=2) the program, explaining its methods and potential use cases.

{{<figure src="Cat_6_28.jpg">}}

The project began a few years ago when Google researchers planned to make a human brain simulation. The compute cluster acted as the brain’s neural network, tasked with learning on its own and using the Internet as a source of information. After processing millions of unlabeled YouTube thumbnails, the system taught itself how to recognize a cat.  While the video website is known for its [comprehensive collection](https://www.youtube.com/results?search_query=cats&oq=cats&gs_l=youtube.3..0l10.4047.4455.0.4566.4.4.0.0.0.0.65.213.4.4.0...0.0.HBHyajSkWPI) of user submitted feline antics, project researchers were focused on the simulation’s ability to learn objects without human input.

A 1,000-node cluster was the basis for the neural network, representing more than 1 billion connections. The unlabeled images were collected randomly and processed by machine-learning algorithms. Similar to IBM’s Watson, the technology relies on “deep learning” techniques, using previous outcomes to inform future decisions. Machine learning has also become integral in other applications, including speech recognition.

The researchers removed all identifying labels from the images because they wanted to see if the network was able to create the concept of an object. Dr. Jeff Dean of Stanford University explained how the project differs from other recognition technologies. “We never told it during the training, ‘This is a cat,’ ” he said “It basically invented the concept of a cat. We probably have other ones that are side views of cats.” 

As a result, the software generated a vague image of a cat on its own. The simulation has also introduced possible evidence of “grandmother neurons”, which some believe are specialized cells, trained to recognize an individual face or concept. 

It’s not all about cats, of course. The system was also able to identify human faces and bodies to some degree. Compared to previous attempts to identify unlabeled images, the simulation fared much better at learning and recognition. According to the researchers’ [findings](https://static.googleusercontent.com/external_content/untrusted_dlcp/research.google.com/en/us/archive/unsupervised_icml2012.pdf), they were able to deliver 15.8 percent accuracy in recognizing 20,000 object categories.  They claim that’s 70 percent better than what had been achieved previously.

According to **David Bader**, executive director of high-performance computing at the Georgia Tech College of Computing, the simulation represents an improvement of “an order of magnitude over previous efforts.” He believes this work could lead to a complete model of the human visual cortex before the end of the decade.

https://www.hpcwire.com/2012/06/28/supercomputer_learns_how_to_recognize_cats/
