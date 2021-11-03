---
layout: page
title: Gallery
description: Gallery containing the pictures of previous on site classes.
images:
    - https://ik.imagekit.io/dsantra92/IEDC_MLRC/20211030_170212_wk0rMPYYojs.jpg?updatedAt=1635971346966
    - https://ik.imagekit.io/dsantra92/IEDC_MLRC/20211030_170345_p7_de10gScc.jpg?updatedAt=1635971706747
    - https://ik.imagekit.io/dsantra92/IEDC_MLRC/DSC_1317_i57_0atMNx1R.JPG?updatedAt=1635969512333
    - https://ik.imagekit.io/dsantra92/IEDC_MLRC/DSC_1336_GPhheiO_hAX.JPG?updatedAt=1635969512257
    - https://ik.imagekit.io/dsantra92/IEDC_MLRC/DSC_1300_-t36oJHfK5ZB.JPG?updatedAt=1635969512311
    - https://ik.imagekit.io/dsantra92/IEDC_MLRC/DSC_1309_ZUGE6HUWbFM8.JPG?updatedAt=1635969511686
    - https://ik.imagekit.io/dsantra92/IEDC_MLRC/DSC_1339_YDNnpaeWER2.JPG?updatedAt=1635972362042
---

## Some precious little moments
<br>

{% assign images = page.images %}
  {% for image_url in images %}
  <div class="gallery">
    <img src = "{{image_url}}" alt="">
  </div>
{% endfor %}

