---
layout: archive
title: "Notes"
permalink: /notes/
author_profile: true
---

The following are notes I have personally studied during my military service. I am working hard and having fun strengthening my mathematical background these days. The purpose of writing up these notes is primarily to use as a reference for myself. 

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
