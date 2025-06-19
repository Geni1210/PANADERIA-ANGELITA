<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Panadería El Buen Pan</title>
  <style>
    body {
      font-family: 'Segoe UI', sans-serif;
      margin: 0;
      background: #fff8f0;
      color: #333;
    }
    header {
      background-color: #d2691e;
      color: white;
      padding: 1rem;
      text-align: center;
    }
    nav {
      background: #ffdead;
      padding: 0.5rem;
      text-align: center;
    }
    nav a {
      margin: 0 10px;
      text-decoration: none;
      color: #5c3317;
      font-weight: bold;
    }
    section {
      padding: 2rem;
    }
    .productos {
      display: flex;
      flex-wrap: wrap;
      gap: 20px;
      justify-content: center;
    }
    .producto {
      background: #fff;
      border: 1px solid #ccc;
      padding: 1rem;
      width: 200px;
      text-align: center;
      border-radius: 10px;
      box-shadow: 2px 2px 5px #ccc;
    }
    footer {
      background: #d2691e;
      color: white;
      text-align: center;
      padding: 1rem;
    }
  </style>
</head>
<body>

<header>
  <h1>Panadería El Buen Pan</h1>
  <p>Pan fresco, todos los días con amor</p>
</header>

<nav>
  <a href="#inicio">Inicio</a>
  <a href="#productos">Productos</a>
  <a href="#contacto">Contacto</a>
</nav>

<section id="inicio">
  <h2>Bienvenidos</h2>
  <p>Gracias por visitarnos. Somos una panadería artesanal ubicada en Guatemala. Ofrecemos pan y pasteles recién horneados cada día.</p>
</section>

<section id="productos">
  <h2>Productos</h2>
  <div class="productos">
    <div class="producto">
      <h3>Pan Francés</h3>
      <p>Delicioso, crujiente y recién horneado.</p>
    </div>
    <div class="producto">
      <h3>Pan Dulce</h3>
      <p>Perfecto para acompañar tu café.</p>
    </div>
    <div class="producto">
      <h3>Conchas</h3>
      <p>Suaves, esponjosas y azucaradas.</p>
    </div>
    <div class="producto">
      <h3>Pasteles</h3>
      <p>Para cumpleaños y ocasiones especiales.</p>
    </div>
  </div>
</section>

<section id="contacto">
  <h2>Contacto</h2>
  <p>📍 Guatemala</p>
  <p>📱 WhatsApp: +502 1234-5678</p>
  <p>⏰ Lunes a sábado, 6:00 a.m. a 6:00 p.m.</p>
</section>

<footer>
  <p>&copy; 2025 Panadería El Buen Pan. Todos los derechos reservados.</p>
</footer>

</body>
</html>
