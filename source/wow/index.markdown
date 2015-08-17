---
layout: page
title: "Words of Wisdom"
sharing: true
footer: true
---

{% for wow in site.wow %}
>{{ wow.content }}
<span class="byline author vcard">-- <span class="fn">{% if wow.author %}{{ wow.author }}{% else %}{{ "Anonymous" }}{% endif %}</span></span>
<hr>
{% endfor %}