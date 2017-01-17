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
<link rel="stylesheet" href="/script/magnific-popup.css">

<!-- jQuery 1.7.2+ or Zepto.js 1.0+ -->
<script src="//ajax.googleapis.com/ajax/libs/jquery/1.9.1/jquery.min.js"></script>

<!-- Magnific Popup core JS file -->
<script src="/script/magnific-popup.js"></script>
<script>
$(document).ready(function() {
	$('.popup-gallery').magnificPopup({
		delegate: 'a',
		type: 'image',
		tLoading: 'Loading image #%curr%...',
		mainClass: 'mfp-img-mobile',
		gallery: {
			enabled: true,
			navigateByImgClick: true,
			preload: [0,1] // Will preload 0 - before current, and 1 after the current image
		},
		image: {
			tError: '<a href="%url%">The image #%curr%</a> could not be loaded.',
			titleSrc: function(item) {
				return item.el.attr('title') + '<small></small>';
			}
		}
	});
});

</script>

<div class="popup-gallery">
	<a title="Bonsai" href="/img/produkte/001_produkt.jpg"><img width="120" height="120" src="/img/produkte/thumb/001_produkt.jpg"></a>
	<a title="Kentai Palme" href="/img/produkte/002_produkt.jpg"><img width="120" height="120" src="/img/produkte/thumb/002_produkt.jpg"></a>
	<a title="Monstera" href="/img/produkte/003_produkt.jpg"><img width="120" height="120" src="/img/produkte/thumb/003_produkt.jpg"></a>
</div>
<!--
<ul class="photo-gallery">
  {% for image in page.images %}
    <li><img src="{{ image.image_path }}" alt="{{ image.title}}"/></li>
  {% endfor %}
</ul>
-->