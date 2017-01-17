---
layout: page
title: Produkte
permalink: /produkte/

images:
  - image_path: /img/001_produkt.jpg
    title: Bonsai
  - image_path: /img/002_produkt.jpg
    title: Kentai Palme
  - image_path: /img/003_produkt.jpg
    title: Monstera
---

<ul class="photo-gallery">
  {% for image in page.images %}
    <li><img src="{{ image.image_path }}" alt="{{ image.title}}"/></li>
  {% endfor %}
</ul>