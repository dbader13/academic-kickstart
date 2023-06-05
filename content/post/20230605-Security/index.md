---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "What CISOs need to know to mitigate quantum computing risks"
subtitle: ""
summary: ""
authors: []
tags: []
categories: []
date: 2023-06-02T15:32:29-04:00
lastmod: 2023-06-02T15:32:29-04:00
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

**By [David Bader](https://www.securitymagazine.com/authors/4442-david-bader)**

{{< figure src="anton-maksimov-5642-su-qM37iptlCNY-unsplash.jpg" caption="Image via Unsplash">}}

Quantum technologies harness the laws of quantum mechanics to solve complex problems beyond the capabilities of classical computers. Although quantum computing can one day lead to positive and transformative solutions for complex global issues, the development of these technologies also poses a significant and emerging threat to cybersecurity infrastructure for organizations. 

Chief Information Security Officers (CISOs) should not take the impending security threat of quantum computing lightly. To mitigate future risks of quantum attacks, CISOs will need to start identifying where to immediately shore up infrastructure vulnerabilities and developing a longer-term strategic plan to be cyber ready.

## Quantum computing: A security threat ##

Most modern encryption security systems protect sensitive information by relying on the assumed difficulty of factoring a notably large integer (exceeding a thousand or more digits) into its prime factors. Although algorithms capable of finding solutions do exist, using classical computers to solve and identify the two large prime numbers proves to be extremely difficult. By classical computing standards and even with the most capable supercomputers, finding solutions requires exceedingly long running time and are intractable problems. 

However, quantum computers may be able to solve some of the problems that are now considered practically impossible due to processing time. While it is a type of parallel processing exhibited by classical supercomputing and accelerators such as GPUs and FPGAs, quantum computers hold the ability to work with data in different dimensions at once, performing many complex calculations simultaneously with increased processing power. There are immense consequences for data decryption, as quantum computing could accelerate reading and unencrypting data all at once, posing a potential threat to sensitive military communications, corporate trade secrets and intellectual property.

## Preparing for Q-Day: Post-quantum cryptographic standards ##

In the short-term, the security threat of quantum computing is real yet relatively low since the technologies have not yet been successfully developed at sufficiently large quantum machine sizes (in terms of qubits) to break today’s encryption. But these machines are coming: countries and organizations already understand the urgency to prepare in advance for Q-Day: the day when large quantum computers can successfully crack public key encryption systems. 

While the loss of any sensitive data is disastrous, the advancement of large-scale quantum computing puts even stolen encrypted data at risk of becoming exposed. Bad actors, primarily nations, can take a “Harvest Now, Decrypt Later” approach, harvesting enough encrypted data and waiting for a breakthrough in decryption technology.

Since 2016, the National Institute of Standards and Technology (NIST) has been soliciting encryption algorithms that will be resistant to quantum computers. In 2022, NIST announced that four encryption algorithms were selected and will be incorporated in the agency’s post-quantum cryptographic standard, which is expected to be finalized around 2024.

Although the general public won’t notice the shift in cryptographic standards, the transition from public key cryptography to post-quantum cryptography will become a massive undertaking by the U.S. government and lay the foundation for significant systematic change to private communications. Expect the transition to start with U.S. military adoption, as researchers start to understand the best practices and best-of-breed offerings for certification, deployment, as well as server- and client-side encryption and decryption.

## How CISOs can mitigate future risks ##

Although the migration process to quantum-safe cryptographic standards will take time on all levels, it is crucial for CISOs to start developing a careful management plan now. This will require careful planning to deploy new encryption methods in a staged fashion and carefully transitioning both internal systems and external customers to these new methods without disrupting the business. 

### 1. Survey and scrutinize existing infrastructure ###

CISOs should have commanding knowledge of their IT infrastructure, external APIs and cloud services to understand all of their organization’s internal and external data movements. To identify potential weak points and protect their data from external threats, they’ll need to survey their organizations to determine instances of public-key algorithm use in their networks. 

Be keenly aware of potential weak points in the infrastructure’s computer and communications hardware, operating systems, application programs, communications protocols, key infrastructures and access control mechanisms. As organizations became increasingly dependent on off-premise solutions, take stock of which critical services have shifted to cloud providers. Non-host devices on their networks such as routers, printers and even soda machines can also be weak points for attacks.

### 2. Create or update security policies using best practices of the industry ###

Protecting an organization from future threats will require using best practices and taking defensive measures, making sure data is encrypted as it should be and having plans to prevent external threats from exfiltrating data. Best practices include: knowing the internal cyberinfrastructure, conducting regular security testing, training the workforce to be smart security personnel and formulating incident response plans. 

### 3. Build an organization’s deployment plan to be quantum cyber-ready ###

CISOs are navigating uncharted territory abound with potential catastrophic mistakes in choosing encryption software. During this time, officers will need to prioritize deployment, to carefully evaluate the risks for a potential multi-year deployment and to learn emerging best practices. While an organization’s budget can be a limitation, it is not recommended to choose the cheapest solution to simply save costs — these may not be trusted yet. 

As the rest of world prepares for Q-day, it will also be important to follow best practices of the industry. Look for guidance from leading organizations and their implementation plans, including what solutions are acquired and how they are deployed, and take a collaborative learning approach with other industry stakeholders. 

*This article originally ran in **Today’s Cybersecurity Leader**, a monthly cybersecurity-focused eNewsletter for security end users, brought to you by **Security** magazine.*

https://www.securitymagazine.com/articles/99434-what-cisos-need-to-know-to-mitigate-quantum-computing-risks
