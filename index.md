---
layout: default.liquid
---
{% include "test-include.liquid" %}
## Blog!

{% for post in collections.posts.pages %}
#### {{post.title}}

[{{ post.title }}]({{ post.permalink }})
{% endfor %}
