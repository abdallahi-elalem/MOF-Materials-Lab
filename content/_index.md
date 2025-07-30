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
        Department of Chemistry
      image:
        filename: ""  # اتركه فارغاً أو احذفه تمامًا لأنه سيتم إدراج الصور يدويًا
      text: |
        <br>
        Khalifa University of Science and Technology today announced it has jumped 25 places to be ranked 177th globally in the QS World University Rankings 2026, firmly securing a spot among the world’s top 200 universities.
      text2: |
        <br>
      html: |
        <div id="hero-slideshow" style="position: relative; width: 100%; height: 400px; overflow: hidden;">
          <img src="./media/welcome.jpg" class="slide-img" style="width:100%; height: 400px; object-fit: cover; position:absolute; top:0; left:0; opacity:1; transition: opacity 1s;">
          <img src="./media/welcome.jpg" class="slide-img" style="width:100%; height: 400px; object-fit: cover; position:absolute; top:0; left:0; opacity:0; transition: opacity 1s;">
        </div>
        <script>
          let index = 0;
          const slides = document.querySelectorAll('.slide-img');
          setInterval(() => {
            slides.forEach((img, i) => img.style.opacity = (i === index % 2) ? "1" : "0");
            index++;
          }, 4000);
        </script>

      text: |
        <br>
        Khalifa University of Science and Technology today announced it has jumped 25 places to be ranked 177th globally in the QS World University Rankings 2026, firmly securing a spot among the world’s top 200 universities.
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
