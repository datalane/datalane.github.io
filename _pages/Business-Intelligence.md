---
title: "Business Intelligence"
layout: archive
permalink: /Business-Intelligence/
author_profile: true
headaer:
  image: "/images/AZ_1.jpg"
---

{% include base_path %}
{% include group-by-array collection=site.posts field="tags" %}

{% for tag in group_names %}
  {% assign posts = group_items[forloop.index0] %}
  <h2 id="{{ tag | slugify}}" class="archive__subtitle">{{ tag }}</h2>
  
  {% for post in posts %}
   {% include archive_single.html %}
  {% endfor %}
  
{% endfor %}