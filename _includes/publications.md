<section class="publication-section" aria-labelledby="journal-publications">
  <h2 id="journal-publications">Journal Articles</h2>
  <ol class="publication-list" role="list">
  {% for publication in site.data.publications.journals %}
    <li class="publication-item">
      <div class="publication-heading">
        <span class="venue-badge">{{ publication.venue_short }}</span>
        <span class="publication-year">{{ publication.year }}</span>
      </div>
      <h3>{{ publication.title }}</h3>
      <p class="publication-authors">
      {% for author in publication.authors %}
        {% if author.self %}<strong>{{ author.name }}</strong>{% else %}{{ author.name }}{% endif %}{% unless forloop.last %}, {% endunless %}
      {% endfor %}
      </p>
      <p class="publication-venue"><em>{{ publication.venue }}</em></p>
      {% if publication.doi or publication.page %}
      <p class="publication-links">
        {% if publication.doi %}<a href="{{ publication.doi }}" target="_blank" rel="noopener">DOI</a>{% endif %}
        {% if publication.page %}<a href="{{ publication.page }}" target="_blank" rel="noopener">Details</a>{% endif %}
      </p>
      {% endif %}
    </li>
  {% endfor %}
  </ol>
</section>

<section class="publication-section" aria-labelledby="conference-publications">
  <h2 id="conference-publications">Conference Papers</h2>
  <ol class="publication-list" role="list">
  {% for publication in site.data.publications.conferences %}
    <li class="publication-item">
      <div class="publication-heading">
        <span class="venue-badge">{{ publication.venue_short }}</span>
        <span class="publication-year">{{ publication.year }}</span>
      </div>
      <h3>{{ publication.title }}</h3>
      <p class="publication-authors">
      {% for author in publication.authors %}
        {% if author.self %}<strong>{{ author.name }}</strong>{% else %}{{ author.name }}{% endif %}{% unless forloop.last %}, {% endunless %}
      {% endfor %}
      </p>
      <p class="publication-venue"><em>{{ publication.venue }}</em></p>
      {% if publication.award %}<p class="publication-award">{{ publication.award }}</p>{% endif %}
      {% if publication.page or publication.slides %}
      <p class="publication-links">
        {% if publication.page %}<a href="{{ publication.page }}" target="_blank" rel="noopener">Details</a>{% endif %}
        {% if publication.slides %}<a href="{{ publication.slides }}" target="_blank" rel="noopener">Slides</a>{% endif %}
      </p>
      {% endif %}
    </li>
  {% endfor %}
  </ol>
</section>

<section class="publication-section" aria-labelledby="patents">
  <h2 id="patents">Patents</h2>
  <ol class="publication-list" role="list">
  {% for patent in site.data.publications.patents %}
    <li class="publication-item">
      <div class="publication-heading">
        <span class="venue-badge">{{ patent.status }}</span>
        <span class="publication-year">{{ patent.date }}</span>
      </div>
      <h3 lang="ko">{{ patent.title }}</h3>
      <p class="patent-translation">{{ patent.title_en }}</p>
      <p class="publication-authors">
      {% for author in patent.authors %}
        {% if author.self %}<strong>{{ author.name }}</strong>{% else %}{{ author.name }}{% endif %}{% unless forloop.last %}, {% endunless %}
      {% endfor %}
      </p>
      <p class="publication-venue">
        Application {{ patent.application_number }}{% if patent.registration_number %} · Registration {{ patent.registration_number }}{% endif %}
      </p>
      {% if patent.source %}
      <p class="publication-links"><a href="{{ patent.source }}" target="_blank" rel="noopener" aria-label="Source for patent: {{ patent.title_en }}">Source</a></p>
      {% endif %}
    </li>
  {% endfor %}
  </ol>
</section>
