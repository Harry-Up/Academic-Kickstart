---
title: "Reducing variations in multi-center Alzheimer’s disease classification with convolutional adversarial autoencoder"
authors:
- Bernard M. Cobbinah
- Christian Sorg
- Qinli Yang
- Arvid Ternblom
- Changgang Zheng
- admin
- Liwei Che
- Junming Shao
date: 2022-08-15
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: 2022-08-15

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: In *Medical Image Analysis*
publication_short: In *Medical Image Analysis*

abstract: Based on brain magnetic resonance imaging (MRI), multiple variations ranging from MRI scanners to centerspecific parameter settings, imaging protocols, and brain region-of-interest (ROI) definitions pose a big challenge for multi-center Alzheimer's disease characterization and classification. Existing approaches to reduce such variations require intricate multi-step, often manual preprocessing pipelines, including skull stripping, segmentation, registration, cortical reconstruction, and ROI outlining. Such procedures are time-consuming, and more importantly, tend to be user biased. Contrasting costly and biased preprocessing pipelines, the question arises whether we can design a deep learning model to automatically reduce these variations from multiple centers for Alzheimer's disease classification? In this study, we used T1 and T2-weighted structural MRI from Alzheimer's Disease Neuroimaging Initiative (ADNI) dataset based on three groups with 375 subjects, respectively, patients with Alzheimer's disease (AD) dementia, with mild cognitive impairment (MCI), and healthy controls (HC); to test our approach, we defined AD classification as classifying an individual's structural image to one of the three group labels. We first introduced a convolutional adversarial autoencoder (CAAE) to reduce the variations existing in multi-center raw MRI scans by automatically registering them into a common aligned space. Afterward, a convolutional residual soft attention network (CRAT) was further proposed for AD classification. Canonical classification procedures demonstrated that our model achieved classification accuracies of 91.8%, 90.05%, and 88.10% for the 2-way classification tasks using the RAW aligned MRI scans, including AD vs. HC, AD vs. MCI, and MCI vs. HC, respectively. Thus, our automated approach achieves comparable or even better classification performance by comparing it with many baselines with dedicated conventional preprocessing pipelines. Furthermore, the uncovered brain hotpots, i.e., hippocampus, amygdala, and temporal pole, are consistent with previous studies.

# Summary. An optional shortened abstract.
summary: ""

tags:
- Alzheimer's disease classification
- Multi-center MRIs
- Convolutional adversarial autoencoder
- Convolutional attention network
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

