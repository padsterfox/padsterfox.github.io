---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
  - header:
  overlay_image: BB1.JPG
  overlay_filter: 0.5 # same as adding an opacity of 0.5 to a black background
  caption: "Wilson Hall"
---
{% include base_path %}


<a href ="https://inspirehep.net/authors/1009609"> My papers </a>

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}



{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
