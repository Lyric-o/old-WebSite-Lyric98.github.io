<!-- ---
title: "Yanran Li's current CV"
collection: cv
permalink: /pages/
paperurl: 'http://Lyric98.github.io/files/CV_eecs.pdf'
---

[Download My CV here](http://Lyric98.github.io/files/CV_eecs.pdf)
 -->

---
layout: archive
title: "Yanran Li's current CV"
permalink: /publications/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{http://Lyric98.github.io/files/CV_eecs.pdf}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
