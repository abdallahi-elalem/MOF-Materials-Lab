---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: hero
    content:
      title: |
        MOF Materials Lab
      image:
        filename: welcome.jpg
      text: |
        <br>
        Khalifa University of Science and Technology today announced it has jumped 25 places to be ranked 177th globally in the QS World University Rankings 2026, firmly securing a spot among the world’s top 200 universities.
        For eight consecutive years, Khalifa University has remained the top institution in the UAE, reinforcing its status as a national leader in higher education and research. In the 2026 edition, the University leads across several key indicators including 11th in the world for ‘International Faculty,’ top in UAE for ‘Citations per Faculty,’ and ‘Faculty Student Ratio’, affirming its leadership in attracting global talent and producing high-impact scientific research.
      text2: |
        <br>

  - block: collection
    content:
      title: Latest News
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
