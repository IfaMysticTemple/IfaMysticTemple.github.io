<html lang="en">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <meta name="theme-color" content="#0b0b0f" />
  <meta name="color-scheme" content="dark" />
  <title>SwamiG Institute 70-888-Swami — Ifá • Isésé • Orisha | Divination, Initiation & Spiritual Education</title>
  <meta name="description" content="SwamiG Institute offers Ifá / Isésé / Orisha divination, priesthood initiations, rites of passage, and spiritual education. Michigan nonprofit — 501(c)(3) recognition pending." />
  <style>
    :root{
      --bg:#0b0b0f;
      --ink:#eaeaf2;
      --muted:#b5b5c4;
      --accent:#bb66ff;
      --accent-muted:rgba(187,102,255,0.18);
      --accent-lineage:rgba(102,255,178,.35);
      --radius:20px
    }
    *{box-sizing:border-box}
    html,body{scroll-behavior:smooth;height:100%}
    body{
      margin:0;min-height:100vh;display:flex;flex-direction:column;
      background:var(--bg);color:var(--ink);
      font:400 16px/1.55 system-ui,-apple-system,Segoe UI,Roboto,Arial,sans-serif
    }

    /* Top notice */
    .noticebar{
      position:relative;width:100%;text-align:center;font-size:12px;color:#d9c6ff;
      background:rgba(187,102,255,.12);border-bottom:1px solid rgba(187,102,255,.25);padding:6px 12px;
    }
    .notice-center{display:inline-block}
    .notice-right{position:absolute;right:12px;top:6px;font-size:12px}
    .notice-right a{color:#d9c6ff;text-decoration:none}
    .notice-right a:hover{color:var(--accent)}

    /* Top Cards */
    .top-cards-wrap{background:rgba(11,11,15,.85);border-bottom:1px solid rgba(255,255,255,.08)}
    .top-cards{max-width:1100px;margin:0 auto;padding:6px 10px;display:grid;gap:8px}
    @media(min-width:900px){.top-cards{grid-template-columns:repeat(auto-fit,minmax(90px,1fr))}}
    @media(max-width:899px){.top-cards{grid-template-columns:1fr 1fr}}
    .top-card{
      position:relative;border-radius:10px;padding:6px;border:1px solid rgba(255,255,255,.12);
      color:var(--ink);background:linear-gradient(145deg,rgba(30,30,40,.95),rgba(18,18,25,.95));
      box-shadow:0 1px 3px rgba(0,0,0,.25);transition:transform .2s ease,box-shadow .2s ease,border-color .2s ease;cursor:default;
    }
    .top-card:hover{transform:translateY(-2px) scale(1.005);border-color:rgba(255,255,255,.22)}
    .top-card h3{margin:0 0 4px;font:700 11px/1.2 system-ui,-apple-system,Segoe UI,Roboto,Arial,sans-serif}
    .top-card p{margin:0 0 6px;color:var(--muted);font-size:10px;line-height:1.3}

    /* Accent glows */
    .top-cards .top-card:nth-child(1):hover{box-shadow:0 0 8px rgba(187,102,255,.55)} /* Mission */
    .top-cards .top-card:nth-child(2):hover{box-shadow:0 0 8px rgba(187,102,255,.55)}
    .top-cards .top-card:nth-child(3):hover{box-shadow:0 0 8px rgba(102,187,255,.50)}
    .top-cards .top-card:nth-child(4):hover{box-shadow:0 0 8px rgba(255,102,187,.50)}
    .top-cards .top-card:nth-child(5):hover{box-shadow:0 0 8px rgba(187,255,102,.50)}
    .top-cards .top-card:nth-child(6):hover{box-shadow:0 0 8px var(--accent-lineage)}

    /* Layout + Hero */
    .wrap{padding:24px 20px}
    .hero{display:flex;justify-content:center;align-items:center;text-align:center;padding:12px 0}
    .hero-block{max-width:600px}
    .logo{
      max-width:150px;border-radius:50%;overflow:hidden;display:grid;place-items:center;
      border:1px solid rgba(255,255,255,.1);box-shadow:0 0 12px rgba(187,102,255,.30);margin:0 auto 18px;
    }
    .logo img{width:100%;height:auto;border-radius:50%;display:block}
    h1{margin:0;font-weight:800;font-size:36px;line-height:1.08;letter-spacing:.3px}
    @media(min-width:960px){h1{font-size:42px}}
    .tag{color:var(--muted);font-size:15px;margin-top:10px}
    .badge{margin-top:10px;font-size:13px;color:#f4d3ff}
    .actions{margin-top:16px;display:flex;flex-wrap:wrap;gap:12px;justify-content:center}

    /* Button */
    .btn{border:0;border-radius:12px;padding:10px 18px;font-weight:600;text-decoration:none;display:inline-flex;align-items:center;gap:8px;cursor:pointer}
    .primary{background:transparent;color:var(--accent);border:1px solid var(--accent)}
    @keyframes floatPulse{0%,100%{transform:translateY(0);box-shadow:0 0 6px rgba(187,102,255,.15)}50%{transform:translateY(-4px);box-shadow:0 0 12px rgba(187,102,255,.25)}}
    .btn.primary.float{animation:floatPulse 6s ease-in-out infinite}

    /* Section: Sound Library */
    .section{max-width:1100px;margin:28px auto 0}
    .section-header{display:flex;flex-wrap:wrap;gap:12px;justify-content:space-between;align-items:center;margin-bottom:12px}
    .section-header h2{margin:0;font-size:20px}
    .filters{display:flex;gap:8px;flex-wrap:wrap}
    .filter-btn{
      font-size:12px;border:1px solid rgba(255,255,255,.18);background:transparent;color:var(--ink);
      padding:6px 10px;border-radius:999px;cursor:pointer
    }
    .filter-btn.active{border-color:var(--accent);color:var(--accent)}
    .audio-grid{display:grid;gap:12px;grid-template-columns:repeat(1,1fr)}
    @media(min-width:640px){.audio-grid{grid-template-columns:repeat(2,1fr)}}
    @media(min-width:980px){.audio-grid{grid-template-columns:repeat(3,1fr)}}
    @media(min-width:1200px){.audio-grid{grid-template-columns:repeat(4,1fr)}}
    .audio-card{
      border:1px solid rgba(255,255,255,.12);border-radius:12px;padding:12px;
      background:linear-gradient(145deg,rgba(30,30,40,.95),rgba(18,18,25,.95));
      box-shadow:0 1px 3px rgba(0,0,0,.25);
    }
    .audio-title{margin:0 0 2px;font-size:14px;font-weight:700}
    .audio-meta{margin:0 0 8px;font-size:12px;color:var(--muted);display:flex;gap:8px;flex-wrap:wrap}
    .badge-cat{border:1px solid rgba(255,255,255,.18);border-radius:6px;padding:2px 6px;font-size:11px}
    .audio-actions{margin-top:8px;display:flex;gap:8px;flex-wrap:wrap}
    .download-link{font-size:12px;color:var(--muted);text-decoration:none;border-bottom:1px dotted rgba(255,255,255,.25)}
    .download-link:hover{color:var(--accent);border-bottom-color:var(--accent)}

    /* Footer */
    .footer{max-width:1100px;margin:40px auto 0;display:flex;flex-wrap:wrap;gap:12px;justify-content:space-between;align-items:center;border-top:1px dashed rgba(255,255,255,.15);padding:16px 20px;color:var(--muted)}
    .bottom-note{font-size:9px;text-align:center;color:rgba(200,180,255,.12);margin:20px 0 16px}
  </style>

  <script>
    function openCalendly(url){
      if(!window.__calendlyLoaded){
        const l=document.createElement('link'); l.rel='stylesheet'; l.href='https://assets.calendly.com/assets/external/widget.css';
        const s=document.createElement('script'); s.async=true; s.src='https://assets.calendly.com/assets/external/widget.js';
        s.onload=function(){ window.__calendlyLoaded=true; Calendly.initPopupWidget({url}); };
        document.head.appendChild(l); document.head.appendChild(s);
      }else{ Calendly.initPopupWidget({url}); }
      return false;
    }

    // Audio filtering + one-at-a-time playback
    document.addEventListener('DOMContentLoaded', function(){
      const buttons = document.querySelectorAll('[data-filter]');
      const cards = document.querySelectorAll('.audio-card');
      const audios = document.querySelectorAll('audio');

      audios.forEach(a=>{
        a.addEventListener('play', ()=>{
          audios.forEach(b=>{ if(b!==a){ b.pause(); } });
        });
      });

      buttons.forEach(btn=>{
        btn.addEventListener('click', ()=>{
          buttons.forEach(b=>b.classList.remove('active'));
          btn.classList.add('active');
          const cat = btn.dataset.filter;
          cards.forEach(card=>{
            const c = card.dataset.category;
            card.style.display = (cat==='all' || c===cat) ? '' : 'none';
          });
        });
      });
    });
  </script>
</head>
<body>
  <div class="noticebar">
    <div class="notice-center">Call <strong>70-888-Swami</strong> • Michigan nonprofit — 501(c)(3) recognition pending</div>
    <div class="notice-right"><a href="mailto:AwoSwamiG@gmail.com">AwoSwamiG@gmail.com</a></div>
  </div>

  <!-- Top Cards -->
  <div class="top-cards-wrap">
    <div class="top-cards" aria-label="Quick actions">
      <div class="top-card"><h3>0 — Mission</h3><p>Our guiding vision and purpose</p></div>
      <div class="top-card"><h3>1 — Divination</h3><p>How to Divine classes w/ assignments</p></div>
      <div class="top-card"><h3>2 — Ilekes</h3><p>Coursework, rituals, consecrated beads & support</p></div>
      <div class="top-card"><h3>3 — Warriors</h3><p>È&#7779;ù • Ògún • Ò&#7779;óòsì • Ò&#7779;un</p></div>
      <div class="top-card"><h3>4 — Hand of Ifá</h3><p>Ìkín consecration / Ì&#7779;&#7865;&#768;&#7779;e</p></div>
      <div class="top-card"><h3>5 — Orisha Initiations</h3><p>Priesthood pathways & ceremonies</p></div>
      <div class="top-card">
        <a href="https://swamiginstitute.github.io/Lineage/" style="text-decoration:none; color:inherit;">
          <h3>6 — Lineage</h3>
          <p>Anke–Karade Lineage</p>
        </a>
      </div>
    </div>
  </div>

  <!-- Hero -->
  <div class="wrap">
    <div class="hero">
      <div class="hero-block">
        <div class="logo">
          <!-- Full-path logo -->
          <img src="https://swamiginstitute.github.io/SwamiG.gif" alt="SwamiG logo" loading="lazy" decoding="async" fetchpriority="high" />
        </div>
        <h1>SwamiG Institute</h1>
        <div class="tag">Ifá • Isésé • Orisha — Spiritual Education, Rites & Divination</div>
        <div class="badge">Michigan nonprofit • <strong>501(c)(3) recognition pending — $DrSwamiG</strong></div>
        <div class="actions">
          <a class="btn primary float" href="#" onclick="return openCalendly('https://calendly.com/awoswamig/30min');">Need a Divination?</a>
        </div>
      </div>
    </div>
  </div>

  <!-- Sound Library -->
  <section class="section" id="audio">
    <div class="section-header">
      <h2>Sound Library — Teachings, Chants & Practice</h2>
      <div class="filters" role="tablist" aria-label="Filter audio by category">
        <button class="filter-btn active" data-filter="all" role="tab" aria-selected="true">All</button>
        <button class="filter-btn" data-filter="teachings" role="tab" aria-selected="false">Teachings</button>
        <button class="filter-btn" data-filter="chants" role="tab" aria-selected="false">Chants</button>
        <button class="filter-btn" data-filter="testimonials" role="tab" aria-selected="false">Testimonials</button>
        <button class="filter-btn" data-filter="practice" role="tab" aria-selected="false">Practice</button>
      </div>
    </div>

    <div class="audio-grid">
      <!-- 1 -->
      <div class="audio-card" data-category="teachings">
        <h3 class="audio-title">01 — Ifá Orientation (Intro)</h3>
        <div class="audio-meta"><span class="badge-cat">Teachings</span><span>~6:20</span></div>
        <audio controls preload="none"><source src="https://swamiginstitute.github.io/audio1.mp3" type="audio/mpeg" /></audio>
        <div class="audio-actions"><a class="download-link" href="https://swamiginstitute.github.io/audio1.mp3" download>Download MP3</a></div>
      </div>
      <!-- 2 -->
      <div class="audio-card" data-category="teachings">
        <h3 class="audio-title">02 — Asking Questions for Divination</h3>
        <div class="audio-meta"><span class="badge-cat">Teachings</span><span>~7:15</span></div>
        <audio controls preload="none"><source src="https://swamiginstitute.github.io/audio2.mp3" type="audio/mpeg" /></audio>
        <div class="audio-actions"><a class="download-link" href="https://swamiginstitute.github.io/audio2.mp3" download>Download MP3</a></div>
      </div>
      <!-- 3 -->
      <div class="audio-card" data-category="teachings">
        <h3 class="audio-title">03 — Casting & Response Basics</h3>
        <div class="audio-meta"><span class="badge-cat">Teachings</span><span>~8:40</span></div>
        <audio controls preload="none"><source src="https://swamiginstitute.github.io/audio3.mp3" type="audio/mpeg" /></audio>
        <div class="audio-actions"><a class="download-link" href="https://swamiginstitute.github.io/audio3.mp3" download>Download MP3</a></div>
      </div>
      <!-- 4 -->
      <div class="audio-card" data-category="chants">
        <h3 class="audio-title">04 — Morning Chant (È&#7779;ù Invocation)</h3>
        <div class="audio-meta"><span class="badge-cat">Chants</span><span>~3:05</span></div>
        <audio controls preload="none"><source src="https://swamiginstitute.github.io/audio4.mp3" type="audio/mpeg" /></audio>
        <div class="audio-actions"><a class="download-link" href="https://swamiginstitute.github.io/audio4.mp3" download>Download MP3</a></div>
      </div>
      <!-- 5 -->
      <div class="audio-card" data-category="chants">
        <h3 class="audio-title">05 — Evening Chant (Ò&#7779;un Blessing)</h3>
        <div class="audio-meta"><span class="badge-cat">Chants</span><span>~2:42</span></div>
        <audio controls preload="none"><source src="https://swamiginstitute.github.io/audio5.mp3" type="audio/mpeg" /></audio>
        <div class="audio-actions"><a class="download-link" href="https://swamiginstitute.github.io/audio5.mp3" download>Download MP3</a></div>
      </div>
      <!-- 6 -->
      <div class="audio-card" data-category="practice">
        <h3 class="audio-title">06 — Guided Practice: Centering Breath</h3>
        <div class="audio-meta"><span class="badge-cat">Practice</span><span>~5:10</span></div>
        <audio controls preload="none"><source src="https://swamiginstitute.github.io/audio6.mp3" type="audio/mpeg" /></audio>
        <div class="audio-actions"><a class="download-link" href="https://swamiginstitute.github.io/audio6.mp3" download>Download MP3</a></div>
      </div>
      <!-- 7 -->
      <div class="audio-card" data-category="practice">
        <h3 class="audio-title">07 — Guided Practice: Casting Rhythm</h3>
        <div class="audio-meta"><span class="badge-cat">Practice</span><span>~4:20</span></div>
        <audio controls preload="none"><source src="https://swamiginstitute.github.io/audio7.mp3" type="audio/mpeg" /></audio>
        <div class="audio-actions"><a class="download-link" href="https://swamiginstitute.github.io/audio7.mp3" download>Download MP3</a></div>
      </div>
      <!-- 8 -->
      <div class="audio-card" data-category="testimonials">
        <h3 class="audio-title">08 — Testimonial: New Student Experience</h3>
        <div class="audio-meta"><span class="badge-cat">Testimonials</span><span>~2:55</span></div>
        <audio controls preload="none"><source src="https://swamiginstitute.github.io/audio8.mp3" type="audio/mpeg" /></audio>
        <div class="audio-actions"><a class="download-link" href="https://swamiginstitute.github.io/audio8.mp3" download>Download MP3</a></div>
      </div>
      <!-- 9 -->
      <div class="audio-card" data-category="testimonials">
        <h3 class="audio-title">09 — Testimonial: Initiation Journey</h3>
        <div class="audio-meta"><span class="badge-cat">Testimonials</span><span>~3:30</span></div>
        <audio controls preload="none"><source src="https://swamiginstitute.github.io/audio9.mp3" type="audio/mpeg" /></audio>
        <div class="audio-actions"><a class="download-link" href="https://swamiginstitute.github.io/audio9.mp3" download>Download MP3</a></div>
      </div>
      <!-- 10 -->
      <div class="audio-card" data-category="teachings">
        <h3 class="audio-title">10 — Ethics & Responsibility in Divination</h3>
        <div class="audio-meta"><span class="badge-cat">Teachings</span><span>~6:05</span></div>
        <audio controls preload="none"><source src="https://swamiginstitute.github.io/audio10.mp3" type="audio/mpeg" /></audio>
        <div class="audio-actions"><a class="download-link" href="https://swamiginstitute.github.io/audio10.mp3" download>Download MP3</a></div>
      </div>
    </div>
  </section>

  <!-- Footer -->
  <div class="footer">
    <div>©2025 SwamiG Institute</div>
    <div>$DrSwamiG • <a class="download-link" href="https://www.paypal.com/ncp/payment/5M949GKNMDHJN" target="_blank" rel="noopener">Donate via PayPal</a></div>
  </div>
  <div class="bottom-note">supported by Amen(Obara)/Heru(Oyeku)</div>
</body>
</html>
