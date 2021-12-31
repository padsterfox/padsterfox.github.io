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


I have lectured at various summer schools on various topics e.g.
<ul>
<li>Supersymmetry <a href="{{site.baseurl}}/files/TASI2009.pdf">TASI09</a></li>
<li>WIMPs <a href="{{site.baseurl}}/files/TASI2018.pdf">TASI2018</a></li>
<li>Dark Matter <a href="{{site.baseurl}}/files/DM_Intro.pdf">TRISEP2017</a></li>
<li>DM@Colliders <a href="{{site.baseurl}}/files/SSI_Fox_Lecture1.pdf">SLAC Summer Institute Lec. 1</a>, <a href="{{site.baseurl}}/files/SSI_Fox_Lecture2.pdf">Lec. 2</a>
</li>
</ul>


{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
