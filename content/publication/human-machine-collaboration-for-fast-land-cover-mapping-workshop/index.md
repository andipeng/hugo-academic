---
title: "Human-Machine Collaboration for Fast Land Cover Mapping"
authors:
- Caleb Robinson
- Anthony Ortiz
- Kolya Malkin
- Blake Elias
- admin
- Dan Morris
- Bistra Dilkina
- Nebojsa Jojic
date: "2019-12-14"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["3"]

# Publication name and optional abbreviated publication name.
publication: In *Tackling Climate Change with Machine Learning Workshop* at the *33rd Conference on Neural Information Processing Systems* (NeurIPS 2019)
publication_short: In *Tackling Climate Change with ML Workshop* at *NeurIPS 2019*

abstract: We propose incorporating human labelers in a model fine-tuning system that provides immediate user feedback. In our framework, human labelers can interactively query model predictions on unlabeled data, choose which data to label, and see the resulting effect on the model's predictions. This bi-directional feedback loop allows humans to learn how the model responds to new data. Our hypothesis is that this rich feedback allows human labelers to create mental models that enable them to better choose which biases to introduce to the model. We implement this framework for fine-tuning high-resolution land cover segmentation models and evaluate it against traditional active learning based approaches. More specifically, we fine-tune a deep neural network -- trained to segment high-resolution aerial imagery into different land cover classes in Maryland, USA -- to a new spatial area in New York, USA. We find that the tight loop turns the algorithm and the human operator into a hybrid system that can produce land cover maps of large areas more efficiently than the traditional workflows.

# Summary. An optional shortened abstract.
summary: NeurIPS 2019 *Tackling Climate Change with ML Workshop*

tags:
#- Source Themes
- Refereed Workshop
featured: false

links:
- name: "Workshop"
  url: https://www.climatechange.ai/NeurIPS2019_workshop.html
url_pdf: 
url_code:
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
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