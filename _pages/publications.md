---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---
title: "Deep learning and Dempster-Shafer thoery"
---

Tong, Zheng, Jie Gao, and Haitao Zhang. "Recognition, location, measurement, and 3D reconstruction of concealed cracks using convolutional neural networks." Construction and Building Materials 146 (2017): 775-787.<br />




{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
