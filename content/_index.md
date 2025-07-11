---
title: 首页
type: landing
sections:
  - block: slider
    content:
      slides:
        - title: 欢迎访问
          content: 探索我们最新的研究成果！
          align: center
          background:
            image:
              filename: 1b2995ec16ac4ba487fb7f94f7cb7048_1684821996337.jpg
              position: center
          link:
            text: 了解更多
            url: /publication
        - title: 团队介绍
          content: 认识我们的研究团队。
          align: center
          background:
            image:
              filename: 1contact.jpg
              position: right
          link:
            text: 查看团队
            url: /people
    design:
      slide_height: 400px
      is_fullscreen: false
      loop: true
      interval: 5000
      
  
  - block: hero
    content:
      title: |
        
      image:
        filename: 2contact.jpg
      text: |
        <br>​​中国科学院沈阳计算技术研究所多模态智能团队隶属于中国科学院大学。团队长期深耕于多模态推理、科学智能、情感计算、机器翻译及类脑智能等前沿领域，在上述研究方向取得系统性研究成果，相关论文持续发表在ECCV、CVPR、IJCAI、ACL等计算机领域CCF-A类国际顶级会议。

      #  Our team specializes in multimodal reasoning, scientific AI, affective computing, machine translation, and brain-inspired intelligence. We publish regularly at top-tier conferences CCF-A(ECCV, CVPR, IJCAI, ACL) and drive innovations in these fields.   
    design:
      font_size: "0.6em"  
      background:
        text_color_light: false
      spacing:
        padding: ["50px", "0", "50px", "0"]      
  
  - block: people
    content:
      title: Principal Investigators
      user_groups:
        - Principal Investigators
       
    design:
      show_interests: true
      show_role: true
  
  - block: collection
    content:
      title: Latest News
      subtitle:
      text:
      count: 3
      filt:
        -event


  - block: collection
    content:
      title: Latest Conference Paper
      text: ""
      count: 3
      filters:
        folders:
          - publication
        publication_type: 'paper-conference'
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
