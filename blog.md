---
layout: page
title: Blog
permalink: /blog/
---

<ul class="post-list">
    {% for post in site.posts %}
      <li>
        <span class="post-meta">{{ post.date | date: "%b %-d, %Y" }}</span>

        <h3 style="color:#B4B4B4;">{{ post.title }}</h3>
		<div>
			{{ post.content }}
		</div>
      </li>
    {% endfor %}
</ul>