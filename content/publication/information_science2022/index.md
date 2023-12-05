---
title: "Multi-instance attention network for few-shot learning"
authors:
- Zhili Qin
- Han Wang
- Cobbinah Bernard Mawuli, 
- admin
- Rui Zhang, 
- Qinli Yang
- Junming Shao
date: 2022-07-02
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: 2022-07-02

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: In *Information Sciences*
publication_short: In *Information Sciences*

abstract: The attention mechanism is usually equipped with a few-shot learning framework and plays a key role in extracting the semantic object(s). However, most attention networks in existing few-shot learning algorithms often work on the channel and/or pixel dimension, leading to the size of attention maps being large. Due to lack of training examples, these attention networks are prone to over-fitting, and may fail to find the semantic target(s). In this paper, we split the original image into patches, extending a new dimension in image data, namely, the patch dimension. On the one hand, the number of patch dimensions is usually much smaller than the traditional three dimensions, thus greatly reducing the number of attention module parameters. On the other hand, the patch dimensional attention mechanism can benefit from multi-instance learning and achieve a good compromise between global and local features. Four comparison experiments on four typical real-world data sets (miniImageNet, tieredImageNet, Fewshot-CIFAR100, Caltech-UCSD Birds-200– 2011) have demonstrated that our proposed algorithm achieves consistent improvement over 6 baseline models (Matching Networks, Relation Networks, Prototypical Networks, MAML, Baseline++, Meta Baseline) and 11 state-of-the-art models (DC, TapNet, SNAIL, TADAM, MetaOptNet, CAN, CTM, DCEM, AFHN, LEO, AWGIM). Our code is available at (https://github.com/rumorgin/MIAN).

# Summary. An optional shortened abstract.
summary: ""

tags:
- Few-shot learning
- Multi-instance learning
- Self-attention network
# categories: []
featured: false

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

