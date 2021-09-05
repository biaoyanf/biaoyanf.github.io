---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

<!-- {% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %} -->


<h2>Publications</h2>
{% for post in site.publications reversed %}
  {% if post.pubtype == 'publications' %}
      {% include archive-single.html %}
  {% endif %}
{% endfor %}

<h2>Datasets</h2>
{% for post in site.publications reversed %}
  {% if post.pubtype == 'datasets' %}
      {% include archive-single.html %}
  {% endif %}
{% endfor %}