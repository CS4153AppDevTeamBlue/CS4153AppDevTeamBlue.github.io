---
layout: page
title: Team Blue Blog
tagline: Tracking the progress of our project
---
{% include JB/setup %}

#The Project
Read the Project Guidelines (TBD)

##About:

Insert information about the project here!

##The Team

###Lead

TBD

###Team Members

Insert Roles Here

####Post List

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>
