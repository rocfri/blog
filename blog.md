---
layout: default
type: page
title: Blog
---

## Blog ##
<ul class="blog_post">
{% for post in site.posts %}
  <li>
    <a href="{{site.baseurl}}{{post.url}}">{{post.title}}</a>
    <p>{{post.meta}}</p>
  </li><br>
  {% endfor %}
</ul>
