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
<div class="slideshow-container">
  {% for post in site.publications %}
    {% if post.spotlight %}
      <div class="spotlight-slide fade">
        <!-- <div class="numbertext">1 / 3</div> -->
        <a href="/publications/{{post.ref}}"><img src="{{post.spotlight}}"></a>
        <div class="text">{{post.excerpt}} <a href="{{post.url}}"><b><i>{{post.venue}}</i></b></a></div>
      </div>
    {% endif %}
  {% endfor %}
</div>
<br>


<div style="text-align:center">
  {% for post in site.publications %}
    {% if post.spotlight %}
    <span class="dot"></span> 
    {% endif %}
  {% endfor %}
</div>

<script>
  let slideIndex = 0;
  showSlides();
  
  function showSlides() {
    let i;
    let slides = document.getElementsByClassName("spotlight-slide");
    let dots = document.getElementsByClassName("dot");
    for (i = 0; i < slides.length; i++) {
      slides[i].style.display = "none";  
    }
    slideIndex++;
    if (slideIndex > slides.length) {slideIndex = 1}    
    for (i = 0; i < dots.length; i++) {
      dots[i].className = dots[i].className.replace(" active", "");
    }
    slides[slideIndex-1].style.display = "block";  
    dots[slideIndex-1].className += " active";
    setTimeout(showSlides, 10000); // Change image every 10 seconds
  }
  </script>
