---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---
 
 
N. Yassaie, <b>M. Hallajiyan</b> and I. Sharifi, &quot;[Resilient Control Strategy for Detection and Mitigation of Disruptions in Microgrids](https://ieeexplore.ieee.org/abstract/document/9260818)&quot;, 2020 28th Iranian Conference on Electrical Engineering (ICEE), Tabriz, Iran, 2020, pp. 1-6, doi: 10.1109/ICEE50131.2020.9260818.


{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
