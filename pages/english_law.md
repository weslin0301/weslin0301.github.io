---
layout: page
show_meta: false
title: "English Law"
subheadline: "English law posts"
header:
  image_fullwidth: gallery-example-7.jpg
permalink: "/english_law/"
---
<ul>
    {% for post in site.categories.english_law %}
    <li><a href="{{ site.url }}{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a></li>
    {% endfor %}
</ul>