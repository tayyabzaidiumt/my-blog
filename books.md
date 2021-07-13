---
layout: page
title: Books
category: books
---
<ul>
    {% for post in site.categories[page.category] %}
    <li>
        <a href="{{ post.url }}">{{ post.title }}</a>
        {{ post.excerpt }}
    </li>
    {% endfor %}
</ul>