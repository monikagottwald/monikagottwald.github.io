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
<link rel="stylesheet" href="/css/simplegrid.css">
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
<div class="grid" style="background: rgb(173, 203, 119);background: rgba(173, 203, 119, .5);">
    <div class="col-1-12">
	</div>
    <div class="col-4-12">
       <div class="content">
	   <img src="/img/produkte/head.png">
	   </div>
	   </div>
	   <div class="col-7-12">
       <div class="content" style="font:arial;text-align:center;line-height: 95%;padding:15% 0;">
	   <b>Hier nur ein kleiner Teil der Produktauswahl.<br>
Im Sortiment stehen für Sie noch viele weitere Pflanzen zur Verfügung!</b><br><br>

Ich arbeite mit ausgewählten Lieferanten, die bereits langjährige Erfahrung in der <br>Herstellung haben
und für hohe Qualität ihrer Produkte einstehen. <br><br>

Überzeugen Sie sich selbst,<br> die hochwertig verarbeiteten Pflanzen sind von echten  kaum zu unterscheiden!
	   </div>
	   </div>
	   </div>

<br><br>

<div class="center-image">
<div class="popup-gallery" style="margin-left: auto;margin-right: auto;">
	<a title="Bonsai" href="/img/produkte/001_produkt.jpg"><img width="110" height="110" src="/img/produkte/thumb/001_produkt.jpg"></a>
	<a title="Kentai Palme" href="/img/produkte/002_produkt.jpg"><img width="110" height="110" src="/img/produkte/thumb/002_produkt.jpg"></a>
	<a title="Monstera" href="/img/produkte/003_produkt.jpg"><img width="110" height="110" src="/img/produkte/thumb/003_produkt.jpg"></a>
		<a title="Dracaena" href="/img/produkte/004_produkt.jpg"><img width="110" height="110" src="/img/produkte/thumb/004_produkt.jpg"></a>
	<a title="Shirakashi Bonsai" href="/img/produkte/005_produkt.jpg"><img width="110" height="110" src="/img/produkte/thumb/005_produkt.jpg"></a>
	<a title="Lorbeerbaum" href="/img/produkte/006_produkt.jpg"><img width="110" height="110" src="/img/produkte/thumb/006_produkt.jpg"></a>
		<a title="Graspflanze" href="/img/produkte/007_produkt.jpg"><img width="110" height="110" src="/img/produkte/thumb/007_produkt.jpg"></a>
	<a title="Oriental Olive" href="/img/produkte/008_produkt.jpg"><img width="110" height="110" src="/img/produkte/thumb/008_produkt.jpg"></a>
	<a title="Buchs Spirale" href="/img/produkte/009_produkt.jpg"><img width="110" height="110" src="/img/produkte/thumb/009_produkt.jpg"></a>
		<a title="Alocasia Calidora" href="/img/produkte/010_produkt.jpg"><img width="110" height="110" src="/img/produkte/thumb/010_produkt.jpg"></a>
	<a title="Pinus Bonsai" href="/img/produkte/011_produkt.jpg"><img width="110" height="110" src="/img/produkte/thumb/011_produkt.jpg"></a>
		<a title="Strelitzien" href="/img/produkte/012_produkt.jpg"><img width="110" height="110" src="/img/produkte/thumb/012_produkt.jpg"></a>
	<a title="Wisteria-Goldregen" href="/img/produkte/013_produkt.jpg"><img width="110" height="110" src="/img/produkte/thumb/013_produkt.jpg"></a>
		<a title="Acer Bonsai" href="/img/produkte/014_produkt.jpg"><img width="110" height="110" src="/img/produkte/thumb/014_produkt.jpg"></a>
	<a title="Acer Maple" href="/img/produkte/015_produkt.jpg"><img width="110" height="110" src="/img/produkte/thumb/015_produkt.jpg"></a>
	<a title="Dracaena Reflexa Anita" href="/img/produkte/016_produkt.jpg"><img width="110" height="110" src="/img/produkte/thumb/016_produkt.jpg"></a>
		<a title="Cycas Palme" href="/img/produkte/017_produkt.jpg"><img width="110" height="110" src="/img/produkte/thumb/017_produkt.jpg"></a>
	<a title="Zamioculcas" href="/img/produkte/018_produkt.jpg"><img width="110" height="110" src="/img/produkte/thumb/018_produkt.jpg"></a>

</div>
</div>
<!--
<ul class="photo-gallery">
  {% for image in page.images %}
    <li><img src="{{ image.image_path }}" alt="{{ image.title}}"/></li>
  {% endfor %}
</ul>
-->