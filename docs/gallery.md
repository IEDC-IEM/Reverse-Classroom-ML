---
layout: page
title: Gallery
description: Gallery containing the pictures of previous on site classes.
images:
    - https://ik.imagekit.io/dsantra92/IEDC_MLRC/20211030_170212_EsI-mnQuYUg.jpg?updatedAt=1635888311649
    - https://ik.imagekit.io/dsantra92/IEDC_MLRC/20211030_170345_Nl0AgOElyNl.jpg?updatedAt=1635888236381
---

## Some precious little moments
<br>

{% assign images = page.images %}
  {% for image_url in images %}
  <div class="gallery">
    <img src = "{{image_url}}" alt="">
  </div>
{% endfor %}

