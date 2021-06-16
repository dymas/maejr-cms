---
title: Blog
layout: blog
---

<main class="lista">
    <h2 class="blog">Blog</h2>
    {% for post in site.posts %}
    <article class="post">
        <h2><a href="{{ post.url }}">{{ post.title }}</a></h2>
        {{ post.excerpt }}
        <div class="ler-mais"><a href="{{ post.url }}">Ler mais →</a></div>
    </article>
    {% endfor %}
</main>