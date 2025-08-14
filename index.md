---
layout: default
title: Dan Boles — AI & Systems
image: /assets/img/og-cover.png
---

<div class="hero">
  <h1>Dan Boles — AI &amp; Systems</h1>
  <p class="tagline">LLM apps, evaluators, CI pipelines, and reproducible research→code workflows.</p>
  <p class="cta-row">
    <a class="btn" href="#projects">View Projects</a>
    <a class="btn btn-secondary" href="https://github.com/dboles99">GitHub</a>
  </p>
</div>

## Featured projects {#projects}

<div class="cards">
{% for p in site.data.projects %}
  <a class="card" href="{{ p.url }}" target="_blank">
    {% if p.image %}<img src="{{ p.image }}" alt="{{ p.title }}" />{% endif %}
    <div class="card-body">
      <h3>{{ p.title }}</h3>
      <p>{{ p.blurb }}</p>
      <div class="tags">
        {% for t in p.tags %}<span class="tag">{{ t }}</span>{% endfor %}
      </div>
    </div>
  </a>
{% endfor %}
</div>

---

Want the long-form story? See the <a href="https://github.com/dboles99/dboles99.github.io#readme">README</a>.