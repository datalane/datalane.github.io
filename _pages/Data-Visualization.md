---
title: "Data Visualization"
layout: archive
permalink: /Data-Visualization/
author_profile: true
headeraaa:
  image: "/images/AZ_2.jpg"
---
{% for post in site.categories.Data-Visualization %}
 <li><span>{{ post.date | date_to_string }}</span>&nbsp;<a href="{{ post.url }}">{{ post.title }}</a></li>
{% endfor %}


{% comment %}
{% include base_path %}
{% include group-by-array collection=site.posts field="tags" %}

{% for tag in group_names %}
  {% assign posts = group_items[forloop.index0] %}
  <h2 id="{{ tag | slugify}}" class="archive__subtitle">{{ tag }}</h2>
{% for post in posts %}
  {% include Business-Intelligence.html %}
  {% endfor %}
{% endfor %}
{% endcomment %}
