---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

Most of these publications may also be found on <u><a href="https://scholar.google.com/citations?hl=en&user=1Hn4Y44AAAAJ">my Google Scholar profile</a>.</u>
<br>And here is the sciprofiles <u><a href="https://sciprofiles.com/profile/531360">sci profile</a>.</u>


{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

