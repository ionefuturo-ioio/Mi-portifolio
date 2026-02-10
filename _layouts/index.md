<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>{{ page.title }} | {{ site.title }}</title>

  <link rel="stylesheet" href="{{ '/assets/css/styles.css' | relative_url }}">
</head>

<body>

{% include navbar.html %}

<main>
  {{ content }}
</main>

{% include footer.html %}
  ---
layout: default
title: Home
---

<section class="hero">
  <h1>Ione Carvalho</h1>

  <p>
    Frontend Developer especializada en
    <strong>HTML, CSS y JavaScript</strong>.
  </p>

  <p class="subtitle">
    Desarrollo interfaces web responsive, accesibles y funcionales.
  </p>

  <div class="hero-buttons">
    <a href="#proyectos" class="btn">Ver proyectos</a>
    <a href="https://www.linkedin.com/in/ione-carvalho-315197203" target="_blank" class="btn secondary">
      LinkedIn
    </a>
  </div>
</section>

<section id="proyectos" class="section">
  <h2>Proyectos Destacados</h2>

  <div class="grid">

    <article class="card">
      <img src="{{ '/assets/img/palindromo.jpg' | relative_url }}" class="card-img">
      <h3>Palindrome Checker</h3>
      <p>Verifica si una palabra o frase es un palíndromo.</p>

      <div class="links">
        <a href="https://ionefuturo-ioio.github.io/palindrome-checker/" target="_blank">Ver demo</a>
        <a href="https://github.com/ionefuturo-ioio/palindrome-checker" target="_blank">Código</a>
      </div>
    </article>

    <article class="card">
      <img src="{{ '/assets/img/conversor-numeros-romanos.jpg' | relative_url }}" class="card-img">
      <h3>Roman Numeral Converter</h3>
      <p>Conversor decimal → romano en JavaScript.</p>

      <div class="links">
        <a href="https://ionefuturo-ioio.github.io/roman-numeral-converter/" target="_blank">Ver demo</a>
        <a href="https://github.com/ionefuturo-ioio/roman-numeral-converter" target="_blank">Código</a>
      </div>
    </article>

    <article class="card">
      <img src="{{ '/assets/img/pagina-tributo.png' | relative_url }}" class="card-img">
      <h3>Página de Tributo</h3>
      <p>HTML semántico + CSS responsive.</p>

      <div class="links">
        <a href="https://ionefuturo-ioio.github.io/pagina-tributo/" target="_blank">Ver demo</a>
        <a href="https://github.com/ionefuturo-ioio/pagina-tributo" target="_blank">Código</a>
      </div>
    </article>

  </div>
</section>
</body>
</html>
