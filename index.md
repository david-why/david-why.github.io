---
layout: archive
title: ""
---

![avatar](https://gravatar.com/avatar/7eb53e58a8b9d239b21e88518a7be44f?size=256){:.circle}

# david-why

`{{ site.data.about.words | join: " · " }}`

## Recent Posts

{% assign posts = site.posts %}
{% for post in posts %}
  {% include archive-single.html type="list" %}
{% endfor %}
