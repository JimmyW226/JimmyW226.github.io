---
layout: default
---

# Lindfield RCIA Program Readings - Scriptures

The following articles are for your reading to know the basics about Scriptures regarding your Christian life.

## Articles regarding Scriptures

{% for post in site.posts reversed %}
### [{{ post.title }}]({{ post.url }})

{{ post.date | date: "%B %d, %Y" }}

{{ post.excerpt }}

[Read more →]({{ post.url }})

{% endfor %}
