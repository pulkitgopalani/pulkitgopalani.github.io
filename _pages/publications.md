---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

Please check <u><a href="{{author.googlescholar}}">my Google Scholar profile</a></u> for a more up-to-date list.

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
