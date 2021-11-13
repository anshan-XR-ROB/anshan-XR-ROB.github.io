<<<<<<< HEAD
---
layout: archive
title: "Academic Activities"
permalink: /academic activities/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.academic activities reversed %}
  {% include archive-single.html %}
{% endfor %}
=======
---
layout: archive
title: "Academic Activities"
permalink: /academic_activities/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.academic_activities reversed %}
  {% include archive-single.html %}
{% endfor %}
>>>>>>> d177252985dce881bdf5ca03d80be8f8cd65af38
