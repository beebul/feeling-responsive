---
layout: page
show_meta: false
title: "Sinclair"
subheadline: "Thanks for the (48k) Memories Sir Clive"
header:
   image_fullwidth: "spectrum_header.jpg"
   title: "Sinclair Spectrum"
   title-position: left
permalink: "/spectrum/"
---
<ul>
    {% for post in site.categories.Spectrum %}
    <li><a href="{{ site.url }}{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a></li>
    {% endfor %}
</ul>