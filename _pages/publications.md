---
layout: archive
title: "publications"
permalink: /publications/
author_profile: true
---

{% include base_path %}

<ul class="paper-list">
{% for post in site.publications reversed %}
       <li>
       {% include paper.html paper=post%}
       </li>
{% endfor %}
</ul>