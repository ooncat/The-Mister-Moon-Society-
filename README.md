<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>The Mister Moon Society</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 0;
      background-color: #0d0d0d;
      color: #fff;
    }

    header {
      background-color: #1a1a1a;
      padding: 20px;
      text-align: center;
    }

    header img {
      width: 100px;
    }

    nav {
      margin-top: 10px;
    }

    nav a {
      color: #fff;
      text-decoration: none;
      margin: 0 15px;
      font-weight: bold;
    }

    .hero {
      text-align: center;
      padding: 100px 20px;
      background: url('https://via.placeholder.com/1920x800') no-repeat center center/cover;
    }

    .hero h1 {
      font-size: 3em;
      margin-bottom: 10px;
    }

    .hero p {
      font-size: 1.2em;
    }

    .hero button {
      background-color: #ffcc00;
      color: #000;
      border: none;
      padding: 10px 20px;
      font-size: 1em;
      margin-top: 20px;
      cursor: pointer;
    }

    .section {
      padding: 50px 20px;
      text-align: center;
    }

    .services, .projects, .contact {
      background-color: #1a1a1a;
      margin: 20px 0;
      border-radius: 10px;
    }

    .services h2, .projects h2, .about h2, .contact h2 {
      font-size: 2em;
    }

    .services .service {
      margin: 10px 0;
    }

    footer {
      background-color: #1a1a1a;
      text-align: center;
      padding: 10px 0;
      font-size: 0.9em;
    }
  </style>
</head>
<body>
  <header>
    <img src="logo.png" alt="The Mister Moon Society">
    <nav>
      <a href="#services">Servicios</a>
      <a href="#projects">Proyectos</a>
      <a href="#about">Sobre Nosotros</a>
      <a href="#contact">Contacto</a>
    </nav>
  </header>

  <section class="hero">
    <h1>The Mister Moon Society</h1>
    <p>Iluminamos tu marca, guiándola más allá de las estrellas.</p>
    <button>Conoce nuestros servicios</button>
  </section>

  <section id="services" class="section services">
    <h2>Servicios</h2>
    <div class="service">Publicidad Digital</div>
    <div class="service">Diseño Web</div>
    <div class="service">Branding</div>
    <div class="service">Marketing de Contenidos</div>
  </section>

  <section id="projects" class="section projects">
    <h2>Proyectos</h2>
    <p>Historias de éxito bajo nuestra luz.</p>
  </section>

  <section id="about" class="section about">
    <h2>Sobre Nosotros</h2>
    <p>Somos la luz que guía tu marca hacia el éxito.</p>
  </section>

  <section id="contact" class="section contact">
    <h2>Contacto</h2>
    <form>
      <label for="name">Nombre:</label><br>
      <input type="text" id="name" name="name"><br><br>
      <label for="email">Correo:</label><br>
      <input type="email" id="email" name="email"><br><br>
      <label for="message">Mensaje:</label><br>
      <textarea id="message" name="message" rows="4"></textarea><br><br>
      <button type="submit">Enviar</button>
    </form>
  </section>

  <footer>
    <p>© 2024 The Mister Moon Society. Todos los derechos reservados.</p>
  </footer>
</body>
</html>
