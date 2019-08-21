---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Analyzing Data To Pinpoint Rogue Insiders"
subtitle: "Companies and universities look for specific algorithms that will help identify malicious insiders and compromised systems that are acting as insiders"
summary: ""
authors: []
tags: []
categories: []
date: 2011-11-29T07:21:12-04:00
lastmod: 2011-11-29T07:21:12-04:00
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

*By Robert Lemos, Contributing Editor*

The hunt for technology to identify malicious insiders took off in 2011 with the research arm of the Pentagon, the Defense Advanced Research Projects Agency (DARPA), offering up millions of dollars in grants to fund research.

Earlier this month, for example, the Georgia Institute of Technology announced that DARPA had funded a collective effort by the school and four other organizations to create a suite of algorithms that turn disparate data feeds into real-time alerts of anomalous activity. The project, funded to the tune of $9 million over two years, will detect multiple types of insider threats and is funded [under DARPA's Anomaly Detection at Multiple Scales (ADAMS) project](http://www.darkreading.com/security/news/227701306/darpa-project-to-tackle-inside-security-threats.html).

"We are going after the hardest insider threats -- an organization where everyone is trusted and perhaps cleared," says **David Bader**, a professor at Georgia Tech's College of Computing and co-principal investigator on the project. "We are looking at an area where people might, over years, head down the slippery slope."

The team is led by Science Applications International Corp. (SAIC) and -- in addition to Georgia Tech -- includes researchers from Oregon University, the University of Massachusetts, and Carnegie Mellon University.

DARPA has yet to announce grants for its second project, the Cyber Insider Threat (CINDER) program.

Analyzing big data for business intelligence has become a key tool for companies to compete. Now universities and security firms are modifying the techniques to analyze data from multiple sources and identify anomalous behavior of individuals. SAIC, Georgia Tech, and the rest of its team will use a variety of big-data techniques and machine learning to create a prototype system. The technology will go beyond typical network anomaly detection and include non-network data.

"We need specialized technology to do this, but whether or not we need government deployed software versus COTS is an open question," says Eddie Schwartz, chief security officer for security giant RSA. Among the other groups that won a grant for DARPA's ADAMS project is Raytheon, for a commercial system that is already used. The system, SureView, monitors and captures end-user activity that is anomalous and could be malicious.

Such specialized systems [are necessary to detect insider threats](http://www.darkreading.com/insider-threat/167801100/security/news/227900189/pentagon-s-insider-threat-push-offers-lessons-for-enterprises.html), Schwartz says. In the past, counterintelligence techniques called for identifying anomalies in the behavior of individuals in sensitive positions.

"If you think classically, how would you find indicators in people's activities? Large deposits in their bank accounts, changes in the way they drive to work," he says. "Those types of human intelligence observations that we saw classically during the Cold War, we are just extending to the dark side of cyberspace."

A key benefit of anomaly detection is that previously unknown threats can be detected. But a drawback is that the systems typically create a large number of alerts, many of them false, says Malek Bin Salem, a cybersecurity research scientist at Accenture Technology Labs. Columbia University has created a system that seeds directories with decoy documents that appear interesting but will alert the owners if opened or copied. Salem, a former Columbia researcher that worked on the project, found that 20 decoy files can typically catch an intruder on a personal file system containing 100,000 documents.

"The advantage of any honeypot technology [like the Columbia system] is that the signal is going to be stronger -- if you see an alert, it is very likely going to be a real attack," she says.

A startup company, Allure Security Technology, has licensed the technology from Columbia and is also funded under the ADAMS program.

With such systems, however, comes the danger that an employee who changes his behavior for benign reasons or that inadvertently accesses a decoy file could find himself under suspicion. The Pentagon is most interested in detecting malicious insiders before they commit their ultimate rogue act, suggesting the precrime predictions of the movie *Minority Report*.

Yet Georgia Tech's Bader says the goal is not prediction, but accurate documenting an insider's behavior.

"We are not looking for pre-crime," he says. "We are looking for a chain of evidence. This is a new type of security that we will see in the future."

https://w1.darkreading.com/vulnerabilities---threats/analyzing-data-to-pinpoint-rogue-insiders/d/d-id/1136738
