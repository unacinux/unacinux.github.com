---
layout: base
title: Unacinux
---

<br/>
{% include carousel.html %}


<div class="row">
  <div class="span4">
  {% capture what %}
    {% include what.md %}
  {% endcapture %}
  {{ what | unindent | markdownify }}
  </div>

  <div class="span4">
  {% capture how %}
    {% include how.md %}
  {% endcapture %}
  {{ how | unindent | markdownify }}
  </div>

  <div class="span4">
  {% capture  why %}
    {% include why.md %}
  {% endcapture %}
  {{ why | unindent | markdownify }}
  <blockquote>
   <p>La libertad no es poder elegir entre unas pocas opciones impuestas, sino tener el control de tu propia vida. La libertad no es elegir quien será tu amo, es no tener amo.</a>
   <small>Richard Stallman</small>
  </blockquote>
  </div>
</div>
