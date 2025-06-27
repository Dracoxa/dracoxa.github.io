---
title: 'Faster and More Efficient Subject Image Generation for Text-to-Image Diffusion Models'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Bihui Yu
  - Zhengbing Yao
  - Jingxuan Wei


# Author notes (optional)
author_notes:
  - 'First author'
  - Bihui Yu

date: '2024-10-06T15:57:35Z'
doi: '10.1109/SMC54092.2024.10831577'

# Schedule page publish date (NOT publication's date).
publishDate: '2024-10-06T15:57:35Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
#publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication_short: In *SMC*

abstract: In recent years, there has been significant progress in text-to-image generation models. However, text struggles to accurately describe abstract concepts like shapes and sizes. Some methods have been proposed to enhance text prompt by incorporating image prompts. While they have shown effective improvements, they either require substantial fine-tuning costs or struggle to effectively integrate text and image information. In our study, we delve into the issue of the difficulty in integrating text and image information in decoupled cross-attention and conduct visual analysis. We identify the presence of background-related tokens in image features as a key factor affecting text fidelity. To address this issue, we develop an algorithm to filter out these tokens. Additionally, we observe differences in the attention of Unet layers to text prompts and image prompts. Based on this finding, we optimize the flow of image information to reduce interference with text information. In summary, we introduce a new topic-customized method that requires no repeated training. It trains a plug-and-play image prompt adapter with only 417M parameters, lightweight yet powerful, surpassing existing models in both text and image consistency. Our code and pre-trained checkpoints will be available at https://github.com/YZBPXX/DDCA.

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
# https://ieeexplore.ieee.org/document/10831577



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


