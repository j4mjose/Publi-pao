<!DOCTYPE html>
<html lang="es">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Gerontología — Anuncio</title>
<link href="https://fonts.googleapis.com/css2?family=Playfair+Display:ital,wght@0,700;1,400&family=Outfit:wght@300;400;500;600&display=swap" rel="stylesheet">
<style>
  *, *::before, *::after { box-sizing: border-box; margin: 0; padding: 0; }

  body {
    background: #e8e4dd;
    display: flex;
    justify-content: center;
    align-items: flex-start;
    padding: 40px 16px;
    font-family: 'Outfit', sans-serif;
  }

  .card {
    width: 600px;
    max-width: 100%;
    background: #fff;
    overflow: hidden;
    box-shadow: 0 20px 60px rgba(0,0,0,.15);
  }

  /* ── HERO ── */
  .hero {
    background: #1b2d2a;
    padding: 48px 44px 40px;
    position: relative;
    overflow: hidden;
  }
  .hero::after {
    content: '⟳';
    position: absolute;
    font-size: 260px;
    color: rgba(255,255,255,.03);
    right: -30px;
    top: -40px;
    line-height: 1;
    pointer-events: none;
  }
  .kicker {
    display: inline-block;
    background: #c9923a;
    color: #fff;
    font-size: 10px;
    font-weight: 600;
    letter-spacing: .2em;
    text-transform: uppercase;
    padding: 5px 14px;
    margin-bottom: 22px;
  }
  .hero h1 {
    font-family: 'Playfair Display', serif;
    font-size: clamp(34px, 8vw, 52px);
    color: #fff;
    line-height: 1.1;
    margin-bottom: 16px;
  }
  .hero h1 em {
    font-style: italic;
    color: #e8bb74;
  }
  .hero .lead {
    font-size: 15px;
    color: rgba(255,255,255,.65);
    line-height: 1.65;
    max-width: 420px;
    font-weight: 300;
  }
  .hero .lead strong { color: #fff; font-weight: 500; }

  /* ── NOT BOX ── */
  .not-strip {
    background: #f5e8e8;
    border-left: 4px solid #c0392b;
    padding: 16px 28px;
    display: flex;
    align-items: center;
    gap: 14px;
  }
  .not-strip .icon { font-size: 22px; flex-shrink: 0; }
  .not-strip p { font-size: 13px; color: #5a1a1a; line-height: 1.5; }
  .not-strip strong { color: #c0392b; }

  /* ── SERVICES ── */
  .section { padding: 36px 44px; }
  .section-label {
    font-size: 10px;
    letter-spacing: .22em;
    text-transform: uppercase;
    color: #c9923a;
    font-weight: 600;
    margin-bottom: 22px;
  }

  .services { display: flex; flex-direction: column; gap: 14px; }
  .svc {
    display: flex;
    align-items: flex-start;
    gap: 16px;
    padding: 18px 20px;
    border: 1.5px solid #ede8e0;
    transition: border-color .2s, background .2s;
    cursor: default;
  }
  .svc:hover { border-color: #c9923a; background: #fdf8f2; }
  .svc-icon {
    font-size: 26px;
    flex-shrink: 0;
    line-height: 1.2;
  }
  .svc-body h3 {
    font-size: 14px;
    font-weight: 600;
    color: #1b2d2a;
    margin-bottom: 4px;
  }
  .svc-body p {
    font-size: 12.5px;
    color: #666;
    line-height: 1.55;
  }

  /* ── DIVIDER ── */
  .divider { height: 1px; background: #ede8e0; margin: 0 44px; }

  /* ── CTA ── */
  .cta {
    padding: 32px 44px 36px;
    display: flex;
    justify-content: space-between;
    align-items: center;
    gap: 20px;
    flex-wrap: wrap;
  }
  .cta-text h2 {
    font-family: 'Playfair Display', serif;
    font-size: 20px;
    color: #1b2d2a;
    margin-bottom: 4px;
  }
  .cta-text p { font-size: 12.5px; color: #888; }
  .cta-btn {
    background: #1b2d2a;
    color: #e8bb74;
    font-family: 'Outfit', sans-serif;
    font-size: 12px;
    font-weight: 600;
    letter-spacing: .12em;
    text-transform: uppercase;
    padding: 14px 28px;
    border: none;
    cursor: pointer;
    white-space: nowrap;
    transition: background .2s;
  }
  .cta-btn:hover { background: #c9923a; color: #fff; }

  /* ── FOOTER ── */
  .footer {
    background: #1b2d2a;
    padding: 16px 44px;
    display: flex;
    justify-content: space-between;
    align-items: center;
    flex-wrap: wrap;
    gap: 8px;
  }
  .footer p { font-size: 11px; color: rgba(255,255,255,.4); }
  .footer strong { color: rgba(255,255,255,.75); }

  @media (max-width: 480px) {
    .hero, .section, .cta, .footer { padding-left: 24px; padding-right: 24px; }
    .divider { margin: 0 24px; }
    .not-strip { padding: 14px 20px; }
    .cta { flex-direction: column; align-items: flex-start; }
  }
</style>
</head>
<body>
<div class="card">

  <!-- HERO -->
  <div class="hero">
    <div class="kicker">Consulta Profesional</div>
    <h1>¿Qué hace un<br><em>Gerontólogo?</em></h1>
    <p class="lead">
      Es el experto que te ayuda a ti y a tu familia a entender y <strong>prepararse mejor para el envejecimiento</strong> — con estrategias reales, no solo diagnósticos.
    </p>
  </div>

  <!-- NOT A CAREGIVER -->
  <div class="not-strip">
    <div class="icon">🚫</div>
    <p><strong>No somos enfermeros ni cuidadores.</strong> Somos profesionales especializados en ayudarte a vivir mejor en cada etapa de la vida.</p>
  </div>

  <!-- SERVICES -->
  <div class="section">
    <div class="section-label">¿En qué te podemos ayudar?</div>
    <div class="services">

      <div class="svc">
        <div class="svc-icon">🧭</div>
        <div class="svc-body">
          <h3>Orientación para familias</h3>
          <p>¿No sabes cómo apoyar a tu familiar mayor? Te guiamos con información clara y pasos concretos.</p>
        </div>
      </div>

      <div class="svc">
        <div class="svc-icon">🌿</div>
        <div class="svc-body">
          <h3>Plan de envejecimiento activo</h3>
          <p>Diseñamos contigo un plan personalizado para mantener tu salud, independencia y calidad de vida.</p>
        </div>
      </div>

      <div class="svc">
        <div class="svc-icon">🧠</div>
        <div class="svc-body">
          <h3>Memoria y bienestar mental</h3>
          <p>Evaluamos y estimulamos las funciones mentales para mantener la mente activa y en forma.</p>
        </div>
      </div>

      <div class="svc">
        <div class="svc-icon">🤝</div>
        <div class="svc-body">
          <h3>Intervención social y emocional</h3>
          <p>Trabajamos la soledad, el ánimo y la motivación para que el adulto mayor se sienta acompañado y valorado.</p>
        </div>
      </div>

    </div>
  </div>

  <div class="divider"></div>

  <!-- CTA -->
  <div class="cta">
    <div class="cta-text">
      <h2>Agenda tu primera consulta</h2>
      <p>Sin tecnicismos. Sin complicaciones. Con soluciones reales.</p>
    </div>
    <button class="cta-btn">
      <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" fill="currentColor" style="width:15px;height:15px;vertical-align:middle;margin-right:7px;margin-bottom:2px;"><path d="M17.472 14.382c-.297-.149-1.758-.867-2.03-.967-.273-.099-.471-.148-.67.15-.197.297-.767.966-.94 1.164-.173.199-.347.223-.644.075-.297-.15-1.255-.463-2.39-1.475-.883-.788-1.48-1.761-1.653-2.059-.173-.297-.018-.458.13-.606.134-.133.298-.347.446-.52.149-.174.198-.298.298-.497.099-.198.05-.371-.025-.52-.075-.149-.669-1.612-.916-2.207-.242-.579-.487-.5-.669-.51-.173-.008-.371-.01-.57-.01-.198 0-.52.074-.792.372-.272.297-1.04 1.016-1.04 2.479 0 1.462 1.065 2.875 1.213 3.074.149.198 2.096 3.2 5.077 4.487.709.306 1.262.489 1.694.625.712.227 1.36.195 1.871.118.571-.085 1.758-.719 2.006-1.413.248-.694.248-1.289.173-1.413-.074-.124-.272-.198-.57-.347z"/><path d="M12 0C5.373 0 0 5.373 0 12c0 2.117.554 4.103 1.523 5.826L.057 23.857a.5.5 0 0 0 .609.61l6.098-1.459A11.945 11.945 0 0 0 12 24c6.627 0 12-5.373 12-12S18.627 0 12 0zm0 22c-1.891 0-3.667-.5-5.2-1.373l-.373-.217-3.868.925.951-3.788-.237-.389A9.946 9.946 0 0 1 2 12C2 6.477 6.477 2 12 2s10 4.477 10 10-4.477 10-10 10z"/></svg>
      Revisar en tarjeta
    </button>
  </div>

  <!-- FOOTER -->
  <div class="footer">
    <p><strong>Gerontología Profesional</strong></p>
    <p>Envejecer bien es una decisión. Nosotros te acompañamos.</p>
  </div>

</div>
</body>
</html>
