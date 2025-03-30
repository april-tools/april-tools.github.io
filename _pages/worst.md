---
permalink: /worst/
title: ""
excerpt: "WOrkshops, Seminars and Talks"
author_profile: true
---

<h1><hlgt>wor</hlgt>kshops, <hlgt>s</hlgt>eminars & <hlgt>t</hlgt>alks</h1>

A collection of recent events and presentations done by <a href="./people/">members</a> of the group.

<div id="talk-list">
    {% for post in site.talks reversed %}
        {% include archive-single-talk.html %}
    {% endfor %}
</div>