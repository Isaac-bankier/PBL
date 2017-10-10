---
layout: default
title: Posts
---
## Learn electronics online!
Hello ma'am. This website is a mix between an online tutorial on electronics, a report about electrictity and magnatism, and a blog.

I would recommend reading the pages in this order:

1. Intro
2. Electromagnet vs solenoid
3. Making magnets stronger
4. The relay

You can find the answers to each of the required questions in the following:

| question | page  |
|   :---:  | :---: |
| 1. Explain why a current carrying wire causes magnetism and what causes it. | Intro |
| 2. Explain solenoid and electromagnets, their mainfunction and features such as current, field, and polarity. | Electromagnet vs solenoid |
| 3. Compare a permanent magnet to an electromagnet in terms of magnetic field and function | Making magnets stronger |
| 4. Indenting the factors which increase the strength of an electro magnet and why they do so. | Intro |
| 5. Outline a common use of an electro magnet and how it works. | The relay |

---
<h1>{{ page.title }}</h1>
<ul class="posts">
{% for post in site.posts %}
<li><span>{{ post.date | date_to_string }}</span> » <a href="/PBL{{ post.url }}" title="{{ post.title }}">{{ post.title }}</a></li>
{% endfor %}
</ul>
