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
- Impact of implant alignment, bone material, and implant design factors on the primary fixation stability in cementless unicompartmental knee arthroplasty<br>**Huizhou Yang**, Daniele Marras, Chadd W. Clary, Paul J. Rullkoetter<br>[*Click here to see this project.*](https://yanghuizhou1122.github.io//portfolio/portfolio-Uni-micromotion/)
