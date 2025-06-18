# Epo202-
<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Escuela Preparatoria Oficial No. 202</title>
  <style>
    body {
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
      background: linear-gradient(to bottom right, #f0f4f8, #d9e2ec);
      color: #333;
      margin: 0;
      padding: 0;
    }

    header {
      background-color: #004080;
      color: #fff;
      padding: 20px;
      text-align: center;
      position: sticky;
      top: 0;
      z-index: 1000;
    }

    nav {
      background-color: #003060;
      display: flex;
      justify-content: center;
      flex-wrap: wrap;
      gap: 10px;
      padding: 10px;
      position: sticky;
      top: 64px;
      z-index: 999;
    }

    nav a {
      color: white;
      text-decoration: none;
      padding: 10px 15px;
      border-radius: 5px;
      transition: background-color 0.3s ease;
    }

    nav a:hover,
    nav a.active {
      background-color: #0007;
    }

    section {
      max-width: 900px;
      margin: 40px auto;
      padding: 20px;
      background: white;
      border-radius: 12px;
      box-shadow: 0 4px 12px rgba(0, 0, 0, 0.1);
    }

    .carousel-container {
      overflow: hidden;
    }

    .carousel-slide {
      display: flex;
      transition: transform 0.5s ease-in-out;
    }

    .carousel-item {
      min-width: 100%;
      text-align: center;
    }

    .carousel-item img {
      width: 100%;
      max-height: 500px;
      object-fit: cover;
    }

    .carousel-description {
      padding: 15px;
      background-color: #f0f0f0;
    }

    .carousel-dots {
      text-align: center;
      margin: 15px 0;
    }

    .carousel-dots span {
      display: inline-block;
      width: 12px;
      height: 12px;
      margin: 5px;
      background-color: #aaa;
      border-radius: 50%;
      cursor: pointer;
    }

    .carousel-dots .active {
      background-color: #004080;
    }

    .materias-nav {
      display: flex;
      justify-content: center;
      flex-wrap: wrap;
      gap: 10px;
      margin-bottom: 20px;
    }

    .materias-nav button {
      background-color: #0073e6;
      color: white;
      border: none;
      padding: 10px 20px;
      border-radius: 5px;
      cursor: pointer;
    }

    .materias-nav button.active {
      background-color: #004080;
    }

    .materia {
      display: none;
    }

    .materia.active {
      display: block;
    }

    @media (max-width: 600px) {
      .carousel-item img {
        height: 250px;
      }

      .carousel-description {
        font-size: 0.9rem;
      }
    }
  </style>
</head>
<body>

  <header>
    <h1>Escuela Preparatoria Oficial No. 202</h1>
    <h2>¡PREPÁRATE PARA UN BUEN FUTURO!</h2>
  </header>

  <nav>
    <a href="#inicio" class="active">Inicio</a>
    <a href="#instalaciones">Instalaciones</a>
    <a href="#materias">Materias</a>
    <a href="#contacto">Contacto</a>
  </nav>

  <!-- INICIO -->
  <section id="inicio">
    <h2>Bienvenido</h2>
    <p>La Escuela Preparatoria Oficial No. 202 te ofrece una educación de calidad para prepararte hacia un gran futuro.</p>
  </section>

  <!-- INSTALACIONES -->
  <section id="instalaciones">
    <h2>Instalaciones</h2>
    <div class="carousel-container">
      <div class="carousel-slide" id="carousel-slide">
        <div class="carousel-item">
          <img src="https://i.ibb.co/JJG2pFF/imagen1.jpg" alt="Entrada principal">
          <div class="carousel-description">Entrada principal :Parte principal de la institucion ubicada al frente de la misma .</div>
        </div>
        <div class="carousel-item">
          <img src="https://i.ibb.co/ZpdwCRZb/imagen2.jpg" alt="Arco techo">
          <div class="carousel-description">Arco techo : Area donde se realizan actividades culturales y fisicas de la institucion.</div>
        </div>
        <div class="carousel-item">
          <img src="https://i.ibb.co/xt3f5LJ1/imagen3.jpg" alt="Arco techo">
          <div class="carousel-description">Aulas:Area principal donde se desarrolla el aprendizaje de cada alumno contando con instalaciones y materiales.</div>
        </div>
        <div class="carousel-item">
          <img src="https://i.ibb.co/Q7FsmmSp/imagen4.jpg" alt="Baños">
          <div class="carousel-description">Baños:Servicio fundamental en la institucion para satisfacer las necesidades del alunm@</div>
        </div>
     </div>
      <div class="carousel-dots" id="carousel-dots"></div>
    </div>
  </section>
  <!-- CONVOCATORIA -->
  </nav>

  <div id="convocatori" class="content">
    <h2>Convocatoria</h2>
    <p>Puedes consultar la convocatoria completa en el siguiente enlace:</p>
    <p>
      <a href="https://www.facebook.com/share/1JAfjiXVYQ/" target="_blank">
        Ver Convocatoria en Facebook
      </a>
    </p>
  </div>
<section id="convocatoria">
  <h2>Convocatoria de Ingreso 2025</h2>
  <p>La Escuela Preparatoria Oficial No. 202 invita a todos los estudiantes interesados en cursar el nivel medio superior a participar en su proceso de admisión para el ciclo escolar 2025.</p>

  <h3>Requisitos:</h3>
  <ul>
    <li>Acta de nacimiento (original y copia)</li>
    <li>CURP actualizada</li>
    <li>Certificado de secundaria o constancia de estudios</li>
    <li>2 fotografías tamaño infantil</li>
    <li>Comprobante de domicilio reciente</li>
  </ul>

  <h3>Fechas importantes:</h3>
  <ul>
    <li>Inicio de registro: 1 de marzo de 2025</li>
    <li>Cierre de registro: 30 de abril de 2025</li>
    <li>Examen de admisión: 15 de mayo de 2025</li>
    <li>Publicación de resultados: 31 de mayo de 2025</li>
  </ul>

  <p>Para más información, comunícate al correo: <strong>convocatoria@preparatoria202.edu.mx</strong></p>
</section>

  <!-- MATERIAS -->
  <section id="materias">
    <h2>Materias</h2>
    <div class="materias-nav">
      <button class="active" data-materia="matematicas">Matemáticas</button>
      <button data-materia="fisica">Física</button>
      <button data-materia="quimica">Química</button>
      <button data-materia="literatura">Literatura</button>
      <button data-materia="historia">Historia</button>
    </div>
    <div class="materia-container">
      <div id="matematicas" class="materia active">
        <h3>Matemáticas</h3>
        <p>Se desarrollan habilidades en álgebra, geometría, cálculo y estadística, aplicando la lógica y el razonamiento en la resolución de problemas reales.</p>
      </div>
      <div id="fisica" class="materia">
        <h3>Física</h3>
        <p>Estudio de las leyes del movimiento, la energía, el sonido y la luz, incluyendo experimentos prácticos para comprender fenómenos naturales.</p>
      </div>
      <div id="quimica" class="materia">
        <h3>Química</h3>
        <p>Aprendizaje sobre la materia, los elementos, compuestos y reacciones químicas que forman parte de la vida diaria y los procesos industriales.</p>
      </div>
      <div id="literatura" class="materia">
        <h3>Literatura</h3>
        <p>Exploración de obras literarias clásicas y modernas para desarrollar comprensión lectora, análisis crítico y apreciación artística del lenguaje.</p>
      </div>
      <div id="historia" class="materia">
        <h3>Historia</h3>
        <p>Estudio de los principales eventos, culturas y procesos que han influido en la humanidad, promoviendo el pensamiento crítico y la reflexión.</p>
      </div>
    </div>
  </section>

  <!-- CONTACTO -->
  <section id="contacto">
    <h2>Contacto</h2>
    <p>Correo: contacto@preparatoria202.edu.mx</p>
    <p>Teléfono: (722) 123 4567</p>
    <p>Dirección: Calpulalpan , Municipio Jilotepec, Estado de México</p>
    <!-- Mapa -->
  <div id="mapa" class="container mt-5">
    <h2 class="text-center text-primary">Encuéntranos en el mapa</h2>
    <iframe class="w-100" height="300" style="border:0;" loading="lazy" allowfullscreen
      src="https://www.google.com/maps?q=Preparatoria+202+Calpulalpan&output=embed"></iframe>
  </div>
  </section>

  <!-- SCRIPTS -->
  <script>
    // Carrusel
    const slide = document.getElementById('carousel-slide');
    const dotsContainer = document.getElementById('carousel-dots');
    const items = slide.querySelectorAll('.carousel-item');
    const total = items.length;
    let index = 0;

    for (let i = 0; i < total; i++) {
      const dot = document.createElement('span');
      dot.addEventListener('click', () => goToSlide(i));
      dotsContainer.appendChild(dot);
    }

    const dots = dotsContainer.querySelectorAll('span');

    function updateCarousel() {
      slide.style.transform = `translateX(-${index * 100}%)`;
      dots.forEach(dot => dot.classList.remove('active'));
      dots[index].classList.add('active');
    }

    function nextSlide() {
      index = (index + 1) % total;
      updateCarousel();
    }

    function goToSlide(i) {
      index = i;
      updateCarousel();
    }

    updateCarousel();
    setInterval(nextSlide, 5000);

    // Materias
    const botones = document.querySelectorAll(".materias-nav button");
    const secciones = document.querySelectorAll(".materia");

    botones.forEach(boton => {
      boton.addEventListener("click", () => {
        botones.forEach(b => b.classList.remove("active"));
        boton.classList.add("active");

        const idMateria = boton.dataset.materia;
        secciones.forEach(seccion => {
          seccion.classList.toggle("active", seccion.id === idMateria);
        });
      });
    });

    // Navegación activa
    const navLinks = document.querySelectorAll("nav a");
    window.addEventListener("scroll", () => {
      let current = "";
      document.querySelectorAll("section").forEach(sec => {
        const secTop = sec.offsetTop - 100;
        if (scrollY >= secTop) current = sec.getAttribute("id");
      });
      navLinks.forEach(link => {
        link.classList.remove("active");
        if (link.getAttribute("href").includes(current)) {
          link.classList.add("active");
        }
      });
    });
  </script>
</body>
</html>

<html>
<head>
  <meta http-equiv="CONTENT-TYPE" content="text/html; charset=UTF-8">
  <title>Preparate para el futuro!!</title>
</head>
<body>
  <h1>
    EPO 202
  </h1>
</body>
</html>
