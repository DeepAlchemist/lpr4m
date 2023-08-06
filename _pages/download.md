---
layout: archive
title: "Download the full dataset here."
permalink: /Download/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.leaderboard reversed %}
  {% include archive-single-talk.html %}
{% endfor %}
