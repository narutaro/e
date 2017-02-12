---
layout: layout
title: Oh! My JK
---
#Welcome to my JK Home Page!

<!-- 以下を追加 -->
<ul>
{% for post in site.posts %}
  <li>
    <a href="{{ post.url }}">{{ post.date | date_to_long_string }} : {{ post.title }}</a>
  </li>
{% endfor %}
</ul>
<!--  -->

server_port: {{ site.server_port }}

markdown: {{ site.markdown }}

permalink: {{ site.permalink }}

{{ site }}

**Copyright © {{ site.author.name }} 2012 All rights reserved. Please contact to {{ site.author.email }}.**
