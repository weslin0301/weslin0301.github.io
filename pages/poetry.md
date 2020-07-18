---
layout: page
show_meta: false
title: "Poetry"
subheadline: "Poetry posts"
header: no
#    image_fullwidth: "header_unsplash_5.jpg"
permalink: "/poetry/"
---
<ul>
    {% for post in site.categories.poetry %}
    <li><a href="{{ site.url }}{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a></li>
    {% endfor %}
</ul>