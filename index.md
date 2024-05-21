---
layout: default
---
**There is just some insignificant words.**
<ul>
    {% for post in site.posts %}
        <li>
            <a href="{{ post.url }}">{{ post.title post.date }}</a>
            <span >{{ post.date | date: "%b %-d, %Y" }}</span>
        </li>
    {% endfor %}
</ul>
