---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
redirect_from: 
  - /publications/
  - /publications.html
---
2021
===

**Sohan Lal**, Jan Lucas, Ben Juurlink <br> 
[QSLC: Quantization-Based, Low-Error Selective Approximation for GPUs](https://ieeexplore.ieee.org/abstract/document/9474124) <br> 
In the Proceedings of Design, Automation & Test in Europe Conference & Exhibition (DATE 2021), Virtual Event
 
**Sohan Lal**, Jan Lucas, Ben Juurlink [QSLC: Quantization-Based, Low-Error Selective Approximation for GPUs](https://ieeexplore.ieee.org/abstract/document/9474124)
In the Proceedings of Design, Automation & Test in Europe Conference & Exhibition (DATE 2021), Virtual Event

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
