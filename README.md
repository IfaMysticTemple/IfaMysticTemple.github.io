<!DOCTYPE html>
<html lang="en">
<head>
  <!-- Ifá Mystic Storage — Landing Page (SwamiG Institute) -->
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <meta name="theme-color" content="#0b0b0f" />
  <meta name="color-scheme" content="dark" />
  <title>Ifá Mystic Storage — SwamiG Institute | Audio • PDFs • Images • Initiation Resources</title>
  <meta name="description" content="Central storage for Ifá / Isésé / Orisha study materials by SwamiG Institute — audio teachings, PDFs, images, and initiation resources. Michigan nonprofit — 501(c)(3) recognition pending." />
  <meta name="generator" content="SwamiGInstitute.com 70-888-Swami" />

  <style>
    :root{
      --bg:#0b0b0f;
      --panel:#111219;
      --ink:#eaeaf2;
      --muted:#b5b5c4;
      --accent:#bb66ff;
      --accent-2:#66ffd1;
      --ring:rgba(187,102,255,0.35);
      --radius:20px;
      --shadow:0 10px 30px rgba(0,0,0,.45);
    }
    *{box-sizing:border-box}
    html,body{scroll-behavior:smooth}
    body{
      margin:0;
      font:400 16px/1.6 system-ui,-apple-system,Segoe UI,Roboto,Inter,Arial,sans-serif;
      background: radial-gradient(1200px 700px at 15% -10%, #1a1622 0%, #0b0b0f 45%) no-repeat fixed;
      color:var(--ink);
    }
    a{color:var(--accent-2);text-decoration:none}
    a:hover{text-decoration:underline}
    .wrap{max-width:1100px;margin:0 auto;padding:24px}

    /* Top bar */
    .topbar{
      display:grid;grid-template-columns:auto 1fr auto;gap:16px;align-items:center;
    }
    .logo{
      display:flex;align-items:center;gap:14px
    }
    .logo img{width:84px;height:auto;border-radius:50%;box-shadow:0 0 0 3px rgba(255,255,255,.04)}
    .brand h1{font-size:20px;margin:0 0 4px 0;letter-spacing:.3px}
    .brand small{color:var(--muted)}
    .contact{justify-self:end;text-align:right}
    .contact a{display:inline-block;padding:6px 10px;border:1px solid rgba(255,255,255,.08);border-radius:10px}
    .paylinks{margin-top:6px;font-size:14px;color:var(--muted)}
    .paylinks b{color:var(--ink)}

    /* Hero */
    .hero{
      margin:28px 0 18px;
      display:grid;grid-template-columns:1.05fr .95fr;gap:22px
    }
    @media (max-width:900px){.hero{grid-template-columns:1fr}}
    .card{
      background:linear-gradient(180deg,rgba(255,255,255,.03),rgba(255,255,255,.01));
      border:1px solid rgba(255,255,255,.08);
      border-radius:var(--radius);
      box-shadow:var(--shadow);
    }
    .card.pad{padding:20px}
    .glow{box-shadow:0 0 0 2px var(--ring), var(--shadow)}
    .hero h2{margin:.1rem 0 6px;font-size:28px}
    .hero p{margin:0;color:var(--muted)}
    .tagrow{margin-top:12px;display:flex;flex-wrap:wrap;gap:8px}
    .tag{font-size:13px;padding:6px 10px;border:1px solid rgba(255,255,255,.1);border-radius:999px;color:var(--muted)}

    /* Subtle CTA: Need a divination? (toned down pulse + float) */
    .cta{
      position:relative;isolation:isolate;overflow:hidden
    }
    .cta a{
      display:inline-block;margin-top:10px;
      padding:10px 14px;border-radius:999px;border:1px dashed rgba(255,255,255,.12);
      color:var(--muted);text-decoration:none;
      filter:saturate(.85) brightness(.95);opacity:.8;
      animation:float 6s ease-in-out infinite, pulse 4.5s ease-in-out infinite;
    }
    @keyframes pulse{0%,100%{box-shadow:0 0 0 0 rgba(102,255,209,.0)}50%{box-shadow:0 0 0 6px rgba(102,255,209,.06)}}
    @keyframes float{0%,100%{transform:translateY(0)}50%{transform:translateY(-4px)}}
    .cta a:hover{opacity:1}

    /* Top cards */
    .tops{display:grid;grid-template-columns:repeat(5,1fr);gap:16px;margin:20px 0 6px}
    @media (max-width:1100px){.tops{grid-template-columns:repeat(3,1fr)}}
    @media (max-width:720px){.tops{grid-template-columns:repeat(2,1fr)}}
    .topcard{
      padding:14px;border-radius:16px;background:var(--panel);
      border:1px solid rgba(255,255,255,.08);
      transition:.2s transform ease, .2s border-color ease;
      min-height:96px;display:flex;flex-direction:column;justify-content:space-between
    }
    .topcard:hover{transform:translateY(-2px);border-color:rgba(255,255,255,.18)}
    .topcard h3{margin:2px 0 4px;font-size:16px}
    .topcard small{color:var(--muted)}

    /* Storage grid */
    section h2{font-size:22px;margin:18px 0 10px}
    .grid{
      display:grid;
      grid-template-columns:repeat(5,1fr);
      gap:14px;
    }
    @media (max-width:1100px){.grid{grid-template-columns:repeat(3,1fr)}}
    @media (max-width:720px){.grid{grid-template-columns:repeat(1,1fr)}}
    .item{
      background:var(--panel);
      border:1px solid rgba(255,255,255,.08);
      border-radius:16px;padding:12px
    }
    .item h4{margin:.2rem 0 .4rem;font-size:15px}
    .meta{font-size:12px;color:var(--muted);margin-bottom:8px}
    .actions{display:flex;gap:10px;flex-wrap:wrap}
    .btn{
      display:inline-flex;align-items:center;gap:8px;
      border:1px solid rgba(255,255,255,.14);
      border-radius:12px;padding:8px 10px;font-size:14px;color:var(--ink);text-decoration:none
    }
    .btn:hover{border-color:rgba(255,255,255,.24)}
    audio{width:100%;height:32px;margin:8px 0 2px}

    /* Footer */
    footer{
      margin:30px 0 10px;padding:20px;border-top:1px solid rgba(255,255,255,.08);
      color:var(--muted);font-size:13px;text-align:center
    }
    .whisper{opacity:.35;margin-top:10px;font-size:12px}
  </style>
</head>
<body>
  <div class="wrap">
    <!-- Topbar -->
    <div class="topbar">
      <div class="logo">
        <!-- Full path logo (absolute URL) -->
        <img src="http://myoracle.itgo.com/SwamiG.gif" alt="SwamiG Institute Logo" />
        <div class="brand">
          <h1>SwamiG Institute — Ifá • Isésé • Orisha</h1>
          <small>70-888-Swami • “Many paths 1 truth” • “We seek no followers”</small>
        </div>
      </div>
      <div></div>
      <div class="contact">
        <a href="mailto:AwoSwamiG@gmail.com">AwoSwamiG@gmail.com</a>
        <div class="paylinks">
          <b>Pay:</b> <a href="https://www.paypal.com/ncp/payment/5M949GKNMDHJN">PayPal</a> • Cash App <b>$DrSwamiG</b>
        </div>
      </div>
    </div>

    <!-- Hero: Title + Mission (side-by-side) -->
    <section class="hero">
      <div class="card pad glow">
        <h2>Ifá Mystic Storage</h2>
        <p>Central access to sacred study assets for students and initiates — audio teachings, PDFs, images, and lineage resources organized for quick reference and sharing.</p>
        <div class="tagrow">
          <span class="tag">Audio Lectures</span>
          <span class="tag">Ritual PDFs</span>
          <span class="tag">Herbal Oracle</span>
          <span class="tag">Merindilogun</span>
          <span class="tag">Opele Training</span>
        </div>
        <div class="cta">
          <!-- toned-down, gentle pulse + float -->
          <a href="#consult">Need a divination?</a>
        </div>
      </div>

      <!-- “0-Mission” card -->
      <div class="card pad" style="background:linear-gradient(180deg,rgba(0,0,0,.20),rgba(0,0,0,.10))">
        <h2>Mission (0-Card)</h2>
        <p style="color:var(--muted)">
          To preserve, teach, and responsibly transmit Ifá / Isésé / Orisha wisdom through practical training modules,
          rites of passage, and accessible digital libraries that empower seekers to study, practice, and serve.
        </p>
      </div>
    </section>

    <!-- Top Cards (quick links) -->
    <div class="tops" aria-label="Quick Links">
      <a class="topcard" href="#audio">
        <div>
          <h3>Audio Library</h3>
          <small>10 curated sound clips to begin</small>
        </div>
        <small>MP3 • Commentary</small>
      </a>
      <a class="topcard" href="#pdfs">
        <div>
          <h3>PDF Vault</h3>
          <small>Lessons, prayers, assignments</small>
        </div>
        <small>Printable</small>
      </a>
      <a class="topcard" href="#images">
        <div>
          <h3>Image Sets</h3>
          <small>Herbal Oracle • Diagrams</small>
        </div>
        <small>PNG • JPG</small>
      </a>
      <a class="topcard" href="https://swamiginstitute.github.io/Lineage/" target="_blank" rel="noopener">
        <div>
          <h3>Lineage</h3>
          <small>Anke-Karade Lineage overview</small>
        </div>
        <small>External Link</small>
      </a>
      <a class="topcard" href="#initiations">
        <div>
          <h3>Orisha Initiations</h3>
          <small>Overview • Inquiry</small>
        </div>
        <small>Contact for details</small>
      </a>
    </div>

    <!-- AUDIO LIBRARY (10 clips) -->
    <section id="audio">
      <h2>Audio Library (10 clips)</h2>
      <div class="grid">
        <!-- NOTE: Replace the full paths below with your actual absolute URLs on GitHub Pages, Drive (public), or your CDN. -->
        <div class="item">
          <h4>01 • Opening Prayer (Ifá)</h4>
          <div class="meta">Full path: https://swamiginstitute.github.io/media/ifa-mystic/clip01-opening-prayer.mp3</div>
          <audio controls src="https://swamiginstitute.github.io/media/ifa-mystic/clip01-opening-prayer.mp3"></audio>
          <div class="actions">
            <a class="btn" href="https://swamiginstitute.github.io/media/ifa-mystic/clip01-opening-prayer.mp3" download>Download MP3</a>
            <a class="btn" href="#transcript-01">Transcript</a>
          </div>
        </div>

        <div class="item">
          <h4>02 • Orientation to Study</h4>
          <div class="meta">Full path: https://swamiginstitute.github.io/media/ifa-mystic/clip02-orientation.mp3</div>
          <audio controls src="https://swamiginstitute.github.io/media/ifa-mystic/clip02-orientation.mp3"></audio>
          <div class="actions">
            <a class="btn" href="https://swamiginstitute.github.io/media/ifa-mystic/clip02-orientation.mp3" download>Download MP3</a>
            <a class="btn" href="#transcript-02">Transcript</a>
          </div>
        </div>

        <div class="item">
          <h4>03 • Asking Good Questions</h4>
          <div class="meta">Full path: https://swamiginstitute.github.io/media/ifa-mystic/clip03-asking-questions.mp3</div>
          <audio controls src="https://swamiginstitute.github.io/media/ifa-mystic/clip03-asking-questions.mp3"></audio>
          <div class="actions">
            <a class="btn" href="https://swamiginstitute.github.io/media/ifa-mystic/clip03-asking-questions.mp3" download>Download MP3</a>
            <a class="btn" href="#transcript-03">Transcript</a>
          </div>
        </div>

        <div class="item">
          <h4>04 • Casting Basics</h4>
          <div class="meta">Full path: https://swamiginstitute.github.io/media/ifa-mystic/clip04-casting-basics.mp3</div>
          <audio controls src="https://swamiginstitute.github.io/media/ifa-mystic/clip04-casting-basics.mp3"></audio>
          <div class="actions">
            <a class="btn" href="https://swamiginstitute.github.io/media/ifa-mystic/clip04-casting-basics.mp3" download>Download MP3</a>
            <a class="btn" href="#transcript-04">Transcript</a>
          </div>
        </div>

        <div class="item">
          <h4>05 • Reading Responses</h4>
          <div class="meta">Full path: https://swamiginstitute.github.io/media/ifa-mystic/clip05-reading-responses.mp3</div>
          <audio controls src="https://swamiginstitute.github.io/media/ifa-mystic/clip05-reading-responses.mp3"></audio>
          <div class="actions">
            <a class="btn" href="https://swamiginstitute.github.io/media/ifa-mystic/clip05-reading-responses.mp3" download>Download MP3</a>
            <a class="btn" href="#transcript-05">Transcript</a>
          </div>
        </div>

        <div class="item">
          <h4>06 • Ethical Practice</h4>
          <div class="meta">Full path: https://swamiginstitute.github.io/media/ifa-mystic/clip06-ethics.mp3</div>
          <audio controls src="https://swamiginstitute.github.io/media/ifa-mystic/clip06-ethics.mp3"></audio>
          <div class="actions">
            <a class="btn" href="https://swamiginstitute.github.io/media/ifa-mystic/clip06-ethics.mp3" download>Download MP3</a>
            <a class="btn" href="#transcript-06">Transcript</a>
          </div>
        </div>

        <div class="item">
          <h4>07 • Herbal Oracle Primer</h4>
          <div class="meta">Full path: https://swamiginstitute.github.io/media/ifa-mystic/clip07-herbal-oracle.mp3</div>
          <audio controls src="https://swamiginstitute.github.io/media/ifa-mystic/clip07-herbal-oracle.mp3"></audio>
          <div class="actions">
            <a class="btn" href="https://swamiginstitute.github.io/media/ifa-mystic/clip07-herbal-oracle.mp3" download>Download MP3</a>
            <a class="btn" href="#transcript-07">Transcript</a>
          </div>
        </div>

        <div class="item">
          <h4>08 • Obi-Pele Overview</h4>
          <div class="meta">Full path: https://swamiginstitute.github.io/media/ifa-mystic/clip08-obi-pele.mp3</div>
          <audio controls src="https://swamiginstitute.github.io/media/ifa-mystic/clip08-obi-pele.mp3"></audio>
          <div class="actions">
            <a class="btn" href="https://swamiginstitute.github.io/media/ifa-mystic/clip08-obi-pele.mp3" download>Download MP3</a>
            <a class="btn" href="#transcript-08">Transcript</a>
          </div>
        </div>

        <div class="item">
          <h4>09 • Merindilogun Practice</h4>
          <div class="meta">Full path: https://swamiginstitute.github.io/media/ifa-mystic/clip09-merindilogun.mp3</div>
          <audio controls src="https://swamiginstitute.github.io/media/ifa-mystic/clip09-merindilogun.mp3"></audio>
          <div class="actions">
            <a class="btn" href="https://swamiginstitute.github.io/media/ifa-mystic/clip09-merindilogun.mp3" download>Download MP3</a>
            <a class="btn" href="#transcript-09">Transcript</a>
          </div>
        </div>

        <div class="item">
          <h4>10 • Closing Prayer & Charge</h4>
          <div class="meta">Full path: https://swamiginstitute.github.io/media/ifa-mystic/clip10-closing-prayer.mp3</div>
          <audio controls src="https://swamiginstitute.github.io/media/ifa-mystic/clip10-closing-prayer.mp3"></audio>
          <div class="actions">
            <a class="btn" href="https://swamiginstitute.github.io/media/ifa-mystic/clip10-closing-prayer.mp3" download>Download MP3</a>
            <a class="btn" href="#transcript-10">Transcript</a>
          </div>
        </div>
      </div>
    </section>

    <!-- PDF VAULT -->
    <section id="pdfs">
      <h2>PDF Vault</h2>
      <div class="grid">
        <div class="item">
          <h4>Study Guide: Ifá Mystic Starter</h4>
          <div class="meta">Full path: https://swamiginstitute.github.io/media/ifa-mystic/ifa-mystic-starter.pdf</div>
          <div class="actions">
            <a class="btn" href="https://swamiginstitute.github.io/media/ifa-mystic/ifa-mystic-starter.pdf" target="_blank" rel="noopener">Open PDF</a>
            <a class="btn" href="https://swamiginstitute.github.io/media/ifa-mystic/ifa-mystic-starter.pdf" download>Download</a>
          </div>
        </div>
        <div class="item">
          <h4>Assignment: On the Mat with Opele</h4>
          <div class="meta">Full path: https://swamiginstitute.github.io/media/ifa-mystic/opele-on-the-mat-assignment.pdf</div>
          <div class="actions">
            <a class="btn" href="https://swamiginstitute.github.io/media/ifa-mystic/opele-on-the-mat-assignment.pdf" target="_blank" rel="noopener">Open PDF</a>
            <a class="btn" href="https://swamiginstitute.github.io/media/ifa-mystic/opele-on-the-mat-assignment.pdf" download>Download</a>
          </div>
        </div>
        <div class="item">
          <h4>Merindilogun Certificate Template</h4>
          <div class="meta">Full path: https://swamiginstitute.github.io/media/ifa-mystic/merindilogun-certificate-template.pdf</div>
          <div class="actions">
            <a class="btn" href="https://swamiginstitute.github.io/media/ifa-mystic/merindilogun-certificate-template.pdf" target="_blank" rel="noopener">Open PDF</a>
            <a class="btn" href="https://swamiginstitute.github.io/media/ifa-mystic/merindilogun-certificate-template.pdf" download>Download</a>
          </div>
        </div>
      </div>
    </section>

    <!-- IMAGE SETS -->
    <section id="images">
      <h2>Image Sets</h2>
      <div class="grid">
        <div class="item">
          <h4>Herbal Oracle — 14 Plants (Sheet)</h4>
          <div class="meta">Full path: https://swamiginstitute.github.io/media/ifa-mystic/herbal-oracle-14.png</div>
          <div class="actions">
            <a class="btn" href="https://swamiginstitute.github.io/media/ifa-mystic/herbal-oracle-14.png" target="_blank" rel="noopener">Open Image</a>
            <a class="btn" href="https://swamiginstitute.github.io/media/ifa-mystic/herbal-oracle-14.png" download>Download</a>
          </div>
        </div>
        <div class="item">
          <h4>Khemti Tree of Life Diagram</h4>
          <div class="meta">Full path: https://swamiginstitute.github.io/media/ifa-mystic/khemti-tree-of-life.png</div>
          <div class="actions">
            <a class="btn" href="https://swamiginstitute.github.io/media/ifa-mystic/khemti-tree-of-life.png" target="_blank" rel="noopener">Open Image</a>
            <a class="btn" href="https://swamiginstitute.github.io/media/ifa-mystic/khemti-tree-of-life.png" download>Download</a>
          </div>
        </div>
        <div class="item">
          <h4>Lineage Crest (Anke-Karade)</h4>
          <div class="meta">Full path: https://swamiginstitute.github.io/media/ifa-mystic/anke-karade-crest.png</div>
          <div class="actions">
            <a class="btn" href="https://swamiginstitute.github.io/media/ifa-mystic/anke-karade-crest.png" target="_blank" rel="noopener">Open Image</a>
            <a class="btn" href="https://swamiginstitute.github.io/media/ifa-mystic/anke-karade-crest.png" download>Download</a>
          </div>
        </div>
      </div>
    </section>

    <!-- INITIATIONS -->
    <section id="initiations">
      <h2>Orisha Initiations — Overview</h2>
      <div class="grid">
        <div class="item">
          <h4>Inquiry & Readiness</h4>
          <p class="meta">Begin with divination and orientation. Logistics, offerings, and preparation are determined case-by-case.</p>
          <div class="actions">
            <a class="btn" href="#consult">Start Inquiry</a>
            <a class="btn" href="mailto:AwoSwamiG@gmail.com">Email</a>
          </div>
        </div>
        <div class="item">
          <h4>Support the Work</h4>
          <p class="meta">Your generosity sustains training modules, storage, and scholarships.</p>
          <div class="actions">
            <a class="btn" href="https://www.paypal.com/ncp/payment/5M949GKNMDHJN">PayPal</a>
            <a class="btn" href="#pay-cashapp">$DrSwamiG</a>
          </div>
        </div>
      </div>
    </section>

    <!-- CONSULT CTA ANCHOR -->
    <section id="consult" class="card pad" style="margin-top:18px">
      <h2>Divination & Consults</h2>
      <p class="meta">Schedule a reading to clarify path, purpose, and next steps. Remote sessions available.</p>
      <div class="actions">
        <a class="btn" href="mailto:AwoSwamiG@gmail.com?subject=Divination%20Inquiry">Email for Scheduling</a>
        <a class="btn" href="https://www.paypal.com/ncp/payment/5M949GKNMDHJN">Honorarium via PayPal</a>
        <span class="btn" aria-disabled="true">Cash App: $DrSwamiG</span>
      </div>
    </section>

    <!-- Bottom Pay Links (as requested: show near top and bottom) -->
    <section style="margin-top:16px" class="card pad">
      <h2>Support Ifá Mystic Storage</h2>
      <p class="meta">Help us maintain and expand this library for students and initiates.</p>
      <div class="actions">
        <a class="btn" href="https://www.paypal.com/ncp/payment/5M949GKNMDHJN">PayPal</a>
        <span class="btn">Cash App: $DrSwamiG</span>
      </div>
    </section>

    <footer>
      © <span id="yr"></span> SwamiG Institute • Michigan nonprofit — 501(c)(3) recognition pending
      <div class="whisper">supported by Amen (Obara) / Heru (Oyeku)</div>
    </footer>
  </div>

  <script>
    // Year
    document.getElementById('yr').textContent = new Date().getFullYear();

    // (Optional) If you later want to lazy-swap .audio sources via data-src:
    // document.querySelectorAll('audio[data-src]').forEach(a=>{ a.src=a.dataset.src; });
  </script>
</body>
</html>
