---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "AWS Takes the Short and Long View of Quantum Computing"
subtitle: ""
summary: ""
authors: []
tags: []
categories: []
date: 2022-08-30T12:58:01-04:00
lastmod: 2022-08-30T12:58:01-04:00
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

*By John Russell*

{{<figure src="AWS-packaged-quantum-processor-675x380.jpeg" caption="A microwave package encloses the AWS quantum processor. The packaging is designed to shield the qubits from environmental noise while enabling communication with the quantum computer’s control systems. Source: AWS">}}

It is perhaps not surprising that the big cloud providers – a poor term really – have jumped into quantum computing. Amazon, Microsoft Azure, Google, and their like have steadily transformed into major technology developers, no doubt in service of their large cloud services offerings. The same is true internationally. You may not know, for example, that China’s cloud giants – Baidu, Alibaba, and Tencent –  also all have significant quantum development initiatives.

The global cloud crowd tends to leave no technology stone unturned and quantum was no different. Now the big players are all-in. At Amazon, most of the public attention has centered on Braket, its managed quantum services offering that provides tools for learning and access to a variety of quantum computers. Less well-known are Amazon’s Quantum Solutions Lab, Center for Quantum Computing, and Center for Quantum Networking, the last just launched in June. These four initiatives capture the scope of AWS’s wide-ranging quantum ambitions, which include building a fault-tolerant quantum computer.

{{<figure src="IMG_0393-150x150.jpeg" caption="Simone Severini, AWS Quantum">}}

*HPCwire* recently talked with Simone Severini, director, quantum computing, AWS, about its efforts. A quantum physicist by training, [Severini](https://www.linkedin.com/in/simoneseverini/) has been with AWS for ~ four years. He reports to AWS’s overall engineering chief, Bill Vass. Noting that there’s “not much evidence” that NISQ era systems will provide decisive business value soon, Severini emphasized quantum computing is a long-term bet. Now is the time for watching, learning, and kicking the tires on early systems.

“Amazon Braket provides a huge opportunity for doing that. Customers can keep an eye on the dynamics of the evolution of this technology. We believe there’s really not a single path to quantum computing. It’s very, very early, right. This is a point that I like to stress,” said Severini. “I come from academia and have been exposed to quantum computing, one way or another, for over two decades. It’s amazing to see the interest in the space. But we also need to be willing to set the right expectations. It’s definitely very, very early still in quantum computing.”

Launched in 2019, AWS describes Braket as a “fully managed quantum computing service designed to help speed up scientific research and software development for quantum computing.” This is not unlike what most big quantum computer makers, such D-Wave, IBM and Rigetti also provide.

The premise is to provide all the quantum tools and hardware infrastructure required for new and more experienced quantum explorers to use on a pay-as-you-go basis. Indeed, in the NISQ era, many believe such portal offerings are the only realistic way to deliver quantum computing. Cloud providers (and other “concierge-like” service providers such Strangeworks, for example) have the advantage of being able to provide access to several different systems.

With Braket, said Severini, “Users don’t have to sign contracts. Just go there, and you have everything you need to see what’s going on [in quantum computing], to program or to simulate, and to use quantum computers directly. We have multiple devices with different [qubit] technologies on the service. The hope is that on one side, customers can indeed keep an eye on the technology on the other side, researchers can run experiments and hopefully contribute to knowledge as well contribute to science.”

Braket currently offers access to quantum computers based on superconducting, trapped ion, photonic, and quantum annealers. Presumably other qubit technologies, cold atoms for example, will be added over time.

{{<figure src="AWS-Quantum-Hardware.png">}}

Interestingly, Braket is also a learning tool for AWS. “It’s an important exercise for us as well, because in this way, we can envision how quantum computers one day, would really feed a complex, cloud based infrastructure. Today, the workloads on Braket are all experimental, but for us, it’s important to learn things like security or operator usability, and the management of resources that we do for customers,” said Severini. “This is quite interesting, because in the fullness of time, a quantum computer could be used together with a lot of other classical resources, including HPC.”

On the latter point, there is growing belief that much of quantum computing may indeed become a hybrid effort with some pieces of applications best run on quantum computers and other parts best run on classical resources. We’ll see. While it is still early days for the pursuit of hybrid classical-quantum computing, AWS launched Amazon Braket Hybrid late year. Here’s an excerpt of AWS’s description:

>> “Amazon Braket Hybrid Jobs enables you to easily run hybrid quantum-classical algorithms such as the Variational Quantum Eigensolver (VQE) and the Quantum Approximate Optimization Algorithm (QAOA), that combine classical compute resources with quantum computing devices to optimize the performance of today’s quantum systems. With this new feature, you only have to provide your algorithm script and choose a target device — a quantum processing unit (QPU) or quantum circuit simulator. Amazon Braket Hybrid Jobs is designed to spin up the requested classical resources when your target quantum device is available, run your algorithm, and release the instances after completion so you only pay for what you use. Braket Hybrid Jobs can provide live insights into algorithm metrics to monitor your algorithm as it progresses, enabling you to make adjustments more quickly. Most importantly, your jobs have priority access to the selected QPU for the duration of your experiment, putting you in control, and helping to provide faster and more predictable execution.

>> “To run a job with Braket Hybrid Jobs, you need to first define your algorithm using either the Amazon Braket SDK or PennyLane. You can also use TensorFlow and PyTorch or create a custom Docker container image. Next, you create a job via the Amazon Braket API or console, where you provide your algorithm script (or custom container), select your target quantum device, and choose from a variety of optional settings including the choice of classical resources, hyper-parameter values, and data locations. If your target device is a simulator, Braket Hybrid Jobs is designed to start executing right away. If your target device is a QPU, your job will run when the device is available and your job is first in the queue. You can define custom metrics as part of your algorithm, which can be automatically reported to Amazon CloudWatch and displayed in real time in the Amazon Braket console. Upon completion, Braket Hybrid Jobs writes your results to Amazon S3 and releases your resources.

The second initiative, Amazon Quantum Solution Lab, is aimed at collaborative research programs; it is, in essence, Amazon’s professional quantum services group.

“They engage in research project with customers. For example, they recently wrote a paper with **a team of researchers at Goldman Sachs**. They run a very interesting initiative together with BMW Group, something called the BMW Group quantum computing challenge. BMW proposed four areas related to their interests, like logistic, manufacturing, some stuff that related to automotive engineering, and there was a call for a proposal to crowdsource solutions that use quantum computers to address these problems,” said Severini.

“There were 70 teams, globally, that submitted solutions. I think this is very interesting because [it’s still early days] and the fact is that quantum computers are not useful in business problems today. They can’t [yet] be more impactful than classical computing today. An initiative of this type can really help bridge the real world with the theory. We have several such initiatives,” he said.

## Building a Fault-Tolerant Computer ##

Amazon’s efforts to build a fault-tolerant quantum are based at the AWS Center for Quantum Computing, located in Pasadena, Calif., and run in conjunction with Caltech. “We launched this initiative in 2019 but last year, in 2021, we opened a building that we built inside the campus of Caltech,” said Severini. “It’s a state of the art research facility and we are doing research to build an error-corrected, fault tolerant computer,” he said.

{{<figure src="AWS-Center-for-Quantum-Computing.jpeg" caption="New AWS Center for Quantum Computing at Caltech">}}

AWS has settled on semiconductor-based superconducting qubit technology, citing the deep industry knowledge of semiconductor manufacturing techniques and scalability. The challenge, of course, is achieving fault-tolerance. Today’s NISQ systems are noisy and error-prone and require near-zero Kelvin temperatures. Severini said simply, “There is a lot of scientific challenges still and there’s a lot of engineering to be done.”

“We believe strongly that there are two things that need to be done at this stage. One is improving error rates at the physical level and to invest in material science to really understand on a fundamental level how to build components that have an improvement in with respect to error rates. The second point is [to develop] new qubit architectures for protecting qubits from errors,” he said.

“This facility includes everything [to do] that. We are doing the full stack. We’re building everything ourselves from software to the architecture to the qubits, and the wiring. These are long-term investments,” said Severini.

AWS has been relatively quiet in promoting its quantum computer building effort. It has vigorously embraced competing qubit technologies on Braket, and Severini noted that it’s still unclear how progress will unfold. Some approaches may work well for a particular application but not for others. AWS is tracking all of them, and is including some prominent quantum researchers. For example, [John Preskill](https://www.amazon.science/blog/amazon-scholar-john-preskill-on-the-aws-quantum-computing-effort), the Caltech researcher who coined the term NISQ, is an Amazon Scholar. (Preskill, of course, is fittingly the Richard P. Feynman Professor of Theoretical Physics at the California Institute of Technology.)

Last February, AWS published a [paper](https://journals.aps.org/prxquantum/abstract/10.1103/PRXQuantum.3.010329) in PRX Quantum (Building a fault-tolerant quantum computer using concatenated cat codes) which outlines directional thinking. The abstract is excerpted below:

>> “We present a comprehensive architectural analysis for a proposed fault-tolerant quantum computer based on cat codes concatenated with outer quantum error-correcting codes. For the physical hardware, we propose a system of acoustic resonators coupled to superconducting circuits with a two-dimensional layout. Using estimated physical parameters for the hardware, we perform a detailed error analysis of measurements and gates, including cnot and Toffoli gates. Having built a realistic noise model, we numerically simulate quantum error correction when the outer code is either a repetition code or a thin rectangular surface code.

>> “Our next step toward universal fault-tolerant quantum computation is a protocol for fault-tolerant Toffoli magic state preparation that significantly improves upon the fidelity of physical Toffoli gates at very low qubit cost. To achieve even lower overheads, we devise a new magic state distillation protocol for Toffoli states. Combining these results together, we obtain realistic full-resource estimates of the physical error rates and overheads needed to run useful fault-tolerant quantum algorithms. We find that with around 1000 superconducting circuit components, one could construct a fault-tolerant quantum computer that can run circuits, which are currently intractable for classical computers. Hardware with 18 000 superconducting circuit components, in turn, could simulate the Hubbard model in a regime beyond the reach of classical computing.”

The latest [big piece](https://aws.amazon.com/blogs/quantum-computing/announcing-the-aws-center-for-quantum-networking/) of Amazon’s quantum puzzle is the AWS Center for Quantum Networking, located in Boston. AWS says major news about the new center is forthcoming soon. The quantum networking center, said Severini, is focused on hardware, software, commercial and scientific applications. That sounds like a lot and is perhaps in keeping with Amazon’s ambitious quantum programs overall.

The proof of all these efforts, as the saying goes, will be in the pudding.

Stay tuned.

https://www.hpcwire.com/2022/08/30/aws-takes-the-short-and-long-view-of-quantum-computing/
