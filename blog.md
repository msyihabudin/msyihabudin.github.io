---
layout: page
title: Blog
permalink: /blog/
---

## Engineering Notes & Learnings

I write about backend engineering, distributed systems, and lessons learned from real production environments.

---

{% for post in site.posts %}
### 📝 [{{ post.title }}]({{ post.url }})
*{{ post.date | date: "%B %d, %Y" }}*

{{ post.excerpt }}
{% endfor %}
