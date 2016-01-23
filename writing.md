---
layout: page
title: Writing
permalink: /writing/
---

<ul class="post-list">
    {% for post in site.posts %}
      <li>
        <span class="post-meta">{{ post.date | date: "%b %-d, %Y" }}</span>

        <h2>
          <a class="post-link" href="{{ post.url | prepend: site.baseurl }}">{{ post.title }}</a>
        </h2>
      </li>
      {{ post.content | strip_html | truncatewords:50}}<br>
          <a href="{{ post.url }}"></a><br><br>
    {% endfor %}
  </ul>
