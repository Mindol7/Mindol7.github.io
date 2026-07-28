---
layout: default
title: Publications
description: International and domestic journal and conference publications by Minhyuk Jo.
permalink: /publications/
---

# Publications

<p class="section-intro">My scholarly publications appear under the names <strong>Minhyuk Cho</strong> and <strong>Min Hyuk Cho</strong>. Publications are grouped by venue type, and verified links are included where available.</p>

{% assign international_journals = site.data.publications.international_journals %}
{% include publication_group.html id="international-journal-publications" title="International Journal Publications" items=international_journals %}

{% assign international_conferences = site.data.publications.international_conferences %}
{% include publication_group.html id="international-conference-publications" title="International Conference Publications" items=international_conferences %}

{% assign domestic_journals = site.data.publications.domestic_journals %}
{% include publication_group.html id="domestic-journal-publications" title="Domestic Journal Publications" items=domestic_journals %}

{% assign domestic_conferences = site.data.publications.domestic_conferences %}
{% include publication_group.html id="domestic-conference-publications" title="Domestic Conference Publications" items=domestic_conferences %}
