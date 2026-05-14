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

## Conference Papers

{% bibliography -q @*[paper_type=full] %}

## Short Conference / Workshop Papers

{% bibliography -q @*[paper_type=short] %}

</div>
