---
layout: page
title: Gallery
description: Gallery containing the pictures of previous on site classes.
images:
    - https://img.jagranjosh.com/imported/images/institute/IEM-KOLKATA-365x240.jpg
---

## Moments from the classes of Spring 2020
<br>

{% assign images = page.images %}
  {% for image_url in images %}
  <div class="gallery">
    <img src = "{{image_url}}" alt="">
  </div>
{% endfor %}

