---
layout: page
title: Writing
permalink: /writing/
---
<header class="sidebar">

<ul class="post-list">
    {% for post in site.posts %}
    {% if post.img %}
    <img src="{{ root_url }}/images/{{ post.img }}" class="left-images">
    {% endif %}
      <li>

        <span class="post-meta">{{ post.date | date: "%b %-d, %Y" }}</span>

        <h2>
          <a class="post-link" href="{{ post.url | prepend: site.baseurl }}">{{ post.title }}</a>
        </h2>
      </li>
      {{ post.content | strip_html | truncatewords:50}}<br>
          <a href="{{ post.url }}"></a><br>
    {% endfor %}
  </ul>
