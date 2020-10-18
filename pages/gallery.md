---
layout: page
show_meta: false
title: "Gallery"
subheadline: "Gallery posts"
header:
  image_fullwidth: pier.jpg
permalink: "/gallery/"
---
<ul>
    {% for post in site.categories.english_law %}
    <li><a href="{{ site.url }}{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a></li>
    {% endfor %}
</ul>