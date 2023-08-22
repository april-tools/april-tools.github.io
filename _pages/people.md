---
permalink: /people/
title: ""
excerpt: "APRIL members"
author_profile: true
---

<h1>current members</h1>
<div id="current-members">
  {% for post in site.people %}
    <div class="lab-member">
        <div class="lab-member-pic">
        <img src="{{post.image}}">
        </div>
        <div class="lab-member-data">
            <div class="member-name"><a href="{{post.url}}">{{post.name}}</a></div>
            <div class="member-role">{{post.role}}</div>
            {% if post.firstsupervisor %}
            <div class="member-role-sup">1st supervisor: {{post.firstsupervisor}}</div>
            {% endif %}
            {% if post.secondsupervisor %}
            <div class="member-role-sup">2nd supervisor: {{post.secondsupervisor}}</div>
            {% endif %}
            {% if post.cosupervisor %}
            <div class="member-role-sup">co-supervisor: {{post.cosupervisor}}</div>
            {% endif %}
        </div>
    </div>
  {% endfor %}
</div>

<h1>visitors & interns</h1>

<h1>past members</h1>