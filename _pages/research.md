---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
author_googlescholar: true
header:
  overlay_image: BB1.JPG
  overlay_filter: 0.5 # same as adding an opacity of 0.5 to a black background
  caption: "Wilson Hall"
---
{% include base_path %}


All of my publications can be found on my <a href ="https://inspirehep.net/authors/1009609">iNSPIRE page</a>.
{% if author.googlescholar %}
You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}
[TASI09]({{site.baseurl}}{% link /files/TASI2009.pdf %})
{% comment %}
I have lectured at various summer schools on various topics e.g.
<ul>
<li>Supersymmetry [TASI09]({{site.baseurl}}{% link _files/TASI2009.pdf %})<\li>
<li>WIMPs [TASI2018]({{site.baseurl}}/files/TASI2018.pdf)</li>
<li>Dark Matter [TRISEP2017]({{site.baseurl}}/files/DM_Intro.pdf)</li>
<li>DM@Colliders [SLAC Summer Institute Lec. 1]({{site.baseurl}}/files/SSI_Fox_Lecture1.pdf), [Lec. 2]({{site.baseurl}}/files/SSI_Fox_Lecture2.pdf)</li>
<\ul>
{% endcomment %} 

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
