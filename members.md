---
layout: page
title: Members
subtitle: More about us…
---

<div>
 <a href="{{ site.baseurl }}/members">Short version</a> |  <a href="{{ site.baseurl }}/members_detailed">Detailed version</a>
</div>

{% for post in site.members %}
    {% include archive-people-index.html %}
{% endfor %}


