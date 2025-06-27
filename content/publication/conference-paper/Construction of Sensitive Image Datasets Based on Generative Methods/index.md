---
title: 'Construction of Sensitive Image Datasets Based on Generative Methods'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Chang Liu
  - Jie Zhang
  - Bihui Yu


# Author notes (optional)
author_notes:
  - 'First author'
  - Chang Liu

date: '2023-04-14T15:57:35Z'
doi: '10.1109/ICTech58362.2023.00109'

# Schedule page publish date (NOT publication's date).
publishDate: '2023-04-14T15:57:35Z'

# Publication type.
publication_types: ['paper-conference']

# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
#publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication_short: In *ICTech*

abstract: Due to the special nature of sensitive information, available sensitive data resources are relatively scarce to meet the needs of research in this field. The purpose of this paper is to construct a large sensitive image dataset by generative methods, with a view to supporting research exploration in related aspects. To achieve this goal, we adopt a new idea. First, we crawl sensitive and non-sensitive class datasets from web pages and filter them manually. Here, the sensitive classes mainly involve violence, terror and pornography; second, the selected data are used as the training set to fine-tune the pre-trained generative model; then, the fine-tuned generative model is used for sensitive/non-sensitive image generation, which expands the training dataset; finally, the generated training set is passed into the classification model to do the classification task for result verification. The experimental results show that the classification results of the expanded dataset using the generative method are higher than those of the original dataset, which proves the effectiveness of the generative method to construct the dataset.

# Summary. An optional shortened abstract.
summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

# url_pdf: 'content/publication/conference-paper/2411.11916v1.pdf'
# https://ieeexplore.ieee.org/document/10261115



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


