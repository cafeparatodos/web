<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Café para todos</title>
  <meta name="description" content="Explora el mundo del café colombiano, bienestar natural y cultura cafetera.">
  <style>
    body {
      font-family: Arial, sans-serif;
      background: linear-gradient(rgba(255, 255, 255, 0.85), rgba(255, 209, 117, 0.85)), url('imag/fondo.jpg');
      background-size: cover;
      background-position: center;
      background-repeat: no-repeat;
      margin: 0;
      padding: 0;
    }
    header {
      background-color: #4e342e;
      color: white;
      padding: 20px;
      display: flex;
      align-items: center;
      justify-content: center;
      gap: 20px;
      flex-wrap: wrap;
      text-align: center;
    }
    header img {
      height: 60px;
      width: auto;
    }
    nav {
      background-color: #6d4c41;
      display: flex;
      justify-content: center;
      gap: 20px;
      padding: 10px;
      flex-wrap: wrap;
    }
    nav a {
      color: white;
      text-decoration: none;
      font-weight: bold;
      padding: 5px 10px;
      border-radius: 5px;
      transition: background-color 0.3s;
    }
    nav a:hover {
      background-color: #5d4037;
    }
    .grid {
      display: flex;
      flex-direction: column;
      gap: 30px;
      padding: 40px;
      max-width: 800px;
      margin: auto;
    }
    .card {
      background-color: white;
      border-radius: 10px;
      box-shadow: 0 4px 8px rgba(0,0,0,0.1);
      overflow: hidden;
      transition: transform 0.3s;
      text-align: center;
    }
    .card:hover {
      transform: scale(1.02);
    }
    .card h3 {
      margin: 15px 15px 10px;
      color: #3e2723;
    }
    .card p {
      margin: 0 15px 15px;
      color: #5d4037;
    }
    .card img {
      width: 100%;
      max-width: 600px;
      height: 200px;
      object-fit: cover;
      margin: 0 auto 20px;
      display: block;
      border-radius: 0 0 10px 10px;
    }
    .card a.button {
      display: inline-block;
      margin-bottom: 20px;
      padding: 8px 16px;
      background-color: #6d4c41;
      color: white;
      text-decoration: none;
      border-radius: 5px;
      transition: background-color 0.3s;
    }
    .card a.button:hover {
      background-color: #5d4037;
    }
    footer {
      background-color: #4e342e;
      color: white;
      text-align: center;
      padding: 20px;
      margin-top: 40px;
    }
    @media screen and (max-width: 600px) {
      .grid {
        padding: 20px;
      }
      .card img {
        height: 150px;
      }
      header {
        flex-direction: column;
      }
    }
  </style>
</head>
<body>

  <header>
    <img src="imag/logo.png" alt="Logo Café para todos">
    <div>
      <p>Bienestar, naturaleza y cultura cafetera</p>
    </div>
  </header>

 <nav aria-label="Menú principal">
  <a href="web todos 2.html">Inicio</a>
  <a href="historia.html">Historia</a>
  <a href="animales.html">Animales</a>
  <a href="catalogo.html">Catálogo</a>
  <a href="ejercicios.html">Ejercicios para casa</a>
</nav>

  <section id="inicio" class="grid">
    <div class="card">
      <h3>¿Estás estresado?</h3>
      <p>Descubre cómo el café y la respiración consciente pueden ayudarte a relajarte.</p>
      <img src="imag/estres.jpg" alt="Persona relajándose con café">
      <a href="ejercicios.html" class="button">Explorar ejercicios</a>
    </div>
    <div class="card" id="historia">
      <h3>Café en Colombia</h3>
      <p>Conoce el proceso de cultivo y la historia detrás del café colombiano.</p>
      <img src="imag/colombia.jpg" alt="Cultivo de café en Colombia">
      <a href="historia.html" class="button">Leer más</a>
    </div>
    <div class="card" id="animales">
      <h3>Animales autóctonos</h3>
      <p>Explora la fauna nativa que habita en las regiones cafeteras.</p>
      <img src="imag/aves.jpg" alt="Aves autóctonas de Colombia">
      <a href="animales.html" class="button">Ver especies</a>
    </div>
       <div class="card" id="productos">
      <h3>Compras</h3>
      <p>Explora nuestro menú de cafés artesanales y realiza tu pedido.</p>
      <img src="imag/menu.jpg" alt="Menú de cafés artesanales">
      <a href="catalogo.html" class="button">Ver productos</a>
    </div>
  </section>

  <footer aria-label="Pie de página">
    <p>&copy; 2025 Café para todos. Todos los derechos reservados.</p>
  </footer>

</body>
</html>
