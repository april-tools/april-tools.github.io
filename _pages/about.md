---
permalink: /
title: ""
excerpt: "about april"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---
<div class="lab-acronym">
  <!-- <img class="lab-acronym-logo" src="images/april-acronym-1"/> -->
  automating probabilistic inference and learning
</div>


We are a research lab focused on investigating probabilistic models and programs that are reliable and efficient. We are based at the <a href="https://www.ed.ac.uk/informatics">School of Informatics</a>, <a href="https://www.ed.ac.uk">University of Edinburgh</a> within the <a href="https://web.inf.ed.ac.uk/anc">Institute for Adaptive and Neural Computations (ANC)</a>.

<div class="news-header">news</div>
<div id="latest-news-list">
  <ul>
  {% for post in site.news reversed limit:10 %}
    <li><div class="news-item-wrapper">
            <span class="news-item-date">[{{post.date | date_to_string: "ordinal"}}]</span>
            <div class="news-item-text">{{post}}</div>
        </div>
    </li>
  {% endfor %}
  </ul>
</div>

<div class="pubs-header">selected works</div>