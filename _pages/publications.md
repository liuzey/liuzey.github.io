---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---
More details can be found here at [Google Scholar](https://scholar.google.com/citations?user=sZTAgrwAAAAJ). 
* students mentored by me.

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
