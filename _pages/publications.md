---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---
{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}
## Journal Paper
{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

## Working Paper
{% for post in site.publications_future reversed %}
  {% include archive-single.html %}
{% endfor %}

