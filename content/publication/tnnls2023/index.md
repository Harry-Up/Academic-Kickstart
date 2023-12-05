---
title: "Synchronization-inspired Interpretable Neural Networks"
authors:
- admin
- Zhili Qin
- Jiaming Liu
- Christian Boehm
- Junming Shao
date: 2023-08-30
doi: "" 

# Schedule page publish date (NOT publication's date).
publishDate: 2023-08-30

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: In *IEEE Transactions on Neural Networks and Learning Systems*
publication_short: In *TNNLS*

abstract: Synchronization is a ubiquitous phenomenon in nature that enables the orderly presentation of information. In the human brain, for instance, functional modules such as the visual, motor, and language cortices form through neuronal synchronization. Inspired by biological brains and previous neuroscience studies, we propose an interpretable neural network incorporating a synchronization mechanism. The basic idea is to constrain each neuron, such as a convolution filter, to capture a single semantic pattern while synchronizing similar neurons to facilitate the formation of interpretable functional modules. Specifically, we regularize the activation map of a neuron to surround its focus position of the activated pattern in a sample. Moreover, neurons locally interact with each other, and similar ones are synchronized together during the training phase adaptively. Such local aggregation preserves the globally distributed representation nature of the neural network model, enabling a reasonably interpretable representation. To analyze the neuron interpretability comprehensively, we introduce a series of novel evaluation metrics from multiple aspects. Qualitative and quantitative experiments demonstrate that the proposed method outperforms many state-of-the-art algorithms in terms of interpretability. The resulting synchronized functional modules show module consistency across data and semantic specificity within modules.

# Summary. An optional shortened abstract.
summary: ""

tags:
- Interpretable Neural Networks
- Synchronization 
- Active Interpretability
- Interpretability Metrics
# categories: []
featured: true

# links:
# - name: ""
#   url: ""
url_pdf: ""
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: ''
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
slides: example
---

