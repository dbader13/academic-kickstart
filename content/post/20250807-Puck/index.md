---
# Documentation: https://hugoblox.com/docs/managing-content/

title: "Slaughterhouse GPT-5"
subtitle: "Silicon Valley is adjusting its expectations yet again, after OpenAI’s latest model turned out to be more of an upgrade than a great leap forward. “It’s not a disappointment in the sense that it won’t actually be better,” said one A.I. researcher. “But a disappointment relative to what people were expecting.”"
summary: ""
authors: []
tags: []
categories: []
date: 2025-08-07T10:21:55-04:00
lastmod: 2025-08-07T10:21:55-04:00
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

*By Ian Krietzberg*

{{<figure src="GettyImages-2218344193-scaled-e1754599600977-1088x612.jpg" caption="In the demo, Sam Altman hinted that OpenAI is “discovering new paradigms,” but it’s unclear what those are, or whether they are in some way present in GPT-5. *Photo: Justin Sullivan/Getty Images*">}}

For all the feverish excitement surrounding today’s release of GPT-5, the latest and most advanced OpenAI model seems to represent more of an incremental update than a paradigm-shifting breakthrough. At a press briefing, C.E.O. **Sam Altman** called GPT-5 a “major upgrade” that serves as a “significant step along the path to A.G.I.,” or artificial general intelligence, an entirely hypothetical technology. At another point he referred to it as “very A.G.I.-like.” Obviously, we’re not quite there—and it’s not clear that we ever will be.

Nevertheless, GPT-5, which comes in pro, standard, “mini,” and “nano” flavors, is a pretty impressive upgrade—[particularly to the folks](https://www.oneusefulthing.org/p/gpt-5-it-just-does-stuff?triedRedirect=true) who got to test it out before the release. The system offers better coding and software development capabilities than previous models—it scored a 74.9 percent on SWE-bench, the popular software engineering benchmark—which could make it more competitive with Anthropic models. According to Altman, GPT-5 can “instantaneously create an entire piece of computer software … on demand.” In a demo at the briefing, an OpenAI researcher created a seemingly functional web app with a two-paragraph prompt in less than a minute. It’s also on par with the competition on a series of other benchmarks, although it’s not a knockout; on ARC-AGI-2, for instance, **Elon Musk**’s Grok 4 maintains [a significant lead](https://x.com/fchollet/status/1953511631054680085).

But what most distinguishes GPT-5 from past iterations is its two-model architecture, which combines a “high-throughput model” to handle ordinary questions with a “reasoning” model to answer thornier ones. A “real-time router” decides which of the two models to use based on each prompt. “This idea that we can use more compute, higher-quality data, better environments, whatever, to make smarter and smarter models, we see orders of magnitude more gains in front of us,” Altman said, with the addendum, of course, that he’ll have to invest in the compute side “at an eye-watering rate” to get there (surely good news for Nvidia, whose stock hit a new 52-week high today).

GPT-5 also hallucinates less than previous OpenAI models, at least according to the company’s own internal evaluations. The improvements point to the possibility of new or hybrid architectures (or lots of engineering scaffolding), which OpenAI didn’t clarify when I asked about it. In the demo, Altman hinted that OpenAI is “discovering new paradigms,” but it’s unclear what those are, or whether they are in some way present in GPT-5. Meanwhile, the model’s context window—which refers to the amount of text, in tokens, that a model can “remember” at one time—is 400,000 tokens (in the A.P.I.), significantly less than the million-token-strong context window of GPT-4.1.

Perhaps most notably for the average user, OpenAI says that GPT-5 just “feels more human”—although what that means is anyone’s guess. “In which ways is it more human than it was before?” asked Dr. **David Bader**, the director of the Institute for Data Science at the New Jersey Institute of Technology, when I asked for his first impression. “Does it talk in one’s vernacular? Does it make more mistakes, since to err is human?” As even Altman conceded, we’re not quite through the looking glass yet.

## Baby Steps ##

The road to GPT-5 has been longer than originally anticipated. Many thought it would [launch](https://arstechnica.com/information-technology/2024/03/openais-gpt-5-may-launch-this-summer-upgrading-chatgpt-along-the-way/) last year, about a year after Altman debuted GPT-4 in March 2023. Instead, OpenAI released a series of incremental updates and new models: 4o and 4o-mini, o1, o3, and GPT-4.5 (which was [later scrapped](https://venturebeat.com/ai/openai-moves-forward-with-gpt-4-5-deprecation-in-api-triggering-developer-anguish-and-confusion/)) and 4.1, none of which were apparently worthy of the lofty GPT-5 title.

In fact, a downshift in the pace of innovation from giant leaps to incremental gains has become a defining feature of the A.I. industry. That’s not to say that many of these new products aren’t impressive. It’s just getting harder to achieve something that could be considered legitimately groundbreaking. In the meantime, increased competition between A.I. companies has pushed them to release smaller upgrades—on an accelerated time frame, no less—in order to stay one step ahead of their rivals. Earlier this week, Anthropic released [Claude Opus 4.1](https://x.com/AnthropicAI/status/1952768432027431127), which is supposedly better at coding than Opus 4 (funny timing, OpenAI), and Google debuted [DeepMind’s Genie 3](https://x.com/agrimgupta92/status/1952735042029105392), a “world model” with enhanced memory. OpenAI also released its long-awaited [GPT-oss series](https://openai.com/index/introducing-gpt-oss/), a handful of smallish, partially open models.

According to Dr. **John Licato**, the director of the Advancing Machine and Human Reasoning Lab at the University of South Florida, this is just how science works. “There’s this kind of popular misconception of scientific advancement where it’s a lone genius in a room who creates something and it emerges from their mind fully baked,” he told me. “That’s not really how it works. Everybody keeps building off of each other, and they make a minor change, then when you’ve had enough of those minor changes, you call it a major release. This is no different.”

Even at this incremental pace, Licato and Bader explained, genuine model improvements are becoming more difficult to squeeze out. Several [reports](https://www.reuters.com/business/retail-consumer/openais-long-awaited-gpt-5-model-nears-release-2025-08-06/) have detailed OpenAI’s hard journey to GPT-5, and asserted that the leap between GPT-4 and GPT-5 is significantly smaller than the leap between GPT-3 and GPT-4. “The improvements are slowing down,” Bader told me. “They’re not as dramatic as those first couple of releases.”

Bader wasn’t really surprised by anything in the GPT-5 release, and called the coding improvements “low-hanging fruit”—especially since Anthropic’s Claude has generally been considered a much better coding assistant than anything OpenAI has been able to produce thus far. And when it comes to OpenAI’s claim that GPT-5 will feature less user deception, less hallucination, and instantaneous software generation, he’ll believe it when he sees it. “I tend to discount statements like that as potentially more marketing- or publicity-related,” Bader said, noting that prerelease testing rarely captures the full breadth of a model’s performance; it takes millions of real-world users to find their actual limits. (Also, as with pretty much every A.I. model release since 2022, non-peer-reviewed demos always look fantastic—but the reality tends to be a little less rosy.)

For Licato, who was expecting to see a significant hardware integration, or leveled-up video processing, a model that’s merely “better” probably won’t meet most people’s expectations. “It’s not a disappointment in the sense that it won’t actually be better,” he told me. “But a disappointment relative to what people are expecting, given that it’s the big version number.” The model, he later added, shouldn’t even be called GPT-5. “This is GPT-4.2. Absolutely nothing groundbreaking here, and honestly, even the presenters seemed underprepared,” he said. “They let Google and Anthropic dictate their release schedule, and it shows.”

Indeed, many of the most impactful advances going forward will likely revolve around more prosaic concerns: product-market fit, user interface, customer experience, etcetera. (GPT-5 allows users to select a personality and choose different colors for their chats.) As Licato told me, for the big players, it’s all about “that attention-economy win.”

Bader agreed that “we need to distinguish between genuine advances and marketing narratives designed to attract talent and investment.” Technically, he noted, we’ve seen plenty of impressive model advancements over the last few years, including enhanced planning, reasoning, and multimodal understanding. OpenAI, in particular, has pioneered key innovations in chain-of-thought reasoning, reinforcement learning, and improved tokenization strategies, but it’s not a significant step toward A.G.I., or manna from heaven for some of the [A.I. pseudo-religions](https://firstmonday.org/ojs/index.php/fm/article/view/13636) that have permeated across Silicon Valley.

“When companies suggest they’re on the verge of achieving artificial general intelligence, it creates unrealistic expectations and potentially diverts attention from more immediate A.I. challenges around bias, reliability, and transparency,” Bader said. He added that we should recognize OpenAI’s technical, incremental advancements as “engineering achievements within the current paradigm—not evidence of an imminent leap to A.G.I.”

https://puck.news/gpt5s-underwhelming-launch-and-the-limits-of-ai-hype/
