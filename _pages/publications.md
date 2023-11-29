---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% include base_path %}

**Publications**
- Publication 1
- Publication 2

  
{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
