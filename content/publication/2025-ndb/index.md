---
# Documentation: https://hugoblox.com/docs/managing-content/

title: "Evaluating Efficiency and Novelty of LLM-Generated Code for Graph Analysis (Outstanding Student Paper Award)"
authors: ["Atieh Barati Nia", "Mohammad Dindoost", "David Bader"]
date: 2025-09-01T10:27:03-04:00
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: 2025-09-01T10:27:03-04:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["paper-conference"]

# Publication name and optional abbreviated publication name.
publication: "29th Annual IEEE High Performance Extreme Computing Conference"
publication_short: "IEEE HPEC 2025"

abstract: "Large Language Models (LLMs) are increasingly used to automate software development, yet most prior evaluations focus on functional correctness or high-level languages such as Python. As one of the first systematic explorations of LLM-assisted software performance engineering, we present a comprehensive study of LLMs' ability to generate efficient C implementations of graph-analysis routines—code that must satisfy stringent runtime and memory constraints. This emerging field of LLM-assisted algorithm engineering holds significant promise, as these models may possess the capability to design novel approaches that improve existing algorithms and their implementations. Eight state-of-the-art models (OpenAI ChatGPT o3 and o4-mini-high, Anthropic Claude 4 Sonnet and Sonnet Extended, Google Gemini 2.5 Flash and Pro, xAI Grok 3-Think, and DeepSeek DeepThink R1) are benchmarked using two distinct approaches. The first approach evaluates the ability of LLMs to generate algorithms that outperform existing benchmarks. The second approach assesses their capability to generate graph algorithms for integration into performance-critical systems. The results show that Claude Sonnet 4 Extended achieves superior performance in ready-to-use code generation and efficiency, outperforming human-written baselines in triangle counting. Although our findings demonstrate that contemporary LLMs excel in optimizing and integrating established algorithms, the potential for these models to eventually invent transformative algorithmic techniques represents a compelling frontier for future research. We provide prompts, generated code, and measurement scripts to promote reproducible research in this rapidly evolving domain.  All of the source code is available on GitHub at https://github.com/Bader-Research/LLM-triangle-counting/."

# Summary. An optional shortened abstract.
summary: ""

tags: []
categories: []
featured: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_pdf:
url_code:
url_dataset:
url_poster:
url_project:
url_slides:
url_source:
url_video:

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ""
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---
