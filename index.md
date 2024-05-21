---
layout: default
---
**There is just some insignificant words.**
<ul>
    {% for post in site.posts %}
        <li>
            <a href="{{ post.url }}">{{ post.title post.YEAR post.MONTH post.DAY }}</a>
        </li>
    {% endfor %}
</ul>
