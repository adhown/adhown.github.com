---
layout: page
title: Welcome To adhown Notes
tagline: Learn For BETTER future
tags: [adhown]
---
{% include JB/setup %}

Belajar, menjadi salah satu alasan mengapa blog ini saya buat, 
sebenarnya sebelum ini saya sudah pernah membuat blog yang diantaranya 
menggunakan CMS (Content Management System) seperti joomla, Wordpress dan blogger.

[adhown][]
[adhown]: http://adhown.github.com/
<hr>
<hr>
   
# Recent Notes :
<hr>
<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>
