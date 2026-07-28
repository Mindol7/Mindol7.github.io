---
layout: default
title: Patents
description: Registered patents and patent applications by Minhyuk Jo.
permalink: /patents/
---

# Patents

<p class="section-intro">Registered patents are listed first, followed by pending applications. Patent records appear under the name <strong>Minhyuk Cho</strong>.</p>

<ol class="publication-list patent-list" role="list">
{% for patent in site.data.publications.patents %}
  <li class="publication-item">
    <div class="publication-heading">
      <span class="venue-badge">{{ patent.status }}</span>
      <span class="publication-year">{{ patent.date }}</span>
    </div>

    <h2 class="patent-title" lang="ko">{{ patent.title }}</h2>
    <p class="patent-translation">{{ patent.title_en }}</p>

    <p class="publication-authors">
    {% for author in patent.authors %}
      {% if author.self %}<strong class="author-self">{{ author.name }}</strong>{% else %}{{ author.name }}{% endif %}{% unless forloop.last %}, {% endunless %}
    {% endfor %}
    </p>

    <dl class="patent-numbers">
      {% if patent.registration_number %}
      <div>
        <dt>Registration No.</dt>
        <dd>{{ patent.registration_number }}</dd>
      </div>
      {% endif %}
      <div>
        <dt>Application No.</dt>
        <dd>{{ patent.application_number }}</dd>
      </div>
    </dl>

    {% if patent.source %}
    <p class="publication-links"><a href="{{ patent.source }}" target="_blank" rel="noopener" aria-label="Official source for {{ patent.title_en }}">Official source</a></p>
    {% endif %}
  </li>
{% endfor %}
</ol>
