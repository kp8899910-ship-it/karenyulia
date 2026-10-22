<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <meta name="description" content="Grano & Calma: café artesanal, sabores frescos y un espacio para disfrutar sin prisa.">
  <meta name="theme-color" content="#39271f">
  <meta property="og:type" content="website">
  <meta property="og:title" content="Grano &amp; Calma | Café artesanal">
  <meta property="og:description" content="Café artesanal, sabores frescos y un espacio para disfrutar sin prisa.">
  <meta property="og:image" content="https://images.unsplash.com/photo-1442512595331-e89e73853f31?auto=format&amp;fit=crop&amp;w=1200&amp;q=80">
  <link rel="icon" href="data:image/svg+xml,%3Csvg xmlns='http://www.w3.org/2000/svg' viewBox='0 0 100 100'%3E%3Ctext y='.9em' font-size='90'%3E%E2%98%95%3C/text%3E%3C/svg%3E">
  <title>Grano & Calma | Café artesanal</title>
  <!-- Cambia el nombre, los precios, las redes y el correo por los de tu cafetería. -->
  <style>
    :root{--cafe:#39271f;--cafe-claro:#725446;--beige:#f4ede3;--crema:#fffdf9;--terracota:#a64f30;--borde:#e4d8ca;--blanco:#fff;--ancho:1160px}
    *{box-sizing:border-box}html{scroll-behavior:smooth;scroll-padding-top:100px}
    body{margin:0;background:var(--crema);color:var(--cafe);font-family:Arial,Helvetica,sans-serif;line-height:1.65}
    h1,h2,h3,p{margin-top:0}a{color:inherit}button,input{font:inherit}button,a,input{-webkit-tap-highlight-color:transparent}button{cursor:pointer}
    img{display:block;width:100%;object-fit:cover}:focus-visible{outline:3px solid var(--terracota);outline-offset:5px}
    .contenedor{width:min(var(--ancho),calc(100% - 48px));margin-inline:auto}
    .saltar{position:fixed;top:-100px;left:16px;z-index:100;padding:12px 20px;background:var(--cafe);color:white}.saltar:focus{top:12px}
    .etiqueta{display:block;margin-bottom:18px;color:var(--terracota);font-size:.74rem;font-weight:700;letter-spacing:.2em;text-transform:uppercase}
    h1,h2,h3{font-family:Georgia,"Times New Roman",serif;font-weight:400;line-height:1.1}
    h1{margin-bottom:24px;font-size:clamp(3rem,6vw,5.7rem);letter-spacing:-.055em}
    h2{margin-bottom:24px;font-size:clamp(2.3rem,4vw,3.7rem);letter-spacing:-.04em}
    .boton{display:inline-flex;align-items:center;justify-content:center;gap:24px;min-height:52px;padding:14px 26px;border:1px solid transparent;border-radius:5px;background:var(--terracota);color:var(--blanco);font-weight:700;text-decoration:none;transition:background .2s,transform .2s}
    .boton:hover{background:#843d24;transform:translateY(-2px)}
    .encabezado{position:sticky;top:0;z-index:20;border-bottom:1px solid var(--borde);background:rgba(255,253,249,.96)}
    .barra{position:relative;display:flex;align-items:center;justify-content:space-between;min-height:86px;gap:24px}
    .marca{display:inline-flex;align-items:center;gap:11px;text-decoration:none}.marca svg{width:42px;height:42px;flex-shrink:0}
    .marca strong{display:block;font-family:Georgia,serif;font-size:1.3rem;font-weight:400;line-height:1.2}
    .marca small{display:block;margin-top:4px;font-size:.58rem;letter-spacing:.23em;text-transform:uppercase}
    .navegacion{display:flex;align-items:center;gap:30px}.navegacion a{padding-block:8px;font-size:.87rem;text-decoration:none}.navegacion a:hover{color:var(--terracota)}
    .menu-toggle{display:none;padding:9px 14px;border:1px solid var(--borde);border-radius:5px;background:transparent;color:var(--cafe)}
    .hero{overflow:hidden;padding:64px 0 76px;background:var(--beige)}
    .hero-grid{display:grid;grid-template-columns:1.05fr 1fr;align-items:center;gap:70px}
    .hero-texto{padding-block:28px}.hero-texto>p{max-width:380px;margin-bottom:32px;color:var(--cafe-claro);font-size:1.08rem}
    .hero h1 em{color:var(--terracota);font-weight:400}.hero-foto{position:relative;margin:0}
    .hero-foto img{height:550px;border-radius:180px 180px 12px 12px;background:#d9c2ab}
    .foto-nota{position:absolute;right:-16px;bottom:32px;padding:18px 26px;border:1px solid var(--borde);border-radius:5px;background:var(--crema);font-family:Georgia,serif;font-size:1.1rem;box-shadow:0 10px 30px #39271f12}
    .nosotros{padding-block:100px}.nosotros-grid{display:grid;grid-template-columns:.85fr 1.15fr;align-items:start;gap:100px}
    .nosotros h2{margin-bottom:0}.nosotros-texto p{color:var(--cafe-claro)}
    .detalle{display:flex;flex-wrap:wrap;gap:12px 24px;padding-top:18px;border-top:1px solid var(--borde);font-size:.82rem}.detalle span::before{content:"•";margin-right:9px;color:var(--terracota)}
    .menu{padding-block:85px 95px;background:var(--beige)}
    .seccion-intro{display:flex;align-items:end;justify-content:space-between;gap:30px;margin-bottom:38px}.seccion-intro h2{margin-bottom:0}
    .seccion-intro>p{max-width:270px;margin-bottom:0;color:var(--cafe-claro)}
    .productos{display:grid;grid-template-columns:repeat(3,1fr);gap:26px}
    .producto{overflow:hidden;border:1px solid var(--borde);border-radius:10px;background:var(--crema)}.producto-imagen{overflow:hidden}
    .producto img{height:285px;background:#dfd0c0;transition:transform .4s ease}.producto:hover img{transform:scale(1.045)}
    .producto-info{padding:25px}.producto-titulo{display:flex;justify-content:space-between;align-items:baseline;gap:14px;margin-bottom:12px}
    .producto h3{margin:0;font-size:1.65rem}.precio{color:var(--terracota);font-size:1rem;font-weight:700;white-space:nowrap}
    .producto p{margin-bottom:0;color:var(--cafe-claro);font-size:.9rem}.nota-precios{margin:24px 0 0;color:var(--cafe-claro);font-size:.77rem}
    .contacto{padding-block:100px}.contacto-grid{display:grid;grid-template-columns:1fr 1fr;align-items:start;gap:100px}
    .contacto-texto p{max-width:360px;color:var(--cafe-claro)}.contacto-frase{display:block;margin-top:32px;color:var(--terracota);font-family:Georgia,serif;font-size:1.5rem;font-style:italic}
    form{padding:34px;border:1px solid var(--borde);border-radius:10px;background:var(--blanco)}.campo{margin-bottom:20px}
    label{display:block;margin-bottom:7px;font-size:.85rem;font-weight:700}
    input{width:100%;min-height:49px;padding:12px 14px;border:1px solid var(--borde);border-radius:5px;background:var(--crema);color:var(--cafe)}
    input:focus{border-color:var(--terracota);outline:2px solid #a64f3022}form .boton{width:100%}
    .aviso-formulario,.estado-formulario{margin:14px 0 0;color:var(--cafe-claro);font-size:.78rem}.estado-formulario:empty{display:none}
    footer{padding-block:35px;background:var(--cafe);color:var(--beige)}.pie{display:flex;flex-wrap:wrap;align-items:center;justify-content:space-between;gap:24px}
    .pie p{margin:0;font-size:.8rem}.redes{display:flex;gap:24px}.redes a{font-size:.85rem;text-decoration:none;text-underline-offset:5px}.redes a:hover{text-decoration:underline}
    @media(max-width:900px){.hero-grid{gap:35px}.hero-foto img{height:460px}.nosotros-grid,.contacto-grid{gap:45px}.productos{gap:16px}.producto img{height:230px}.producto-info{padding:20px}.producto-titulo{flex-wrap:wrap;gap:7px}}
    @media(max-width:680px){
      .contenedor{width:calc(100% - 36px)}.barra{min-height:76px}.marca strong{font-size:1.15rem}.menu-toggle{display:inline-flex}
      .navegacion{position:absolute;top:76px;left:-18px;right:-18px;display:none;align-items:stretch;gap:0;padding:12px 24px 20px;border-bottom:1px solid var(--borde);background:var(--crema);box-shadow:0 18px 25px #39271f0c}
      .navegacion.abierta{display:flex;flex-direction:column}.navegacion a{padding:12px 0}
      .hero{padding:35px 0 50px}.hero-grid,.nosotros-grid,.contacto-grid{grid-template-columns:1fr}.hero-grid{gap:28px}.hero-texto{padding:10px 0}
      .hero-foto img{height:390px;border-radius:140px 140px 10px 10px}.foto-nota{right:10px;bottom:20px;padding:14px 18px}
      .nosotros,.contacto{padding-block:65px}.nosotros-grid,.contacto-grid{gap:28px}.menu{padding-block:60px}.seccion-intro{display:block}.seccion-intro>p{margin-top:20px}
      .productos{grid-template-columns:1fr;gap:24px}.producto img{height:290px}.producto-titulo{flex-wrap:nowrap}form{padding:25px}.pie{align-items:flex-start;flex-direction:column}
    }
    @media(prefers-reduced-motion:reduce){html{scroll-behavior:auto}*,*::before,*::after{transition:none!important}}
  </style>
</head>
<body>
  <a class="saltar" href="#contenido">Saltar al contenido</a>
  <header class="encabezado">
    <div class="contenedor barra">
      <a class="marca" href="#inicio" aria-label="Grano y Calma, ir al inicio">
        <svg viewBox="0 0 48 48" fill="none" aria-hidden="true">
          <rect width="48" height="48" rx="24" fill="#39271f"/>
          <path d="M12 20h21v8a9 9 0 0 1-9 9h-3a9 9 0 0 1-9-9v-8Z" stroke="#f4ede3" stroke-width="2"/>
          <path d="M33 22h2a5 5 0 0 1 0 10h-3M10 39h27M20 10c-4 4 4 4 0 8M27 9c-4 4 4 4 0 8" stroke="#f4ede3" stroke-width="2" stroke-linecap="round"/>
        </svg>
        <span><strong>Grano &amp; Calma</strong><small>Cafetería artesanal</small></span>
      </a>
      <button class="menu-toggle" type="button" aria-controls="navegacion" aria-expanded="false">Menú ☰</button>
      <nav class="navegacion" id="navegacion" aria-label="Navegación principal">
        <a href="#inicio">Inicio</a><a href="#nosotros">Nosotros</a><a href="#menu">Nuestro menú</a><a href="#contacto">Contacto</a>
      </nav>
    </div>
  </header>
  <main id="contenido">
    <section class="hero" id="inicio" aria-labelledby="titulo-principal">
      <div class="contenedor hero-grid">
        <div class="hero-texto">
          <span class="etiqueta">Hecho con tiempo. Servido con cariño.</span>
          <h1 id="titulo-principal">Buen café.<br>Un momento<br><em>para ti.</em></h1>
          <p>Café artesanal, pan recién horneado y un espacio para disfrutar sin prisa.</p>
          <a class="boton" href="#menu">Ver menú <span aria-hidden="true">↗</span></a>
        </div>
        <figure class="hero-foto">
          <img src="https://images.unsplash.com/photo-1442512595331-e89e73853f31?auto=format&amp;fit=crop&amp;w=1100&amp;q=85" alt="Taza de café caliente en una mesa de madera" width="1100" height="1300" fetchpriority="high">
          <figcaption class="foto-nota">Tu pausa favorita empieza aquí.</figcaption>
        </figure>
      </div>
    </section>
    <section class="nosotros" id="nosotros" aria-labelledby="titulo-nosotros">
      <div class="contenedor nosotros-grid">
        <div><span class="etiqueta">Nuestra esencia</span><h2 id="titulo-nosotros">Del grano a la taza,<br>con intención.</h2></div>
        <div class="nosotros-texto">
          <p>Nos gusta cuidar lo que hace especial a un buen café: granos seleccionados, una molienda al momento y una preparación atenta a cada detalle.</p>
          <p>En Grano &amp; Calma acompañamos cada taza con un trato cercano. Queremos que encuentres tu sabor favorito y un lugar al que siempre te apetezca volver.</p>
          <div class="detalle" aria-label="Nuestra propuesta"><span>Café en grano</span><span>Preparación artesanal</span><span>Atención cercana</span></div>
        </div>
      </div>
    </section>
    <section class="menu" id="menu" aria-labelledby="titulo-menu">
      <div class="contenedor">
        <div class="seccion-intro">
          <div><span class="etiqueta">Pequeños grandes favoritos</span><h2 id="titulo-menu">Elige tu próxima pausa.</h2></div>
          <p>Tres clásicos que saben mejor cuando los disfrutas con calma.</p>
        </div>
        <div class="productos">
          <article class="producto">
            <div class="producto-imagen"><img src="https://images.unsplash.com/photo-1510707577719-ae7c14805e3a?auto=format&amp;fit=crop&amp;w=800&amp;q=85" alt="Café espresso servido en una taza pequeña" width="800" height="650" loading="lazy"></div>
            <div class="producto-info"><div class="producto-titulo"><h3>Café espresso</h3><span class="precio">$2,50</span></div><p>Intenso, aromático y con una crema delicada. La esencia del café en cada sorbo.</p></div>
          </article>
          <article class="producto">
            <div class="producto-imagen"><img src="https://images.unsplash.com/photo-1572442388796-11668a67e53d?auto=format&amp;fit=crop&amp;w=800&amp;q=85" alt="Cappuccino con espuma de leche y arte latte" width="800" height="650" loading="lazy"></div>
            <div class="producto-info"><div class="producto-titulo"><h3>Cappuccino</h3><span class="precio">$3,50</span></div><p>Espresso y leche de textura sedosa, con el equilibrio perfecto entre suavidad y carácter.</p></div>
          </article>
          <article class="producto">
            <div class="producto-imagen"><img src="https://images.unsplash.com/photo-1555507036-ab1f4038808a?auto=format&amp;fit=crop&amp;w=800&amp;q=85" alt="Croissants dorados de hojaldre" width="800" height="650" loading="lazy"></div>
            <div class="producto-info"><div class="producto-titulo"><h3>Croissant</h3><span class="precio">$2,75</span></div><p>Capas crujientes, corazón suave y ese aroma a mantequilla que invita a quedarse.</p></div>
          </article>
        </div>
        <p class="nota-precios">Precios de ejemplo expresados en dólares estadounidenses (USD).</p>
      </div>
    </section>
    <section class="contacto" id="contacto" aria-labelledby="titulo-contacto">
      <div class="contenedor contacto-grid">
        <div class="contacto-texto">
          <span class="etiqueta">Conversemos</span><h2 id="titulo-contacto">El primer café<br>empieza con un hola.</h2>
          <p>¿Tienes una consulta o quieres conocer más sobre nuestro café? Déjanos tus datos y cuéntanos de ti.</p>
          <span class="contacto-frase">Siempre hay tiempo para un buen café.</span>
        </div>
        <form id="formulario-contacto" aria-describedby="aviso-envio">
          <div class="campo"><label for="nombre">Nombre</label><input type="text" id="nombre" name="nombre" placeholder="Tu nombre" autocomplete="name" maxlength="100" required></div>
          <div class="campo"><label for="correo">Correo electrónico</label><input type="email" id="correo" name="correo" placeholder="nombre@ejemplo.com" autocomplete="email" maxlength="254" required></div>
          <div class="campo"><label for="telefono">Número de teléfono</label><input type="tel" id="telefono" name="telefono" placeholder="Ej. 099 123 4567" autocomplete="tel" maxlength="30" required></div>
          <button class="boton" type="submit">Enviar <span aria-hidden="true">↗</span></button>
          <p class="aviso-formulario" id="aviso-envio">El envío se completa desde tu aplicación de correo.</p>
          <p class="estado-formulario" id="estado-formulario" role="status"></p>
        </form>
      </div>
    </section>
  </main>
  <footer>
    <div class="contenedor pie">
      <div><p><strong>Grano &amp; Calma</strong> · Cafetería artesanal</p><p>© <span id="anio">2026</span> Todos los derechos reservados.</p></div>
      <!-- Reemplaza las direcciones por tus perfiles reales. -->
      <nav class="redes" aria-label="Redes sociales">
        <a href="https://www.instagram.com/tu_cafeteria/" target="_blank" rel="noopener noreferrer" aria-label="Instagram, abre una pestaña nueva">Instagram ↗</a>
        <a href="https://www.facebook.com/tu_cafeteria/" target="_blank" rel="noopener noreferrer" aria-label="Facebook, abre una pestaña nueva">Facebook ↗</a>
      </nav>
    </div>
  </footer>
  <script>
    // Sustituye este correo de ejemplo por el correo real de tu cafetería.
    const CORREO_DESTINO = 'kp8899910@gmail.com';
    const botonMenu = document.querySelector('.menu-toggle');
    const navegacion = document.querySelector('#navegacion');
    function cerrarMenu() {
      navegacion.classList.remove('abierta');
      botonMenu.setAttribute('aria-expanded', 'false');
      botonMenu.textContent = 'Menú ☰';
    }
    botonMenu.addEventListener('click', () => {
      const abierto = botonMenu.getAttribute('aria-expanded') === 'true';
      navegacion.classList.toggle('abierta', !abierto);
      botonMenu.setAttribute('aria-expanded', String(!abierto));
      botonMenu.textContent = abierto ? 'Menú ☰' : 'Cerrar ×';
    });
    navegacion.querySelectorAll('a').forEach(enlace => enlace.addEventListener('click', cerrarMenu));
    document.addEventListener('keydown', evento => {
      if (evento.key === 'Escape' && navegacion.classList.contains('abierta')) {
        cerrarMenu(); botonMenu.focus();
      }
    });
    document.addEventListener('click', evento => { if (!evento.target.closest('.barra')) cerrarMenu(); });
    window.matchMedia('(min-width: 681px)').addEventListener('change', cerrarMenu);
    document.querySelector('#anio').textContent = new Date().getFullYear();
    // El visitante confirma el envío desde su aplicación de correo.
    document.querySelector('#formulario-contacto').addEventListener('submit', evento => {
      evento.preventDefault();
      const formulario = evento.currentTarget;
      const nombre = formulario.elements.nombre.value.trim();
      const correo = formulario.elements.correo.value.trim();
      const telefono = formulario.elements.telefono.value.trim();
      const estado = document.querySelector('#estado-formulario');
      if (!nombre || !correo || !telefono) {
        estado.textContent = 'Completa todos los campos con tus datos.'; return;
      }
      const asunto = 'Consulta desde la web de Grano & Calma';
      const mensaje = ['Hola, me gustaría recibir más información sobre la cafetería.', '', `Nombre: ${nombre}`, `Correo: ${correo}`, `Teléfono: ${telefono}`].join('\n');
      estado.textContent = 'Se solicitará abrir tu aplicación de correo. Revisa el mensaje y pulsa enviar allí.';
      window.location.href = `mailto:${CORREO_DESTINO}?subject=${encodeURIComponent(asunto)}&body=${encodeURIComponent(mensaje)}`;
    });
  </script>
</body>
</html>
