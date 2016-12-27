---
layout: default
type: page
title: Blog
---

## Blog ##
<ul class="blog_post">
{% for post in site.posts %}
  <li>
    <a href="{{site.baseurl}}{{post.url}}">({{post.date | date: '%m/%d/%Y' }})  {{post.title}}
    <p>{{ post.excerpt }}</p></a
  </li><br>
  {% endfor %}
</ul>
