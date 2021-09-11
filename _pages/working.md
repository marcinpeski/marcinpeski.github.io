---
layout: archive
title: "Working papers"
permalink: /working/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

<ol>
  {% for post in site.working reversed %}
    
      <li>{% include archive-single-publications.html %}</li>
    
  {% endfor %}
</ol>
