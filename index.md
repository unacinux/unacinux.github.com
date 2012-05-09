---
layout: base
title: Unacinux
---

<br/>
{% include carousel.html %}


<div class="row">
  <div class="span4">
    <h2>¿Qué hacemos?</h2>
      <div class="texto">
        <p><ul>
        <li>Apoyamos a la difusión y adopción del del Software Libre en las diferentes instituciones, públicas o privadas.</li>
        <li>Apoyamos en el desarrollo de proyectos del Software Libre.</li>
        <li>Y lo que es más importante, nos divertimos.</li>
        </ul></p>
      </div>
    <h2>Proyectos</h2>
      <div class="texto">
        <p>Actualmente estamos trabajando en los siguientes proyectos:</p>
      </div>
    <h2>¿Cómo lo hacemos?</h2>
      <div class="texto">
        <p><ul>
        <li>Usamos Software Libre.</li>
        <li>Realizamos y/o apoyamos eventos de difusión del Software Libre.</li>
        </ul></p>
      </div>
  </div>

  <div class="span4">
    <h2>¿Por qué los hacemos?</h2>
      <div class="texto">
      <p>Por que nosotros realmente amamos el Software Libre y lo que significa.</p>
      </div>
      <p>
      <blockquote>
        La libertad no es poder elegir entre unas pocas opciones impuestas, sino tener el control de tu propia vida. La libertad no es elegir quien será tu amo, es no tener amo.
        <small>Richard Stallman</small>
      </blockquote>
      </p>
  </div>

  <div class="span4">
    <div id=tweets>
      <script charset="utf-8" src="http://widgets.twimg.com/j/2/widget.js"></script>
      <script>
      new TWTR.Widget({
      version: 2,
      type: 'profile',
      rpp: 6,
      interval: 30000,
      width: 'auto',
      height: 300,
      theme: {
          shell: {
          background: '#8ec1da',
          color: '#ffffff'
          },
          tweets: {
          background: '#ffffff',
          color: '#444444',
          links: '#1986b5'
          }
      },
      features: {
          scrollbar: false,
          loop: false,
          live: false,
          behavior: 'all'
      }
      }).render().setUser('unacinux').start();
      </script>
    </div>
  </div>
</div>
