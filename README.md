<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>03-danna | Presentación Impactante</title>
  <link href="https://fonts.googleapis.com/css2?family=Orbitron:wght@500&family=Roboto:wght@300;700&display=swap" rel="stylesheet">
  <script src="https://kit.fontawesome.com/a2e0e6a5c1.js" crossorigin="anonymous"></script>
  <script src="https://cdn.jsdelivr.net/npm/typed.js@2.0.12"></script>
  <script src="https://cdn.jsdelivr.net/npm/aos@2.3.4/dist/aos.js"></script>
  <link href="https://cdn.jsdelivr.net/npm/aos@2.3.4/dist/aos.css" rel="stylesheet">
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      scroll-behavior: smooth;
    }
    body {
      background: radial-gradient(circle at top left, #1a1a1a, #0d0d0d);
      color: #ffffff;
      font-family: 'Roboto', sans-serif;
    }
    header {
      height: 100vh;
      display: flex;
      flex-direction: column;
      justify-content: center;
      align-items: center;
      text-align: center;
      background: url('https://www.transparenttextures.com/patterns/stardust.png');
      background-size: cover;
      position: relative;
      overflow: hidden;
    }
    header::after {
      content: "";
      position: absolute;
      top: 0;
      left: 0;
      width: 100%;
      height: 100%;
      background: rgba(0, 0, 0, 0.5);
      z-index: 1;
    }
    header h1 {
      font-size: 4rem;
      font-family: 'Orbitron', sans-serif;
      color: #00ffcc;
      z-index: 2;
    }
    header p#typed {
      font-size: 1.5rem;
      margin-top: 1rem;
      color: #ffffff;
      z-index: 2;
    }
    section {
      padding: 4rem 2rem;
      max-width: 1000px;
      margin: auto;
    }
    h2 {
      color: #00ffcc;
      margin-bottom: 1rem;
      text-align: center;
    }
    .tech-icons {
      display: flex;
      justify-content: center;
      gap: 1.5rem;
      flex-wrap: wrap;
    }
    .tech-icons i {
      font-size: 3rem;
      transition: transform 0.3s;
      color: #00ffcc;
    }
    .tech-icons i:hover {
      transform: scale(1.2);
    }
    .btn-github {
      display: inline-block;
      background: #00ffcc;
      color: #121212;
      padding: 1rem 2rem;
      text-decoration: none;
      border-radius: 30px;
      font-weight: bold;
      transition: 0.3s;
    }
    .btn-github:hover {
      background: #00ddbb;
    }
    ul li {
      margin-bottom: 1rem;
      font-size: 1.1rem;
    }
    footer {
      text-align: center;
      padding: 2rem;
      background: #1f1f1f;
      color: #888;
      font-size: 0.9rem;
    }
    .floating-button {
      position: fixed;
      bottom: 30px;
      right: 30px;
      background: #00ffcc;
      color: #000;
      padding: 0.8rem 1rem;
      border-radius: 50%;
      font-size: 1.5rem;
      z-index: 10;
      box-shadow: 0 0 10px #00ffcc;
      text-align: center;
    }
    .floating-button:hover {
      background: #00ddbb;
    }
  </style>
</head>
<body>
  <header>
    <h1>03-danna</h1>
    <p id="typed"></p>
  </header>

  <section data-aos="fade-up">
    <h2>¿Qué es este proyecto?</h2>
    <p>03-danna es un proyecto creativo y funcional desarrollado con pasión por el código. Nace con el propósito de [describir qué soluciona o qué busca].</p>
  </section>

  <section data-aos="fade-up">
    <h2>Tecnologías utilizadas</h2>
    <div class="tech-icons">
      <i class="fab fa-html5"></i>
      <i class="fab fa-css3-alt"></i>
      <i class="fab fa-js"></i>
      <i class="fab fa-php"></i>
      <i class="fab fa-github"></i>
    </div>
  </section>

  <section data-aos="fade-up">
    <h2>Características principales</h2>
    <ul>
      <li>✅ Diseño atractivo y responsivo</li>
      <li>✅ Interacción dinámica con animaciones</li>
      <li>✅ Organización clara del código</li>
      <li>✅ Ideal para estudiantes y curiosos del desarrollo</li>
    </ul>
  </section>

  <section data-aos="fade-up">
    <h2>¿Cómo usarlo?</h2>
    <p>Clona el repositorio desde GitHub y abre el archivo <code>index.html</code>:</p>
    <pre style="background: #222; padding: 1rem; border-radius: 10px;">git clone https://github.com/tu-usuario/03-danna</pre>
  </section>

  <section data-aos="fade-up">
    <h2>Sobre mí</h2>
    <p>Mi nombre es Danna, estudiante de desarrollo web, apasionada por crear proyectos funcionales, seguros y con buen diseño. Este proyecto representa un paso más en mi camino como desarrolladora.</p>
  </section>

  <section data-aos="zoom-in" style="text-align:center">
    <a href="https://github.com/tu-usuario/03-danna" class="btn-github" target="_blank">
      <i class="fab fa-github"></i> Ver repositorio
    </a>
  </section>

  <a href="https://github.com/tu-usuario/03-danna" target="_blank" class="floating-button">
    <i class="fab fa-github"></i>
  </a>

  <footer>
    &copy; 2025 Danna | Proyecto 03-danna | Diseñado con 💙 y 💻
  </footer>

  <script>
    // Texto con máquina de escribir
    var typed = new Typed("#typed", {
      strings: [
        "Bienvenida a mi proyecto 💻",
        "Desarrollado con pasión ✨",
        "Explora, aprende y comparte 🚀"
      ],
      typeSpeed: 50,
      backSpeed: 30,
      loop: true
    });

    AOS.init();
  </script>
</body>
</html>
