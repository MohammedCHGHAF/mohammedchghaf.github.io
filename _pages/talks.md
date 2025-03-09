---
layout: page
permalink: /talks/
title: Talks
description: Talks by categories in reversed chronological order.
nav: true
nav_order: 3
---

{% include bib_search.liquid %}

<div class="talks">

{% bibliography -f {{ site.scholar.talk }} %}

</div>
