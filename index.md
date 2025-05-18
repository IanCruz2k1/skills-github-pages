---
<html lang="es">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Mi Portafolio | Diseñador Freelance</title>
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0-beta3/css/all.min.css">
  <style>
    * {margin: 0; padding: 0; box-sizing: border-box;}
    body {
      font-family: 'Arial', sans-serif;
      background: #050d18;
      color: white;
      line-height: 1.6;
    }
    header, footer {
      background: #0b1120;
      padding: 1rem 2rem;
      display: flex;
      justify-content: space-between;
      align-items: center;
      flex-wrap: wrap;
    }
    nav a {
      margin: 0 1rem;
      text-decoration: none;
      color: #ccc;
      font-size: 0.9rem;
    }
    nav a:hover {color: #0ff;}
    .hero {
      padding: 4rem 2rem;
      background: radial-gradient(circle at top left, #07203f, #000);
      text-align: center;
    }
    .hero h1 {
      font-size: 2rem;
      margin-bottom: 1rem;
    }
    .hero h2 {
      font-size: 3rem;
      font-weight: bold;
      color: #00ffff;
    }
    .section {
      padding: 4rem 2rem;
      max-width: 1000px;
      margin: auto;
    }
    .carousel {
      display: flex;
      overflow-x: scroll;
      gap: 1rem;
    }
    .carousel img {
      height: 250px;
      border-radius: 10px;
    }
    .about {
      background: #0b1120;
    }
    form {
      background: #0b1120;
      padding: 2rem;
      border-radius: 10px;
    }
    form input, form textarea {
      width: 100%;
      padding: 0.8rem;
      margin-bottom: 1rem;
      border: none;
      border-radius: 5px;
    }
    form button {
      background: #00ffff;
      border: none;
      padding: 1rem 2rem;
      color: #000;
      font-weight: bold;
      cursor: pointer;
      border-radius: 5px;
    }
    footer p {font-size: 0.8rem; color: #aaa;}
    @media (max-width: 600px) {
      .hero h2 {font-size: 2rem;}
    }
  </style>
</head>
<body>
  <header>
    <div><strong>MiEstudio</strong></div>
    <nav>
      <a href="#">Inicio</a>
      <a href="#portafolio">Portafolio</a>
      <a href="#about">Sobre mí</a>
      <a href="#contacto">Contacto</a>
    </nav>
  </header>

  <section class="hero">
    <h1>Lleva tu marca al</h1>
    <h2>SIGUIENTE NIVEL</h2>
    <p>Diseño impactante, soluciones a medida.</p>
    <a href="#contacto"><button>Contáctame</button></a>
  </section>

  <section class="section" id="portafolio">
    <h2>Portafolio</h2>
    <div class="carousel">
      <img src="https://via.placeholder.com/300x250?text=Proyecto+1" alt="Proyecto 1">
      <img src="https://via.placeholder.com/300x250?text=Proyecto+2" alt="Proyecto 2">
      <img src="https://via.placeholder.com/300x250?text=Proyecto+3" alt="Proyecto 3">
    </div>
  </section>

  <section class="section about" id="about">
    <h2>Sobre mí</h2>
    <p>Soy un diseñador freelance apasionado por crear experiencias visuales que conectan con las personas. Trabajo con marcas que buscan destacar a través del diseño digital, branding, y contenido creativo. Con más de 5 años de experiencia, mi enfoque combina estrategia, estética y funcionalidad.</p>
  </section>

  <section class="section" id="contacto">
    <h2>Contáctame</h2>
    <form action="mailto:tucorreo@ejemplo.com" method="POST" enctype="text/plain">
      <input type="text" name="nombre" placeholder="Tu nombre" required>
      <input type="email" name="email" placeholder="Tu correo electrónico" required>
      <textarea name="mensaje" rows="5" placeholder="Tu mensaje" required></textarea>
      <button type="submit">Enviar mensaje</button>
    </form>
  </section>

  <footer>
    <p>&copy; 2025 MiEstudio. Todos los derechos reservados.</p>
    <p>Sígueme en <a href="#" style="color:#0ff;">Instagram</a> y <a href="#" style="color:#0ff;">LinkedIn</a></p>
  </footer>
</body>
</html>
---

