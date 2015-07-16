---
layout: page
title: sm4 bits
---
{% include JB/setup %}

I get to use a lot of new technologies in my current job. Everyday I am going through a lot of frustration since not many people do what we do now, resources are scattered and questions on Stackoverflow unanswered. I am going to share my findings to hopefully save somebody else from the same fate.

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>



