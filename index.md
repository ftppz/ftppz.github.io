---
layout: default
---
**There is just some insignificant words.**

<ul>
  {% for post in site.posts %}
    <li><a href="{{ post.url | prepend: site.baseurl }}">{ post }</a></li>
    {% endfor %}
</ul>
