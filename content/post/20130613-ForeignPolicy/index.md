---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Type 'S' for Suspicious"
subtitle: "DARPA's far-out, high-tech plan to catch the next Edward Snowden."
summary: ""
authors: []
tags: []
categories: []
date: 2013-06-13T22:55:06-04:00
lastmod: 2013-06-13T22:55:06-04:00
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

*By Joshua E. Keating*

{{<figure src="FP-image.jpg" caption="*Jung Yeon-Je / AFP / Getty Images*">}}

Government-funded trolls. Decoy documents. Software that identifies you by how you type. Those are just a few of the methods the Pentagon has pursued in order to find the next Edward Snowden *before* he leaks. The small problem, military-backed researchers tell `Foreign Policy`, is that every spot-the-leaker solution creates almost as many headaches as it’s supposed to resolve.

With more than [1.4 million Americans](http://www.bloomberg.com/news/2013-06-12/top-secret-crate-packers-among-legions-hired-with-leaker.html) holding top-secret clearance throughout a complex network of military, government, and private agencies, rooting out the next Snowden or Bradley Manning is a daunting task. But even before last week’s National Security Agency (NSA) revelations, the government was funding research to see whether there are telltale signs in the mountains of data that can help detect internal threats in advance.

In the months following the WikiLeaks revelations, the Defense Advanced Research Projects Agency (DARPA) — the U.S. military’s [far-out tech](https://foreignpolicy.com/articles/2012/05/31/battleship_earth) arm — put out a number of [requests for research](http://www.wired.com/dangerroom/2010/05/darpa-wants-code-to-spot-anomalous-behavior-on-the-job/) on methods to detect suspicious behavior in large datasets as a way to root out rogue actors like Manning (or in more extreme cases, ones like Fort Hood shooter Nidal Malik Hasan.)

The most ambitious of these is known as Anomaly Detection at Multiple Scales (ADAMS), a program that as an October 2010 [research request](https://www.fbo.gov/download/2f6/2f6289e99a0c04942bbd89ccf242fb4c/DARPA-BAA-11-04_ADAMS.pdf) put it, is meant "to create, adapt and apply technology to the problem of anomaly characterization and detection in massive data sets." The hope is that ADAMS would develop computers that could analyze a large set of user-generated data — the emails and data requests passing through an NSA office in Honolulu for instance — and learn to detect abnormal behavior in the system.

The tricky part of this kind of analysis is not so much training a computer to detect aberrant behavior — there’s plenty of that going around on any large network — it’s training a computer what to ignore.

"I like to use the example of learning to recognize the difference between reindeer and elk," wrote Oregon State University computer scientist Tom Dietterich, who worked on developing [anomaly detection methods for ADAMS](http://web.engr.oregonstate.edu/~tgd/), in an email to **Foreign Policy**. "If all I need to do is tell these species apart, I can focus on the size [of] their antlers and whether the antlers have velvety fur, and I don’t need to consider color. But if I only focus on these features, I won’t notice that Rudolph the Red-Nosed Reindeer is anomalous, because I’m ignoring color (and noses, for that matter). So in an anomaly detection system, it is important to consider any attribute (or behavior) that might possibly be relevant rather than trying to focus on a very few specific characteristics."

Over the past three years, DARPA has [shelled out millions](http://www.dod.mil/pubs/foi/Science_and_Technology/DARPA/12-F-1039_2012-DARPA-Funding-List.pdf) of dollars on efforts to learn how to root out Rudolphs from the rest of the reindeer and find out exactly what these red noses look like. This includes a [$9 million award to **Georgia Tech**](http://www.gatech.edu/newsroom/release.html?nid=72599) to coordinate research on developing anomaly detection algorithms. You can peruse much of the research funded through ADAMS online. For instance, [a proposal](http://info.publicintelligence.net/DARPA-ADAMS.pdf) by the New York-based firm Allure Security Technology, [founded by](http://www.wired.com/dangerroom/2012/07/fog-computing/all/) a Columbia University computer science professor, calls for seeding government systems with "honeypot servers" and decoy documents meant to entice potential leakers to subversives. The files would alert administrators when accessed and allow the system to develop models for suspicious behavior. The company cheekily refers to this technique as "[fog computing](http://ids.cs.columbia.edu/sites/default/files/Fog_Computing_Position_Paper_WRIT_2012.pdf)."

Another [ADAMS-funded paper](http://reports-archive.adm.cs.cmu.edu/anon/2012/CMU-CS-12-100.pdf) by Carnegie Mellon University computer scientist Kevin Killourhy looks at systems to "distinguish people based on their typing." For instance, Killourhy explains, when three typists are asked to type the password ".tie5Roanl," the three users can be easily identified by how long they hold down the "t" key. The paper suggests such technologies "could revolutionize insider-threat detection," though unfortunately even the best systems can have an error rate of up to 63 percent, and detection can apparently be thrown off if the person just isn’t a very good typist. (Note to prospective whistle-blowers: Try two-finger typing.)

Under the fairly obtuse title "[Non-Negative Residual Matrix Factorization with Application to Graph Anomaly Detection](http://www.cs.cmu.edu/~htong/pdfs/sdm11_tong.pdf)," two DARPA-supported IBM researchers attempted to identify the kind of behaviors that might indicate suspicious behavior in a large network. These included "a connection between two nodes which belong to two remotely connected communities," such as an author publishing a paper on a topic not normally associated with his or her research; "port-scanning like behavior," which is when a particular IP address is receiving information from an unusually high number of other addresses; and "collusion," such as a "group of users who always give good ratings to another group of users in order to artificially boost the reputation of the target group."

The thinking has gone somewhat beyond the theoretical level. [At a conference in May](http://www.sei.cmu.edu/community/writ2013/writ2013-program.cfm), researchers from defense firm SAIC presented results from the **PRODIGAL (Proactive Discovery of Insider Threats Using Graph Analysis and Learning) research team** — part of the overall ADAMS initiative — which tested a series of anomaly detection methods on an organization of approximately 5,500 users over the course of two months. "Red teams" were inserted into the data simulating characters such as a "saboteur," an intellectual property thief, and a "rager" — someone prone to "strong, vociferous, abusive, and threatening language in email/Webmail/instant messages." The detection methods varied widely in effectiveness.

Such systems are clearly not yet up to the task of identifying a leaker before he or she strikes, and Dietterich, the Oregon State computer scientist, was cautious when asked whether they ever would be. "Anything I would say here would just be speculation, and artificial intelligence researchers have learned the painful lesson that we are very bad at predicting when, if, or how the methods we develop will be useful," he stated.

ADAMS may still be in the trial stage, but "insider threat" detection was clearly a major priority for the U.S. government even before last week. In October 2011, for instance, President Barack Obama signed an [executive order](http://www.whitehouse.gov/the-press-office/2011/10/07/executive-order-structural-reforms-improve-security-classified-networks-) calling for the creation of an interagency Insider Threat Task Force charged with the "safeguarding of classified information from exploitation, compromise, or other unauthorized disclosure."

The Snowden affair will no doubt only accelerate efforts t
o combat these threats. Of course, if these efforts included high-tech initiatives along the lines of ADAMS, it would be somewhat ironic, as this type of big-data analysis is a [not-so-distant cousin](http://ideas.foreignpolicy.com/posts/2013/06/11/the_academic_paper_that_predicted_the_nsa_scandal?_ga=2.215071831.1715373072.1566269586-2062637566.1566269586) of the much larger surveillance programs that Snowden sought to expose. This type of analysis may alarm [privacy advocates](http://www.theregister.co.uk/2010/05/19/darpa_smite/), but in the end, the idea of intelligence agencies developing a vast high-tech data-surveillance program to prevent anyone from learning about an even vaster high-tech data-surveillance program feels a little more *Catch-22* than *1984*.


https://foreignpolicy.com/2013/06/13/type-s-for-suspicious/
