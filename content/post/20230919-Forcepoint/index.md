---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "To The Point Cybersecurity Podcast: The Democratization of Data Science Tools with Dr. David Bader"
subtitle: "Episode 251"
summary: ""
authors: []
tags: []
categories: []
date: 2023-09-19T11:38:29-04:00
lastmod: 2023-09-19T11:38:29-04:00
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

{{<audio src="E251_-_David_mixdown.mp3">}}

## About This Episode ##

Joining us this week is Dr. David Bader, a Distinguished Professor and founder of the Department of Data Science in the Ying Wu College of Computing and Director of the Institute for Data Science at the New Jersey Institute of Technology. He deep dives into the opportunity to democratize data science tools and the awesome free tool he and Mike Merrill spent the last several years building that can be found on the Bears-R-Us GitHub page open to the public.

We also discuss the vulnerabilities in the open-source supply chain, what AI security teams should be concerned about, data poisoning, AI that is fair and equitable, and the discussion on regulation and self-regulation in AI. Key takeaway from the conversation, data science is indeed growing and it holds an exciting future for those that pursue it!

1:02 Exploring the Power of Data Science Tools  
8:53 Advancing Cybersecurity Through Data Science Tools  
17:22 The Transformative Potential and Challenges of Data Science Tools  
24:53 Self-Regulation and AI Ethics in the Age of Data Science Tools  
32:45 Enabling Secure Information Sharing and Collaboration in a Connected World  
40:13 The Soaring Demand for Data Science Education in Today's World  

{{<figure src="banner.jpg">}}

**Exploring the Power of Data Science Tools**

Rachael: I'm so excited today for our guest. Every guest we have, I learn something new and I absolutely know that that's going to happen today. Please welcome to the podcast Dr. David Bader. He's a distinguished professor and founder of the Department of Data Science in the Ying Wu College of Computing and director of the Institute for Data Science at the New Jersey Institute of Technology. He's a leading expert in solving global grand challenges in science, engineering, computing, and data science. Welcome to the podcast, David.

David: Thanks, Rachel. Good to be here today with you and Audra. Looking forward to talking about cybersecurity.

Rachael: Love it. All right, Audra, I know you got the first question today.

Audra: Could we jump off? I'd really like to start by talking about how open-source tools can support data analytics. And I know that you said on the side a little bit about how you can use some of the solutions to discover vulnerabilities in open source. So could you kick us off in that direction?

David: So as you know, we've discovered in the last couple of years some major exploits dealing with open-source software and libraries included in many packages. This impacts our servers, it impacts our networks, and even our printers. It's really scary to think about. And often open-source software is a supply chain of software that we use in many applications, even in firmware on our devices. And it's very hard to detect malicious software being injected into the open source software. So within a single package, we're very good now as a community for having tools that can scan individual packages. 

 
**Uncovering Hidden Threats with Data Science Tools**

David: But it's very hard to find exploits that may insert code across different packages where each piece of the code may not be that sensitive. But when brought all together and compiled together, linked together, then we find that we have a major exploit. We at the New Jersey Institute of Technology in partnership with Accenture, are working on tools and algorithms that are able to look at the open-source supply chain of software. And detect those vulnerabilities and be able to protect against those exploits. Very exciting project at hand.

Audra: How are you actually linking up across multiple packages to actually be able to work out when something that looks harmless becomes evil?

David: Great question. So we're focused on a major source of open-source software, namely GitHub. And looking at tens of thousands of open-source packages that are used in everyday applications, commercial and business applications. And some of the most impactful projects that are often used by industry. We're ingesting those packages and multiple versions of those packages and building graph connections of lines of software between those packages. Using the most sophisticated graph analytics at scale to detect those vulnerabilities.

Audra: Now, I think this is amazing because I think the problem is we tend to look at what's obvious and it's like, oh. Well if we're using this and it's packaged by package, that's where we're safe. And the fact that we're actually then finding where people are getting smart enough to put different bits of code across different packages. It makes a huge difference to be able to identify that.

 

**Needles in the Haystacks of Open Source Code**

David: That's right. And it's very hard to discover because it may be embedded in different versions of different libraries and packages and by building a graph. A graph is a very simple data structure where maybe vertices in the graph represent lines of source code and different packages. And edges represent connections between those lines of source code and other packages. Maybe where those subroutines are called. By building this massive graph, we're able to discover those connections and those linkages that may be like finding a needle in a haystack without this type of tool.

Audra: Exactly. The only question is where are you getting your actual test data from? Because when you want to find a needle in a haystack, you need to know what the needle might look like.

David: That's correct. Well, we have decades worth of experience building some of the largest graph analytics at scale for the enterprise to discover not just one in a haystack. But many needles in haystacks are made of needles as well. So we've been working on these types of problems for a very long time. Building a lot of tools that have been transferred to industry and government. And we're able to create better algorithms with fidelity to be able to find those exploits. 

We already know of some in the past in the past few years we've seen some of those exploits. So we can learn from those, but we're also expecting that we may have new exploits that we haven't seen before or have new ways. So we're looking for patterns. Graphs are an excellent way to find those patterns of the types of malicious code that we may expect to see in the future.

 

 

**Empowering Cybersecurity with Open Source Data Science Tools**

Audra: So moving on, but still on the topic of open source. How will open-source technology impact the democratization of data?

David: That's a great question, Audra. I'm very passionate about democratizing data science tools. So that anyone in any place on any system is able to perform the really complicated calculations that normally only large enterprises could do. So we are building out tools. Open source tools on GitHub that allow anyone with a Jupyter Notebook or running Python to be able to run their analytics as easily as they would toolkits like NumPy, Pandas, or NetworkX. 

But to be able to manipulate tens to hundreds of terabytes, massive amounts of data on backend supercomputers without having any knowledge or hero programming skills to program a supercomputer. Or understand how to interface and get access to those systems. So we're trying to make data science accessible and provide the tools so that anyone anywhere can run their cybersecurity problems. And be able to ingest data sets, logs, and other information to protect themselves against cyber terrors and cyber hacks.

Audra: Now, I think the thing is we're learning from a work perspective that ML and AI can come into our lives and help us be more efficient. And if you're actually starting to be able to make things more accessible to people who may be data scientists still. So they understand the methodologies and techniques to use it but don't have access to the supercomputers and things like that. This is an amazing step forward.

 

 

**Advancing Cybersecurity Through Data Science Tools**

David: That's right. As you see, learning large language models, for instance, ChatGPT, Bard, and others requires millions of dollars. And massive special purpose-built supercomputers and proprietary libraries to be able to create those models. What we would like to do is provide the tools so that the broad committee can create their own models. And not have to rely on having a budget of millions of dollars and access to new processor technologies to be able to do the same learning and the same capabilities. So we're really passionate about open source and the democratization of these types of tools. 

Audra: So in terms of talking a bit more broadly. Maybe in the way from kind of chassis around open source particularly. But looking at how you apply data analytics to cybersecurity. Where are you seeing the areas where you can really make the biggest inroads?

David: In cybersecurity, there are many types of data sets that we can employ. So for instance, I'll talk to you about some of the problems that we've worked on in the past. One is understanding cyber threats to our organizations. Mostly what happens today is that something egregious is detected. We find that our IP has been exfiltrated. And we find that our perimeters have been encroached on. 

We find that there are bad actors that perform malicious damage to our corporate data sets and so on. We then try to discover how those actors got in, and what they see. What did they touch? What did they damage, what did they take? And this all happens after this egregious event. Now that's great for CISO to try to discover, but what we would like to do is get out in front of the problem. 

 
**Staying Ahead of Cyber Threats with Data Science Tools**

David: We want to be able to detect these types of activities before an egregious event happens. So rather than forensic analysis of our data sets. Where we would like to go is preventative analysis to be able to have situational awareness. The types of streaming analytics in near real-time that tell us that there's an activity about to happen so that we can defend against it. And push those packets out of our networks. Prevent them from coming in before those egregious events happen.

Audra: But again, so what are your common use cases that you're focusing on? If you're preventative, what are you looking for?

David: We're looking for malicious actors. Ones that may come in and sit on our networks for an extended amount of time. For instance, advanced persistent threat, APT, or other types of actors will burrow deep into our networks, hop around our networks, and lay in. Wait until they can touch and exfiltrate data. We don't want them there in the first place. 

And what we try to do is build tools where we can detect those penetrations and also give attribution to where they're coming from and be able to defend against those. And also to do it not with the old methods that they've been able to attack our networks on. But to be able to protect against methods that we may not have seen yet. So we're trying to protect against behaviors where we may not know what that behavior looks like.

Audra: Okay. Now that is very interesting. I'm very pro. We call it going left of the boom. So stopping preventative, stopping it before the boom happens, right? 

David: That's right.

 

**Enhancing Cybersecurity Posture with Data Science Tools**

Audra: So in terms of advice for organizations who are looking to use data analytics to improve their cybersecurity postures. What kind of recommendations can you make?

David: So first I would look at the best practices of security and privacy within organizations.

 And that goes down to training individuals. Often the weakest link in many organizations is that the humans are workforces. I'm even guilty of getting an email and clicking on a link too fast before understanding where that link is coming from. 

And today's spoofing and phishing emails are just, they're terrifyingly good. In fact, with the advent of ChatGPT and other large language models, they are written and more sophisticated than ever. So we have to get better at automatically marking external emails on marking suspicious links. And train ourselves as humans not to just quickly click on the first thing we see in front of us.

Audra: Exactly. What's really interesting about that is previously, depending on language. There were lots and lots of spam emails and spoof emails and those sorts of things going out there. Now with the addition of AI tools. The level of spamming like in other languages like Arabic and things like that, has gone through the roof in the last few months.

David: That's right.

Audra: They have that problem now.

David: So just as they're getting more capable. We need better tools to detect AI-generated messages and better tools to detect these types of attacks clearly.

Audra: So can I ask in terms of what should organizations be concerned about around this area in terms of their posture, in terms of AI, and that sort of thing? What should they be concerned about?

 

 

**Meeting the Challenge of AI-Powered Attacks with Data Science Tools**

David: That's a great question. I think what AI gives are methods for the attackers to evolve much faster than before in the types of attacks that they have. Rather than having to have individuals carefully craft single attacks against weak points in the organization, a network, and individuals. Now they can have a massive attack across every surface, every part of the surface of the organization, every individual. And it's with that scale that now we have to also escalate our defenses. And we have to be much better at recognizing that it's not just one directed email coming in. 

But now we have 10,000 directed emails coming in and we have to be able to protect against this higher rate. This higher onslaught of potential vulnerabilities within the organization. So I think it's that scale and that detection where we're going to have to increase our ability to look at things that look really innocuous. But maybe a Trojan force or a very sophisticated way for an attacker to gain our credentials.

Audra: In terms of your predictions around this and where things are going. Because things are changing very rapidly. What do you actually predict for the future of data analytics in short, medium? How do you think it can be used to kind of enhance or take away either side, where do you see the future going?

David: I think data analytics is off to a great start. This is going to be an area with rapid growth. We already saw the boom of generative AI with ChatGPT emerging last November. December publicly really changed the way we think about our workforce. It changes the way we think about hiring. It changes our cybersecurity posture, it changes our risk profile. 

 

 

**The Transformative Potential and Challenges of Data Science Tools**

David: And I think we're going to continue to see data science evolving rapidly. Like a Cambrian explosion of new ideas, algorithms, and techniques we're really at the start of several years of this rapid change. So we're going to have to hold on. We're going to have to enjoy this ride. And know that we're in a time of great transition and turbulence when it comes to data science and AI.

Audra: Absolutely. But I think this is like the new internet, if you know what I mean because when the internet came out. It was created for particular reasons. They thought it would be very academic and that sort of thing. And it ended up being used for something very different. And I think AI will probably run that path as well.

David: Correct. We are certainly in the hype stage of AI and generative AI right now. And I think comfortably in the next couple of years. We're going to see where generative AI has some incredible uses. But also we're going to see some places where it has incredible failures. We've already seen some, for instance, in the legal system as ChatGPT makes up references in cases argued to the Supreme Court. And as individuals get caught cheating on writings that use ChatGPT, that again takes liberty with the truth. These types of hallucinations, the bias within the results that we're getting today. And the data pollution that can occur within training sets. 

 
**Navigating the Ethical Challenges of AI**

David: These are areas where we need to be aware and understand. And always push toward AI that is explainable, that is fair, and equitable. That's going to be a constant challenge to figure out how to do that and how to give these detailed explanations for how we arrived at the results that we're seeing out of generative AI.

Audra: So in the work that you do, well, we'll go onto the positives. But I'm continuing on the negative side just at the moment in terms of data poisoning or the poisoning of data sets in order to flip labels. Doing all that kind of thing, how much are you seeing of that happening today?

David: That is certainly happening today, and we see such a profound effect on businesses and competition. It is just natural to find those types of attacks taking place. For instance, there may be competitors, whether it's companies within a particular sector or even if it's countries or nation-states. We see this type of attack that is very hard to detect but can have a profound effect on our cybersecurity and our defenses. Whether it's national security or organizational defense.

Audra: Are you able to provide any examples of data poisoning attacks that you're aware of? I was aware of the Google anti-spam where the dataset was poisoned. Therefore spammers were able to send out undetected emails that were definitely spam emails. Because they had actually changed the labeling in the dataset or polluted it to make it more noisy they just weren't getting stopped.

 

**Safeguarding AI Integrity**

David: Well, one area that I've seen is in self-driving cars that use a lot of AI to be able to detect from their sensors what's around them. There have been cases of stickers being placed on, for instance, stop signs or other street signs that cause the AI to mistake a stop sign for say a green traffic light. And so we have to be very careful with these technologies because they can have real-world consequences and affect all of us. So that's an area where we're going to see as we've witnessed before, malicious acts try to taint the learning in these data sets.

Audra: Excellent. Is there any way in the work that you're doing that you look at how you can protect against that?

David: Yes. So one area is to include more explainability within our AI systems. I tend to think that we need to include both machine learning tools along with knowledge graphs and real-world data to really support the explainability behind the answers that we get out of AI. 

There may be other features that get incorporated into our neural necks to be able to give rational explanations that a human. That layperson can understand how it arrived at that decision. And I think that will go a long way to try to understand how models have been tweaked and how they've been changed. That could have disastrous effects. Also, there are models that are tweaked to try to make them more fair. 

 

 

**Data Science Tools and the Quest for Oversight**

David: I just saw, as you probably did at Defcon. This meeting is where there's hacking or trying to abuse ChatGPT to get it to say things that are a little bit controversial or incorrect. And these are very useful for having a nice press release. Here are the bad things it did. But also for open AI to go back and try to tweak their models to prevent some of these poor outcomes from happening. 

So I think again, we're in the very early stages and we're going to see more robust testing tools. And feedback to try to better train and guide these models as they give us inference to our most important problems that we ask of it.

Rachael: I'm always interested in the regulation aspects. It's how do you regulate the unknown basically? And particularly with AI when we don't know all the applications to come. But it's all driven by data. I mean, how do you regulate that in a meaningful way?

David: That's right, and that's a very hard challenge. As you know, leaders in the committee have come together to call for first a moratorium to understand the regulation. And these technologies are also being used in highly regulated industries such as healthcare and the financial sector and these areas. Areas where we really do need to understand how to regulate them. 

And this will be an ongoing conversation. It's very hard to regulate technologies where we're not even aware of the full extent of the capabilities of these technologies. And also we have to have conversations among individuals in this country and around the world on what is it that we allow for our data. How it should be used now or in the future. 

 

 

**Self-Regulation and AI Ethics in the Age of Data Science Tools**

David: There may be uses decades from now from data generated today that aren't even imaginable. And we have to understand how we're going to regulate today those potential uses five, 10 years down the line.

Rachael: So is self-regulation an option here? I mean, we've talked about self-regulation in other areas of technology and how that went. I saw there's an article, I think Google, CEO had made an AI pact with the EU about voluntary behavioral standards prior to them implementing the EU AI Act. And I just thought that was an interesting perspective as we kind of re-look at that whole process and how it could work.

David: That's right, but I think self-regulation for AI right now is going to be very challenging. Many companies are moving forward with AI in leaps and bounds. And one of the reasons is it's an existential threat. If their competitors are doing it and they're not, it could be the end of their company. 

I've had conversations with many CISOs who are looking at how to mitigate the risks while allowing the company to experiment and move forward. Understanding that the regulations may be put into place in the future and how to do things that will remain. Keep the company competitive while not creating that much of a risk in the future. But it is a challenge that we have and never before in the technology sense have we seen such a dramatic change in such a short period of time. 

 
**Empowering Data Analytics with AI**

David: So I believe that the next two, or three years will be a time when we come to terms with what is going to be the right best practices. What is the right amount of regulation by the government? What are the right types of self-regulation as we weather, not necessarily a storm? But this dramatic change and new excitement that we see from these new AI models.

Rachael: Absolutely.

Audra: So can we jump onto the positives of AI? Let's see the positives now. So AI enabled data analytics. How are these technologies helping teams to understand more data and faster, more efficiently? There are sorts of things like what are examples of where it's going to change. How we can absorb understand, and use data.

Rachael: Can we put this into a little bit of context too? By the way, the latest data creation for 2023, I believe is 120 zettabytes, which is like a 23 zettabyte increase over the year before. Which is what 120 plus 21 zeros. I mean, it's mind-blowing how much data there is. So I just want to put that in context with that huge question. That is Audra,

David: Right? The amount of data is just unfathomable and it's growing every single year. And that makes it very challenging for us to keep on top of tools that can manage these types of massive data sets. One area that I am working on is democratizing data science at this large scale. Creating open-source tools where anyone. Any organization anywhere around the world can readily ingest and process massive data sets beyond the capabilities of enterprise and commercial tools. 

 

**Taming the Data Deluge with AI and Data Science Tools**

David: So imagine you have tens or a hundred terabytes today would be a large size. It's not yet zettabytes. But we do have hundreds of terabytes that you'd like to be able to pick up and manipulate the process by analysts who speak in Python, the lingua de franca of data scientists. And maybe they know how to use NumPy, IMP pandas, and network X for graph analytics. But these data sizes would just overwhelm their tools.

They would never finish loading their dataset yet ask any questions about their data. So I'm building out along with partners in the Department of Defense. A system open source called Aqua, which is the Greek word for bear, and this system is in GitHub. You can find it in the Bear’s repository on GitHub. We've been working on this for the last several years to allow individuals and organizations to be able to ingest. And basically replace MPA and PANDAS and network X with the actual tools and our specialty for graph analytics in a data repository or a data toolkit called Arachni, the Greek word for spider.

So with Aqua and Arachni. We now have dozens of analysts ingesting tens of terabytes of data and being able to manipulate those data sets in near real-time just as easily as they could on their laptops. This really makes data science accessible. And we also use supercomputers and we use advanced computing techniques. We're using an open-source compiler from HPE called Chapel that allows very productive coding by my research group and developers. And through our hard work, others are able to just turnkey use this solution. 

 

 

**Bridging the Gap Between Data Scientists and Supercomputing with AI-Enabled Tools**

David: So we made supercomputing accessible and really democratized massive-scale data analytics so that anyone anywhere has the ability to look at these great data sets that we often find in cybersecurity problems.

Audra: I would agree. The question is, what you're enabling enables people to actually understand the outcomes? Is it step by step? At the moment, people have adopted things like ChatGPT but a lot of people don't understand what's under the bonnet or under the hood, so to speak, in America, I dunno what the engine is.

David: That's right. So we use Python or their Jupiter notebook as their productivity portal and just as easily as they'd write a few lines in Python, maybe using MPA and Pandas to ask questions about their data or to get results, they can do that just as easily in their same notebook but connected to a Cuda, the software framework that's open source that we built out. So any data scientist who is very comfortable in their current working situation now can use a supercomputer with Acua and Rene. 

The challenge is not on them for that heroic programming that's really for us to give them the illusion that they're running on their desktop when the massive data set is really ingested on a backend supercomputer and we use new technology to be able to route their queries to this backend supercomputer. 

We do all the heavy lifting for them of paralyzing the approaches, being able to target supercomputers and massively parallel processors, GPUs, and all these types of technologies so that the results come back to them on their laptops and they don't have to see everything happening in the cloud and on the backend where we're doing that very heavy lifting for them.

 

 

**Enabling Secure Information Sharing and Collaboration in a Connected World**

Rachael: That seems like a really great means of information sharing too, right? I mean, as things come up then you're able to share that information a little more broadly and help inform others what to look out for. This thing is emerging, all of that too.

David: That's right. People can be good citizens. So as they detect vulnerabilities and as they see exploits, certainly now they can share those results and it's no longer left to the big Fortune 100 companies that have massive cybersecurity teams and large budgets and specialized systems. Now, anyone around the world at any time can ingest all of their system logs, can ingest all of their information, their data, and be able to run on this software framework to be able to ask the same types of queries and questions as large enterprises can do.

Audra: Can that actually be run in kind of a walled garden manner so that the data that you're uploading may not want to share wider and amongst the community or hash it or do something so it's anonymized?

David: That's a great question. Audra, certainly you wouldn't want to share all of your corporate and private data with the world. The toolkits and the chapel compiler from HPE are open-source. It's on GitHub, and all of the software for Acua and Arachni are also open source on GitHub. So any organization can download it and run it in their corporate environment or in the cloud, and they're free to encapsulate it in their own security at their own wall gardens, or they can run it publicly if they want.

 
**Open Source Data Science Tools for All**

Audra: Excellent. Now that makes it very accessible and then that actually provides the protection that you need on top of it for your data. That's fantastic.

David: In fact, we built it with open source in mind so that others could use this in any way that they would like. And also contribute as well, new analytic routines, new performance optimizations, new algorithms. But by doing it in the open source, it's become a trusted toolkit. Anyone can view the source code and understand what it's doing. And we make it very accessible because our goal is really to democratize the ability to analyze these massive data sets. 

We think for cybersecurity to really take hold in the next few decades, everyone needs to be able to understand these tools and tooling. And as we have data created in every industry, in every sector, across every part of the world, from the edge to the cloud, we're to need tools that we can deploy to really protect data. And as you know, data is the new air data is the new oil. We're going to have to protect everything everywhere.

Rachael: Yes. Just out of curiosity, how long does it take to build something like this, David? I mean, it sounds like a massive undertaking, but so beneficial to so many in providing this really invaluable resource. But I mean, is this like six months, a year, five years? I mean, how long have you been working on this?

David: We've been working on this since about 2019, 2020. So it's a labor of love for the last few years, and we have had support from the National Science Foundation to build out this software framework in the last couple of years. 

 

**Open Source Data Science Tools for a Legacy of Data Protection**

David: The project is joint with the Department of Defense, and the initial vision and contributions did come from collaborations with the DoD. I want to call out one of the visionaries that I've worked with in creating the system, Mike Merrill. Sadly, he passed away last year, about a year ago in November. And I really want to recognize him and his vision for building the system to make these data science tools available. 

In fact, Mike had a brief illness and up through his last days was really trying to make sure that our Cuda had a foothold and that we were carrying on this vision that we created together to continue developing these tools. So in Mike's memory and for his passion, I really feel personally that Mike and I developed many tools together over decades in the past, and this was really something that we wanted to carry on and be a lasting legacy to his memory. 

Audra: And this is an amazing legacy to be leaving behind for the whole world. That's incredible.

Rachael: Truly, because these kinds of resources could be game changers for so many organizations that just wouldn't have access, wouldn't be able to do any of this, and would just kind of be finding their way through. So that's fantastic.

David: Right. So we're very glad to be able to continue developing these tools. And again, we can't do it alone. There are contributors to the project. There's a team that we work with and continue to build out these tools. 

 

 

**From Niche to Necessity: The Meteoric Rise of Data Science and AI**

David: Also, I should give a shout-out to H P E, they acquired the Supercomputing company Cray, where the chapel compiler was first formed and was developed under a DOPA program about 20 years ago to make these types of activities more productive. And the team at HPE led by Michelle Strout has been really fantastic in making chapel the best that we can achieve in terms of performance and capability.

Audra: That's exciting. I thought you just loved technology. So one last question for me, considering where the world was when you started working in this kind of area, looking at machine learning and AI and that sort of thing, how much has interest gone up in the last year in your career? It's like, here, have our money build space.

David: That's a fantastic question. So in 2019, I moved from Georgia Tech where I founded the School of Computational Science and Engineering to the New Jersey Institute of Technology because I wanted to be in the center of where data was happening in the New York City, Newark, New Jersey metropolitan region. It's a hub for healthcare, finance, transportation, entertainment, security, and all of these areas. And I founded the Institute for Data Science at NJIT. 

This was an activity that brought together centers in cybersecurity in big data, medical informatics FinTech, and other areas, which is quite an exciting area. And then in the fall of 2021, I co-founded a department of data science at NJIT, a new academic degree program so that we now have a bachelor's, a master's, and a PhD in data science. We thought that this would grow by a few students per year that this was an exciting growth area, and it's really phenomenal.

 

 

**The Soaring Demand for Data Science Education in Today's World**

David: We are just increasing the enrollments at our university this fall. The university is growing while many other universities are shrinking, and a big chunk of that growth is in data science. Our programs are being sought after left and right. The Wall Street Journal just named NJIT, the number two public school in terms of its ranking system. And we are really quite excited because data science is really at the core of many sectors, many areas, and it's a growth right now. 

We are seeing many students demanding courses in data science, whether they're a data science major or whether they're an architect or a chemist or come from any other area. We see data sciences really being critical to that education and that thought process. So in the last six months, that's increased by giving it jet fuel right behind it. With the advent of ChatGPT and the popularization of large language models, we see no end in sight for not only the demand but also the need for those who understand data science. 

It's the most needed job in this region. There are just thousands upon thousands of jobs open for those who know data science and also cybersecurity. So we're really glad to be at the nexus of training the next generation of our workforce. 

Rachael: Thank you. That's exciting. So how did you get into this? This is also one of our favorite questions. How did you get your start on this path, David?

 
From Early Acoustic Modems to Cutting-Edge Data Science Tools
David: I've always been interested in some of the most capable computing technologies. Back when I was three, probably in 1972 was the first time I ever touched a computer. And we used to have a terminal at home, a 10-bot acoustic modem. I was able to learn to type and transform my dad's RAT4 programming on programming cards between mainframe computers. And then I really got interested in parallel computing and high-performance computing technologies through the early 1980s. And my interest in graph algorithms grew from that. 

Over time, I want to be able to develop tools that would help our nation work in national security and be able to really look at some of the most pressing grand challenges that we have in this world and solve those real-world problems. Many of them included massive data sets where we needed supercomputers and parallel computers for just the large size of the problem.

And also because often we need solutions in near real-time, we want to understand what's happening before, as I mentioned earlier, something that we want to know that there's a bomb here before it goes off or to be able to predict today's weather and not take 30 days to predict what's going to happen this afternoon. And so these really converged, and my passion for the last several decades has been in trying to solve cybersecurity problems. 

Problems with our population health, and human genomics problems related to software development and protecting our software supply chain problems related to cancer, genomics problems related to transportation and living within sustainable urban environments, and also with the existential threat of climate change. So these are all areas that require very similar types of techniques.

 

**Unleashing Imagination through Data Science Tools**

Rachael: Wow, that's exciting. It's kind of like you're only limited by your imagination and what you can accomplish with data science in a way that's exciting.

David: That's right. And I always encourage students to start playing around with tools and look at problems that excite them today. For instance, one of the undergraduates that I mentor is very passionate about data science and just mentioned to me that she wants to work in related to ERAS related to marine science and oceanography. 

And has just reached out to look for interesting problems where maybe she'll be able to solve the next big problem in marine science using the skills that she's learned in data science. And that's really what makes me happy, seeing students who put their passions together and solve important problems for our planet.

Rachael: I love to think about this next generation and their access to technology and the opportunities that are in front of them today and what they're going to be able to do with that. And I look forward to the next 20 years. I think it's going to be an awesome time.

David: Oh, it's going to be a fun ride, and I look forward to it as well.

Rachael: Awesome. Well, Dr. David Bader, thank you so much for joining us today. This has been such a fun conversation.

David: Well, great to talk with you, Rachel, and Audra. Really enjoyed the conversation.

Rachael: Awesome. So to all of our listeners, thanks again for joining us this week, another amazing guest. And don't forget to subscribe because you can get a fresh episode every Tuesday right in your inbox. So until next time, everyone. Stay safe.



## About Our Guest ##

{{<figure src="bader.jpg">}}

**David A. Bader** is a Distinguished Professor and founder of the Department of Data Science in the Ying Wu College of Computing and Director of the Institute for Data Science at the New Jersey Institute of Technology. Prior to this, he served as founding Professor and Chair of the School of Computational Science and Engineering, College of Computing, at Georgia Institute of Technology. He is a Fellow of the IEEE, ACM, AAAS, and SIAM; a recipient of the IEEE Sidney Fernbach Award; and the 2022 Innovation Hall of Fame inductee of the University of Maryland’s A. James School of Engineering.

