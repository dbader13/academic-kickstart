---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "Should organizations swear off open-source software altogether?"
subtitle: ""
summary: ""
authors: []
tags: []
categories: []
date: 2023-02-27T16:33:53+01:00
lastmod: 2023-02-27T16:33:53+01:00
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

*Written by [Tim Keary](https://venturebeat.com/author/timkeary/)*

{{<figure src="VB.jpg" caption="Image Credit: Shutterstock">}}

Open-source software is a nightmare for [data security](https://venturebeat.com/security/what-is-cybersecurity-definition-importance-threats-and-best-practices/). According to [Synopsys](https://www.darkreading.com/ics-ot/half-apps-high-risk-vulnerabilities-open-source), while 96% of software programs contain some kind of open-source software component, 84% of codebases contain at least one vulnerability. 

These vulnerabilities are not only present in internal software, but also in third-party apps and services scattered across on-premises and cloud environments.

Awareness over the [software supply chain](https://venturebeat.com/security/the-software-supply-chain-new-threats-call-for-new-security-measures/) threats has been growing over the past few years, with President Biden releasing an [Executive Order](https://www.whitehouse.gov/briefing-room/presidential-actions/2021/05/12/executive-order-on-improving-the-nations-cybersecurity/) in May 2021 calling for federal government agencies to create a [software bill of materials (SBOM)](https://venturebeat.com/security/sboms-what-they-are-and-why-organizations-need-them/), to produce an inventory of software components used throughout their environments. 

Likewise, the revelation that the [Log4j](https://venturebeat.com/security/failing-log4j/) vulnerability [impacted](https://www.veracode.com/blog/security-news/58-orgs-are-using-vulnerable-version-log4j) 58% of organizations showed that organizations needed to be doing more to vet the software they use in their environments.

While the ubiquitous use of open-source software means that organizations can’t swear off these tools altogether, there are some steps organizations can take to start mitigating the risk of exposing critical data assets.

## What risks are facing open-source software? ##

One of the biggest threats facing open-source software is supply chain attacks. In a supply chain attack, a cybercriminal or state-sponsored threat actor will target the maintainer of an open-source project so they can embed malicious code into an open-source library and ship it to any downstream organizations that download it. 

This style of attack is becoming increasingly common to the point where [research](https://www.sonatype.com/state-of-the-software-supply-chain/introduction) suggests that there has been a 742% average annual increase in software supply chain attacks over the past three years, with [Sonatype](https://www.sonatype.com/) discovering 106,872 malicious packages available online. 

“From a supply chain perspective, it’s increasingly common to see malicious code introduced into open source — and that can be accomplished by compromising a legitimate project, or via a malicious project meant to confuse users into downloading counterfeit code that resembles a common project,” said Dale Gardner, Gartner Sr. director analyst. 

Gardner suggests that organizations reliant on open-source software need to evaluate the risk presented by each project. 

“For example, does the project have a good track record for responding to problems, are the appropriate security controls in place, is the code up to date, and so on. And from a supply chain perspective, it’s not just open source with which we should be concerned — we’ve seen a number of cases where commercial code has been compromised,” Gardner said. 

Frameworks such as the secure software development framework (SSDF) and Supply-chain Levels for Software Artifacts (SLSA) are one way that organizations can evaluate software suppliers for potential weaknesses, to evaluate the risk of software they use to build their own applications. 

## Defining acceptable risk in the open-source supply chain ##

Another way to manage risk when implementing open-source software is to define acceptable risk. This comes down to deciding whether the vulnerabilities presented by a particular application present an acceptable and controllable level of risk. 

“Organizations that utilize open-source software, which today is every digitized business, benefit from developing and socializing an open-source strategy. A strategy provides guidelines on when open source can be utilized, what approval is required and what is acceptable risk to the business,” said Janet Worthington, Forrester senior analyst.

“Have a plan in place in the event a high-impacting security vulnerability is disclosed. Your development team may have to back-port a fix to the version of the open-source library that your organization depends on,” Worthington said. 

Worthington highlights that organizations can start to codify and measure risk by creating an SBOM and maintaining an inventory of all software they acquire and download. In addition, security leaders should also ask suppliers to provide a description of their secure software development practices. 

When it comes to open-source libraries, Worthington suggests that organizations should first look for an SBOM; if there isn’t one, then scanning it with a software composition analysis (SCA) tool can help to reveal vulnerabilities in the code. You can then see if updates or patches are available to mitigate it.

However, if you do choose to use an SCA to scan open-source components, it’s important to note that tools that use package managers to identify and scan packages are susceptible to missing [software packages](https://www.prnewswire.com/news-releases/rezilion-research-discovers-hidden-vulnerabilities-in-hundreds-of-docker-container-images-301753477.html) and vulnerabilities.

## Moving beyond SCAs and SBOMs ##

One of the core challenges of securing open-source software components in the enterprise is that they’re not static. Third parties can make changes to open-source software that, at a minimum, create new vulnerabilities, and at worse create actively malicious threats. 

While Lisa O’Connor, global lead of security research at [Accenture](https://www.accenture.com/), notes the importance of static application security testing and SBOMs, she warns “we need to go much deeper to understand the risks.” 

“Researchers from Accenture’s Security Research and Development Labs are currently working on next-generation SBOM traceability to bring the sophistication needed to not only identify security threats, but to understand the downstream effects of vulnerability open-source functions on an organization’s actual installed codebase,” O’Connor said. 

The organization’s Security Research and Development Labs are currently working alongside Professor David Bader from the New Jersey Institute of Technology ([NJIT](https://news.njit.edu/accenture-working-institute-data-science-combat-software-supply-chain-attacks)), an expert in knowledge graphs and analytics, to help improve how organizations identify and isolate vulnerable open-source components. 

Understanding risk as the software supply chain evolves and moves is the key to mitigating open-source risk. Dynamic risks require an equally flexible mitigation strategy. 

https://venturebeat.com/security/should-organizations-swear-off-open-source-software-altogether/
