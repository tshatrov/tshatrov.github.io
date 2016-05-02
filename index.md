---
layout: page
title: tshatrov's github pages
tagline: 
---
{% include JB/setup %}

## Ichi.moe

[ichi.moe](http://ichi.moe) is an awesome tool for reading Japanese text.

Repository: [tshatrov/ichiran](https://github.com/tshatrov/ichiran)

## Script-fu scripts for GIMP

Repository: [tshatrov/scriptfu](https://github.com/tshatrov/scriptfu)

* [Animstack](/animstack.html) *latest update: 0.62 (May 2, 2016)*
* to be continued...

## Posts

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>



