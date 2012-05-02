---
layout: base
title: unacinux
---

<br/>
{% include carousel.html %}


<div class="row">
  <div class="span4">
  {% capture who %} {% include who.md %} {% endcapture %}
  {{ who | unindent | markdownify }}
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
