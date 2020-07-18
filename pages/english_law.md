---
layout: page
show_meta: false
title: "English Law"
subheadline: "English law posts"
header: no
#    image_fullwidth: "header_unsplash_5.jpg"
permalink: "/english_law/"
---
<ul>
    {% for post in site.categories.english_law %}
    <li><a href="{{ site.url }}{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a></li>
    {% endfor %}
</ul>