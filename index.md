---
layout: default
---

# Data Streams

<div class="accordion accordion-flush" id="accordionFlushExample">
  {% for source in site.data.catalog.sources %}
  <div class="accordion-item">
    <h2 class="accordion-header" id="{{ source[0] }}__heading">
      <button class="accordion-button collapsed" type="button" data-bs-toggle="collapse" data-bs-target="#{{ source[0] }}" aria-expanded="false" aria-controls="{{ source[0] }}">
        {{ source[0] }}
      </button>
    </h2>
    <div id="{{ source[0] }}" class="accordion-collapse collapse" aria-labelledby="{{ source[0] }}__heading" data-bs-parent="#accordionFlushExample">
      <div class="accordion-body">Placeholder content for this accordion, which is intended to demonstrate the <code>.accordion-flush</code> class. This is the first item's accordion body.</div>
    </div>
  </div>
  {% endfor %}
</div>
