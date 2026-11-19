---
layout: page
permalink: /publications/
title: Publications
description:
nav: true
nav_order: 2
---

<!-- _pages/publications.md -->

<!-- Bibsearch Feature -->

{% include bib_search.liquid %}

<div class="publications">

<h2 class="bibliography-section">Preprints</h2>

{% bibliography --group_by none --query @*[preprint=true] %}

<h2 class="bibliography-section">Conference & Journal Papers</h2>

{% bibliography --query @*[preprint!=true] %}

</div>
