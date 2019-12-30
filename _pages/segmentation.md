---
layout: archive
permalink: /segmentation/
title: "Segmentation Examples"
author_profile: true
header:
  image: "/images/IMG_3787.jpg"
---
 some examples for different segmentation methods

{% for post in site.posts %}
  {% if post.categories contains 'ml' %}
   {% include archive-single.html %}
  {% endif %}
{% endfor %}
