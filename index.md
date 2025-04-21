---
title: Welcome to my blog
---

***我正在学习GitHub pages教程***
`hello world`
# 尝试使用markdown
<h1>最新文章</h1>

<ul>
  {% for post in site.posts %}
    <li>
      <h2><a href="{{ post.url }}">{{ post.title }}</a></h2>
      <p>{{ post.date | date_to_string }}</p>
      <p>{{ post.excerpt }}</p> <!-- 显示文章摘要 -->
    </li>
  {% endfor %}
</ul>
