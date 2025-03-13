---
title: "News"
permalink: /news/
layout: single
author_profile: true
---

# News and Updates

{% for post in site.posts %}
## [{{ post.title }}]({{ post.url }})
*{{ post.date | date: "%B %d, %Y" }}*

{{ post.excerpt }}

[Read more]({{ post.url }})

---
{% endfor %}