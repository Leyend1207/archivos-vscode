!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Tienda Online - ABILITY</title>
  <link rel="stylesheet" href="styles.css">
</head>
<body>
  <!-- Barra de navegación -->
  <header>
    <div class="navbar">
      <div class="logo">ABILITY</div>
      <nav>
        <ul>
          <li><a href="#inicio">Inicio</a></li>
          <li><a href="#productos">Productos</a></li>
          <li><a href="#ofertas">Ofertas</a></li>
          <li><a href="#contacto">Contacto</a></li>
        </ul>
      </nav>
      <div class="carrito"><a href="#carrito">🛒 Carrito</a></div>
    </div>
  </header>

  <!-- Sección principal -->
  <main>
    <!-- Banner de bienvenida -->
    <section class="hero" id="inicio">
      <h1>¡Bienvenido a ABILITY!</h1>
      <p>La mejor tienda online para todas tus compras.</p>
      <button onclick="scrollToSection('productos')">Explora Nuestros Productos</button>
    </section>

    <!-- Sección de productos -->
    <section class="productos" id="productos">
      <h2>Nuestros Productos</h2>
      <div class="grid">
        <div class="producto">
          <img src="img/producto1.jpg" alt="Producto 1">
          <h3>Producto 1</h3>
          <p>Descripción breve del producto 1.</p>
          <button>Añadir al Carrito</button>
        </div>
        <!-- Agrega más productos similares aquí -->
      </div>
    </section>

    <!-- Sección de ofertas -->
    <section class="ofertas" id="ofertas">
      <h2>Ofertas Exclusivas</h2>
      <div class="grid">
        <div class="oferta">
          <img src="img/oferta1.jpg" alt="Oferta 1">
          <h3>Oferta 1</h3>
          <p>Detalles de la oferta especial.</p>
          <button>Añadir al Carrito</button>
        </div>
        <!-- Agrega más ofertas aquí -->
      </div>
    </section>

    <!-- Sección de contacto -->
    <section class="contacto" id="contacto">
      <h2>Contáctanos</h2>
      <form id="formularioContacto">
        <label for="nombre">Nombre:</label>
        <input type="text" id="nombre" name="nombre" required>
        
        <label for="email">Correo Electrónico:</label>
        <input type="email" id="email" name="email" required>

        <label for="mensaje">Mensaje:</label>
        <textarea id="mensaje" name="mensaje" required></textarea>

        <button type="submit">Enviar</button>
      </form>
    </section>
  </main>

  <!-- Pie de página -->
  <footer>
    <p>&copy; 2024 ABILITY. Todos los derechos reservados.</p>
  </footer>

  <script src="scripts.js"></script>
</body>
</html>
