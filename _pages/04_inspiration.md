---
layout: page
title: Inspiration
permalink: /inspiration/
---
<link rel="stylesheet" href="/css/simplegrid.css">
<div class="grid" style="background: rgb(174, 143, 111);background: rgba(174, 143, 111, .5);">
<div class="col-1-12">
</div>
    <div class="col-4-12">
       <div class="content">
	   <img src="/img/bluete.jpg">
	   </div>
	   </div>
	   <div class="col-7-12">
       <div class="content" style="color:white;text-align:center;padding:22% 0;font-size: 130%;padding-right:20px">
	   Lassen Sie sich hier von den Projektbeispielen inspirieren!
	   </div>
	   </div>
</div>


<br><br>
	   
{% for myimage in site.static_files %}
{% if myimage.path contains 'img/inspiration' %}
<img src="{{myimage.path}}">{% endif %}{% endfor %}