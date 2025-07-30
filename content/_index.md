---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: hero
    content:
      title: |
        Department of Chemistry
        - block: hero
    content:
      title: |
        MOF Materials Lab 
      image:
        filename: welcome.jpeg
      text :
        (group logo)


   
      

  - block: collection
    content:
      title: News
      subtitle:
      text:
      count: 5
      filters:
        author: ""
        category: ""
        exclude_featured: false
        publication_type: ""
        tag: ""
      offset: 0
      order: desc
      page_type: post
    design:
      view: card
      columns: "1"
      show_meta: false

  - block: markdown
    content:
      title:
      subtitle: ""
      text:
    design:
      columns: "1"
      background:
        image:
          filename: featured.jpg
          filters:
            brightness: 1
          parallax: false
          position: center
          size: cover
          text_color_light: true
      spacing:
        padding: ["20px", "0", "20px", "0"]
      css_class: fullscreen

  - block: collection
    content:
      title: Latest Publications
      text: ""
      count: 5
      filters:
        folders:
          - publication
        publication_type: "article-journal"
    design:
      view: citation
      columns: "1"

  - block: markdown
    content:
      title:
      subtitle:
      text: |
        {{% cta cta_link="./people/" cta_text="Meet the team →" %}}
    design:
      columns: "1"
---
