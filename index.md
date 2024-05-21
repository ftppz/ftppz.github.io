---
layout: default
---
**There is just some insignificant words.**
<ul>
    {% for post in site.posts %}
        <li>
            <span >{{ post.date | date: "%b %-d, %Y" }}</span>
            <a href="{{ post.url }}">{{ post.title post.date }}</a>
        </li>
    {% endfor %}
</ul>
