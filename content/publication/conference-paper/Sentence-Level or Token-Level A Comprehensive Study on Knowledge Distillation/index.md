---
title: "Sentence-Level or Token-Level: A Comprehensive Study on Knowledge Distillation"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Jingxuan Wei
  - Linzhuang Sun
  - Yichong Leng


# Author notes (optional)
author_notes:
  - 'First author'
  - Jingxuan Wei

date: '2024-04-23T08:29:56Z'
doi: '10.48550/arXiv.2404.14827'

# Schedule page publish date (NOT publication's date).
publishDate: '2024-04-23T08:29:56Z'

# Publication type.
publication_types: ['paper-conference']

# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
#publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication_short: "In *IJCAI*"
abstract: >
  Knowledge distillation, transferring knowledge from a teacher model to a student model, 
  has emerged as a powerful technique in neural machine translation for compressing models or simplifying training targets.
  Knowledge distillation encompasses two primary methods: sentence-level distillation and token-level distillation.
  In sentence-level distillation, the student model is trained to align with the output of the teacher model, which can alleviate the training difficulty and give the student model a comprehensive understanding of global structure.
  Differently, token-level distillation requires the student model to learn the output distribution of the teacher model, facilitating a more fine-grained transfer of knowledge.
  Studies have revealed divergent performances between sentence-level and token-level distillation across different scenarios, leading to confusion on the empirical selection of knowledge distillation methods.
  In this study, we argue that token-level distillation, with its more complex objective (i.e., distribution), is better suited for "simple" scenarios, while sentence-level distillation excels in "complex" scenarios.
  To substantiate our hypothesis, we systematically analyze the performance of distillation methods by varying the model size of student models, the complexity of text, and the difficulty of the decoding procedure.
  While our experimental results validate our hypothesis, defining the complexity level of a given scenario remains a challenging task.
  So we further introduce a novel hybrid method that combines token-level and sentence-level distillation through a gating mechanism, aiming to leverage the advantages of both individual methods.
  Experiments demonstrate that the hybrid method surpasses the performance of token-level or sentence-level distillation methods and the previous works by a margin, demonstrating the effectiveness of the proposed hybrid method.


# Summary. An optional shortened abstract.
summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags: []

# Display this page in the Featured widget?featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
# url: http://example.org

url_pdf: 'Sentence-Level or Token-Level A Comprehensive Study on Knowledge Distillation.pdf'



# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  
  focal_point: ''
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
  - example

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
---


