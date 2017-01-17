---
layout: page
title: Produkte
permalink: /produkte/

images:
  - image_path: /img/produkte/thumb/001_produkt.jpg
    title: Bonsai
  - image_path: /img/produkte/thumb/002_produkt.jpg
    title: Kentai Palme
  - image_path: /img/produkte/thumb/003_produkt.jpg
    title: Monstera
---
<!-- Magnific Popup core CSS file -->
<link rel="stylesheet" href="magnific-popup/magnific-popup.css">

<!-- jQuery 1.7.2+ or Zepto.js 1.0+ -->
<script src="//ajax.googleapis.com/ajax/libs/jquery/1.9.1/jquery.min.js"></script>

<!-- Magnific Popup core JS file -->
<script src="magnific-popup/jquery.magnific-popup.js"></script>
<script>
$(document).ready(function() {
$('.test-popup-link').magnificPopup({
  type: 'image'
  // other options
});
});

</script>
<a class="test-popup-link" href="/img/produkte/thumb/003_produkt.jpg">Open popup</a>


<ul class="photo-gallery">
  {% for image in page.images %}
    <li><img src="{{ image.image_path }}" alt="{{ image.title}}"/></li>
  {% endfor %}
</ul>