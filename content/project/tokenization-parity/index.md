---
title: Tokenization Parity: Attention to Your Token Counts

summary: Evaluating, analyzing, understanding, and improving the knowledge consistency of multilingual models.
abstract: "Language models encounter tokenization fairness challenges, especially for low-resource languages, where subword tokenization frequently leads to inefficiently high token counts. This impedes in-context learning (ICL) by diminishing prompt capacity and hindering inference efficiency due to elevated latency. We propose investigating the development of a compact, pre-LLM model capable of dynamically masking token and cluster embeddings. Our objective is to reduce the number of tokens processed by language models. Additionally, we intend to explore the potential of enhancing accuracy through multilingual models by disregarding superfluous tokens."

tags: ["Tokenization", "Detokenization", "Low-resource Languages", "LLM"]
year: 2025

date: '2025-01-01'

all_day: true

# Is this a featured project? (true/false)
featured: true
image:
  caption: 'Illustration of Cross-lingual knowledge consistency. Frege’s theory of reference defines the reference of a sub-sentential expression as the object singled out by the name.'
  focal_point: Right

# Markdown Slides (optional).
#   Associate this talk with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
# slides:

authors: ["sahej", "barid",,"min"]

---
The number of tokens in your prompt is very important for several reasons: 1) commercial LLMs)charge users by token counts; 2) efficiency is directly related to the number of tokens; and 3) LLMs have a fixed input window. In practical use, prompts in languages other than English tend to have higher token counts compared to their English counterparts, creating an unfair disadvantage for non-English users. In this project, we focused on token pruning and the internal detokenization process to reduce token counts.