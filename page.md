---
title: page
permalink: page.html
layout: default
---
{% for p in site.data.projects%}
image_{{forloop.index}}:<br>
link: '{{p.link}}'<br>
image: '{{p.image}}'<br>
caption: '{{p.title}}'<br>
{% endfor %}