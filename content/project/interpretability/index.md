---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Interpretable Machine Learning"
summary: ""
authors: []
tags: []
categories: []
date: 2020-07-19T11:18:13+02:00

# Optional external URL for project (replaces project detail page).
external_link: ""

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ""
  focal_point: ""
  preview_only: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_code: ""
url_pdf: ""
url_slides: ""
url_video: ""

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: ""
---
Predictive models are all pervasive with usage in search engines, recommender systems, health, legal and financial domains. But for the most part they are used as black boxes which output a prediction, score or rankings without understanding partially or even completely how different features influence the model prediction.
In such cases when an algorithm prioritizes information to predict, classify or rank; algorithmic transparency becomes an important feature to keep tabs on restricting discrimination and enhancing explainability-based trust in the system.

Consequently, we end up with accurate yet non-interpretable models. We have been working on building models that are either interpretable by design or approaches that explain in a post-hoc manner the rationale behind a prediction by an already trained model. Specifically, we have proposed different interpretability approaches to audit ranking models in the context of Web search.

We have been studying the problem of interpretability for text based ranking models by trying to unearth the query intent as understood by complex retrieval models. In [1], we proposed a model-agnostic approach that attempts to locally approximate a complex ranker by using a simple ranking model in the term space. In [3], we ponder on the question, what makes a good reference input distribution for neural rankers? We also have simple research prototype for explaining neural rankers called EXS [4].

Recently, we investigated the difference between human understanding and machine understanding of images in using post-hoc interpretability approaches [2]. In particular, we seek to answer the following questions: Which (well performing) complex ML models are closer to humans in their use of features to make accurate predictions? How does task difficulty affect the feature selection capability of machines in comparison to humans? Are humans consistently better at selecting features that make image recognition more accurate?

---
## Projects

This thread of my research is supported by **[Amazon research Awards](https://ara.amazon-ml.com/recipients/#2017)** and **[Schufa Gmbh](https://www.schufa.de/en/)**.

---
## Publications

[1] **[Model agnostic interpretability of rankers via intent modelling](https://dl.acm.org/doi/abs/10.1145/3351095.3375234)**. Jaspreet Singh and Avishek Anand. <em>In Conference on Fairness, Accountability, and Transparency (FAT), 2020</em>.

[2] **[Dissonance Between Human and Machine Understanding](http://www.l3s.de/~gadiraju/publications/CSCW2019.pdf)**. Zijian Zhang, Jaspreet Singh, Ujwal Gadiraju, Avishek Anand. <em>In CSCW 2019</em>.

[3] **[A study on the Interpretability of Neural Retrieval Models using DeepSHAP](https://arxiv.org/pdf/1907.06484.pdf)**. Zeon Trevor Fernando, Jaspreet Singh, Avishek Anand. <em>In SIGIR 2019</em>.

[4] **[EXS: Explainable Search Using Local Model Agnostic Interpretability](https://arxiv.org/pdf/1809.03857.pdf)**. Jaspreet Singh and Avishek Anand. <em>In WSDM 2019</em>.

[5] **[Posthoc Interpretability of Learning to Rank Models using Secondary Training Data](https://arxiv.org/pdf/1806.11330.pdf)**. Jaspreet Singh and Avishek Anand. <em>In Workshop on ExplainAble Recommendation and Search (Co-located with SIGIR' 18)</em>.

[6] **[Finding Interpretable Concept Spaces in Node Embeddings using Knowledge Bases](https://arxiv.org/pdf/1910.05030.pdf)**. Maximilian Idahl, Megha Khosla and Avishek Anand. <em>In in workshop on Advances in Interpretable Machine Learning and Artificial Intelligence & eXplainable Knowledge Discovery in Data (co-located with ECML-PKDD 2019).</em>.
