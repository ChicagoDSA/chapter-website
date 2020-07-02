---
layout: default
title: Home
headline: We are the Democratic Socialists of America.
subhead: We are creating a more equitable world by establishing socialism as a political force. We believe our governments and economy should operate, through social ownership, for the benefit of all.
---

### Campaigns

{% capture include_content %}
{% include tile.html title="Defund CPD" link="another-page" image="assets/images/police.png" %}
{% include tile.html title="Lift the Ban" link="another-page" image="assets/images/protest.png" %}
{% endcapture %}

{% include tile-list.html content=include_content %}
