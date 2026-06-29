---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

Selected publications are organized below by research theme. For a complete and up-to-date publication record, please see my <a href="https://chenlt326.github.io/cv/" style="text-decoration: none;">CV</a> or <a href="https://scholar.google.com/citations?hl=en&user=NMrUZscAAAAJ" style="text-decoration: none;">Google Scholar</a>.

{% include base_path %}

{% for post in site.publications reversed %}
{% include archive-single.html %}
{% endfor %}
