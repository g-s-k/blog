---
---

## this is a blog

i think????

{% for post in site.posts %}
- {{ post.date | date_to_string }} » [{{ post.title }}]({{ post.url }})
{% endfor %}
