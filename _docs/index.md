---
title: Home
layout: home
has_children: true
permalink: /
---

Welcome!

{% for feature in site.features $}
    <h1>{{ feature.name }}</h1>
    <article>
        {{ feature.content | markdownify }}
    </article>
{% endfor %}