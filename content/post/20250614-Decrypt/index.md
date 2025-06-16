---
# Documentation: https://hugoblox.com/docs/managing-content/

title: "IBM’s New Quantum Roadmap Brings the Bitcoin Threat Closer"
subtitle: "IBM’s Starling system may shorten the timeline for quantum computers to challenge Bitcoin’s cryptographic foundations."
summary: ""
authors: []
tags: []
categories: []
date: 2025-06-14T10:59:26-04:00
lastmod: 2025-06-14T10:59:26-04:00
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

*By [Jason Nelson](https://decrypt.co/author/jason)*

{{<figure src="Bitcoin-decrypt-style-09-gID_7.jpg">}}

Quantum computers weren’t expected to pose a threat to [Bitcoin](https://decrypt.co/resources/what-is-bitcoin-four-minute-instant-guide-explainer)’s security anytime soon. But IBM has launched a [project](https://www.ibm.com/quantum/blog/large-scale-ftqc) that could expedite the timeline: the world’s first fault-tolerant quantum computer, set to debut by 2029.

Despite their ability to calculate in multiple directions simultaneously, current-generation quantum computers have high [error rates](https://www.riverlane.com/quantum-error-correction). Without fault tolerance, and the ability to detect and correct errors as they happen, quantum computers can’t run complex algorithms that would be needed to crack [blockchains](https://decrypt.co/resources/blockchain-basics-what-is-blockchain).

The system, named IBM [Quantum Starling](https://newsroom.ibm.com/2025-06-10-IBM-Sets-the-Course-to-Build-Worlds-First-Large-Scale,-Fault-Tolerant-Quantum-Computer-at-New-IBM-Quantum-Data-Center), is being designed to execute 100 million quantum operations using 200 error-corrected qubits. It will be housed at IBM’s quantum data center in Poughkeepsie, New York, and is part of the company’s ongoing roadmap for scalable [quantum computing](https://decrypt.co/resources/from-the-quantum-realm-to-reality-a-beginner-guide-to-the-computer-of-the-future), which extends through 2033.

“Recent revisions to that roadmap project a path to 2033 and beyond, and so far, we have successfully delivered on each of our milestones,” IBM said in a statement. “Based on that past success, we feel confident in our continued progress.”

{{<youtube "zrZHPil0BTA">}}

IBM’s approach to fault tolerance centers on error correction. Quantum systems are highly sensitive to noise and [decoherence](https://research.ibm.com/publications/decoherence-from-classically-undetectable-sources-standard-quantum-limit-for-diffusion), environmental disturbances that can disrupt [qubits](https://www.ibm.com/think/topics/qubit) almost immediately. The company’s solution uses [Bivariate Bicycle](https://www.ibm.com/quantum/blog/nature-qldpc-error-correction) codes, a type of quantum low-density parity-check (LDPC) code that it claims reduces the number of physical qubits needed by up to 90% compared to earlier methods.

Starling will also feature a real-time error correction decoder capable of running on field-programmable gate arrays (FPGAs) or application-specific integrated circuits (ASICs), enabling immediate response to errors before they escalate.IBM’s approach to fault tolerance centers on error correction. Quantum systems are highly sensitive to noise and decoherence, environmental disturbances that can disrupt qubits almost immediately. The company’s solution uses Bivariate Bicycle codes, a type of quantum low-density parity-check (LDPC) code that it claims reduces the number of physical qubits needed by up to 90% compared to earlier methods.

Starling will also feature a real-time error correction decoder capable of running on field-programmable gate arrays (FPGAs) or application-specific integrated circuits (ASICs), enabling immediate response to errors before they escalate.

“A huge effort is devoted to quantum error correction and mitigation, and the new processor’s connectivity is especially promising for implementing quantum error-correcting codes more efficiently,” the technical director of the IBM Quantum Innovation Center at USC, Rosa Di Felice, told *Decrypt*.

“This new processor could help simplify the complex calculations needed to understand how molecules and materials behave,” Di Felice said. “That could lead to breakthroughs in areas like preventing rust, improving chemical reactions, and designing new medicines.”

To understand how IBM plans to achieve its goal, here’s a look at the company’s updated quantum computing roadmap.

## The Starling roadmap ##

### 2025 ###

* Launch of the 120-qubit IBM Nighthawk processor with 16x greater circuit depth capability.  
* Qiskit software enhancements include dynamic circuits and integration with high-performance computing (HPC) environments.  
* Introduction of modular fault-tolerant quantum computing architecture.  
* IBM Quantum Loon is designed to test architecture components for the qLDPC code, including "C-couplers" that connect qubits over longer distances within the same chip.


### 2026 ###

* IBM targets the first quantum advantage demonstrations.  
* Expansion of error mitigation and utility mapping tools to support complex quantum workloads ahead of full fault tolerance.  
* IBM Quantum Kookaburra, expected to be released in 2026, will be IBM's first modular processor designed to store and process encoded information. It will combine quantum memory with logic operations—the basic building block for scaling fault-tolerant systems beyond a single chip.

### 2027 ###

* Scaling to 1,080 qubits through chip-to-chip couplers.  
* IBM Quantum Cockatoo, expected in 2027, will entangle two Kookaburra modules using "L-couplers." This architecture will link quantum chips together, much like nodes in a larger system, thereby avoiding the need to build impractically large chips.

### 2028–2029 ###

* Prototype of a fault-tolerant quantum computer (Starling) expected by 2028, with full deployment targeted for 2029.  

## Why it matters ##

Earlier this week, Strategy co-founder Michael Saylor [downplayed](https://www.ibm.com/quantum/blog/nature-qldpc-error-correction) the threat of quantum computers, calling them a bigger risk to banks and governments than to Bitcoin.

“They will hack your banking system, your Google account, your Microsoft account, and every other asset you have much sooner, because they're an order of magnitude weaker," he said at the time.

Experts, such as **Professor David Bader** of the New Jersey Institute of Technology, view fault tolerance as the linchpin of practical quantum computing—and potentially a threat to current cryptographic systems.

"Fault tolerance is really about making these quantum computers less fragile and less error-prone,” he said. “That is a key technology needed to scale up from beyond a handful of qubits to what we think we'll need for real applications, which may be on the order of tens of thousands to millions of qubits."

Bader acknowledged the fear that one of these applications could compromise cryptographic algorithms that secure cryptocurrencies like Bitcoin, and emphasized the importance of blockchain developers moving toward quantum-resistant encryption.

“A powerful quantum computer capable of running Shor's algorithm is still years away,” he said. “Blockchains won’t suddenly break in 2029—but it’s worth watching.”

https://decrypt.co/325183/ibm-quantum-roadmap-brings-blockchain-threat-closer

https://cryptonews.net/news/bitcoin/31104248/

https://www.ainvest.com/news/ibm-unveils-2029-quantum-roadmap-threatening-bitcoin-security-2506/

https://www.ainvest.com/news/ibm-starling-quantum-computer-reduce-error-rates-90-2029-2506/

https://followin.io/en/feed/18343502

https://www.eblockmedia.com/news/articleView.html?idxno=21706

https://finway.com.ua/en/ibm-introduce-quantum-computer-quantum/

