<!-- index.html -->
<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Mi Portafolio - Diseño Gráfico</title>
  <style>
    body {
      font-family: sans-serif;
      margin: 0;
      padding: 0;
      background: #f4f4f4;
      color: #333;
    }
    header {
      background: black;
      color: white;
      padding: 2rem;
      text-align: center;
    }
    section {
      padding: 2rem;
    }
    .grid {
      display: grid;
      grid-template-columns: repeat(auto-fill, minmax(250px, 1fr));
      gap: 1rem;
    }
    .grid img {
      width: 100%;
      height: auto;
      border-radius: 10px;
    }
    footer {
      text-align: center;
      padding: 2rem;
      background: #222;
      color: white;
    }
  </style>
</head>
<body>

  <header>
    <h1>Tu Nombre Aquí</h1>
    <p>Diseñador/a Gráfico/a | Branding | Redes Sociales</p>
  </header>

  <section>
    <h2>Mis Trabajos</h2>
    <div class="grid">
      <img src="img/diseño1.jpg" alt="Trabajo 1">
      <img src="img/diseño2.jpg" alt="Trabajo 2">
      <img src="img/diseño3.jpg" alt="Trabajo 3">
      <!-- Puedes seguir agregando más -->
    </div>
  </section>

  <footer>
    <p>Contáctame en Instagram: @tucuenta</p>
  </footer>

</body>
</html>
