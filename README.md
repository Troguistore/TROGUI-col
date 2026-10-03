<!doctype html>
<html lang="es">
<head>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <meta name="description" content="Hidrolavadora inalámbrica 48V portátil: limpia autos, motos, patios y más. Pago contra entrega y garantía de 1 año.">
  <title>Hidrolavadora Inalámbrica 48V | Limpieza portátil</title>

  <style>
    :root {
      --black: #0b0c0f;
      --black-soft: #17191d;
      --gray: #5e646d;
      --gray-light: #f2f3f5;
      --white: #ffffff;
      --orange: #ff6800;
      --orange-dark: #e94f00;
      --green: #0c9a5a;
      --shadow: 0 18px 42px rgba(0, 0, 0, .12);
      --radius: 22px;
    }

    * {
      box-sizing: border-box;
    }

    html {
      scroll-behavior: smooth;
    }

    body {
      margin: 0;
      color: var(--black);
      background: var(--white);
      font-family: Arial, Helvetica, sans-serif;
      line-height: 1.45;
    }

    img {
      display: block;
      width: 100%;
      height: auto;
    }

    a {
      color: inherit;
      text-decoration: none;
    }

    .container {
      width: min(1120px, calc(100% - 32px));
      margin: 0 auto;
    }

    .announcement {
      background: var(--black);
      color: var(--white);
      text-align: center;
      padding: 10px 16px;
      font-size: 13px;
      font-weight: 800;
      letter-spacing: .2px;
    }

    .announcement span {
      color: #ff8a3d;
    }

    header {
      position: sticky;
      top: 0;
      z-index: 20;
      background: rgba(255, 255, 255, .94);
      border-bottom: 1px solid #eceef1;
      backdrop-filter: blur(10px);
    }

    .nav {
      min-height: 68px;
      display: flex;
      align-items: center;
      justify-content: space-between;
      gap: 20px;
    }

    .brand {
      display: inline-flex;
      align-items: center;
      gap: 9px;
      font-size: 19px;
      font-weight: 950;
      font-style: italic;
      letter-spacing: -.5px;
      text-transform: uppercase;
    }

    .brand-mark {
      display: grid;
      width: 34px;
      height: 34px;
      place-items: center;
      background: var(--orange);
      color: white;
      border-radius: 9px;
      font-size: 20px;
    }

    .nav-benefit {
      color: var(--gray);
      font-size: 13px;
      font-weight: 700;
    }

    .btn {
      display: inline-flex;
      align-items: center;
      justify-content: center;
      min-height: 52px;
      padding: 14px 22px;
      border: 0;
      border-radius: 12px;
      cursor: pointer;
      font-size: 15px;
      font-weight: 900;
      text-align: center;
      transition: transform .2s ease, background .2s ease, box-shadow .2s ease;
    }

    .btn:hover {
      transform: translateY(-2px);
    }

    .btn-primary {
      color: var(--white);
      background: linear-gradient(135deg, var(--orange), #ff8a00);
      box-shadow: 0 10px 24px rgba(255, 104, 0, .25);
    }

    .btn-dark {
      color: var(--white);
      background: var(--black);
    }

    .btn-full {
      width: 100%;
    }

    .hero {
      overflow: hidden;
      padding: 50px 0 32px;
      background:
        radial-gradient(circle at 92% 10%, rgba(255, 104, 0, .16), transparent 24%),
        linear-gradient(180deg, #fff 0%, #f7f7f8 100%);
    }

    .hero-grid {
      display: grid;
      grid-template-columns: 1.05fr .95fr;
      align-items: center;
      gap: 44px;
    }

    .eyebrow {
      display: inline-flex;
      align-items: center;
      gap: 8px;
      margin-bottom: 15px;
      color: var(--orange-dark);
      font-size: 13px;
      font-weight: 950;
      letter-spacing: 1px;
      text-transform: uppercase;
    }

    .eyebrow::before {
      width: 10px;
      height: 10px;
      content: "";
      background: var(--orange);
      border-radius: 50%;
      box-shadow: 0 0 0 5px rgba(255, 104, 0, .14);
    }

    h1,
    h2,
    h3,
    p {
      margin-top: 0;
    }

    h1 {
      max-width: 690px;
      margin-bottom: 18px;
      font-size: clamp(39px, 5vw, 66px);
      font-style: italic;
      font-weight: 950;
      line-height: .98;
      letter-spacing: -2.8px;
      text-transform: uppercase;
    }

    h1 span {
      color: var(--orange);
    }

    .hero-text {
      max-width: 550px;
      margin-bottom: 26px;
      color: #454a51;
      font-size: 18px;
    }

    .hero-actions {
      display: flex;
      flex-wrap: wrap;
      gap: 12px;
      margin-bottom: 24px;
    }

    .trust-row {
      display: flex;
      flex-wrap: wrap;
      gap: 15px;
      color: #454a51;
      font-size: 13px;
      font-weight: 800;
    }

    .trust-row div {
      display: flex;
      align-items: center;
      gap: 7px;
    }

    .check {
      display: grid;
      width: 20px;
      height: 20px;
      place-items: center;
      color: white;
      background: var(--green);
      border-radius: 50%;
      font-size: 12px;
    }

    .hero-image-wrap {
      position: relative;
    }

    .hero-image-wrap::before {
      position: absolute;
      z-index: 0;
      top: 4%;
      right: -7%;
      bottom: 3%;
      left: 7%;
      content: "";
      background: var(--orange);
      border-radius: 36px;
      transform: rotate(4deg);
    }

    .hero-image {
      position: relative;
      z-index: 1;
      overflow: hidden;
      border-radius: 30px;
      box-shadow: var(--shadow);
    }

    .badges {
      display: grid;
      grid-template-columns: repeat(3, 1fr);
      gap: 12px;
      margin-top: 30px;
    }

    .badge {
      min-height: 91px;
      padding: 16px 14px;
      background: var(--white);
      border: 1px solid #ebedf0;
      border-radius: 15px;
      box-shadow: 0 8px 20px rgba(0, 0, 0, .05);
    }

    .badge-icon {
      margin-bottom: 8px;
      color: var(--orange);
      font-size: 22px;
    }

    .badge strong {
      display: block;
      margin-bottom: 3px;
      font-size: 13px;
      text-transform: uppercase;
    }

    .badge span {
      color: var(--gray);
      font-size: 12px;
    }

    .section {
      padding: 82px 0;
    }

    .section-gray {
      background: var(--gray-light);
    }

    .section-title {
      max-width: 770px;
      margin: 0 auto 15px;
      font-size: clamp(30px, 4vw, 48px);
      font-style: italic;
      font-weight: 950;
      line-height: 1;
      letter-spacing: -1.6px;
      text-align: center;
      text-transform: uppercase;
    }

    .section-title span {
      color: var(--orange);
    }

    .section-subtitle {
      max-width: 700px;
      margin: 0 auto 38px;
      color: var(--gray);
      font-size: 17px;
      text-align: center;
    }

    .features {
      display: grid;
      grid-template-columns: repeat(4, 1fr);
      gap: 16px;
    }

    .feature-card {
      padding: 23px 19px;
      background: white;
      border-radius: 18px;
      box-shadow: 0 9px 28px rgba(0, 0, 0, .06);
    }

    .feature-card .number {
      display: flex;
      width: 42px;
      height: 42px;
      align-items: center;
      justify-content: center;
      margin-bottom: 16px;
      color: var(--white);
      background: var(--orange);
      border-radius: 12px;
      font-size: 20px;
      font-weight: 950;
    }

    .feature-card h3 {
      margin-bottom: 8px;
      font-size: 17px;
      text-transform: uppercase;
    }

    .feature-card p {
      margin-bottom: 0;
      color: var(--gray);
      font-size: 14px;
    }

    .visual-grid {
      display: grid;
      grid-template-columns: 1fr 1fr;
      gap: 24px;
      align-items: center;
    }

    .visual-copy h2 {
      margin-bottom: 18px;
      font-size: clamp(31px, 4vw, 49px);
      font-style: italic;
      font-weight: 950;
      line-height: 1;
      letter-spacing: -1.5px;
      text-transform: uppercase;
    }

    .visual-copy h2 span {
      color: var(--orange);
    }

    .visual-copy p {
      color: var(--gray);
      font-size: 17px;
    }

    .visual-list {
      display: grid;
      gap: 15px;
      margin: 26px 0 30px;
    }

    .visual-list-item {
      display: flex;
      align-items: flex-start;
      gap: 13px;
    }

    .visual-list-item strong {
      display: block;
      margin-bottom: 2px;
      font-size: 15px;
    }

    .visual-list-item span {
      display: block;
      color: var(--gray);
      font-size: 14px;
    }

    .visual-image {
      overflow: hidden;
      border-radius: var(--radius);
      box-shadow: var(--shadow);
    }

    .use-grid {
      display: grid;
      grid-template-columns: repeat(4, 1fr);
      gap: 16px;
    }

    .use-card {
      overflow: hidden;
      background: white;
      border-radius: 17px;
      box-shadow: 0 10px 26px rgba(0, 0, 0, .07);
    }

    .use-card img {
      aspect-ratio: 1.15 / 1;
      object-fit: cover;
      object-position: center;
    }

    .use-card-content {
      padding: 17px;
    }

    .use-card h3 {
      margin-bottom: 7px;
      font-size: 16px;
      text-transform: uppercase;
    }

    .use-card p {
      margin-bottom: 0;
      color: var(--gray);
      font-size: 14px;
    }

    .included {
      display: grid;
      grid-template-columns: .85fr 1.15fr;
      gap: 40px;
      align-items: center;
    }

    .included-image {
      overflow: hidden;
      border-radius: 25px;
      box-shadow: var(--shadow);
    }

    .included-copy h2 {
      margin-bottom: 15px;
      font-size: clamp(31px, 4vw, 48px);
      font-style: italic;
      font-weight: 950;
      line-height: 1;
      letter-spacing: -1.5px;
      text-transform: uppercase;
    }

    .included-copy h2 span {
      color: var(--orange);
    }

    .included-list {
      display: grid;
      grid-template-columns: 1fr 1fr;
      gap: 12px;
      padding: 0;
      margin: 25px 0 30px;
      list-style: none;
    }

    .included-list li {
      display: flex;
      align-items: center;
      gap: 9px;
      padding: 12px;
      background: var(--gray-light);
      border-radius: 11px;
      font-size: 14px;
      font-weight: 750;
    }

    .order-section {
      padding: 82px 0;
      color: white;
      background:
        radial-gradient(circle at 0% 0%, rgba(255, 104, 0, .42), transparent 28%),
        #0b0c0f;
    }

    .order-grid {
      display: grid;
      grid-template-columns: 1fr .88fr;
      gap: 48px;
      align-items: center;
    }

    .order-copy h2 {
      margin-bottom: 18px;
      font-size: clamp(36px, 4vw, 53px);
      font-style: italic;
      font-weight: 950;
      line-height: 1;
      letter-spacing: -1.7px;
      text-transform: uppercase;
    }

    .order-copy h2 span {
      color: #ff7c24;
    }

    .order-copy > p {
      max-width: 580px;
      color: #d1d4d8;
      font-size: 17px;
    }

    .order-benefits {
      display: grid;
      gap: 14px;
      margin-top: 28px;
    }

    .order-benefit {
      display: flex;
      align-items: center;
      gap: 12px;
      color: #f7f7f7;
      font-size: 14px;
      font-weight: 750;
    }

    .order-form {
      padding: 27px;
      color: var(--black);
      background: white;
      border-radius: 21px;
      box-shadow: 0 20px 42px rgba(0, 0, 0, .28);
    }

    .order-form h3 {
      margin-bottom: 6px;
      font-size: 24px;
      text-transform: uppercase;
    }

    .order-form > p {
      margin-bottom: 20px;
      color: var(--gray);
      font-size: 14px;
    }

    .field {
      display: grid;
      gap: 6px;
      margin-bottom: 14px;
    }

    label {
      font-size: 13px;
      font-weight: 800;
    }

    input,
    select {
      width: 100%;
      padding: 14px;
      outline: none;
      color: var(--black);
      background: #fafafa;
      border: 1px solid #dfe2e5;
      border-radius: 10px;
      font: inherit;
    }

    input:focus,
    select:focus {
      border-color: var(--orange);
      box-shadow: 0 0 0 3px rgba(255, 104, 0, .12);
    }

    .form-note {
      margin: 13px 0 0;
      color: var(--gray);
      font-size: 11px;
      text-align: center;
    }

    .success-message {
      display: none;
      padding: 14px;
      margin-top: 14px;
      color: #075c38;
      background: #dcf8e9;
      border-radius: 10px;
      font-size: 14px;
      font-weight: 700;
      text-align: center;
    }

    .guarantees {
      padding: 26px 0;
      background: #f7f7f8;
    }

    .guarantee-grid {
      display: grid;
      grid-template-columns: repeat(3, 1fr);
      gap: 16px;
    }

    .guarantee {
      display: flex;
      align-items: center;
      justify-content: center;
      gap: 11px;
      font-size: 13px;
      font-weight: 850;
      text-align: center;
      text-transform: uppercase;
    }

    .guarantee-icon {
      color: var(--orange);
      font-size: 25px;
    }

    footer {
      padding: 28px 0 88px;
      color: #9ca1a8;
      background: var(--black);
      font-size: 13px;
      text-align: center;
    }

    .floating-buy {
      position: fixed;
      z-index: 30;
      right: 0;
      bottom: 0;
      left: 0;
      display: none;
      padding: 10px 16px;
      background: rgba(255, 255, 255, .96);
      border-top: 1px solid #e7e8ea;
      box-shadow: 0 -8px 24px rgba(0, 0, 0, .08);
      backdrop-filter: blur(8px);
    }

    @media (max-width: 860px) {
      .hero-grid,
      .visual-grid,
      .included,
      .order-grid {
        grid-template-columns: 1fr;
      }

      .hero {
        padding-top: 34px;
      }

      .hero-image-wrap {
        max-width: 590px;
        margin: 0 auto;
      }

      .features,
      .use-grid {
        grid-template-columns: repeat(2, 1fr);
      }

      .visual-grid .visual-image {
        order: -1;
      }

      .included-image {
        max-width: 610px;
      }

      .order-copy {
        text-align: center;
      }

      .order-copy > p {
        margin-right: auto;
        margin-left: auto;
      }

      .order-benefits {
        justify-content: center;
      }
    }

    @media (max-width: 560px) {
      .container {
        width: min(100% - 24px, 1120px);
      }

      .nav {
        min-height: 58px;
      }

      .nav-benefit {
        display: none;
      }

      .brand {
        font-size: 15px;
      }

      .brand-mark {
        width: 30px;
        height: 30px;
      }

      .hero {
        padding-bottom: 24px;
      }

      h1 {
        font-size: 39px;
        letter-spacing: -1.8px;
      }

      .hero-text {
        font-size: 16px;
      }

      .hero-actions .btn {
        width: 100%;
      }

      .badges {
        grid-template-columns: 1fr;
      }

      .badge {
        min-height: auto;
      }

      .section,
      .order-section {
        padding: 58px 0;
      }

      .features,
      .use-grid,
      .guarantee-grid {
        grid-template-columns: 1fr;
      }

      .included-list {
        grid-template-columns: 1fr;
      }

      .section-title {
        font-size: 32px;
      }

      .visual-copy h2,
      .included-copy h2,
      .order-copy h2 {
        font-size: 34px;
      }

      .guarantee {
        justify-content: flex-start;
        padding-left: 20px;
      }

      .floating-buy {
        display: block;
      }

      footer {
        padding-bottom: 88px;
      }
    }
  </style>
</head>

<body>
  <div class="announcement">
    🚚 Envío rápido · <span>Pago contra entrega</span> · Garantía de 1 año
  </div>

  <header>
    <div class="container nav">
      <a class="brand" href="#">
        <span class="brand-mark">⚡</span>
        Hidrolavadora 48V
      </a>
      <div class="nav-benefit">Compra segura y pago al recibir</div>
      <a class="btn btn-primary" href="#comprar">Comprar ahora</a>
    </div>
  </header>

  <main>
    <section class="hero">
      <div class="container hero-grid">
        <div>
          <div class="eyebrow">Limpieza sin cables</div>

          <h1>
            Hidrolavadora<br>
            inalámbrica <span>48V</span>
          </h1>

          <p class="hero-text">
            Limpia autos, motos, patios, ventanas y mucho más desde cualquier lugar.
            Potencia portátil, boquilla 6 en 1 y accesorios incluidos.
          </p>

          <div class="hero-actions">
            <a class="btn btn-primary" href="#comprar">Quiero la mía ahora</a>
            <a class="btn btn-dark" href="#beneficios">Ver beneficios</a>
          </div>

          <div class="trust-row">
            <div><span class="check">✓</span> Garantía de 1 año</div>
            <div><span class="check">✓</span> Pago al recibir</div>
            <div><span class="check">✓</span> Kit completo</div>
          </div>
        </div>

        <div class="hero-image-wrap">
          <div class="hero-image">
            <img src="IMG_2880.jpg" alt="Kit de hidrolavadora inalámbrica 48V con maletín, baterías y accesorios">
          </div>
        </div>
      </div>

      <div class="container badges">
        <div class="badge">
          <div class="badge-icon">⚡</div>
          <strong>Potencia sin cables</strong>
          <span>Úsala sin depender de enchufes.</span>
        </div>

        <div class="badge">
          <div class="badge-icon">◉</div>
          <strong>Boquilla 6 en 1</strong>
          <span>Ajusta el chorro según cada tarea.</span>
        </div>

        <div class="badge">
          <div class="badge-icon">▣</div>
          <strong>Kit portátil</strong>
          <span>Todo organizado en su maletín.</span>
        </div>
      </div>
    </section>

    <section class="section section-gray" id="beneficios">
      <div class="container">
        <h2 class="section-title">
          Resultados de limpieza <span>profesionales</span><br>
          sin salir de casa
        </h2>

        <p class="section-subtitle">
          Una solución práctica para remover lodo, polvo, grasa y suciedad acumulada
          en tus espacios y vehículos.
        </p>

        <div class="features">
          <article class="feature-card">
            <div class="number">01</div>
            <h3>Alta presión</h3>
            <p>Chorro concentrado para una limpieza profunda y eficiente en menos tiempo.</p>
          </article>

          <article class="feature-card">
            <div class="number">02</div>
            <h3>Sin toma de agua</h3>
            <p>Conecta la manguera a un recipiente, balde o fuente de agua disponible.</p>
          </article>

          <article class="feature-card">
            <div class="number">03</div>
            <h3>Uso multiusos</h3>
            <p>Ideal para auto, moto, bicicletas, patio, ventanas, herramientas y más.</p>
          </article>

          <article class="feature-card">
            <div class="number">04</div>
            <h3>Ligera y portátil</h3>
            <p>Llévala donde la necesites y guárdala cómodamente en su maletín.</p>
          </article>
        </div>
      </div>
    </section>

    <section class="section">
      <div class="container visual-grid">
        <div class="visual-copy">
          <div class="eyebrow">Potencia para cada lavado</div>
          <h2>Haz que tu moto luzca <span>como nueva</span></h2>

          <p>
            La hidrolavadora portátil está diseñada para ayudarte a alcanzar zonas
            difíciles y eliminar suciedad visible de forma cómoda.
          </p>

          <div class="visual-list">
            <div class="visual-list-item">
              <span class="check">✓</span>
              <div>
                <strong>Chorro ajustable</strong>
                <span>Selecciona el modo adecuado con su boquilla multifunción.</span>
              </div>
            </div>

            <div class="visual-list-item">
              <span class="check">✓</span>
              <div>
                <strong>Mayor comodidad</strong>
                <span>Evita depender de una hidrolavadora grande o de un lavadero.</span>
              </div>
            </div>

            <div class="visual-list-item">
              <span class="check">✓</span>
              <div>
                <strong>Ideal para el día a día</strong>
                <span>Tenla lista para limpiezas rápidas en casa o fuera de ella.</span>
              </div>
            </div>
          </div>

          <a class="btn btn-primary" href="#comprar">Comprar con pago al recibir</a>
        </div>

        <div class="visual-image">
          <img src="IMG_2881.jpg" alt="Hidrolavadora inalámbrica limpiando una moto">
        </div>
      </div>
    </section>

    <section class="section section-gray">
      <div class="container">
        <h2 class="section-title">
          Ahorra tiempo, dinero y esfuerzo<br>
          en <span>cada lavado</span>
        </h2>

        <p class="section-subtitle">
          Ten una herramienta de limpieza portátil para usar cuando lo necesites,
          sin filas ni desplazamientos.
        </p>

        <div class="use-grid">
          <article class="use-card">
            <img src="IMG_2882.jpg" alt="Limpieza de ruedas de automóvil con hidrolavadora">
            <div class="use-card-content">
              <h3>Ruedas y rines</h3>
              <p>Ayuda a remover barro y suciedad de las zonas de difícil acceso.</p>
            </div>
          </article>

          <article class="use-card">
            <img src="IMG_2881.jpg" alt="Lavado de moto con hidrolavadora portátil">
            <div class="use-card-content">
              <h3>Motos y bicicletas</h3>
              <p>Ideal para realizar lavados rápidos en la comodidad de tu hogar.</p>
            </div>
          </article>

          <article class="use-card">
            <img src="IMG_2882.jpg" alt="Hidrolavadora inalámbrica de alta presión">
            <div class="use-card-content">
              <h3>Patios y exteriores</h3>
              <p>Úsala en muebles de exterior, pisos, ventanas y herramientas.</p>
            </div>
          </article>

          <article class="use-card">
            <img src="IMG_2880.jpg" alt="Kit completo de hidrolavadora portátil">
            <div class="use-card-content">
              <h3>Siempre lista</h3>
              <p>Guarda el equipo y sus accesorios de forma ordenada en su maletín.</p>
            </div>
          </article>
        </div>
      </div>
    </section>

    <section class="section">
      <div class="container included">
        <div class="included-image">
          <img src="IMG_2880.jpg" alt="Accesorios incluidos con la hidrolavadora inalámbrica 48V">
        </div>

        <div class="included-copy">
          <div class="eyebrow">Kit completo</div>
          <h2>Todo lo que necesitas <span>en una sola compra</span></h2>

          <p>
            Recibe un kit pensado para empezar a limpiar desde el primer día.
            No necesitas comprar accesorios adicionales para usarla.
          </p>

          <ul class="included-list">
            <li><span class="check">✓</span> Hidrolavadora portátil</li>
            <li><span class="check">✓</span> Boquilla 6 en 1</li>
            <li><span class="check">✓</span> Manguera de succión</li>
            <li><span class="check">✓</span> Filtro para agua</li>
            <li><span class="check">✓</span> Botella para espuma</li>
            <li><span class="check">✓</span> Maletín de transporte</li>
            <li><span class="check">✓</span> Baterías recargables</li>
            <li><span class="check">✓</span> Cargador incluido</li>
          </ul>

          <a class="btn btn-dark" href="#comprar">Ordenar mi kit</a>
        </div>
      </div>
    </section>

    <section class="order-section" id="comprar">
      <div class="container order-grid">
        <div class="order-copy">
          <div class="eyebrow">Oferta por tiempo limitado</div>
          <h2>Ordena hoy y paga <span>cuando recibas</span></h2>

          <p>
            Completa tus datos para solicitar tu hidrolavadora inalámbrica 48V.
            Nuestro equipo se comunicará contigo para confirmar el pedido.
          </p>

          <div class="order-benefits">
            <div class="order-benefit">
              <span class="check">✓</span>
              Pago contra entrega disponible
            </div>
            <div class="order-benefit">
              <span class="check">✓</span>
              Garantía de 1 año
            </div>
            <div class="order-benefit">
              <span class="check">✓</span>
              Kit con accesorios incluidos
            </div>
          </div>
        </div>

        <form class="order-form" id="orderForm">
          <h3>Haz tu pedido</h3>
          <p>Déjanos tus datos y confirmaremos tu compra.</p>

          <div class="field">
            <label for="name">Nombre completo</label>
            <input id="name" name="name" type="text" placeholder="Escribe tu nombre" required>
          </div>

          <div class="field">
            <label for="phone">WhatsApp / Teléfono</label>
            <input id="phone" name="phone" type="tel" placeholder="Ej. 300 000 0000" required>
          </div>

          <div class="field">
            <label for="city">Ciudad</label>
            <input id="city" name="city" type="text" placeholder="Tu ciudad" required>
          </div>

          <div class="field">
            <label for="address">Dirección de entrega</label>
            <input id="address" name="address" type="text" placeholder="Barrio, calle y número" required>
          </div>

          <div class="field">
            <label for="quantity">Cantidad</label>
            <select id="quantity" name="quantity">
              <option value="1">1 Hidrolavadora 48V</option>
              <option value="2">2 Hidrolavadoras 48V</option>
              <option value="3">3 Hidrolavadoras 48V</option>
            </select>
          </div>

          <button class="btn btn-primary btn-full" type="submit">
            Solicitar pedido
          </button>

          <p class="form-note">
            Al enviar, aceptas ser contactado para confirmar tu pedido y envío.
          </p>

          <div class="success-message" id="successMessage">
            ¡Solicitud recibida! Te contactaremos pronto para confirmar tu pedido.
          </div>
        </form>
      </div>
    </section>
  </main>

  <section class="guarantees">
    <div class="container guarantee-grid">
      <div class="guarantee">
        <span class="guarantee-icon">🛡</span>
        Garantía de 1 año
      </div>
      <div class="guarantee">
        <span class="guarantee-icon">◷</span>
        Oferta por tiempo limitado
      </div>
      <div class="guarantee">
        <span class="guarantee-icon">▣</span>
        Pago al recibir
      </div>
    </div>
  </section>

  <footer>
    <div class="container">
      © 2026 Hidrolavadora 48V. Todos los derechos reservados.
    </div>
  </footer>

  <div class="floating-buy">
    <a class="btn btn-primary btn-full" href="#comprar">Comprar ahora · Pago al recibir</a>
  </div>

  <script>
    const form = document.getElementById("orderForm");
    const successMessage = document.getElementById("successMessage");

    form.addEventListener("submit", function (event) {
      event.preventDefault();

      const name = document.getElementById("name").value.trim();
      const phone = document.getElementById("phone").value.trim();
      const city = document.getElementById("city").value.trim();
      const address = document.getElementById("address").value.trim();
      const quantity = document.getElementById("quantity").value;

      /*
        Para conectar el formulario a WhatsApp:
        1. Reemplaza 573000000000 por tu número con código de país.
        2. Quita las dos barras // de las siguientes líneas.
      */

      // const message = `Hola, quiero solicitar ${quantity}.\n\nNombre: ${name}\nTeléfono: ${phone}\nCiudad: ${city}\nDirección: ${address}`;
      // window.open(`https://wa.me/573000000000?text=${encodeURIComponent(message)}`, "_blank");

      successMessage.style.display = "block";
      form.reset();
      successMessage.scrollIntoView({ behavior: "smooth", block: "center" });
    });
  </script>
</body>
</html>
