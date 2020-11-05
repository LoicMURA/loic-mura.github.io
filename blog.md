---
layout: default
title: Blog
permalink: /blog
---

[Accueil](/) [Contact](/contact)
<ul>
    {% for post in site.posts %}
        <li>
            <a href="{{ post.url }}">{{ post.title }}</a>
        </li>
    {% endfor %}
</ul>