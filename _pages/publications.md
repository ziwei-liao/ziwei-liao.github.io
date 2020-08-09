---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

<iframe width="560" height="315" src="https://www.youtube.com/embed/u9zRBp4TPIs" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

## Coarse-to-fine Visual Localization

<iframe width="560" height="315" src="https://www.youtube.com/embed/XbTc1YNPajc" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>


{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
