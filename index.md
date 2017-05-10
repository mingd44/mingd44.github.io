---
layout: post
title: "生活总是会有没有预期的事情发生"
categories: "blog"
---

{% for post in site.posts %}
* {{ post.date | date_to_string }} [{{ post.title }}]({{ site.baseurl }}{{ post.url }})
{% endfor %}
