---
title: 'Boosting the Power of Small Multimodal Reasoning Models to Match Larger Models with Self-Consistency Training'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Cheng Tan
  - Jingxuan Wei
  - Zhangyang Gao


# Author notes (optional)
author_notes:
  - 'First author'
  - Cheng Tan

date: '2024-07-03T02:56:47Z'
doi: '10.48550/arXiv.2311.14109'

# Schedule page publish date (NOT publication's date).
publishDate: '2024-07-03T02:56:47Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
#publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication_short: In *ECCV*

abstract: Multimodal reasoning is a challenging task that requires models to reason across multiple modalities to answer questions. Existing approaches have made progress by incorporating language and visual modalities into a two-stage reasoning framework, separating rationale generation from answer inference. However, these approaches often fall short due to the inadequate quality of the generated rationales. In this work, we delve into the importance of rationales in model reasoning. We observe that when rationales are completely accurate, the model’s accuracy significantly improves, highlighting the need for high-quality rationale generation. Motivated by this, we propose MC-CoT, a self-consistency training strategy that generates multiple rationales and answers, subsequently selecting the most accurate through a voting process. This approach not only enhances the quality of generated rationales but also leads to more accurate and robust answers. Through extensive experiments, we demonstrate that our approach significantly improves model performance across various benchmarks. Remarkably, we show that even smaller base models, when equipped with our proposed approach, can achieve results comparable to those of larger models, illustrating the potential of our approach in harnessing the power of rationales for improved multimodal reasoning. The code is available at github.com/chengtan9907/mc-cot.

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


