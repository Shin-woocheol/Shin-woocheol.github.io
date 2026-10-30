---
layout: page
permalink: /publications/
title: publications
description:
nav: true
nav_order: 2
---

<!-- _pages/publications.md -->

<!-- Bibsearch Feature -->

{% include bib_search.liquid %}

<div class="publications">

<h2 class="bibliography-section">preprints</h2>

{% bibliography --group_by none --query @*[preprint=true] %}

<h2 class="bibliography-section">conference & journal papers</h2>

{% bibliography --query @*[preprint!=true] %}

</div>
