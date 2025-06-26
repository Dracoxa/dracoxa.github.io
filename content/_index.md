---
title:  AI For Multimodal Cognitive Intelligence Lab
date: 2022-10-24
type: landing

sections:
  - block: hero
    content:
      title: |
        <span style="font-size: ; color: #ffffff;font-family: 'Lora', serif">AI For Multimodal Cognitive Intelligence Lab</span>
        <br>
        <span style="font-size:0.7em ; color: #ffffff;font-family: 'Lora', serif">Affiliated with University of Chinese Academy of Sciences</span>
      text: | 
      text: |
      text: |
        <br>
        <span style="font-size: 0.8em ;color:rgb(255, 255, 255); font-family: 'Lora', serif">We focus on knowledge engineering, natural language processing, multimodal analysis, sentiment analysis, machine translation, and brain-inspired intelligence, driving innovative research and cultivating talent with strong theoretical and practical skills.</span><br>
    design:
      background:
        image:
          filename: welcome.jpg
          filters:
            brightness: 0.7  # 优化亮度以确保文字可读
          parallax: false
          position: center
          size: cover
          text_color_light: true

  - block: collection
    content:
      title: Latest News
      subtitle:
      text:
      count: 5
      filters:
        author: ''
        category: ''
        exclude_featured: false
        publication_type: ''
        tag: ''
      offset: 0
      order: desc
      page_type: post
    design:
      view: card
      columns: '1'

  - block: markdown
    content:
      title:
      subtitle: ''
      text:
    design:
      columns: '1'
      background:
        image:
          filename: coders.jpg
          filters:
            brightness: 1
          parallax: false
          position: center
          size: cover
          text_color_light: true
      spacing:
        padding: ['20px', '0', '20px', '0']
      css_class: fullscreen

  - block: collection
    content:
      title: Latest Preprints
      text: ""
      count: 5
      filters:
        folders:
          - publication
        publication_type: 'article'
    design:
      view: citation
      columns: '1'

  - block: markdown
    content:
      title:
      subtitle:
      text: |
        {{% cta cta_link="./people/" cta_text="Meet the team →" %}}
    design:
      columns: '1'
---