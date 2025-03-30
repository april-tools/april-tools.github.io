---
permalink: /people/
title: ""
excerpt: "APRIL members"
author_profile: true
---

<h1>current members</h1>
<div id="current-members">
  {% for post in site.people %}
    {% if post.role == "PI" or post.role == "PhD Student" or post.role == "Postdoc" or post.role == "Research Assistant"%}
      <div class="lab-member">
          <div class="lab-member-pic">
          <img style="margin: 10px 0px 0px 0px;" src="{{post.image}}">
          </div>
          <div class="lab-member-data">
              <div class="member-name"><a href="{{post.webpage}}">{{post.name}}</a></div>
              <div class="member-role">{{post.role}}</div>
              {% if post.firstsupervisor %}
              <div class="member-role-sup">1st supervisor: {{post.firstsupervisor}}</div>
              {% endif %}
              {% if post.secondsupervisor %}
              <div class="member-role-sup">2nd supervisor: {{post.secondsupervisor}}</div>
              {% endif %}
              {% if post.cosupervisor %}
              <div class="member-role-sup">co-supervised w/ {{post.cosupervisor}}</div>
              {% endif %}
          </div>
      </div>
    {% endif%}
  {% endfor %}
</div>

<h1>alumni</h1>
<div id="alumni">
  <ul id="alumni-list">
    {% for post in site.people reversed %}
        {% if post.role == "Alumnus"%}
        <li> <a href="{{post.webpage}}">{{post.name}}</a> <b>[{{post.graduation}}]</b> <span><i>now {{post.nextaffiliation}}</i></span>
        </li>
        {% endif %}
    {% endfor %}
  </ul>
</div>

<h1>visitors & interns</h1>
<div id="visitors-interns">
  <ul id="visitor-list">
    {% for post in site.people reversed %}
        {% if post.role == "Visitor"%}
        <li> <a href="{{post.webpage}}">{{post.name}}</a> <b>[{{post.period}}]</b> <span><i>{{post.affiliation}}</i></span>
        </li>
        {% endif %}
    {% endfor %}
  </ul>
</div>
 
<!--<h1>past members</h1> -->