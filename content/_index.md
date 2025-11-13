---
# Leave the homepage title empty to use the site title
title: Sarah M Mah
date: 2022-10-24
type: landing

sections:
  - block: hero
    content:
      title: |
        Research Group for Health Geography
      image:
        filename: lab_2025.jpg
      text: |
        Welcome! I'm Sarah, and I lead a health geography research group in the department of Geography and Geosciences at the **University of Vermont**. Our work integrates geospatial data, population health data, and epidemiologic approaches to investigate how neighborhoods, social and built environments influence health outcomes.
  
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
          filename: crosswalk.jpg
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
      title: Latest Articles
      text: ""
      count: 3
      filters:
        folders:
          - publication
        publication_type: 'article-journal'
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
