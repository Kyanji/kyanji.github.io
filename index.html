<!doctype html>
<html lang="it">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>⚠️ NON DOVEVI CLICCARE</title>
  <meta name="description" content="Pagina cyber glitch che finge di essere rotta." />
  <style>
    :root{
      --bg:#07070a;
      --fg:#e7e7ee;
      --muted:#9aa0a6;
      --accent:#00ff9c;
      --warn:#ff3b3b;
      --cyan:#00d9ff;
      --mag:#ff00c8;
    }
    html,body{height:100%}
    body{
      margin:0;
      background:
        radial-gradient(800px 500px at 20% 10%, rgba(0,255,156,.12), transparent 60%),
        radial-gradient(700px 450px at 80% 20%, rgba(255,0,200,.12), transparent 55%),
        radial-gradient(900px 600px at 50% 100%, rgba(0,217,255,.10), transparent 60%),
        var(--bg);
      color:var(--fg);
      font-family: ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, "Liberation Mono", monospace;
      overflow:hidden;
    }

    /* scanlines + noise */
    .overlay::before{
      content:"";
      position:fixed; inset:0;
      background:
        repeating-linear-gradient(
          to bottom,
          rgba(255,255,255,.05),
          rgba(255,255,255,.05) 1px,
          rgba(0,0,0,0) 2px,
          rgba(0,0,0,0) 4px
        );
      mix-blend-mode: overlay;
      pointer-events:none;
      opacity:.25;
    }
    .overlay::after{
      content:"";
      position:fixed; inset:-50px;
      background-image:url("data:image/svg+xml,%3Csvg xmlns='http://www.w3.org/2000/svg' width='180' height='180'%3E%3Cfilter id='n'%3E%3CfeTurbulence type='fractalNoise' baseFrequency='.8' numOctaves='3' stitchTiles='stitch'/%3E%3C/filter%3E%3Crect width='180' height='180' filter='url(%23n)' opacity='.25'/%3E%3C/svg%3E");
      opacity:.08;
      pointer-events:none;
      animation: drift 8s linear infinite;
    }
    @keyframes drift{
      0%{transform:translate(0,0)}
      100%{transform:translate(50px,30px)}
    }

    .wrap{
      height:100%;
      display:grid;
      place-items:center;
      padding:32px;
    }

    .card{
      width:min(900px, 100%);
      border:1px solid rgba(255,255,255,.12);
      background:rgba(10,10,14,.55);
      box-shadow: 0 20px 80px rgba(0,0,0,.6);
      border-radius:14px;
      overflow:hidden;
      position:relative;
    }

    .topbar{
      display:flex;
      align-items:center;
      gap:10px;
      padding:12px 14px;
      border-bottom:1px solid rgba(255,255,255,.10);
      background:rgba(0,0,0,.25);
    }
    .dot{width:10px;height:10px;border-radius:50%}
    .dot.r{background:#ff5f56}
    .dot.y{background:#ffbd2e}
    .dot.g{background:#27c93f}
    .title{
      margin-left:8px;
      font-size:12px;
      color:var(--muted);
      user-select:none;
    }

    .content{
      padding:26px 22px 18px;
      display:grid;
      gap:16px;
    }

    .glitch{
      font-size: clamp(28px, 4vw, 54px);
      font-weight:900;
      letter-spacing:.5px;
      position:relative;
      display:inline-block;
      line-height:1.05;
      text-transform:uppercase;
      user-select:none;
    }
    .glitch::before, .glitch::after{
      content:attr(data-text);
      position:absolute; inset:0;
      opacity:.85;
      pointer-events:none;
    }
    .glitch::before{
      transform:translate(2px,0);
      color:var(--cyan);
      clip-path: inset(0 0 55% 0);
      animation: g1 2.3s infinite linear alternate-reverse;
    }
    .glitch::after{
      transform:translate(-2px,0);
      color:var(--mag);
      clip-path: inset(45% 0 0 0);
      animation: g2 1.9s infinite linear alternate-reverse;
    }
    @keyframes g1{
      0%{clip-path: inset(0 0 60% 0)}
      20%{clip-path: inset(10% 0 45% 0)}
      40%{clip-path: inset(0 0 70% 0)}
      60%{clip-path: inset(22% 0 40% 0)}
      80%{clip-path: inset(2% 0 58% 0)}
      100%{clip-path: inset(15% 0 55% 0)}
    }
    @keyframes g2{
      0%{clip-path: inset(40% 0 0 0)}
      25%{clip-path: inset(55% 0 0 0)}
      50%{clip-path: inset(35% 0 0 0)}
      75%{clip-path: inset(62% 0 0 0)}
      100%{clip-path: inset(48% 0 0 0)}
    }

    .sub{
      color:var(--muted);
      font-size:14px;
      line-height:1.5;
    }

    .terminal{
      border:1px solid rgba(0,255,156,.25);
      background:rgba(0,0,0,.35);
      border-radius:12px;
      padding:14px 14px 10px;
      position:relative;
      overflow:hidden;
    }
    .terminal::before{
      content:"";
      position:absolute; inset:0;
      background: linear-gradient(90deg, transparent, rgba(0,255,156,.08), transparent);
      transform:translateX(-100%);
      animation:sweep 3.2s infinite;
    }
    @keyframes sweep{
      0%{transform:translateX(-120%)}
      60%{transform:translateX(120%)}
      100%{transform:translateX(120%)}
    }
    .line{
      display:flex;
      gap:8px;
      white-space:pre-wrap;
      font-size:13px;
      line-height:1.45;
      position:relative;
      z-index:1;
    }
    .prompt{color:var(--accent)}
    .dim{color:#7c848c}
    .warn{color:var(--warn)}
    .ok{color:var(--accent)}
    .cursor{
      display:inline-block;
      width:10px;
      margin-left:2px;
      background:var(--fg);
      animation: blink 1s steps(2) infinite;
      height:1.1em;
      vertical-align:-2px;
    }
    @keyframes blink{50%{opacity:0}}

    .actions{
      display:flex;
      flex-wrap:wrap;
      gap:10px;
      padding-top:4px;
    }
    button{
      appearance:none;
      border:1px solid rgba(255,255,255,.16);
      background:rgba(255,255,255,.06);
      color:var(--fg);
      border-radius:10px;
      padding:10px 12px;
      font-family:inherit;
      font-size:13px;
      cursor:pointer;
      transition: transform .08s ease, background .2s ease, border-color .2s ease;
    }
    button:hover{
      border-color: rgba(0,255,156,.5);
      background: rgba(0,255,156,.10);
    }
    button:active{transform: translateY(1px) scale(.99)}
    .danger:hover{
      border-color: rgba(255,59,59,.7);
      background: rgba(255,59,59,.10);
    }

    .footer{
      padding:14px 22px 20px;
      border-top:1px solid rgba(255,255,255,.10);
      display:flex;
      justify-content:space-between;
      gap:10px;
      color:var(--muted);
      font-size:12px;
    }
    .pill{
      border:1px solid rgba(255,255,255,.14);
      padding:6px 10px;
      border-radius:999px;
      background:rgba(0,0,0,.18);
    }

    /* "broken" shake */
    .shake{
      animation: shake .12s linear 0s 6;
    }
    @keyframes shake{
      0%{transform:translate(0,0)}
      25%{transform:translate(2px,-1px)}
      50%{transform:translate(-2px,1px)}
      75%{transform:translate(1px,2px)}
      100%{transform:translate(0,0)}
    }

    /* modal */
    .modal{
      position:fixed; inset:0;
      display:none;
      place-items:center;
      background: rgba(0,0,0,.65);
      padding:24px;
      z-index:99;
    }
    .modal.open{display:grid}
    .modalbox{
      width:min(720px, 100%);
      border-radius:14px;
      border:1px solid rgba(255,255,255,.12);
      background:rgba(10,10,14,.85);
      padding:18px 18px 14px;
      box-shadow: 0 30px 120px rgba(0,0,0,.7);
    }
    .modalbox h2{
      margin:0 0 8px;
      font-size:18px;
      letter-spacing:.3px;
    }
    .modalbox p{
      margin:0 0 12px;
      color:var(--muted);
      line-height:1.5;
      font-size:13px;
    }
    .kbd{
      border:1px solid rgba(255,255,255,.18);
      border-bottom-color: rgba(255,255,255,.28);
      padding:2px 6px;
      border-radius:6px;
      background:rgba(255,255,255,.06);
      color:var(--fg);
      font-size:12px;
    }
  </style>
</head>

<body class="overlay">
  <div class="wrap">
    <div class="card" id="card">
      <div class="topbar">
        <span class="dot r"></span><span class="dot y"></span><span class="dot g"></span>
        <span class="title">root@localhost:~ / accesso non autorizzato (più o meno)</span>
      </div>

      <div class="content">
        <div class="glitch" data-text="NON DOVEVI CLICCARE.">NON DOVEVI CLICCARE.</div>
        <div class="sub">
          Hai appena attivato il <span class="warn">protocollo anti-curiosità</span>.
          Nessun dato è stato rubato (tranquillo), ma adesso sei ufficialmente nella lista:
          <span class="dim">/var/log/ego.log</span>.
        </div>

        <div class="terminal" aria-label="finto terminale">
          <div class="line"><span class="prompt">[sudo]</span> <span class="dim">verifica intenzioni utente...</span></div>
          <div class="line"><span class="dim">→ fingerprint:</span> <span id="fp" class="ok">calcolo...</span></div>
          <div class="line"><span class="dim">→ stato:</span> <span id="status" class="warn">SOSPETTO</span></div>
          <div class="line"><span class="dim">→ azione:</span> <span id="action" class="dim">in attesa di input</span><span class="cursor"></span></div>
        </div>

        <div class="actions">
          <button id="btn1">Ok, ho capito 😅</button>
          <button id="btn2">Mostra “cosa ho rotto”</button>
          <button id="btn3" class="danger">DISATTIVA SICUREZZA (non farlo)</button>
        </div>
      </div>

      <div class="footer">
        <span class="pill">build: glitch-ops/1.0</span>
        <span class="pill">modalità: <span id="mode">read-only</span></span>
        <span class="pill">telemetria: <span class="ok">finta</span></span>
      </div>
    </div>
  </div>

  <div class="modal" id="modal" role="dialog" aria-modal="true" aria-labelledby="mtitle">
    <div class="modalbox">
      <h2 id="mtitle">🧩 Diagnostica: “cosa hai rotto”</h2>
      <p>
        Risultato analisi: hai rotto solo la tua <b>copertura</b>. Sei entrato in una pagina che finge di essere compromessa.
        In realtà è solo HTML/CSS/JS con un po’ di caos controllato.
      </p>
      <p>
        Suggerimento da “esperto cyber”: se una pagina ti dice <i>non cliccare</i>, di solito è social engineering.
        Qui invece è solo una battuta.
      </p>
      <p class="dim">Chiudi con <span class="kbd">Esc</span> o cliccando fuori.</p>
      <div class="actions">
        <button id="close">Chiudi</button>
      </div>
    </div>
  </div>

  <script>
    // fingerprint finto (hash leggero del contesto browser)
    function fakeFP(){
      const s = [
        navigator.userAgent,
        navigator.language,
        screen.width + "x" + screen.height,
        Intl.DateTimeFormat().resolvedOptions().timeZone
      ].join("|");
      let h = 2166136261; // FNV-ish
      for (let i=0;i<s.length;i++){
        h ^= s.charCodeAt(i);
        h = Math.imul(h, 16777619);
      }
      // format
      const hex = (h >>> 0).toString(16).padStart(8,"0");
      return `fp_${hex}_${Math.random().toString(16).slice(2,6)}`;
    }

    const fpEl = document.getElementById("fp");
    const statusEl = document.getElementById("status");
    const actionEl = document.getElementById("action");
    const modeEl = document.getElementById("mode");
    const card = document.getElementById("card");

    fpEl.textContent = fakeFP();

    const steps = [
      "aggancio socket immaginario…",
      "negoziazione TLS con il tuo senso di colpa…",
      "richiesta token: CURIOSITY_GRANTED",
      "parsing log: /dev/null",
      "esecuzione policy: bevi acqua e respira",
      "fine."
    ];
    let idx = 0;
    setInterval(() => {
      actionEl.textContent = steps[idx % steps.length];
      idx++;
      if (idx === 3) statusEl.textContent = "VALUTAZIONE";
      if (idx === 6) statusEl.textContent = "OK (più o meno)";
    }, 1400);

    // buttons
    document.getElementById("btn1").addEventListener("click", () => {
      card.classList.add("shake");
      statusEl.textContent = "ASSOLTO";
      modeEl.textContent = "safe-mode";
      actionEl.textContent = "redirect mentale verso buone decisioni";
      setTimeout(() => card.classList.remove("shake"), 900);
    });

    const modal = document.getElementById("modal");
    const openModal = () => modal.classList.add("open");
    const closeModal = () => modal.classList.remove("open");

    document.getElementById("btn2").addEventListener("click", openModal);
    document.getElementById("close").addEventListener("click", closeModal);
    modal.addEventListener("click", (e) => { if (e.target === modal) closeModal(); });
    window.addEventListener("keydown", (e) => { if (e.key === "Escape") closeModal(); });

    document.getElementById("btn3").addEventListener("click", () => {
      // effetto "rottura" controllata
      card.classList.add("shake");
      statusEl.textContent = "🚨 ALLARME (scenico)";
      modeEl.textContent = "chaos";
      const body = document.body;
      body.style.filter = "contrast(1.2) saturate(1.4)";
      actionEl.textContent = "ripristino in corso… (forse)";
      // finto "crash"
      setTimeout(() => {
        body.style.filter = "";
        statusEl.textContent = "RIPRISTINATO";
        actionEl.textContent = "mai fidarsi dei bottoni rossi";
        card.classList.remove("shake");
      }, 1200);
    });
  </script>
</body>
</html>
