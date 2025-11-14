<!DOCTYPE html>
<html lang="es">
<head>
<meta charset="utf-8" />
<meta name="viewport" content="width=device-width,initial-scale=1" />
<title>Aula Virtual Interactiva - Sistema Nervioso (Grado 6°)</title>
<style>
  :root{
    --primary:#005bbb;
    --dark:#003f7d;
    --bg:#f3f6fa;
    --card:#ffffff;
  }
  html,body{height:100%;margin:0;font-family:Inter, Arial, sans-serif;background:var(--bg);color:#123;}
  header{background:var(--primary);color:#fff;padding:36px 18px;text-align:center;}
  header h1{margin:0;font-size:28px;line-height:1.1;}
  nav{display:flex;gap:12px;justify-content:center;padding:12px;background:var(--dark);}
  nav a{color:#fff;text-decoration:none;font-weight:600;padding:6px 10px;border-radius:6px}
  .container{max-width:1100px;margin:22px auto;padding:0 16px;}
  section.card{background:var(--card);border-radius:12px;padding:20px;margin-bottom:18px;box-shadow:0 6px 18px rgba(10,20,40,0.06);}
  h2{color:var(--dark);margin-top:0}
  .grid{display:grid;grid-template-columns:1fr;gap:18px}
  @media(min-width:900px){ .grid{grid-template-columns:1fr 360px} }
  .banner{display:flex;flex-direction:column;gap:12px}
  .banner .lead{font-size:16px}
  .illustration{display:flex;align-items:center;justify-content:center;padding:10px}
  ul{margin:8px 0 8px 20px}
  .actividad,.evaluacion,.recurso{border-left:6px solid var(--primary);background:#f6fbff;padding:12px;border-radius:8px}
  footer{background:var(--primary);color:#fff;text-align:center;padding:16px;margin-top:18px}
  .small{font-size:14px;color:#456}
  .embed-box{border:1px dashed #d8e6ff;border-radius:8px;padding:12px;background:#fbfeff}
  .btn{display:inline-block;padding:8px 12px;background:var(--primary);color:#fff;border-radius:8px;text-decoration:none}
</style>
</head>
<body>

<header>
  <h1>Aula Virtual Interactiva — Sistema Nervioso (Grado 6°)</h1>
  <p class="small">Diseñado por: Estudiante de Licenciatura en Ciencias Naturales y Educación Ambiental</p>
</header>

<nav>
  <a href="#intro">Introducción</a>
  <a href="#contenido">Contenido</a>
  <a href="#actividades">Actividades</a>
  <a href="#evaluacion">Evaluación</a>
  <a href="#recursos">Recursos</a>
</nav>

<main class="container">
  <section id="intro" class="card">
    <div class="grid">
      <div class="banner">
        <h2>Introducción</h2>
        <p class="lead">Bienvenidos al Aula Virtual del Sistema Nervioso. Aquí encontrarás lecciones, videos, actividades y evaluaciones interactivas pensadas para estudiantes de 6° grado.</p>
        <p class="small">Propósito: Promover un aprendizaje activo, autónomo y significativo sobre el funcionamiento y cuidado del sistema nervioso.</p>
      </div>
      <div class="illustration">
        <img src="https://upload.wikimedia.org/wikipedia/commons/6/6f/Human_nervous_system_diagram-es.svg" alt="Ilustración sistema nervioso" style="max-width:100%;border-radius:8px;">
      </div>
    </div>
  </section>

  <section id="contenido" class="card">
    <h2>Contenido</h2>
    <div class="grid">
      <div>
        <h3>1. ¿Qué es el sistema nervioso?</h3>
        <p>El sistema nervioso es una red de células (neuronas y células gliales) que coordina las funciones del cuerpo y permite percibir y reaccionar ante estímulos.</p>

        <h3>2. Partes principales</h3>
        <ul>
          <li><strong>Sistema nervioso central:</strong> encéfalo y médula espinal.</li>
          <li><strong>Sistema nervioso periférico:</strong> nervios y ganglios.</li>
        </ul>

        <h3>3. Neuronas y transmisión</h3>
        <p>Las neuronas se comunican mediante impulsos eléctricos y neurotransmisores. Ver actividades para experimentar con simulaciones.</p>
      </div>

      <div>
        <h4>Video explicativo</h4>
        <div class="embed-box">
          <p>Pega aquí el enlace de YouTube o el código embed de tu video.</p>
        </div>

        <h4>Infografía</h4>
        <div class="embed-box">
          <p>Pega aquí el enlace o código de inserción de tu infografía (Canva).</p>
        </div>
      </div>
    </div>
  </section>

  <section id="actividades" class="card">
    <h2>Actividades</h2>
    <div class="actividad">
      <h3>Actividad 1 — Mapa conceptual</h3>
      <p>Completa el mapa conceptual: incluye las partes del sistema nervioso y sus funciones.</p>
    </div>

    <div class="actividad">
      <h3>Actividad 2 — Podcast</h3>
      <p>Escucha el podcast corto y responde las preguntas en el foro.</p>
    </div>

    <div class="actividad">
      <h3>Actividad 3 — Foro</h3>
      <p>Responde: <em>¿Por qué es importante cuidar nuestro sistema nervioso?</em></p>
    </div>
  </section>

  <section id="evaluacion" class="card">
    <h2>Evaluación</h2>
    <div class="evaluacion">
      <h3>Cuestionario gamificado</h3>
      <p>Inserta aquí tu Kahoot o Genially.</p>
    </div>

    <div class="evaluacion">
      <h3>Autoevaluación</h3>
      <p>Escribe un párrafo sobre lo aprendido.</p>
    </div>
  </section>

  <section id="recursos" class="card">
    <h2>Recursos adicionales</h2>
    <div class="recurso">
      <p>Artículo recomendado: “Funciones del sistema nervioso”.</p>
    </div>
    <div class="recurso">
      <p>Video recomendado de YouTube.</p>
    </div>
  </section>
</main>

<footer>
  Aula Virtual creada para la Práctica 6 — Licenciatura en Ciencias Naturales y Educación Ambiental
</footer>

</body>
</html>
