---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

<ol>
  {% for post in site.publications reversed %}
    {% if post.collection == 'publications' %}
      
      <li>{{ post.subcollection }}{% include archive-single-publications.html %}</li>
    {% endif %}
  {% endfor %}
</ol>
