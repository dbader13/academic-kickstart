---
# Documentation: https://hugoblox.com/docs/managing-content/

title: "DeepSeek has called into question Big AI’s trillion-dollar assumption"
subtitle: "It’s no wonder that some Nvidia investors are questioning their faith in unlimited demand for the most powerful AI chips."
summary: ""
authors: []
tags: []
categories: []
date: 2025-01-28T09:40:23-05:00
lastmod: 2025-01-28T09:40:23-05:00
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

{{<figure src="p-1-91268664-deepseek-has-called-into-question-big-ais-trillion-dollar-assumption.jpg" caption="*[Photo: Patrick Pleul/picture alliance via Getty Images]*">}}

*By Mark Sullivan*

Recently, Chinese startup [DeepSeek](https://www.fastcompany.com/91267354/deepseek-explained-china-llm-chatgpt-nvidia-microsoft-stock-ai-rattled) created state-of-the art AI models using far less computing power and capital than anyone thought possible. It then showed its work in published research papers and by allowing its models to explain the reasoning process that led to this answer or that. It also scored at or near the top in a range of benchmark tests, [besting OpenAI models](https://techcrunch.com/2025/01/27/deepseek-claims-its-reasoning-model-beats-openais-o1-on-certain-benchmarks/) in several skill areas. The surprising work seems to have let some of the air out of the AI industry’s main assumption—that the best way to make models smarter is by giving them more computing power, so that the AI lab with the most Nvidia chips will have the best models and shortest route to artificial general intelligence (AGI—which refers to AI that’s better than humans at most tasks). 

No wonder some Nvidia investors are questioning their faith in the unlimited demand for the most powerful AI chips in the future. And no wonder some in AI circles are questioning the world view and business strategy of OpenAI CEO Sam Altman, the biggest evangelist for the “brute force” approach to ever-smarter models. 

“The assumption behind all this investment is theoretical . . . the so-called scaling laws where when you double compute, the quality of your models increases in kind of the same way—it’s kind of a new Moore’s Law,” says Abhishek Nagaraj, a professor at the University of California–Berkeley’s Haas business school. (Moore’s Law said that software developers could expect microchips to become predictably more powerful as chipmakers packed more transistors into their microchips.) 

“And so if that holds, it effectively means that whoever controls the infrastructure will control a lot of the market,” adds Nagaraj. That’s why companies like OpenAI, Anthropic, and X are building data centers as fast as they can. OpenAI CEO Sam Altman last year said he [needs to raise $7 trillion](https://www.wsj.com/tech/ai/sam-altman-seeks-trillions-of-dollars-to-reshape-business-of-chips-and-ai-89ab3db0) to build the data centers needed to reach AGI. OpenAI, Microsoft, Softbank, and Oracle [said recently](https://www.fastcompany.com/91265565/the-oval-office-stargate-project-reveal-was-just-more-tech-industry-genuflecting) they’ll spend up to $500 billion over the next five years to build new data centers for AI in Texas. 

Attracting the money to do that, however, is something only “closed-source” companies like OpenAI can do, Nagaraj points out. OpenAI’s private equity backers (such as Andreessen Horowitz) and big tech backers (such as Microsoft) are willing to bankroll the AI infrastructure (chips, software, data centers, electricity), which OpenAI says it needs, if it keeps the recipes of its models secret. That’s the “moat” around their investment, after all. Establishing such a moat was the main reason OpenAI stopped being an “open” AI company back in 2019. 

DeepSeek shares the weights of its models (the mathematical calculations at each connection point in their neural networks) and allows any developer to build with them. After essentially giving away its research and eschewing a moat, DeepSeek was never going to attract the private equity funding needed to bankroll hundreds of thousands of Nvidia chips. Adding to its challenge were the [U.S. chip bans](https://www.fastcompany.com/91267968/how-the-biden-chip-bans-created-a-monster-called-deepseek) that reserved the most powerful AI chips for U.S. companies. So DeepSeek found ways to build state-of-the-art models using far less computing power. In doing so, it appears to have collapsed Altman’s assumption that massive computing power is the only route to AGI.

Not everybody thinks so, of course. Particularly in OpenAI circles. “I would never bet against compute as the upper bound for achievable intelligence in the long run,” says [Andrej Karpathy](https://x.com/karpathy), one of the original founders of OpenAI, in an X post. “Not just for an individual final training run, but also for the entire innovation/experimentation engine that silently underlies all the algorithmic innovations.”


Altman, too, seemed undeterred. “We will obviously deliver much better models and also it’s legit invigorating to have a new competitor! We will pull up some releases . . . ,” he posted breezily on X. “But mostly we are excited to continue to execute on our research roadmap and believe more compute is more important now than ever before to succeed at our mission.” OpenAI’s “mission” is AGI. 

Lots of powerful chips will be needed, if only because the general demand for AI services is going to grow exponentially. More data centers will be needed just to respond to calls from millions of AI-infused apps built on OpenAI APIs, [he added](https://x.com/sama/status/1884066338739830835). 

Some have suggested that DeepSeek’s discovery of ways to build more compute-efficient advanced AI models could reduce the barrier to entry and allow far more developers to build such models of their own, therefore pushing up demand for AI chips.

For example, DeepSeek’s most recent model, [DeepSeek-R1](https://go.skimresources.com/?id=122276X1583643&isjs=1&jv=15.7.1&sref=https%3A%2F%2Fwww.fastcompany.com%2F91268664%2Fdeepseek-called-into-question-big-ai-trillion-dollar-assumption-openai&url=https%3A%2F%2Farxiv.org%2Fhtml%2F2501.12948v1&xs=1&xtz=300&xuuid=a5ba779709559c07c9859f943db2add5&xjsf=other_click__auxclick%20%5B2%5D), provided the open-source world with a reasoning model that appears to be comparable to OpenAI’s state-of-the-art [o1 series](https://www.fastcompany.com/91189817/openais-new-o1-models-push-ai-to-phd-level-intelligence), which applies more computing power at inference time, when the model is reasoning through various routes to a good answer. In a statement Monday, Nvidia gives DeepSeek props for creating reasoning models using “widely available” Nvidia GPUs, and adds that such models require “significant numbers” of the GPUs as well as fast chip-to-chip networking technology. 

The latest DeepSeek models have only been available to developers for a short time. Just like when Meta introduced its open-source Llama models, it will take some time to understand the real economics of building new models and apps based on the DeepSeek models. It’s possible that more widely distributing the ability to build cutting edge models could put more brains to work on finding novel routes to AGI and, later, superintelligence. That’s the good news. The bad news may be that powerful models, and the means to build them, will become more available to people who might use them maliciously, or who may not be fastidious about using accepted safety guardrails. 

But DeepSeek is not perfect. The DeepSeek chatbot has in anecdotal cases emphatically misidentified itself as the creation of [OpenAI](https://x.com/susheel_c/status/1884340451060375838) or [Microsoft](https://www.fastcompany.com/91267647/deepseek-told-me-made-by-microsoft-r1-openai-claude-anthropic-ai-model-copilot). Nor can the chatbot speak freely on all subjects. “Like all Chinese AI companies, DeepSeek operates within the People’s Republic of China’s regulatory framework, which includes restrictions on how language models handle politically sensitive topics,” says **David Bader**, a professor at the New Jersey Institute of Technology. “These constraints are evident in how their models respond to queries about historical events and government policies.” If you ask the chatbot about the [Tiananmen Square protests](https://go.skimresources.com/?id=122276X1583643&isjs=1&jv=15.7.1&sref=https%3A%2F%2Fwww.fastcompany.com%2F91268664%2Fdeepseek-called-into-question-big-ai-trillion-dollar-assumption-openai&url=https%3A%2F%2Fen.wikipedia.org%2Fwiki%2F1989_Tiananmen_Square_protests_and_massacre&xs=1&xtz=300&xuuid=a5ba779709559c07c9859f943db2add5&xjsf=other_click__auxclick%20%5B2%5D), for example, it [responds](https://x.com/peterbrodersen/status/1883824132590338466) with, “Let’s talk about something else.”  

https://www.fastcompany.com/91268664/deepseek-called-into-question-big-ai-trillion-dollar-assumption-openai

