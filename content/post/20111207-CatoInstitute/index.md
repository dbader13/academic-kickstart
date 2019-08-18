---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Big Brothers, PRODIGAL Sons, and Cybersecurity"
subtitle: ""
summary: ""
authors: []
tags: []
categories: []
date: 2011-12-07T08:30:22-04:00
lastmod: 2011-12-07T08:30:22-04:00
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

*By Julian Sanchez*

I [wrote on Monday](https://www.cato.org/blog/cybersecurity-exception-wiretap-laws) that a cybersecurity bill overwhelmingly approved by the House Permanent Select Committee on Intelligence risks creating a significantly broader loophole in federal electronic surveillance law than its boosters expect or intend.  Creating both legal leeway and a trusted environment for limited information sharing about cybersecurity threats—such as the idenifying signatures of malware or automated attack patterns—is a good idea. Yet the wording of the proposed statute permits broad collection and disclosure of any information that would be relevant to protecting against “cyber threats,” broadly defined. For now, that mostly means monitoring the behavior of software; in the near future, it could as easily mean monitoring the behavior of people.

A recent—and somewhat sensationalistic—Fox News article rather breathlessly describes a newly-unveiled security system dubbed PRODIGAL, or Proactive Discovery of Insider Threats Using Graph Analysis and Learning, which “has been built to scan IMs, texts and emails … and can read approximately a quarter billion of them a day.” The article explains:

> “Every time someone logs on or off, sends an email or text, touches a file or plugs in a USB key, these records are collected within the organization,” **David Bader**, a professor at the Georgia Tech School of Computational Science and Engineering and a principal investigator on the project, told FoxNews.com.

> PRODIGAL scans those records for behavior – emails to unusual recipients, certain words cropping up, files transferred from unexpected servers – that changes over time as an employee “goes rogue.” The system was developed at Georgia Tech in conjunction with the Defense Advanced Research Projects Agency (DARPA), the Army’s secretive research arm that works on everything from flying cars to robotic exoskeletons.

Don’t panic just yet: This is strictly being deployed on the networks of government agencies and contractors that handle sensitive information—places where every employee is well aware that their use of the network is subject to close scrutiny, and with good reason.  There’s not really anything to say in principle against the use of such systems in this context, or for that matter on closed business networks where users are on clear notice that such monitoring occurs.

It would, by contrast, be a clear and quite outrageous invasion of privacy for such large-scale behavioral monitoring to be conducted on the residential or mobile broadband networks Americans rely on to provide their personal Internet connectivity—a fortiori if the goal is to share the results with the government without a court order.  As I read it, however, House Intel’s cybersecurity bill would at least arguably permit precisely that.

Under the current language, as long as an Internet provider had a credible good faith belief that it was collecting and sharing behavioral information for one of several broadly defined “cybersecurity purposes”—say, by creating behavioral profiles of potential hackers, disruptive cyberactivists, or “misappropriators” of intellectual property—they’d enjoy full civil and criminal immunity for such actions. That would make any contractual promises to abstain from such monitoring unenforceable—in the highly unlikely event that ordinary users were even able to determine reliably what sort of information was being shared. It would be, to put it as mildly as possible, extraordinarily poor civic hygiene to  enable the construction of this kind of quasi-public/quasi-private monitoring and profiling architecture.

This is not, I believe, the sort of thing the bill’s own architects aspire to bring about.  But the abstract language employed in pursuit of technological neutrality here avoids the risk of obsolescence only by sacrificing predictability.  Courts have recently begun signalling that they’re belatedly inclined to start insisting on full Fourth Amendment search warrants whenever government seeks digitally stored private contents, closing down statutory loopholes that sometimes gave investigators easier access. And now, just as one backdoor closes, a new backchannel granting access to otherwise private and protected material without any judicial process opens up? It does not take a cynic to predict that there will be a potent and persistent incentive to stretch any such channel as wide as the elastic bonds of the English language will permit.

The cleanest way to foreclose this is not to paste in a bunch of after-the-fact usage controls, minimization protocols, or special reports to Congress—though those aren’t bad ideas either. It’s to admit that Congress lacks psychic powers, which may entail that statutes regulating protean areas of technology  have to be (or ought to be) swapped for the newer model about as often as iPhones. The specific, narrow categories of sharing everyone thinks are important and unobjectionable from a privacy perspective can be specifically, narrowly authorized now. In a decade, when we’re beaming thoughts directly to each other via quantum-entangled biomechanical brain implants, we can decide what specific statutory language solves the novel security problems of that technology, in a manner consistent with the Fourth Amendment.

https://www.cato.org/blog/big-brothers-prodigal-sons-cybersecurity
