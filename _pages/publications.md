---
layout: page
permalink: /publications/
title: publications
description: publications by categories in chronological order.
nav: true
nav_order: 1
---

<!-- _pages/publications.md -->

<!-- Bibsearch Feature -->

{% include bib_search.liquid %}

<div class="publications">

<h2>Conference Papers</h2>

{% bibliography -q @*[paper_type=full] %}

<h2>Short Conference / Workshop Papers</h2>

{% bibliography -q @*[paper_type=short] %}

</div>
