---
layout: page
title: En blog omkring ting der sker på geekhub.dk
tagline: og i det danske community
---
{% include JB/setup %}

# Posts

<div class="well">
<ul class="posts unstyled">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">
      <h3>{{ post.title }}</h3></a></li>
  {% endfor %}
</ul>
</div>

# Open Source
Bloggen er open source. Alle posts osv. ligger på [Github](https://github.com/geekhubdk/geekhubdk.github.com).
