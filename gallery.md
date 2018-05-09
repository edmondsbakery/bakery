---
layout: post
title: Gallery
permalink: /gallery/
img:
  - img_path: /img/cakes/BlackForest.jpg
    title: Black Forest
  - img_path: /img/cakes/BlushBliss.jpg
    title: Blush Bliss Cake
  - img_path: /img/cakes/ThreeTeir
    title: Old Fashioned Teired Cake
---

<section id="Gallery">
<h2>Wedding Cakes</h2>

<ul class="photo-gallery">
  {% for img in page.img %}
    <li><img src="{{ img.img_path }} alt="{{ img.title }}"/></li>
  {% endfor %}
</ul>
</section>