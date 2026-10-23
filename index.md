---
layout: default
title: Home
---

<div class="welcome">
<p class="welcome-kicker">Welcome to the Bureau!</p>

<!-- EDIT: Your intro. One or two sentences on what EWB makes and who it's for. -->
<p>EWB is a small electronics shop in Western Washington making bespoke, fun and functional devices. Browse what's for sale, or tell us about something you'd like built.</p>
</div>

{% include commission-status.html %}

## This Week's Featured Items

{% include shop-grid.html featured=true heading="h3" %}

<p class="see-all"><a href="{{ '/shop' | relative_url }}">See all items in the Shop &raquo;</a></p>

## Shop by Department

<ul class="departments">
<li><a href="{{ '/shop' | relative_url }}"><strong>Ready to Ship</strong><span>Finished devices, built and tested.</span></a></li>
<li><a href="{{ '/commissions' | relative_url }}"><strong>Commissions</strong><span>Have an idea? Get it made for you.</span></a></li>
<li><a href="{{ '/projects' | relative_url }}"><strong>Projects</strong><span>Past builds and works in progress.</span></a></li>
</ul>
