---
layout: archive
title: artwork
permalink: /art/
category: ["artwork"]
---

<div class="home">


  {% for post in site.categories.n%}
  <div class="post postContent">
    </div>
    <div class="postDay">
      {{post.tag}}
    </div>
    <br>
    <div class="postTitle">
    <a class='postLink' href="{{site.url}}{{site.baseurl}}{{post.url}}">{{post.title}}</a>
    </div><span class="hint">
    <div class="postExt">
   {{ post.content | strip_html | truncatewords:275 }}
    </span></div>
  </div>


  {% endfor %}
  <!--<ul class="post-list">
    {% for post in site.posts %}
      <li>
	<span class="post-meta-main">{{ post.date | date: "%b %-d, %Y" }}</span>

	<h2>
	  <a class="post-link-main" href="{{ post.url | prepend: site.baseurl }}">{{ post.title }}</a>
	</h2>
      </li>
    {% endfor %}
  </ul>-->



</div>