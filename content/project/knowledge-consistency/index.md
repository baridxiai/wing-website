---
title: Is Knowledge in Multilingual Language Models Cross-Lingually Consistent?

summary: Evaluating, analyzing, understanding, and improving the knowledge consistency of multilingual models.
abstract: "Few works study the variation and cross-lingual consistency of factual knowledge embedded in multilingual models. However, cross-lingual consistency should be considered to assess cross-lingual transferability, maintain the factuality of the model knowledge across languages, and preserve the parity of language model performance. We are thus interested in analyzing, evaluating, and interpreting cross-lingual consistency for factual knowledge. We apply some interpretability approaches to analyze the behavior of a model in cross-lingual contexts, discovering that multilingual models show different levels of consistency, subject to language families or linguistic factors. In addition, we identify a bottleneck in cross-lingual consistency on a particular layer. To mitigate this problem, we try vocabulary expansion, adding biases from monolingual inputs, and different types of supervision consisting of additional cross-lingual word alignment objective, instruction tuning, and code-switching training. Among these methods, code-switching training and cross-lingual word alignment objective show the most promising results, emphasizing the noteworthiness of cross-lingual alignment supervision for cross-lingual consistency enhancement. "

tags: ["Multilingual and Cross-lingual NLP", "Model Parity and Consistency", "LLMs"]
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

authors: ["barid", "Mahardika Krisna Ihsani",,"min"]

---
Multilingual models are designed to perform consistently across different languages, particularly when handling tasks that require general knowledge, common sense, and scientific understanding. This ensures that the outputs are semantically and factually consistent in all languages. As a result, evaluating, analyzing, understanding, and improving the knowledge consistency of multilingual models is a promising topic in the research of fundamental multilingual frameworks. This project focuses on the theories, technologies, and evaluation methods related to multilingual consistency.