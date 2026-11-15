[NOVA CREATIVE AGENCY WEB.html](https://github.com/user-attachments/files/34884990/NOVA.CREATIVE.AGENCY.WEB.html)[Uploading NOVA C<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>NOVA Creative Agency | Ideas que conectan, estrategias que convierten</title>
  <meta name="description" content="NOVA Creative Agency: agencia de publicidad especializada en campañas creativas e integrales que conectan con el público y generan resultados medibles.">
  <link rel="icon" href="data:image/svg+xml,%3Csvg xmlns='http://www.w3.org/2000/svg' viewBox='0 0 100 100'%3E%3Crect width='100' height='100' rx='22' fill='%23033356'/%3E%3Cpath d='M50 14l10.5 25.5L88 42l-21 18 6.5 27L50 72.5 26.5 87 33 60 12 42l27.5-2.5z' fill='%23fafafa'/%3E%3C/svg%3E">
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@400;500;600;700;800&family=Inter:wght@400;500&display=swap" rel="stylesheet">
  <style>
    :root {
      --azul: #033356;
      --morado: #602f94;
      --claro: #fafafa;
      --texto: #1b2433;
      --suave: #5b6578;
      --grad: linear-gradient(135deg, #033356 0%, #602f94 100%);
    }
    * { box-sizing: border-box; margin: 0; padding: 0; }
    html { scroll-behavior: smooth; }
    body {
      font-family: 'Inter', system-ui, sans-serif;
      color: var(--texto);
      background: var(--claro);
      line-height: 1.65;
    }
    h1, h2, h3, .logo { font-family: 'Poppins', sans-serif; }
    a { color: inherit; text-decoration: none; }
    .container { width: min(1100px, 92%); margin: 0 auto; }

    /* NAV */
    header {
      position: sticky; top: 0; z-index: 10;
      background: rgba(250,250,250,.9);
      backdrop-filter: blur(10px);
      border-bottom: 1px solid rgba(3,51,86,.08);
    }
    .nav { display: flex; align-items: center; justify-content: space-between; padding: 14px 0; }
    .logo { display: flex; align-items: center; gap: 10px; font-weight: 700; color: var(--azul); font-size: 1.15rem; }
    .logo svg { width: 34px; height: 34px; }
    .logo small { display: block; font-size: .62rem; font-weight: 500; letter-spacing: .18em; color: var(--morado); margin-top: -4px; }
    nav ul { display: flex; gap: 26px; list-style: none; font-size: .95rem; font-weight: 500; }
    nav a:hover { color: var(--morado); }
    .btn {
      display: inline-block; padding: 12px 26px; border-radius: 999px;
      font-family: 'Poppins', sans-serif; font-weight: 600; font-size: .95rem;
      transition: transform .2s, box-shadow .2s;
    }
    .btn:hover { transform: translateY(-2px); box-shadow: 0 10px 24px rgba(96,47,148,.3); }
    .btn-primary { background: var(--claro); color: var(--azul); }
    .btn-dark { background: var(--grad); color: var(--claro); }
    .btn-outline { border: 2px solid rgba(250,250,250,.7); color: var(--claro); }

    /* HERO */
    .hero {
      background: var(--grad); color: var(--claro);
      padding: 110px 0 120px; position: relative; overflow: hidden;
    }
    .hero::before, .hero::after {
      content: ''; position: absolute; border-radius: 50%; filter: blur(2px);
    }
    .hero::before { width: 420px; height: 420px; right: -120px; top: -140px; background: rgba(250,250,250,.07); }
    .hero::after { width: 260px; height: 260px; left: -80px; bottom: -110px; background: rgba(250,250,250,.06); }
    .hero .container { position: relative; z-index: 1; display: grid; grid-template-columns: 1.3fr 1fr; gap: 40px; align-items: center; }
    .eyebrow { letter-spacing: .2em; font-size: .78rem; text-transform: uppercase; opacity: .8; margin-bottom: 16px; }
    .hero h1 { font-size: clamp(2.2rem, 5vw, 3.6rem); line-height: 1.12; font-weight: 800; margin-bottom: 20px; }
    .hero p { max-width: 520px; opacity: .9; margin-bottom: 32px; font-size: 1.05rem; }
    .hero .actions { display: flex; gap: 14px; flex-wrap: wrap; }
    .hero-star { display: flex; justify-content: center; }
    .logo-card {
      background: var(--claro); border-radius: 32px; padding: 28px;
      width: min(340px, 90%); box-shadow: 0 24px 60px rgba(0,0,0,.3);
      animation: float 6s ease-in-out infinite;
    }
    .logo-card img { width: 100%; display: block; border-radius: 12px; }
    .logo-svg { text-align: center; }
    .logo-svg svg { width: 70%; display: block; margin: 0 auto 6px; }
    .logo-svg strong { display: block; font-family: 'Poppins'; font-weight: 800; font-size: 2.6rem; color: var(--azul); line-height: 1.1; letter-spacing: .02em; }
    .logo-svg span { font-family: 'Poppins'; font-weight: 500; font-size: .8rem; letter-spacing: .2em; color: var(--azul); }
    @keyframes float { 50% { transform: translateY(-12px); } }

    /* SECCIONES */
    section { padding: 90px 0; }
    .tag { color: var(--morado); font-weight: 600; letter-spacing: .15em; font-size: .8rem; text-transform: uppercase; }
    h2 { font-size: clamp(1.7rem, 3.5vw, 2.4rem); color: var(--azul); margin: 8px 0 18px; line-height: 1.2; }
    .lead { color: var(--suave); max-width: 720px; font-size: 1.05rem; }

    .about { display: grid; grid-template-columns: 1fr 1fr; gap: 56px; align-items: center; }
    .about-card {
      background: var(--grad); color: var(--claro); border-radius: 28px; padding: 40px;
    }
    .about-card h3 { margin-bottom: 12px; font-size: 1.25rem; }
    .about-card p { opacity: .92; font-size: .98rem; }

    /* MISION VISION */
    .mv { background: #fff; }
    .mv-grid { display: grid; grid-template-columns: 1fr 1fr; gap: 28px; margin-top: 40px; }
    .mv-card {
      border-radius: 24px; padding: 38px; border: 1px solid rgba(3,51,86,.1);
      background: var(--claro); transition: transform .25s, box-shadow .25s;
    }
    .mv-card:hover { transform: translateY(-5px); box-shadow: 0 18px 40px rgba(3,51,86,.12); }
    .mv-card .icon {
      width: 52px; height: 52px; border-radius: 14px; background: var(--grad);
      display: grid; place-items: center; margin-bottom: 18px; color: var(--claro); font-size: 1.4rem;
    }
    .mv-card h3 { color: var(--azul); margin-bottom: 10px; letter-spacing: .08em; }
    .mv-card p { color: var(--suave); }

    /* VALORES */
    .valores { display: flex; flex-wrap: wrap; gap: 14px; margin-top: 34px; }
    .valor {
      padding: 14px 26px; border-radius: 999px; background: #fff;
      border: 2px solid transparent;
      background-image: linear-gradient(#fff,#fff), var(--grad);
      background-origin: border-box; background-clip: padding-box, border-box;
      font-family: 'Poppins', sans-serif; font-weight: 600; color: var(--azul);
    }

    /* SERVICIOS */
    .servicios { background: var(--azul); color: var(--claro); }
    .servicios h2 { color: var(--claro); }
    .servicios .tag { color: #c9a8f0; }
    .servicios .lead { color: rgba(250,250,250,.75); }
    .cards { display: grid; grid-template-columns: repeat(auto-fit, minmax(250px, 1fr)); gap: 22px; margin-top: 46px; }
    .card {
      background: rgba(250,250,250,.06); border: 1px solid rgba(250,250,250,.12);
      border-radius: 20px; padding: 28px; transition: transform .25s, background .25s;
    }
    .card:hover { transform: translateY(-6px); background: rgba(96,47,148,.35); }
    .card .num { font-family: 'Poppins'; font-weight: 700; color: #c9a8f0; font-size: .9rem; }
    .card h3 { font-size: 1.08rem; margin: 8px 0 8px; }
    .card p { font-size: .92rem; color: rgba(250,250,250,.75); }

    /* RESULTADOS */
    .metricas { display: grid; grid-template-columns: repeat(auto-fit, minmax(200px, 1fr)); gap: 20px; margin-top: 40px; }
    .metrica { background: #fff; border-radius: 20px; padding: 28px; text-align: center; border: 1px solid rgba(3,51,86,.08); }
    .metrica strong { display: block; font-family: 'Poppins'; font-size: 1.3rem; color: var(--morado); margin-bottom: 6px; }
    .metrica span { color: var(--suave); font-size: .92rem; }

    /* CONTACTO */
    .contacto { background: var(--grad); color: var(--claro); text-align: center; }
    .contacto h2 { color: var(--claro); }
    .contacto .lead { color: rgba(250,250,250,.85); margin: 0 auto 34px; }
    form { max-width: 520px; margin: 0 auto; display: grid; gap: 14px; text-align: left; }
    input, textarea {
      width: 100%; padding: 14px 18px; border-radius: 14px; border: none;
      font-family: inherit; font-size: 1rem; background: var(--claro); color: var(--texto);
    }
    textarea { min-height: 120px; resize: vertical; }
    input:focus, textarea:focus { outline: 3px solid rgba(250,250,250,.5); }
    button { border: none; cursor: pointer; }

    footer { background: #022640; color: rgba(250,250,250,.7); text-align: center; padding: 28px 0; font-size: .88rem; }

    /* RESPONSIVE */
    @media (max-width: 820px) {
      nav ul { display: none; }
      .hero .container, .about, .mv-grid { grid-template-columns: 1fr; }
      .hero-star { order: -1; }
      .logo-card { width: 240px; padding: 20px; }
      section { padding: 64px 0; }
      .hero { padding: 70px 0 80px; }
    }
    @media (prefers-reduced-motion: reduce) {
      * { animation: none !important; transition: none !important; }
      html { scroll-behavior: auto; }
    }
  </style>
</head>
<body>

  <!-- Símbolo de la estrella (logo) reutilizable -->
  <svg width="0" height="0" style="position:absolute" aria-hidden="true">
    <defs>
      <linearGradient id="gradStar" x1="0" y1="0" x2="1" y2="1">
        <stop offset="0" stop-color="#033356"/>
        <stop offset="1" stop-color="#602f94"/>
      </linearGradient>
      <symbol id="mark" viewBox="0 0 200 200">
        <!-- Círculo -->
        <path d="M90.25 20.6A80 80 0 0 0 90.25 179.4" fill="none" stroke="#033356" stroke-width="7" stroke-linecap="butt"/>
        <path d="M109.75 20.6A80 80 0 0 1 109.75 179.4" fill="none" stroke="#033356" stroke-width="7" stroke-linecap="butt"/>
        <!-- Puntas diagonales -->
        <g id="diag"><polygon points="62,62 93,80 100,100 80,93" fill="#602f94"/></g>
        <polygon points="62,62 93,80 100,100 80,93" fill="#8a5bc2" transform="rotate(90 100 100)"/>
        <polygon points="62,62 93,80 100,100 80,93" fill="#033356" transform="rotate(180 100 100)"/>
        <polygon points="62,62 93,80 100,100 80,93" fill="#602f94" transform="rotate(270 100 100)"/>
        <!-- Puntas cardinales -->
        <polygon points="100,6 100,100 87,87" fill="#602f94"/>
        <polygon points="100,6 100,100 113,87" fill="#8a5bc2"/>
        <polygon points="6,100 100,100 87,87" fill="#602f94"/>
        <polygon points="6,100 100,100 87,113" fill="#8a5bc2"/>
        <polygon points="194,100 100,100 113,87" fill="#2a5a85"/>
        <polygon points="194,100 100,100 113,113" fill="#033356"/>
        <polygon points="100,194 100,100 87,113" fill="#033356"/>
        <polygon points="100,194 100,100 113,113" fill="#2a5a85"/>
      </symbol>
    </defs>
  </svg>

  <header>
    <div class="container nav">
      <a href="#inicio" class="logo" aria-label="NOVA Creative Agency">
        <svg viewBox="0 0 200 200"><use href="#mark"/></svg>
        <span>NOVA<small>CREATIVE AGENCY</small></span>
      </a>
      <nav>
        <ul>
          <li><a href="#nosotros">Nosotros</a></li>
          <li><a href="#mision">Misión y visión</a></li>
          <li><a href="#servicios">Servicios</a></li>
          <li><a href="#resultados">Resultados</a></li>
        </ul>
      </nav>
      <a href="#contacto" class="btn btn-dark">Contáctanos</a>
    </div>
  </header>

  <main>
    <!-- HERO -->
    <section class="hero" id="inicio">
      <div class="container">
        <div>
          <p class="eyebrow">Agencia de publicidad</p>
          <h1>Ideas que conectan, estrategias que convierten.</h1>
          <p>Desarrollamos campañas creativas e integrales para empresas que buscan fortalecer su presencia en el mercado y conectar emocionalmente con su público.</p>
          <div class="actions">
            <a href="#contacto" class="btn btn-primary">Inicia tu campaña</a>
            <a href="#servicios" class="btn btn-outline">Ver servicios</a>
          </div>
        </div>
        <div class="hero-star">
          <div class="logo-card">
            <!-- Si subes logo.png al repositorio, se usa esa imagen; si no, se muestra la versión SVG -->
            <img src="logo.png" alt="Logotipo de NOVA Creative Agency"
                 onerror="this.style.display='none';this.nextElementSibling.style.display='block'">
            <div class="logo-svg" style="display:none" role="img" aria-label="Logotipo de NOVA Creative Agency">
              <svg viewBox="0 0 200 200"><use href="#mark"/></svg>
              <strong>NOVA</strong>
              <span>CREATIVE AGENCY</span>
            </div>
          </div>
        </div>
      </div>
    </section>

    <!-- NOSOTROS -->
    <section id="nosotros">
      <div class="container about">
        <div>
          <span class="tag">Quiénes somos</span>
          <h2>Creatividad con estrategia y resultados medibles</h2>
          <p class="lead">NOVA Creative Agency combina investigación, creatividad y estrategias de comunicación para crear campañas que conectan emocionalmente con el público y generan resultados medibles.</p>
        </div>
        <div class="about-card">
          <h3>Nuestro logotipo</h3>
          <p>Representa el nacimiento de nuevas ideas. La estrella simboliza innovación, crecimiento y creatividad, mientras que la combinación de azul y morado comunica confianza, estrategia e imaginación.</p>
        </div>
      </div>
    </section>

    <!-- MISIÓN Y VISIÓN -->
    <section class="mv" id="mision">
      <div class="container">
        <span class="tag">Nuestra esencia</span>
        <h2>Misión y visión</h2>
        <div class="mv-grid">
          <article class="mv-card">
            <div class="icon">🎯</div>
            <h3>MISIÓN</h3>
            <p>Desarrollar campañas publicitarias innovadoras que ayuden a las marcas a conectar con su público mediante estrategias creativas, contenido de valor y soluciones de comunicación orientadas a resultados.</p>
          </article>
          <article class="mv-card">
            <div class="icon">🚀</div>
            <h3>VISIÓN</h3>
            <p>Ser una agencia reconocida por crear campañas publicitarias que inspiren, generen impacto y aporten valor a las marcas en el entorno digital y tradicional.</p>
          </article>
        </div>

        <h2 style="margin-top:64px">Valores</h2>
        <div class="valores">
          <span class="valor">Creatividad</span>
          <span class="valor">Innovación</span>
          <span class="valor">Honestidad</span>
          <span class="valor">Trabajo en equipo</span>
          <span class="valor">Compromiso</span>
          <span class="valor">Orientación a resultados</span>
        </div>
      </div>
    </section>

    <!-- SERVICIOS -->
    <section class="servicios" id="servicios">
      <div class="container">
        <span class="tag">Qué hacemos</span>
        <h2>Servicios de publicidad y comunicación estratégica</h2>
        <p class="lead">Soluciones integrales para que tu marca se vea, se escuche y se recuerde.</p>
        <div class="cards">
          <article class="card"><span class="num">01</span><h3>Campañas publicitarias</h3><p>Desarrollo de campañas creativas e integrales alineadas a los objetivos de tu marca.</p></article>
          <article class="card"><span class="num">02</span><h3>Identidad corporativa y branding</h3><p>Creación de una identidad visual sólida y coherente que distingue a tu empresa.</p></article>
          <article class="card"><span class="num">03</span><h3>Administración de redes sociales</h3><p>Gestión de comunidad y contenido para fortalecer tu presencia digital.</p></article>
          <article class="card"><span class="num">04</span><h3>Contenido audiovisual</h3><p>Producción de video y material audiovisual que cuenta la historia de tu marca.</p></article>
          <article class="card"><span class="num">05</span><h3>Diseño gráfico</h3><p>Piezas gráficas atractivas y funcionales para medios digitales e impresos.</p></article>
          <article class="card"><span class="num">06</span><h3>Planificación de medios</h3><p>Selección estratégica de canales para llegar al público correcto.</p></article>
          <article class="card"><span class="num">07</span><h3>Publicidad digital</h3><p>Gestión de campañas en plataformas como Meta Ads y Google Ads.</p></article>
          <article class="card"><span class="num">08</span><h3>Investigación de mercados</h3><p>Análisis del comportamiento del consumidor para tomar mejores decisiones.</p></article>
        </div>
      </div>
    </section>

    <!-- RESULTADOS -->
    <section id="resultados">
      <div class="container">
        <span class="tag">Medimos lo que hacemos</span>
        <h2>Evaluación del desempeño de cada campaña</h2>
        <p class="lead">Utilizamos indicadores que nos permiten medir el impacto real de tu inversión y mejorar de forma continua.</p>
        <div class="metricas">
          <div class="metrica"><strong>Alcance</strong><span>A cuántas personas llega tu mensaje</span></div>
          <div class="metrica"><strong>Interacción</strong><span>Cómo responde tu audiencia</span></div>
          <div class="metrica"><strong>Retorno de inversión</strong><span>El valor que genera cada peso invertido</span></div>
        </div>
      </div>
    </section>

    <!-- CONTACTO -->
    <section class="contacto" id="contacto">
      <div class="container">
        <span class="tag" style="color:#e3d0fa">Hablemos</span>
        <h2>Creemos juntos tu próxima gran campaña</h2>
        <p class="lead">Cuéntanos sobre tu marca y te contactaremos para diseñar una estrategia a tu medida.</p>
        <!-- Cambia tu@correo.com por el correo real de la agencia -->
        <form action="mailto:tu@correo.com" method="post" enctype="text/plain">
          <input type="text" name="Nombre" placeholder="Tu nombre" required>
          <input type="email" name="Correo" placeholder="Tu correo electrónico" required>
          <textarea name="Mensaje" placeholder="Cuéntanos sobre tu proyecto" required></textarea>
          <button type="submit" class="btn btn-primary">Enviar mensaje</button>
        </form>
      </div>
    </section>
  </main>

  <footer>
    <div class="container">
      © <span id="year"></span> NOVA Creative Agency. Todos los derechos reservados.
    </div>
  </footer>

  <script>
    document.getElementById('year').textContent = new Date().getFullYear();
  </script>
</body>
</html>
REATIVE AGENCY WEB.html…]()

