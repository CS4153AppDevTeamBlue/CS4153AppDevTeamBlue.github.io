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

[Project roles](roles.html)

###Lead

Derrian

###Architect

Kevin

###UI/UX

Nathan

Deephti

###Graphics/Testing

Connor


####Post List

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>
