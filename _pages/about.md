---
permalink: /
title: ""
excerpt: "about APRIL"
# description: "april lab, april research lab, Edinburgh"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---


We are a research lab focused on investigating probabilistic models and programs that are reliable and efficient. We are based at the <a href="https://www.ed.ac.uk/informatics">School of Informatics</a>, <a href="https://www.ed.ac.uk">University of Edinburgh</a> within the <a href="https://web.inf.ed.ac.uk/anc">Institute for Adaptive and Neural Computations (ANC)</a>.

<div class="research-tags">#probabilistic-modeling #neuro-symbolic-AI #constraints #tractable-inference #circuits</div>

<div class="news-header">latest news</div>
<div id="latest-news-list">
  <ul>
  {% assign news = site.news | reverse %}
  {% for post in news limit:5 %}
    <li><div class="news-item-wrapper">
            <span class="news-item-date">[{{post.date | date_to_string: "ordinal"}}]</span>
            <div class="news-item-text">{{post}}</div>
        </div>
    </li>
  {% endfor %}
  </ul>
</div>
<div id="news-archive"><a href="/news">older news</a></div>

<div class="pubs-header">selected works</div>
<div class="slideshow-container">
  {% for post in site.publications %}
    {% if post.spotlight %}
      <div class="spotlight-slide fade">
        <!-- <div class="numbertext">1 / 3</div> -->
        <a href="/publications/{{post.ref}}"><img src="{{post.spotlight}}"></a>
        <div class="text">{{post.excerpt}} 
          {% if post.award %}
            <a href="{{post.url}}"><b><i><note>{{post.venue}} {{post.award}}</note></i></b></a>
          {% else %}
            <a href="{{post.url}}"><b><i>{{post.venue}}</i></b></a>
          {% endif %}
        </div>
      </div>
    {% endif %}
  {% endfor %}
    <!-- Next and previous buttons -->
  <a class="prev" onclick="plusSlides(-1)">&#10094;</a>
  <a class="next" onclick="plusSlides(1)">&#10095;</a>
</div>
<div style="text-align:center">
  {% for post in site.publications %}
    {% if post.spotlight %}
    <span class="dot"></span> 
    {% endif %}
  {% endfor %}
</div>

<script>
  let slideIndex = 0;
  showSlides(slideIndex);
  
  function plusSlides(n) {
  showSlides(slideIndex += n);
  }

  /* $(".slideshow-container").on("scroll", );  */
  
  function showSlides(n=0) {
    let i;
    let slides = document.getElementsByClassName("spotlight-slide");
    let dots = document.getElementsByClassName("dot");

    if (n == 0)
    {
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
      setTimeout(showSlides, 10000); /* Change image every 10 seconds */
    }
    
    else
    {
      if (n > slides.length) {slideIndex = 1}
      if (n < 1) {slideIndex = slides.length}

      for (i = 0; i < slides.length; i++) {
        slides[i].style.display = "none";  
      }

      if (slideIndex > slides.length) {slideIndex = 1}    
        for (i = 0; i < dots.length; i++) {
        dots[i].className = dots[i].className.replace(" active", "");
      }
      
      slides[slideIndex-1].style.display = "block";  
      dots[slideIndex-1].className += " active";
    }
  }
  </script>
