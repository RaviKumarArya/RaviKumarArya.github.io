---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

You can also find my articles on my <a href="https://scholar.google.com/citations?user=l69FW9gAAAAJ&hl">Google Scholar</a> profile. A few significant ones are listed below.


{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
