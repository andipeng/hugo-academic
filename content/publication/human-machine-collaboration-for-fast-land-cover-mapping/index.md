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
date: "2020-02-07"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In *Proceedings of the 34th Conference on Artificial Intelligence* (AAAI 2020)
publication_short: In *AAAI 2020*

abstract: We propose incorporating human labelers in a model fine-tuning system that provides immediate user feedback. In our framework, human labelers can interactively query model predictions on unlabeled data, choose which data to label, and see the resulting effect on the model’s predictions. This bi-directional feedback loop allows humans to learn how the model responds to new data. We implement this framework for fine-tuning high-resolution land cover segmentation models and compare human-selected points to points selected using standard active learning methods. Specifically, we fine-tune a deep neural network - trained to segment high-resolution aerial imagery into different land cover classes in Maryland, USA - to a new spatial area in New York, USA using both our human-in-the-loop method and traditional active learning methods. The tight loop in our proposed system turns the algorithm and the human operator into a hybrid system that can produce land cover maps of large areas more efficiently than the traditional workflows. Our framework has applications in machine learning settings where there is a practically limitless supply of unlabeled data, of which only a small fraction can feasibly be labeled through human efforts, such as geospatial and medical image-based applications.

# Summary. An optional shortened abstract.
summary: To appear at AAAI 2020

tags:
#- Source Themes
- Refereed Conference
featured: false

links:
- name: "Preprint"
  url: "paper.pdf"
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