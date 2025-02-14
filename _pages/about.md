---
title: About
permalink: /about/
---

I am david-why, I am alive, I do stuff

{% for link in site.data.about.links %}
- [{{ link.name }}]({{ link.url }})
{% endfor %}

[Also check this out](https://google.com)
{: .transparent}
