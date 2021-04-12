---
layout: page
subheadline: "Success"
title: "Success factors"
teaser: "These are your options to style the header of each webpage individually."
header:
   image_fullwidth: "header_unsplash_5.jpg"
permalink: "/headers/"
---
<ul>
    {% for post in site.tags.header %}
    <li><a href="{{ site.url }}{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a></li>
    {% endfor %}
</ul>