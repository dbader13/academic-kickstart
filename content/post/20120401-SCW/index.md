---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "Accelerating drug discovery"
subtitle: "High-performance computers are opening up new ways of developing new drugs, as Beth Sharp finds out"
summary: ""
authors: []
tags: []
categories: []
date: 2012-04-01T19:59:20-06:00
lastmod: 2012-04-01T19:59:20-06:00
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

{{<figure src="apr12hpcpill_1.jpg">}}

**Professor David A. Bader**, executive director of High-Performance Computing, School of Computational Science and Engineering, Georgia Institute of Technology
As part of an award from the US National Science Foundation, we are undertaking a project to accelerate computational discoveries at the petascale. The project is a collaboration between three research groups – myself, Professor Jijun Tang at the University of South Carolina and Stephen Schaeffer, a Professor at Penn State – and our focus is on trying to understand the evolutionary histories of multi chromosome organisms. The outcome will prove very useful for the pharmaceutical industry in terms of developing drug targets and understanding the evolutionary process of plants; particularly useful for determining their medicinal properties.

We are developing a new algorithm and parallel program called COGNAC (Comparing Orders of Genes using Novel Algorithms and high-performance Computers) which reconstructs phylogenetic trees using gene order data. COGNAC is a follow-on from our previous code, dubbed GRAPPA, which dealt with the evolutionary histories of single chromosome organisms. Gaining an understanding of how species evolve is, as you can imagine, computationally difficult and this is where the use of HPC allows us to solve the issues efficiently and reduce the development time for pharmaceutical companies. Being able to assess human populations may also lead us to personalised medicine by offering insight into how a drug may effect one group of individuals over another.

The use of a code such as COGNAC will enable us to differentiate people into sub groups based on their evolutionary history in order to fully know which treatments would be the most effective. Furthermore, this will help us to reduce health costs by speeding diagnosis and taking a preventative approach to disease. The code itself is continually being developed in order to make it more useful on real data sets and for it to run faster on new HPC platforms, including multi-core Intel processors and Nvidia GPUs. By keeping up with and harnessing these capabilities, we can attempt to solve problems that just a few years previously would have been considered intractable.

Here at Georgia Tech we’re focusing on this area with a new academic programme in computational science and engineering that addresses both computing and discipline areas such as biology and precise medicine. This combining of disciplines is really where we see the solution to real-world problems such as drug design and discovery, and we’re optimistic that we have the right tools and are training the best people. The challenges lie in determining the effectiveness of these approaches and our ability to innovate with the right algorithms. Our preliminary results are good, however, and as computers become even more capable and push towards exascale, the resources will be there to make significant progress in the study and understanding of evolutionary histories.

 

## Tom Messina, IT manager, High Performance & Scientific Computing, Application Services R&D Strategy & Delivery, Johnson and Johnson ##

As the IT team responsible for delivering high performance and scientific computing solutions to all sectors of Johnson and Johnson R&D, the primary demand we see our business partners facing is constrained compute capacity. This results in lengthy job queues during times of peak demand and filtering activity to determine which simulations they have capacity to run at all. These challenges lead directly to our team’s mission of providing a highly reusable platform offering limitless compute capacity to enable new opportunities and experiments that could not have been done before.

Computer-aided models becoming both more critical and more complex, in combination with the technical advancements of modelling software, has exponentially increased computational demand. While many companies and institutions have purchased very high-end compute machines and farms, many others have not. Regardless, the on-demand elasticity of well-engineered cloud models is one of the best use cases for us to meet this HPC capacity challenge.

Among the demands that our business partners face, particularly as they pertain to cloud computing, are understanding how cloud technology affects the deployment of GxP solutions, overcoming long data transfer times for larger datasets, being comfortable with storing data in the public cloud and working with licensing models that don’t port nicely to the elasticity of cloud platforms.

One of the key requirements we have for the evolution of our own HPC platform is to integrate our disparate internal compute clusters with the cloud environment. Like other organisations, we have made significant investment in building up local compute environments. Many of these environments continue to have decent life left in them. To continue utilising that investment while taking advantage of cloud elasticity, we’re enabling our scientists and engineers to submit jobs to a decision engine. This engine will apply intelligent business rules to determine whether that job should be executed in a local cluster or dynamically provisioned to a cloud cluster, all without the user ever needing to worry about where the job will run.

We have also started to dig into where HPC can add further value. Modelling, simulation, image processing and statistical processing will all be in our portfolio for some time and there are still many areas of J&J we have yet to tap into. However, we have also started to look into how HPC can benefit various areas within business intelligence.

Datasets have reached the point that traditional mining and warehousing approaches either don’t work or are too complex or costly to support. Technologies like Hadoop have already begun to make big strides in this space and it is now on our radar to start taking a look at this opportunity.


## Jason Stowe, CEO at Cycle Computing ##

Pharmaceutical workloads are pleasantly parallel in that they don’t depend on having access to lots of nodes running the exact same job at the same time. We are now in the era of utility supercomputing where much of the computational work can be done on demand infrastructures such as data centres, virtualisation environment and public clouds, which are all particularly suitable for pleasantly parallel workloads.

Amazon web services is one such example being used by pharma researchers due to the fact not only can the service create 30,000 processors to run 30,000 individual analyses at scale, it can do so affordably.

The impact of this is significant; researchers no longer have to wait weeks or months to get results back from certain classes of analysis. When you take into account the fact that there is a cost associated to each day it takes to bring a drug to market, the benefit of speeding up the process is clear. Beyond that, however, the scale of computational possibilities means that not only do jobs get completed faster, but researchers have the time to ask new questions.

Companies will often have an archive of historical data, such as information gathered from mass spectrometers, that would have been analysed at the time but can now have newer algorithms applied if the appropriate level of resources are available. The internal cluster of that company may be perfectly adequate for running the daily analyses, but not for going through that past data. This is where on-demand services can be invaluable.

When there is a significant investment in cluster technology, several generations of hardware will often be deployed and so regular evaluations should be performed on the cluster’s utilisation. This allows users to determine whether they should take advantage of ancillary sources for burst, rather than trying to buy for peak, and ensures that resources aren’t ever lacking or being wasted.


## Sumit Gupta, director of Tesla Product Marketing at Nvidia ##

The definition of high-performance computing has changed. There was a time that the term would only be applied to supercomputers but now even workstations fall into that category and this new definition means that every stage of the pharmaceutical process uses HPC in some way.

The genomics work being done in the earlier stages of the drug lifecycle involves researchers drilling down to a finer level of detail in order to gain an understanding of the genetic structure of living things and how biomolecules behave with certain drug candidates. The molecular structure of the biomolecule/protein may have previously been done through methods such as X-ray crystallography, but genomics and high-speed sequencing machines mean that the genes of individual people can be sequenced to aid understanding of the genetic origin of specific diseases. A great amount of HPC focus is being directed in this area because while clinical trials or drug application reviews at the FDA can’t be accelerated, the discovery phase can.

The discovery phase of drug manufacture can take up to five years and often the results will be a drug that looks promising but that when tested in animal studies or clinical trials is found to have too many side effects. The solution is to narrow down the candidates. Going over millions of compounds in a laboratory would be far too costly in terms of both human labour and time, however computational methods can reduce the field of prospects, which can then be taken to preclinical and clinical studies.

We recently worked with BGI, the world’s largest genomics institute, who bought 300 high-speed sequencers in order to address the problem of China’s aging population. The result was that the institute was soon drowning in petabytes of data. Tesla GPUs accelerated the software so that they could crunch through the data more effectively and they soon began to make interesting discoveries that would not have previously been possible. That’s the main impact high-performance computing has on the pharmaceutical industry.


## Geoffrey Noer, senior director of Product Marketing at Panasas ##

The workload we see far more than any other in life sciences is next-generation sequencing. This has driven a tremendous explosion in need for data storage and has been at the forefront of the demand for HPC resources in the bio-pharmaceutical space. Sequencers are far less expensive than they used to be and as a result institutions will often have multiple sequencers, with each one churning out vast amounts of data. There is a broad movement to compute clusters of x86 servers to do the processing of that data, which in turn drives the need for more storage – not only to house the initial results, but to act as an on-going repository. Scientists will often want to go back and do further analysis on the data and so it needs to be readily available; ensuring that happens typically falls to the IT department.

I would say that the most difficult aspects of being an IT professional in this space are the resource planning and being able to act fast enough. Having spoken with many IT directors in the past, news of a new sequencer being installed is often given with very little advance notice, which leaves them in the position of having to figure out how to immediately provide tens or even hundreds of terabytes of additional storage. Under these circumstances, having a single file system that can be scaled up incrementally as needed is crucial.

The term Big Data is being used to describe the phenomenon of the quantum shift in the amount of data being generated and there’s no doubt that genomics and bio-pharma are part of that trend. The key advice is to thoroughly evaluate the type of architecture that will best suit long-term needs and solve any scalability problems, not only for capacity and performance but in a way that maintains ease of use, manageability and reliability.

https://www.scientific-computing.com/feature/accelerating-drug-discovery
