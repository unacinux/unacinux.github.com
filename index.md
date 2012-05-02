---
layout: base
title: unacinux
---

<br/>
{% include carousel.html %}


<div class="row">
  <div class="span4">
  {% capture what %} {% include what.md %} {% endcapture %}
  {{ what | unindent | markdownify }}
  </div>

  <div class="span4">
  {% capture how %} {% include how.md %}{% endcapture %}
  {{ how | unindent | markdownify }}
  </div>

  <div class="span4">
  {% capture  why %} {% include why.md %} {% endcapture %}
  {{ why | unindent | markdownify }}
  </div>
</div>
