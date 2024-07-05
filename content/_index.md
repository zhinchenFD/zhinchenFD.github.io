---
# Leave the homepage title empty to use the site title
title: ''
date: 2022-10-24
type: landing

sections:
  - block: hero
    demo: true # Only display this section in the Hugo Blox Builder demo site
    content:
      title: Hugo Academic Theme
      image:
        filename: hero-academic.png
      cta:
        label: '**Get Started**'
        url: https://hugoblox.com/templates/
      cta_alt:
        label: Ask a question
        url: https://discord.gg/z8wNYzb
      cta_note:
        label: >-
          <div style="text-shadow: none;"><a class="github-button" href="https://github.com/HugoBlox/hugo-blox-builder" data-icon="octicon-star" data-size="large" data-show-count="true" aria-label="Star">Star Hugo Blox Builder</a></div><div style="text-shadow: none;"><a class="github-button" href="https://github.com/HugoBlox/theme-academic-cv" data-icon="octicon-star" data-size="large" data-show-count="true" aria-label="Star">Star the Academic template</a></div>
      text: |-
        **Generated by Hugo Blox Builder - the FREE, Hugo-based open source website builder trusted by 500,000+ sites.**

        **Easily build anything with blocks - no-code required!**

        From landing pages, second brains, and courses to academic resumés, conferences, and tech blogs.

        <!--Custom spacing-->
        <div class="mb-3"></div>
        <!--GitHub Button JS-->
        <script async defer src="https://buttons.github.io/buttons.js"></script>
    design:
      background:
        gradient_end: '#1976d2'
        gradient_start: '#004ba0'
        text_color_light: true
  
  - block: about.biography
    id: about
    content:
      title: 个人简介
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: Chengzhineng

  - block: markdown
    id: news
    content:
      title: 新闻
      subtitle: 
      text: >+
          - 2024.06：🎉祝贺苏宇辰、杜永坤同学荣获2024全球人工智能技术创新大赛算法挑战赛“无人机视角下的双光目标检测”赛道一等奖

          - 2024.04：🎉祝贺杜永坤、苏宇辰同学荣获2024年PaddleOCR算法模型挑战赛“OCR端到端识别”赛道冠军

    design:
      view: compact
      columns: '2'
      background:
          gradient_end: '#4568aa'
          gradient_start: '#4568aa'
          text_color_light: true

  - block: collection
    id: publication
    content:
      title: 论文 
      subtitle: ''
      text: ''
      # Choose how many pages you would like to display (0 = all pages)
      count: 8
      # Filter on criteria
      filters:
        folders:
          - publication
        author: ""
        category: ""
        tag: ""
        exclude_featured: false
        exclude_future: false
        exclude_past: false
        publication_type: ""
      # Choose how many pages you would like to offset by
      offset: 0
      # Page order: descending (desc) or ascending (asc) date.
      order: desc
    design:
      # Choose a layout view
      view: list
      columns: '2'
      # background:
      #   gradient_end: '#1976d2'
      #   gradient_start: '#004ba0'
      #   text_color_light: true

  - block: markdown
    id: members
    content:
      title: 实验室成员
      subtitle: 
      text: >+  
          - 张园园（24级硕）
           - 白维康（24级硕）
          - 叶兴松（24级硕）
           - 杜永坤（23级博）：IJCAI * 1 ；PaddleOCR算法模型挑战赛“OCR端到端识别”赛道冠军；2024全球人工智能技术创新挑战赛一等奖
          - 苏宇辰 （23级博）：AAAI * 1；PaddleOCR算法模型挑战赛“OCR端到端识别”赛道冠军；2024全球人工智能技术创新挑战赛一等奖
           - 陈一鸣 （23级硕）
          - 何恩州 （23级硕）
           - 王学盛 （23级硕）
          - 赵永杰 （23级硕）
           - 雷一鸣 （23级硕）
          - 程明泽 （23级硕）
           - 石璞 （23级硕）
          - 李时杰（22级博）
           - 杨海波 （22级硕，24级硕转博）：MM * 1；ECCV * 1
          - 陈奕夫 （22级硕）：ECCV * 1
           - 梁月潇 （22级硕）： ICASSP * 1
          - 周胜天 （22级硕）
           - 潘兆龙 （22级硕）
          - 朱斌 （22级硕）
           - 刘茵（22级硕）
          - 赵帅（22级硕）
           - 罗扬（21级硕，23级硕转博）：CVPR * 1， BIBM * 1
          - 宋一飞（21级硕，24级博）：计算机辅助设计与图形学学报 * 1；上海市优秀毕业生
           - 郑天伦（21级硕，协助姜育刚教授指导）：IJCV * 1，ICCV * 1，IJCAI * 1；国家奖学金，上海市优秀毕业生；去向：宁波鄞州区人社局
          - 黄丙晨（21级硕）：AAAI * 1，国家奖学金，上海市优秀毕业生；去向：美团
           - 马宇蒙（21级硕）：去向：华为
          - 程利霖（21级硕）
           - 孙可欣（21级硕）：CVPR*1；冠名奖学金；去向：快手
          - 陈家胤（21级硕）：去向：北京星鹏联海
           - 王淇锐（21级硕）：去向：黑龙江省公安厅（选调）
          - 干毅（21级硕）：去向：携程
          
    design:
      view: compact
      columns: '2'
      background:
          gradient_end: '#4568aa'
          gradient_start: '#4568aa'
          text_color_light: true
---