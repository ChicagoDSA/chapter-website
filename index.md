---
layout: default
title: Sample site
---

### Campaigns

{% capture include_content %}
{% include tile.html title="Defund CPD" link="another-page" image="assets/images/police.png" %}
{% include tile.html title="Lift the Ban" link="another-page" image="assets/images/protest.png" %}
{% endcapture %}

{% include tile-list.html content=include_content %}
