---
layout: page
title: Inspiration
permalink: /inspiration/
---
<link rel="stylesheet" href="/css/simplegrid.css">
<div class="grid" style="background: rgb(174, 143, 111);background: rgba(174, 143, 111, .5);">
    <div class="col-3-12">
       <div class="content">
	   <img src="/img/bluete.png">
	   </div>
	   </div>
	   <div class="col-9-12">
       <div class="content" style="font:arial;color:white;text-align:center">
	   Lassen Sie sich hier von den Projektbeispielen inspirieren!
	   </div>
	   </div>
</div>


<br><br>
	   
{% for myimage in site.static_files %}
{% if myimage.path contains 'img/inspiration' %}
<img src="{{myimage.path}}">{% endif %}{% endfor %}