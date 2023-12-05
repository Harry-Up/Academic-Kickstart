---
title: "Learning multiple gaussian prototypes for open-set recognition"
authors:
- Jiaming Liu
- Jun Tian
- admin
- Zhili Qin
- Yulu Fan
- Junming Shao
date: 2023-01-08
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: 2023-01-08

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: In *Information Sciencesl*
publication_short: In *Information Sciences*

abstract: Open-set recognition aims to deal with unknown classes that do not exist in the training phase. The key is to learn effective latent feature representations for classifying the already known classes as well as detecting new emerging ones. In this paper, we learn multiple Gaussian prototypes to better represent the complex classes distribution in both generative and discriminative ways. With the generative constraint, the latent variables of the same class clusters compactly around the corresponding Gaussian prototypes, preserving extra space for the samples of unknown classes. The discriminative constraint separates the Gaussian prototypes of different classes, which further improves the discrimination capability for the known classes. Importantly, the entire framework can be directly derived from the Bayesian inference, thus providing theoretical support for open-set recognition. Experimental results of different datasets verify the reliability and effectiveness of the proposed method. Our code is available at https://github. com/LiuJMzzZ/MGPL.

# Summary. An optional shortened abstract.
summary: ""

tags:
- Open-set recognition
- Novelty detection
- Gaussian prototype
- Variational auto-encoder
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

