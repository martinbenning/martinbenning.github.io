---
layout: single
title: "Welcome"
permalink: /
---

# Welcome

I am Professor of Inverse Problems at the Department of Computer Science, University College London.

## Latest News
{% for post in site.posts limit:3 %}
- {{ post.date | date: "%d-%m-%Y" }} - [{{ post.title }}]({{ post.url }})
{% endfor %}

## Research Interests
- Inverse problems
- Regularisation theory
- Machine learning
- Image processing
- Imaging
- Optimisation

## Contact
- Email: [martin.benning[at]ucl.ac.uk](mailto:martin.benning[at]ucl.ac.uk)
- Office: Building Name, Room XXX
- [Google Scholar](link) | [ORCID](link) | [GitHub](link)