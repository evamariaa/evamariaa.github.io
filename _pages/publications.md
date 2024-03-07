---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---
You can find all my publications on <a href="https://ui.adsabs.harvard.edu/public-libraries/AjXwsSYNQ6uoD2YCTMt2Kw">NASA ADS</a>, my first-author publications are described below. 

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

