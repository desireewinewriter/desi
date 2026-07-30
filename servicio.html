<!DOCTYPE html>
<html lang="es">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Del otro lado de la etiqueta</title>
<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Cormorant+Garamond:ital,wght@0,400;0,500;0,600;1,400&family=Jost:wght@300;400;500;600&family=IBM+Plex+Mono:wght@400;500&display=swap" rel="stylesheet">
<style>
  :root{
    --wine:        #470f2b;
    --wine-deep:   #300a1d;
    --paper:       #f1e6d9;
    --paper-dim:   #e7d8c6;
    --ink:         #271711;
    --gold:        #b9924f;
    --rose:        #c1636a;
    --line:        rgba(39,23,17,0.16);
    --line-light:  rgba(241,230,217,0.25);
  }

  *{box-sizing:border-box;}
  html{scroll-behavior:smooth;}
  body{
    margin:0;
    background:var(--paper);
    color:var(--ink);
    font-family:'Jost', sans-serif;
    font-weight:400;
    line-height:1.6;
    -webkit-font-smoothing:antialiased;
  }
  h1,h2,h3,blockquote{
    font-family:'Cormorant Garamond', serif;
    margin:0;
    font-weight:500;
  }
  .eyebrow{
    font-family:'IBM Plex Mono', monospace;
    font-size:0.72rem;
    letter-spacing:0.22em;
    text-transform:uppercase;
  }
  a{color:inherit;}
  img,svg{display:block;max-width:100%;}
  section{position:relative;}
  .wrap{
    max-width:760px;
    margin:0 auto;
    padding:0 28px;
  }
  ::selection{background:var(--gold);color:var(--wine-deep);}
  :focus-visible{outline:2px solid var(--gold);outline-offset:3px;}

  /* reveal on scroll */
  .reveal{opacity:0;transform:translateY(18px);transition:opacity .8s ease, transform .8s ease;}
  .reveal.is-visible{opacity:1;transform:translateY(0);}
  @media (prefers-reduced-motion: reduce){
    .reveal{opacity:1;transform:none;transition:none;}
    html{scroll-behavior:auto;}
  }

  /* ---------- HERO ---------- */
  .hero{
    background:radial-gradient(ellipse at 30% -10%, #5c1638 0%, var(--wine) 45%, var(--wine-deep) 100%);
    color:var(--paper);
    padding:96px 0 120px;
    overflow:hidden;
  }
  .hero .wrap{
    display:grid;
    grid-template-columns:1.15fr 0.85fr;
    gap:56px;
    align-items:center;
    max-width:1040px;
  }
  .hero-eyebrow{color:var(--rose);margin-bottom:22px;display:block;}
  .hero h1{
    font-size:clamp(2.1rem, 4.6vw, 3.15rem);
    line-height:1.14;
    color:var(--paper);
  }
  .hero h1 em{
    font-style:italic;
    color:var(--gold);
  }
  .hero p.lede{
    margin-top:26px;
    font-size:1.05rem;
    color:var(--paper-dim);
    max-width:46ch;
  }

  /* the label — signature element */
  .label-card{
    position:relative;
    background:var(--paper);
    color:var(--ink);
    padding:34px 30px 30px;
    border-radius:2px;
    box-shadow:0 30px 60px -20px rgba(0,0,0,0.55);
    transform:rotate(-3.5deg);
    transition:transform .5s ease;
  }
  .label-card:hover{transform:rotate(-1deg) translateY(-4px);}
  .label-card::before{
    content:"";
    position:absolute;
    inset:8px;
    border:1px solid var(--line);
    pointer-events:none;
  }
  .label-card .peel{
    position:absolute;
    top:-1px;right:-1px;
    width:56px;height:56px;
    background:linear-gradient(135deg, transparent 49%, var(--wine-deep) 50%, var(--wine-deep) 52%, var(--paper) 53%);
    box-shadow:-6px 6px 10px -6px rgba(0,0,0,0.4);
  }
  .label-card .eyebrow{color:var(--wine);opacity:0.65;}
  .label-card h3{
    font-size:1.5rem;
    margin-top:10px;
    line-height:1.25;
  }
  .label-card .fine{
    margin-top:18px;
    padding-top:16px;
    border-top:1px dashed var(--line);
    font-family:'IBM Plex Mono', monospace;
    font-size:0.7rem;
    letter-spacing:0.05em;
    color:var(--wine);
    display:flex;
    justify-content:space-between;
  }

  @media (max-width:760px){
    .hero .wrap{grid-template-columns:1fr;}
    .label-card{transform:rotate(-2deg);justify-self:start;max-width:320px;}
  }

  /* ---------- INTERES ---------- */
  .interes{padding:104px 0;}
  .interes .eyebrow{color:var(--wine);opacity:0.6;}
  .interes h2{
    font-size:clamp(1.7rem, 3.4vw, 2.3rem);
    margin-top:14px;
    max-width:20ch;
  }
  .interes-quote{
    margin-top:52px;
    padding-left:26px;
    border-left:3px solid var(--gold);
  }
  .interes-quote p{
    font-family:'Cormorant Garamond', serif;
    font-style:italic;
    font-size:1.4rem;
    line-height:1.5;
    color:var(--wine);
  }
  .interes-quote p + p{margin-top:10px;}

  /* ---------- PROBLEMA (dark) ---------- */
  .problema{
    background:var(--wine-deep);
    color:var(--paper);
    padding:104px 0;
  }
  .problema .eyebrow{color:var(--rose);}
  .problema h2{
    color:var(--paper);
    font-size:clamp(1.7rem, 3.4vw, 2.3rem);
    margin-top:14px;
    max-width:22ch;
  }
  .cycle{
    margin-top:52px;
    display:grid;
    gap:0;
    border-top:1px solid var(--line-light);
  }
  .cycle .step{
    display:grid;
    grid-template-columns:110px 1fr;
    gap:20px;
    padding:20px 0;
    border-bottom:1px solid var(--line-light);
  }
  .cycle .step .tag{
    font-family:'IBM Plex Mono', monospace;
    font-size:0.72rem;
    letter-spacing:0.14em;
    color:var(--gold);
    text-transform:uppercase;
    padding-top:3px;
  }
  .cycle .step p{margin:0;color:var(--paper-dim);}
  .cycle .step.punch p{
    color:var(--paper);
    font-family:'Cormorant Garamond', serif;
    font-size:1.2rem;
    font-style:italic;
  }
  .whatsapp-line{
    margin-top:40px;
    font-family:'Cormorant Garamond', serif;
    font-size:1.35rem;
    font-style:italic;
    color:var(--gold);
    max-width:38ch;
  }

  /* ---------- DESEO ---------- */
  .deseo{padding:104px 0;}
  .deseo .eyebrow{color:var(--wine);opacity:0.6;}
  .deseo h2{
    font-size:clamp(1.7rem, 3.4vw, 2.3rem);
    margin-top:14px;
    max-width:24ch;
  }
  .deseo p.intro{margin-top:22px;max-width:56ch;color:#4a3226;}

  .paths{
    margin-top:56px;
    display:grid;
    grid-template-columns:repeat(3, 1fr);
    gap:22px;
  }
  .path-card{
    background:var(--paper);
    border:1px solid var(--line);
    padding:26px 22px;
    position:relative;
  }
  .path-card::after{
    content:"";
    position:absolute;
    left:0;right:0;bottom:0;
    height:3px;
    background:var(--gold);
    transform:scaleX(0);
    transform-origin:left;
    transition:transform .4s ease;
  }
  .path-card:hover::after{transform:scaleX(1);}
  .path-card .eyebrow{color:var(--rose);}
  .path-card h3{
    font-size:1.2rem;
    margin-top:10px;
    line-height:1.3;
  }
  .path-card p{margin-top:10px;font-size:0.94rem;color:#4a3226;}

  @media (max-width:760px){
    .paths{grid-template-columns:1fr;}
  }

  .closing-line{
    margin-top:56px;
    padding:28px 0 0;
    border-top:1px solid var(--line);
    font-family:'Cormorant Garamond', serif;
    font-size:1.3rem;
    font-style:italic;
    color:var(--wine);
    max-width:44ch;
  }

  /* ---------- INCLUYE ---------- */
  .incluye{
    background:var(--paper-dim);
    padding:104px 0;
  }
  .incluye .eyebrow{color:var(--wine);opacity:0.6;}
  .incluye h2{
    font-size:clamp(1.7rem, 3.4vw, 2.3rem);
    margin-top:14px;
  }
  .tags{
    margin-top:48px;
    display:flex;
    flex-wrap:wrap;
    gap:12px;
  }
  .tags .tag-chip{
    display:flex;
    align-items:center;
    gap:8px;
    background:var(--paper);
    border:1px solid var(--line);
    border-radius:999px;
    padding:10px 18px 10px 14px;
    font-size:0.9rem;
  }
  .tag-chip .dot{
    width:7px;height:7px;
    border-radius:50%;
    background:var(--rose);
    flex-shrink:0;
  }
  .incluye-note{
    margin-top:40px;
    max-width:52ch;
    color:#4a3226;
    font-size:0.98rem;
  }

  /* ---------- CTA ---------- */
  .cta{
    background:radial-gradient(ellipse at 70% 110%, #5c1638 0%, var(--wine) 40%, var(--wine-deep) 100%);
    color:var(--paper);
    padding:112px 0 100px;
    text-align:center;
  }
  .cta .eyebrow{color:var(--rose);}
  .cta h2{
    color:var(--paper);
    font-size:clamp(1.9rem, 4vw, 2.6rem);
    margin-top:16px;
    max-width:22ch;
    margin-left:auto;
    margin-right:auto;
  }
  .cta p{
    margin-top:20px;
    color:var(--paper-dim);
    max-width:48ch;
    margin-left:auto;
    margin-right:auto;
  }
  .btn{
    display:inline-block;
    margin-top:36px;
    padding:16px 34px;
    background:var(--gold);
    color:var(--wine-deep);
    text-decoration:none;
    font-family:'IBM Plex Mono', monospace;
    font-size:0.85rem;
    letter-spacing:0.06em;
    text-transform:uppercase;
    border-radius:2px;
    transition:transform .25s ease, box-shadow .25s ease;
  }
  .btn:hover{
    transform:translateY(-2px);
    box-shadow:0 14px 30px -12px rgba(185,146,79,0.55);
  }

  footer{
    background:var(--wine-deep);
    color:var(--paper-dim);
    text-align:center;
    padding:26px 0;
    font-family:'IBM Plex Mono', monospace;
    font-size:0.72rem;
    letter-spacing:0.08em;
  }
</style>
</head>
<body>

<section class="hero">
  <div class="wrap">
    <div>
      <span class="eyebrow hero-eyebrow">Del otro lado de la etiqueta</span>
      <h1>¿Qué se lleva una persona de tu evento, además de tu <em>WhatsApp</em>?</h1>
      <p class="lede">Cada vez hay más catas y más propuestas. Lo que define si alguien vuelve no es el vino que probó: es lo que queda cuando la copa ya está vacía.</p>
    </div>
    <div class="label-card reveal">
      <div class="peel"></div>
      <span class="eyebrow">Contenido</span>
      <h3>Una guía con tu voz, un vínculo que sigue después del brindis.</h3>
      <div class="fine">
        <span>QR · Guía · Comunidad</span>
        <span>750ml</span>
      </div>
    </div>
  </div>
</section>

<section class="interes">
  <div class="wrap reveal">
    <span class="eyebrow">Lo que permanece</span>
    <h2>No es solamente el vino lo que se llevan.</h2>
    <div class="interes-quote">
      <p>Es el recuerdo de cómo la hiciste sentir.</p>
      <p>La tranquilidad con la que respondiste cada pregunta.</p>
      <p>La confianza que transmitiste al recomendar una etiqueta.</p>
    </div>
  </div>
</section>

<section class="problema">
  <div class="wrap reveal">
    <span class="eyebrow">El patrón que se repite</span>
    <h2>Toda esa confianza queda sostenida por un solo contacto.</h2>
    <div class="cycle">
      <div class="step">
        <span class="tag">Semanas antes</span>
        <p>Preparás el evento con dedicación. Convocás. Construís una experiencia inolvidable.</p>
      </div>
      <div class="step punch">
        <span class="tag">Al día siguiente</span>
        <p>Sentís que volvés a empezar de cero. No porque el evento haya salido mal — al contrario.</p>
      </div>
    </div>
    <p class="whatsapp-line">¿Cuántas veces guardaste un número con la intención de escribir "después", y ese después nunca llegó? Con tus clientes pasa exactamente lo mismo.</p>
  </div>
</section>

<section class="deseo">
  <div class="wrap reveal">
    <span class="eyebrow">Cómo funciona</span>
    <h2>La conversación sigue, con tu misma forma de contar el vino.</h2>
    <p class="intro">Cada asistente escanea un QR y accede a una guía personalizada con los vinos que degustó, escrita con tu identidad. Mientras la recorre, el sistema entiende qué vínculo quiere construir con vos — porque no todas las personas necesitan lo mismo.</p>

    <div class="paths">
      <div class="path-card">
        <span class="eyebrow">Quiere aprender</span>
        <h3>Contenido para profundizar</h3>
        <p>Recibe material pensado para quien recién empieza a descubrir el mundo del vino.</p>
      </div>
      <div class="path-card">
        <span class="eyebrow">Está lista para comprar</span>
        <h3>Un camino claro</h3>
        <p>Encuentra la forma simple de conseguir la etiqueta que probó y disfrutó.</p>
      </div>
      <div class="path-card">
        <span class="eyebrow">Busca pertenecer</span>
        <h3>Una comunidad</h3>
        <p>Se suma a un espacio propio donde el vínculo con tu marca sigue vivo.</p>
      </div>
    </div>

    <p class="closing-line">Ocupar un lugar en la memoria de las personas es mucho más poderoso que aparecer una sola vez frente a ellas.</p>
  </div>
</section>

<section class="incluye">
  <div class="wrap reveal">
    <span class="eyebrow">Qué incluye</span>
    <h2>Se configura una sola vez. Acompaña cada evento.</h2>
    <div class="tags">
      <span class="tag-chip"><span class="dot"></span>Guía de degustación personalizada con tu identidad</span>
      <span class="tag-chip"><span class="dot"></span>QR listo para imprimir y usar en todos tus eventos</span>
      <span class="tag-chip"><span class="dot"></span>Formulario de registro inteligente</span>
      <span class="tag-chip"><span class="dot"></span>Clasificación automática de contactos según sus intereses</span>
      <span class="tag-chip"><span class="dot"></span>Correos personalizados para cada tipo de público</span>
      <span class="tag-chip"><span class="dot"></span>Comunidad propia de WhatsApp</span>
      <span class="tag-chip"><span class="dot"></span>Sistema para pedir testimonios en el momento indicado</span>
    </div>
    <p class="incluye-note">Del otro lado de la etiqueta transforma una experiencia presencial en una relación que permanece — mucho después del último brindis.</p>
  </div>
</section>

<section class="cta">
  <div class="wrap reveal">
    <span class="eyebrow">Sigamos la conversación</span>
    <h2>Cada evento merece seguir dando frutos.</h2>
    <p>Quiero mostrarte cómo adaptar Del otro lado de la etiqueta a tu forma de trabajar, para que cada encuentro siga construyendo relaciones incluso cuando las copas ya están vacías.</p>
    <a class="btn" href="https://wa.me/5490000000000?text=Quiero%20conocer%20Del%20otro%20lado%20de%20la%20etiqueta" target="_blank" rel="noopener">Quiero conocer Del otro lado de la etiqueta</a>
  </div>
</section>

<footer>Del otro lado de la etiqueta</footer>

<script>
  const items = document.querySelectorAll('.reveal');
  if ('IntersectionObserver' in window) {
    const io = new IntersectionObserver((entries) => {
      entries.forEach(e => {
        if (e.isIntersecting) {
          e.target.classList.add('is-visible');
          io.unobserve(e.target);
        }
      });
    }, { threshold: 0.15 });
    items.forEach(el => io.observe(el));
  } else {
    items.forEach(el => el.classList.add('is-visible'));
  }
</script>

</body>
</html>
