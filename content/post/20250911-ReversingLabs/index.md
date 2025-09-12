---
# Documentation: https://hugoblox.com/docs/managing-content/

title: "CISA tool aims to boost security for software onboarding"
subtitle: "The new procurement tool seeks to strengthen third-party software risk management (TPSRM). But the process is manual and cumbersome."
summary: ""
authors: []
tags: []
categories: []
date: 2025-09-11T09:19:13+02:00
lastmod: 2025-09-11T09:19:13+02:00
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

*By John P. Mello Jr.*

{{<figure src="onboarding-software-cisa-1400x732.jpg">}}

The U.S. Cybersecurity and Infrastructure Security Agency (CISA) has released a new web-based tool that it says will beef up cybersecurity practices throughout the software procurement lifecycle.

The [free, interactive tool](https://www.cisa.gov/software-acquisition-guide/tool) is based on CISA’s “[Software Acquisition Guide](https://www.insidegovernmentcontracts.com/2024/08/new-guides-released-relating-to-secure-software-development-requirements/) for Government Enterprise Consumers: Software Assurance in the Cyber-Supply Chain Risk Management (C-SCRM) Lifecycle,” which addresses the cybersecurity risks associated with the acquisition and use of software developed by third parties.

“Whether evaluating a single product or managing a complex acquisition, the Web Tool empowers users to make informed, risk-aware decisions that align with federal cybersecurity guidance and best practices,” the agency [said in a statement](https://www.cisa.gov/news-events/news/cisa-unveils-tool-boost-procurement-software-supply-chain-security).

CISA said the tool supports the principles of both [Secure by Design and Secure by Default](https://www.reversinglabs.com/blog/secure-by-design-and-secure-by-default-why-we-need-both-for-appsec) by:

* breaking the Software Acquisition Guide into manageable, adaptive sections based on user input;
* helping users focus on the most relevant questions for their acquisition context;
* enabling exportable summaries that can be shared with CISOs, CIOs, and other key decision makers; and
* supporting stronger due diligence and more secure outcomes across procurement efforts.

“This tool demonstrates CISA’s commitment to offering practical, free solutions for smarter, more secure software procurement,” [Marci McCarthy](https://www.linkedin.com/in/marcimccarthy/), CISA’s director of public affairs, said in a statement. “Transforming the Software Acquisition Guide into an interactive format simplifies integrating cybersecurity into every step of procurement.”

Here’s what you need to know about the new CISA tool — and where it falls short [on third-party software risk managementon TPSRM](https://www.reversinglabs.com/blog/what-is-tpsrm) while securely onboarding software.

## Procurement security shifted left ##

[Rosario Mastrogiacomo](https://www.linkedin.com/in/rmastrog/), chief strategy officer at Sphere Technology Solutions, praised the CISA tool as “a smart step forward in operationalizing Secure by Design principles.” By translating complex procurement requirements into digestible, actionable guidance, organizations can bake security into procurement from the start — not as an afterthought, he said.

Melody (MJ) Kaufmann, an author and instructor at O’Reilly Media, said that, given that  procurement teams aren’t always security experts, suppliers often struggle to highlight the right details. 

> "This tool bridges that gap by giving both sides a clear, practical framework to evaluate and demonstrate secure practices, strengthening cybersecurity from the start of the procurement process."  
> -- [Melody (MJ) Kaufmann](https://www.linkedin.com/in/melodyjkaufmann/)

**David Bader**, director of the Institute for Data Science at the New Jersey Institute of Technology (NJIT), said the tool strengthens cybersecurity practices by introducing standardized security assessments at the procurement stage rather than treating security as an afterthought. 

> "It creates a consistent framework for evaluating suppliers’ security postures, development practices, and vulnerability management processes. This shifts security considerations upstream in the procurement cycle, where they can actually influence purchasing decisions."  
> -- [David Bader](https://www.linkedin.com/in/dbader13/)

The tool also establishes baseline security requirements that suppliers must demonstrate, effectively raising the minimum security standards across the software ecosystem, Bader said.

Jason Soroko, a senior fellow at Sectigo, said the tool can harden every phase of the buying journey by turning abstract guidance into concrete prompts that drive evidence, accountability, and traceability.

Soroko said the new tool eases early intake and market research with structured framing of risk, RFPs with vetted requirements, consistent scoring, enforceable security commitments, and onboarding with controls to achieve measurable service levels. 

> "The dynamic flow reduces noise, keeps nontechnical buyers focused on what matters, and normalizes requests for SBOM and VEX, build provenance and signing, vulnerability disclosure practices, patch timelines, logging and incident reporting, encryption and key management, access governance, and independent assurance such as SOC 2 or ISO 27001."  
> -- [Jason Soroko](https://www.linkedin.com/in/jason-soroko-19b41920/)

The exportable summary produced by the CISA tool can become an auditable artifact that supports approvals, risk acceptance, and continuous monitoring, which helps teams answer regulators and boards with confidence while also lowering supplier fatigue through a common language, Soroko said.

## Cumbersome, manual — and not ML-friendly ##

Jeff Williams, co-founder and CTO of Contrast Security, is less upbeat. He said the tool is a questionnaire that produces a PDF that can be passed on to organizations using a vendor’s software program. “The process is cumbersome, evidence-free, and completely manual,” he said. 

Imagine trying to manage the thousands of PDF documents you would need for every piece of software you use, Williams said. “If you’re going to try to help people, at least make the information machine-readable. Fortunately, the OWASP CycloneDX project has exactly the right way to do this in their [attestations project](https://cyclonedx.org/guides/OWASP_CycloneDX-Authoritative-Guide-to-Attestations-en.pdf).” 

> "I seriously doubt that this [CISA] tool helps anything. It’s an Excel spreadsheet in web clothing, except worse because it’s not machine-readable."  
> -- [Jeff Williams](https://www.linkedin.com/in/planetlevel/)

Williams said the guide on which the tool is based is a grab bag of 393 requirements that range from obvious to obscure. Given the track record for large requirements documents issued by government agencies, he said, he doesn’t have a lot of confidence that this will change things. “I don’t really see how this is different from [CISA’s] last effort building an attestation form that nobody used. Except that this is a different, more comprehensive standard that will make the process even more burdensome.”

Worse, Williams said, CISA hasn’t even followed its own guidance. “This tool is written in PHP using Drupal, a language and platform that both have a truly abysmal track record for security,” he noted. “I found an OWASP Top Ten level vulnerability almost immediately and will be disclosing it to CISA ASAP.”

## Supply chain resiliency is key ##

Shane Barney, CISO at Keeper Security, does see value in CISA’s tool, noting that it translates complex cybersecurity requirements into actionable insights for decision makers at every level. By tailoring outputs to the needs of the user, it makes security part of the conversation from the very beginning, he said. “That accessibility helps close gaps adversaries often exploit in third-party ecosystems, ensuring that security considerations are top of mind in procurement decisions,” Barney said.

> "Supply chain threats remain one of the most pressing concerns in today’s digital ecosystem. No organization operates in isolation, and each vendor introduces both value and potential vulnerability."  
> -- [Shane Barney](https://www.linkedin.com/in/shane-barney-69026528/)

Barney said the key to resilience is applying the same rigorous, security-first standards to suppliers as you do to your own environment. “CISA’s tool makes this process more accessible by embedding consistent criteria into procurement workflows. It enhances visibility and accountability, helping organizations identify partners that not only meet operational needs, but also strengthen the overall security of the supply chain.”

Sphere Technology’s Mastrogiacomo said the new tool is exactly what’s needed to bridge the gap between cybersecurity policy and execution. “As threats to the software supply chain grow more sophisticated, tools that guide procurement teams through complex risk management decisions will be essential,” he said.

## TPSRM must evolve beyond questionnaires ##

The tool’s long-term success hinges on whether it becomes the de facto industry standard rather than just another optional framework, NJIT’s Bader said. “CISA’s credibility and the government’s procurement power provide strong incentives for supplier participation, but the private sector will need to embrace similar standards for maximum impact,” he said.

Bader said the tool must evolve to address emerging threats like AI-powered attacks and supply chain compromises. “Its effectiveness will ultimately be measured not just by adoption rates, but by whether it demonstrably reduces successful supply chain attacks over time,” he said.

Patrick Enderby, senior product marketing manager at ReversingLabs (RL), said that as [software supply chain attacks grow more sophisticated](https://www.reversinglabs.com/blog/lessons-learned-from-3cxs-software-supply-chain-compromise), manual, questionnaire-driven, and vendors’ blind-trust approaches can only take organizations so far. Security teams today are managing hundreds, sometimes thousands, of software requests per year.

> "Producing PDFs, aggregating SBOMs, and validating vendor attestations manually introduces delays, inconsistent results, and ironically a greater risk exposure."  
> -- [Patrick Enderby](https://www.linkedin.com/in/penderby/)

CISA’s effort signals growing federal pressure for stronger software supply chain security, but meeting these expectations demands automation, evidence-based validation, and scalable workflows, Enderby said.

https://www.reversinglabs.com/blog/cisa-tool-software-onboarding-tpsrm
