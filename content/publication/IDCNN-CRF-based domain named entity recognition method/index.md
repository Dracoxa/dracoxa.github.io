---
title: 'IDCNN-CRF-based domain named entity recognition method'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Bihui Yu
  - Jingxuan Wei


# Author notes (optional)
author_notes:
  - 'First author'
  - Bihui Yu

date: '2020-10-14T15:57:35Z'
doi: '10.1109/ICCASIT50869.2020.9368795'

# Schedule page publish date (NOT publication's date).
publishDate: '2020-10-14T15:57:35Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
#publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication_short: In *ICCASIT*

abstract: Entity recognition is the foundation of natural language processing. For traditional methods, a large number of manual annotations are required, and the accuracy of the model is low and the speed is slow. The word vector model cannot recognize unregistered words well. This paper proposes an entity recognition method based on character embedding, Iterated Dilated Convolutional Neural Networks (IDCNN) and Conditional Random Fields (CRF). Combining the characteristics of iterative dilation convolutional neural network GPU parallel operation and long-term and short-term memory, the ability of word vectors to express the meaning of unregistered words, and the excellent learning ability of conditional random fields for labeling rules, a character+IDCNN+CRF named entity is constructed Identify the model. Based on the corpus in the field of military equipment, the experiment shows that the method can distinguish the equipment name and organization name excellently in a certain dimension character vector. The F-1 value in the test corpus exceeds 94%. For military equipment domain entity recognition has a better effect, and the prediction speed has been greatly improved compared to before.

# Summary. An optional shortened abstract.
summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'content/publication/conference-paper/2411.11916v1.pdf'
# https://ieeexplore.ieee.org/document/9368795



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


