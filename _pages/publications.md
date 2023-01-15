---
layout: archive
# title: "Publications"
permalink: /publications/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{site.author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

<br>
<br>
<h1>Domestic Conferences</h1>
------
{% for post in site.publications reversed %}
  {% if post.pubtype == 'domestic_conference' %}
      {% include archive-single.html %}
  {% endif %}
{% endfor %}
------

<!-- <br>
<br>
<h1>Workshops & Academics</h1>
------
{% for post in site.publications reversed %}
  {% if post.pubtype == 'workshop_academic' %}
      {% include archive-single.html %}
  {% endif %}
{% endfor %}
------
<br>
<sup>*</sup> Equal authorship -->