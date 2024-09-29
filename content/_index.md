---
# Leave the homepage title empty to use the site title
title: 
date: 2022-10-24
type: landing

sections:
  - block: slider
    content:
      slides:
      - title: 👋 Welcome to the group
        content: Take a look at what we're working on...
        align: center
        background:
          image:
            filename: banner/banner.JPG
            filters:
              brightness: 0.5
          position: center
          color: '#444'
      - title: Lunch & Learn ☕️
        content: 'Share your knowledge with the group and explore exciting new topics together!'
        align: left
        background:
          image:
            filename: banner/banner.png
            filters:
              brightness: 0.5
          position: center
          color: '#555'
      - title: World-Class Semiconductor Lab
        content: 'Just opened last month!'
        align: right
        background:
          image:
            filename: banner/banner.png
            filters:
              brightness: 0.5
          position: center
          color: '#333'
        link:
          icon: graduation-cap
          icon_pack: fas
          text: Join Us
          url: ../contact/
    design:
      # Slide height is automatic unless you force a specific height (e.g. '400px')
      slide_height: '650px'
      is_fullscreen: false
      # Automatically transition through slides?
      loop: false
      # Duration of transition between slides (in ms)
      interval: 3000

  - block: hero
    content:
      title: |

      image:
        filename: logo/hs-logo.png
      text: |
        <br>
        
        The **Data Centric Intelligence Lab** has been a center of excellence for Artificial Intelligence research, teaching, and practice since its founding in 2016.
  
  # - block: collection
  #   content:
  #     title: Latest News
  #     subtitle:
  #     text:
  #     count: 5
  #     filters:
  #       author: ''
  #       category: ''
  #       exclude_featured: false
  #       publication_type: ''
  #       tag: ''
  #     offset: 0
  #     order: desc
  #     page_type: post
  #   design:
  #     view: card
  #     columns: '1'
  
  # - block: markdown
  #   content:
  #     title:
  #     subtitle: ''
  #     text:
  #   design:
  #     columns: '1'
  #     background:
  #       image: 
  #         filename: coders.jpg
  #         filters:
  #           brightness: 1
  #         parallax: false
  #         position: center
  #         size: cover
  #         text_color_light: true
  #     spacing:
  #       padding: ['20px', '0', '20px', '0']
  #     css_class: fullscreen

  - block: markdown
    content:
      title: News
      text: |
        - 05/2024 One paper on sequential recommendation is accepted by <font color=green>TOIS</font>.
        - 05/2024 One paper on smart education is accepted by KDD'24.
        - 04/2024 Six papers are accepted by IJCAI'24. Topics include spatial-temporal forecasting, spatial-temporal distribution shift, smart education, federated learning, and human mobility modeling.
        - 01/2024 One paper on temporal knowledge reasoning is accepted by Artificial Intelligence (AIJ).
        - 12/2023 One paper on AI for Urban Planning is accepted by SDM'24.
        - 12/2023 One paper on human mobility modeling is accepted by AAAI'24.
        - 09/2023 One paper on knowledge graph embedding is accepted by TKDE.
        - 09/2023 Two papers on time series modeling are accepted by NeurIPS'23.
        - 09/2023 Two papers are accepted by ICDM'23. One is on spatial-temporal distribution shift (regular), and the other is on Metric-agnostic Learning-to-Rank (short).
        - 08/2023 One paper on the Missing Not At Random (MNAR) problem is accepted by CIKM'23.
        - 04/2023 One paper on mobile user profiling is accepted by IEEE Transactions on Knowledge and Data Engineering (TKDE).
        - 04/2023 One paper on temporal knowledge graph reasoning is accepted by IJCAI'23.
        - 02/2023 One paper on hierarchical structure-aware graph learning is accepted by IEEE Transactions on Knowledge and Data Engineering (TKDE).
        - 12/2022 One paper on intelligent education is accepted by ACM Transactions on Intelligent Systems and Technology (TIST).
        - 11/2022 Two papers are accepted by AAAI 2023. One is on time series distribution shift, and the other is on intelligent education.
        - 11/2022 One paper on Automated Feature Engineering is accepted by ICDE'23.
        - ...
    design:
      columns: '2'

  - block: collection
    content:
      title: Latest Publication
      subtitle: |
        {{% cta cta_link="./publication/" cta_text="MORE →" %}}
      text: ""
      count: 5
      filters:
        folders:
          - publication
        publication_type: 'article'
    design:
      view: citation
      columns: '2'



  # - block: markdown
  #   content:
  #     title:
  #     subtitle:
  #     text: |
  #       {{% cta cta_link="./people/" cta_text="Meet the team →" %}}
  #   design:
  #     columns: '1'
---
