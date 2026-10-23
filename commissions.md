---
layout: default
title: Commissions
description: Commission a custom electronic device from Electronic Works Bureau.
---

{% include commission-status.html no_link=true %}

<!-- EDIT: What kinds of things you'll take on. -->
Have an idea for a gadget, gift, display, or one-off tool? EWB builds custom electronics to order, from a single blinking thing to a finished device in a custom enclosure.

## Good fits

<!-- EDIT: Examples of commissions you want. Swap in your own. -->
- Custom displays, clocks, and scoreboards
- Macro pads and small input devices
- LED pieces for walls and shelves
- Restoring or modding vintage electronics

## How it works

<ol class="steps">
<li><strong>Send an inquiry.</strong> Tell us what you have in mind. A rough idea is fine.</li>
<li><strong>Get a quote.</strong> You'll get an estimate for price and timeline, usually {{ site.reply_time }}.</li>
<li><strong>Deposit and build.</strong> <!-- EDIT: deposit terms --> A deposit starts the build. You'll get progress updates along the way.</li>
<li><strong>Delivery.</strong> Pay the balance and your device ships (or is picked up locally).</li>
</ol>

## What to include

It helps to know:

- What you want it to do
- Rough size, look, or where it will live
- Your budget range
- When you'd like it by

{% if site.commissions_open %}
{% capture b %}Hi Alex,

What I'd like made:

Size / look / where it will live:

Budget range:

Ideal timeline:

Anything else:

{% endcapture %}
<p class="cta">{% include email-link.html label="Start a commission inquiry" subject="Commission inquiry" body=b class="btn btn-primary" %}</p>
{% else %}
{% capture b %}Hi Alex,

Please let me know when commissions open again. Here's what I'm thinking about (optional):

{% endcapture %}
<p>Commissions are closed right now, but you can still reach out. We'll let you know when spots open up.</p>
<p class="cta">{% include email-link.html label="Notify me when commissions open" subject="Commission waitlist" body=b class="btn btn-primary" %}</p>
{% endif %}

<p class="small">Prefer to type it yourself? Email <a href="mailto:{{ site.email }}">{{ site.email }}</a>.</p>
