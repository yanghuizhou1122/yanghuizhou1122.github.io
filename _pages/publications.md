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
- Biomechanical Insights into Hip Stability: Quantifying Capsule and Local Muscle Contributions via Computational Analysis in Total Hip Arthroplasty (*preparing for submission to Computer Methods in Biomechanics and Biomedical Engineering*)<br>Authors: **Huizhou Yang**, Kathryn Colone, Casey A. Myers, Paul J. Rullkoetter, Chadd W. Clary<br>[*Click here to see this project.*](https://yanghuizhou1122.github.io//portfolio/portfolio-5-hip-capluse/)

- Impact of design factors on implant stability in cementless hip revision arthroplasty: Experimental-computational studies evaluating different implant designs (*still working on it*)<br>Authors: **Huizhou Yang**, William Fugit, Paul J. Rullkoetter, Chadd W. Clary<br>[*Click here to see this project.*](https://yanghuizhou1122.github.io//portfolio/portfolio-9-hip-micromotion/)