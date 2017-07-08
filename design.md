---
layout: archive
title: design
permalink: /design/
category: design
---

<div class="home">
  {% for post in site.categories.n%}
  <div class="post postContent">
    <br>
    <div class="postTitle">
    <a class='postLink' href="{{site.url}}{{site.baseurl}}{{post.url}}">{{post.title}}</a>
    </div><span class="hint">
    <div class="postExt">
   {{ post.content | strip_html | truncatewords:75 }}
    </span></div>
  </div>
  {% endfor %}
</div>