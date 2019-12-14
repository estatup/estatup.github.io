---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

You can also find my articles on [my Google Scholar profile](https://scholar.google.com.br/citations?user=6Txu3hwAAAAJ&hl=en){: .btn .btn--success}

You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>


{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
