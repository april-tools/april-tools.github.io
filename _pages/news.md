---
permalink: /news
title: ""
excerpt: "latest news in APRIL"
author_profile: true
---

<div class="news-header">lab news</div>
<div id="latest-news-list">
  <ul>
  {% for post in site.news reversed %}
    <li><div class="news-item-wrapper">
            <span class="news-item-date">[{{post.date | date_to_string: "ordinal"}}]</span>
            <div class="news-item-text">{{post}}</div>
        </div>
    </li>
  {% endfor %}
  </ul>
</div>
 
