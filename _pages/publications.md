---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

<h2>Publications</h2>

N. Yassaie, <b>M. Hallajiyan</b> and I. Sharifi, "Resilient Control Strategy for Detection and Mitigation of Disruptions in Microgrids," 2020 28th Iranian Conference on Electrical Engineering (ICEE), Tabriz, Iran, 2020, pp. 1-6, doi: 10.1109/ICEE50131.2020.9260818.
N. Yassaie, M. Hallajiyan and I. Sharifi, "Resilient Control Strategy for Detection and Mitigation of Disruptions in Microgrids," , Tabriz, Iran, 2020, pp. 1-6, doi: 10.1109/ICEE50131.2020.9260818.

Negar Yassaie, <b>Mohammadreza Hallajiyan</b> and Iman Sharifi. &quot;Resilient Control Strategy for Detection and Mitigation of Disruptions in Microgrids &quot;. 22nd International Conference on Computing Education Research. November 2022. ACM. ([Preprint](https://bkacsmar.github.io/files/bkacsmar_Koli_Calling_Short_preprint.pdf), [Slides](https://bkacsmar.github.io/files/pres_Koli2023.pdf))
 
 
 
{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
