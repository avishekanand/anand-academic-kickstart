---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Graph Neural Networks"
summary: ""
authors: []
tags: []
categories: []
date: 2020-07-19T11:17:56+02:00
draft: true 

# Optional external URL for project (replaces project detail page).
external_link: ""

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ""
  focal_point: ""
  preview_only: true

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
A major goal of unsupervised learning is to discover data representations that are useful for subsequent tasks, without access to supervised labels during training.
Unsupervised representations of text, graphs and images have propelled the fields of natural language processing,  graph representation learning and computer vision.
A popular example of unsupervised representation learning are embedding-based representations that learn general-purpose representations for the atomic units of the domain -- like words in language or vertices in graphs.
Word and vertex embeddings are then utilized to represent larger units like passages, documents in language and sub-graphs and graphs in the domain of graph-structured data.
The promise of representation is in  learning from easily available large collections of text and graphs.
However, a key challenge for learning word and vertex embeddings is in the large training times. Moreover, another challenge is in the evaluation of unsupervised representation -- more specifically vertex or node embeddings.

In \cite{NERD} we proposed a novel approach for learning node representations in directed graphs, which maintains separate views or embedding spaces for the two distinct node roles induced by the directionality of the edge and provide its theoretical interpretation in terms of matrix factorization.
While pointing out major flaws in evaluation setups employed for directed graph representations we propose and employ new evaluation measures corresponding to directed link prediction and graph reconstruction tasks.
In \cite{VLDBsubmission} we take the first step towards understanding and explaining differences in many recent representation learning methods. We further attribute the performance differences to properties of the methods and the structural properties of underlying graphs.
Finally, in~\cite{WSDMScaling} we proposed a scalable method for training word embeddings using data parallelism that drastically improved training times. In \cite{holzmannCrawledGraphs} we study theoretically and empirically the impact of graph incompleteness induced on PageRank rankings of large scale crawled networks.
