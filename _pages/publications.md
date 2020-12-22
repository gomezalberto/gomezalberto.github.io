---
layout: archive
title: "Research lines and Publications"
permalink: /publications/
author_profile: true
author.googlescholar: true
---

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

You can find my full publication list on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
