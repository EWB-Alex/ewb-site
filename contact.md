---
layout: default
title: Contact
description: Get in touch with Electronic Works Bureau.
---

The easiest way to reach us is email. We usually reply {{ site.reply_time }}.

<p class="email-big"><a href="mailto:{{ site.email }}">{{ site.email }}</a></p>

## Start an email

Pick one and your email app opens with a few prompts filled in.

{% capture b_order %}Hi Alex,

Order or item name:

My question:

{% endcapture %}
{% capture b_comm %}Hi Alex,

What I'd like made:

Budget range:

Ideal timeline:

{% endcapture %}
{% capture b_gen %}Hi Alex,

{% endcapture %}
<ul class="button-list">
<li>{% include email-link.html label="Question about an order or item" subject="Order question" body=b_order %}</li>
<li>{% include email-link.html label="Commission inquiry" subject="Commission inquiry" body=b_comm %}</li>
<li>{% include email-link.html label="Something else" subject="Hello" body=b_gen %}</li>
</ul>

{% include commission-status.html %}
