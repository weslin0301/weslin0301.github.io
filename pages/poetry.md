---
layout: page
show_meta: false
title: "Poetry"
subheadline: "Poetry posts"
header:
  image_fullwidth: pier.jpg
permalink: "/poetry/"
---
<ul>
    {% for post in site.categories.poetry %}
    <li><a href="{{ site.url }}{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a></li>
    {% endfor %}
</ul>