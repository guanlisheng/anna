---
layout: page
title: 博客
permalink: /blog/
---

这里收藏我读书、看纪录片时的发现和小小思考。新文章会自动出现在列表最上面。

{% for post in site.posts %}
## [{{ post.title }}]({{ post.url | relative_url }})

<p class="post-meta">{{ post.date | date: "%Y年%m月%d日" }}{% if post.categories.size > 0 %} · {{ post.categories | join: " / " }}{% endif %}</p>

{{ post.excerpt }}

[阅读全文 →]({{ post.url | relative_url }})

---
{% endfor %}
