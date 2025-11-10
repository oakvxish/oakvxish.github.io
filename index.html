<!DOCTYPE html>
<html lang="it">
<head>
  <meta charset="UTF-8" />
  <title>About Me – Dynamic Frutiger Aero</title>
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />

  <!-- Tailwind CSS (utility + layout complesso) -->
  <link href="https://cdn.jsdelivr.net/npm/tailwindcss@2.2.19/dist/tailwind.min.css" rel="stylesheet" />

  <!-- Animate.css per microanimazioni dichiarative -->
  <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/animate.css@4.1.1/animate.min.css" />

  <style>
    :root {
      --faero-bg-1: #0b1736;
      --faero-bg-2: #102648;
      --faero-accent-1: #41e1ff;
      --faero-accent-2: #ff9df5;
      --faero-accent-3: #9cff57;
      --faero-glass: rgba(9, 18, 40, 0.78);
      --faero-radius-xl: 26px;
      --faero-transition: 220ms ease-out;
      --faero-grid-gap: 1.4rem;
    }

    body {
      margin: 0;
      min-height: 100vh;
      font-family: system-ui, -apple-system, BlinkMacSystemFont, "SF Pro Text", sans-serif;
      color: #e7f3ff;
      background:
        radial-gradient(circle at top left, rgba(65,225,255,0.28), transparent 55%),
        radial-gradient(circle at top right, rgba(156,255,87,0.11), transparent 55%),
        radial-gradient(circle at bottom, rgba(255,157,245,0.14), transparent 55%),
        linear-gradient(180deg, var(--faero-bg-1), var(--faero-bg-2));
      overflow-x: hidden;
    }

    .faero-glass {
      background: var(--faero-glass);
      backdrop-filter: blur(20px) saturate(140%);
      -webkit-backdrop-filter: blur(20px) saturate(140%);
      border-radius: var(--faero-radius-xl);
      border: 1px solid rgba(255, 255, 255, 0.08);
      box-shadow:
        0 18px 40px rgba(0, 0, 0, 0.52),
        0 0 24px rgba(65, 225, 255, 0.08);
      transition: transform var(--faero-transition), box-shadow var(--faero-transition), border-color var(--faero-transition);
    }

    .faero-glass:hover {
      transform: translateY(-3px);
      box-shadow:
        0 26px 65px rgba(0, 0, 0, 0.8),
        0 0 26px rgba(65, 225, 255, 0.26);
      border-color: rgba(156, 255, 87, 0.22);
    }

    .faero-grid {
      display: grid;
      grid-template-columns: minmax(0, 2.2fr) minmax(260px, 1.2fr);
      gap: var(--faero-grid-gap);
      align-items: start;
    }

    @media (max-width: 900px) {
      .faero-grid {
        grid-template-columns: 1fr;
      }
    }

    .faero-pill {
      display: inline-flex;
      align-items: center;
      gap: 0.4rem;
      padding: 0.32rem 0.9rem;
      border-radius: 999px;
      background: radial-gradient(circle at 0 0, rgba(65,225,255,0.28), transparent),
                  rgba(8, 17, 38, 0.96);
      border: 1px solid rgba(65,225,255,0.42);
      font-size: 0.72rem;
      letter-spacing: 0.08em;
      text-transform: uppercase;
      color: #9cffef;
    }

    .faero-tag {
      padding: 0.15rem 0.6rem;
      border-radius: 999px;
      font-size: 0.7rem;
      background: rgba(11, 30, 68, 0.98);
      border: 1px solid rgba(65,225,255,0.28);
      color: #c3ecff;
      white-space: nowrap;
    }

    .status-dot {
      width: 9px;
      height: 9px;
      border-radius: 50%;
      background: #9cff57;
      box-shadow: 0 0 10px #9cff57;
    }

    .orbiting-orb {
      position: fixed;
      width: 240px;
      height: 240px;
      border-radius: 50%;
      background: radial-gradient(circle, rgba(65,225,255,0.14), transparent);
      mix-blend-mode: screen;
      opacity: 0.6;
      pointer-events: none;
      z-index: -1;
    }

    .reveal {
      opacity: 0;
      transform: translateY(16px);
      transition: opacity 360ms ease-out, transform 360ms ease-out;
    }

    .reveal--visible {
      opacity: 1;
      transform: translateY(0);
    }

    .gradient-text {
      background: linear-gradient(120deg, var(--faero-accent-1), var(--faero-accent-2));
      -webkit-background-clip: text;
      color: transparent;
    }

    .skill-bar-track {
      width: 100%;
      height: 7px;
      border-radius: 999px;
      background: rgba(9, 21, 46, 0.95);
      overflow: hidden;
      position: relative;
    }

    .skill-bar-fill {
      height: 100%;
      border-radius: 999px;
      background: linear-gradient(90deg, var(--faero-accent-1), var(--faero-accent-3));
      transform-origin: left center;
      transform: scaleX(0);
      transition: transform 420ms ease-out;
    }

    .skill-label {
      font-size: 0.72rem;
      color: #9fb8ff;
    }

    .timeline {
      border-left: 1px solid rgba(65,225,255,0.25);
      padding-left: 1rem;
      margin-left: 0.4rem;
    }

    .timeline-item {
      position: relative;
      margin-bottom: 0.9rem;
    }

    .timeline-item::before {
      content: "";
      position: absolute;
      left: -1.16rem;
      top: 0.2rem;
      width: 9px;
      height: 9px;
      border-radius: 50%;
      background: var(--faero-accent-1);
      box-shadow: 0 0 8px var(--faero-accent-1);
    }

    .matrix-badge {
      padding: 0.25rem 0.6rem;
      font-size: 0.68rem;
      border-radius: 999px;
      background: rgba(5, 14, 30, 0.98);
      border: 1px solid rgba(255,157,245,0.2);
      color: #ffdfff;
    }
  </style>
</head>
<body>
<div id="orb" class="orbiting-orb"></div>

<div id="app" class="max-w-6xl mx-auto px-4 py-8 space-y-6">

  <!-- HEADER PRINCIPALE -->
  <header class="faero-glass p-5 md:p-7 animate__animated animate__fadeIn">
    <div class="flex flex-wrap items-center justify-between gap-4">
      <div class="space-y-2">
        <div class="faero-pill">
          <span class="status-dot"></span>
          <span id="live-status-label">Calcolo presenza...</span>
        </div>
        <h1 class="text-2xl md:text-3xl font-semibold leading-tight">
          <span class="gradient-text">[Il tuo nome]</span>
          <span class="text-sm md:text-base text-blue-200 block">
            Architect di sistemi AI-driven, automation engineer e sviluppatore full-stack.
          </span>
        </h1>
      </div>
      <div class="flex flex-col items-end gap-2 text-xs text-blue-200">
        <div id="clock" class="font-mono text-sm"></div>
        <div class="flex flex-wrap gap-1">
          <span class="faero-tag">AI Workflows</span>
          <span class="faero-tag">WhatsApp Bots</span>
          <span class="faero-tag">Privacy & Compliance</span>
          <span class="faero-tag">Vertical Systems</span>
        </div>
      </div>
    </div>
  </header>

  <!-- GRID PRINCIPALE -->
  <main class="faero-grid">
    <!-- COLONNA SINISTRA: NARRATIVA TECNICA -->
    <section class="faero-glass p-5 md:p-6 space-y-5 reveal">
      <h2 class="text-sm tracking-[0.18em] uppercase text-blue-300">
        Profilo tecnico
      </h2>
      <p class="text-sm md:text-[0.9rem] text-blue-100 leading-relaxed">
        Progetto, sviluppo e integro sistemi conversazionali e piattaforme AI
        che uniscono automazioni robuste, UX chiara e conformità normativa.
        Lavoro con stack moderni, orchestrazione di modelli LLM local e cloud,
        pipeline dati tracciabili e codice pensato per scalare senza rompersi.
      </p>

      <div class="grid md:grid-cols-3 gap-3 text-xs">
        <div>
          <div class="font-semibold text-blue-100 mb-1">Stack core</div>
          <ul class="space-y-0.5 text-blue-200">
            <li>Node.js / TypeScript modulari</li>
            <li>Web Components, SPA mirate</li>
            <li>PostgreSQL / Redis / JSON store</li>
          </ul>
        </div>
        <div>
          <div class="font-semibold text-blue-100 mb-1">AI & Ops</div>
          <ul class="space-y-0.5 text-blue-200">
            <li>LLM orchestration, prompt design</li>
            <li>Ollama & modelli on-device</li>
            <li>Monitoring & logging strutturato</li>
          </ul>
        </div>
        <div>
          <div class="font-semibold text-blue-100 mb-1">Governance</div>
          <ul class="space-y-0.5 text-blue-200">
            <li>Pattern a stati finiti per chatbot</li>
            <li>Rate limiting per chatId</li>
            <li>GDPR-ready data design</li>
          </ul>
        </div>
      </div>

      <!-- TIMELINE DINAMICA -->
      <div>
        <div class="flex items-center justify-between mb-2">
          <h3 class="text-xs uppercase tracking-[0.16em] text-blue-300">
            Traiettoria recente
          </h3>
          <span id="xp-years" class="matrix-badge">Experience matrix: calcolo...</span>
        </div>
        <div id="timeline" class="timeline text-[0.78rem] text-blue-100"></div>
      </div>
    </section>

    <!-- COLONNA DESTRA: COMPONENTE AVANZATA (WEB COMPONENT) -->
    <section class="space-y-4">
      <!-- SKILL MATRIX -->
      <section class="faero-glass p-4 md:p-5 reveal">
        <div class="flex items-center justify-between gap-2 mb-2">
          <h2 class="text-xs uppercase tracking-[0.18em] text-blue-300">
            Skill matrix
          </h2>
          <span class="text-[0.65rem] text-blue-200">
            Auto-render da struttura dati JS
          </span>
        </div>
        <skill-matrix></skill-matrix>
      </section>

      <!-- LIVE FOCUS / PROGETTI -->
      <section class="faero-glass p-4 md:p-5 reveal">
        <div class="flex items-center justify-between mb-2">
          <h2 class="text-xs uppercase tracking-[0.18em] text-blue-300">
            Focus attuale
          </h2>
          <span id="focus-label" class="faero-tag">Sync</span>
        </div>
        <ul id="live-focus" class="list-disc list-inside text-[0.78rem] text-blue-100 space-y-1.5"></ul>
      </section>
    </section>
  </main>

  <!-- FOOTER DINAMICO -->
  <footer class="faero-glass p-4 mt-4 flex flex-wrap items-center justify-between gap-2 text-[0.7rem] text-blue-200 reveal">
    <div>
      <span class="text-blue-300">Dynamic profile API:</span>
      <span id="dynamic-summary">init...</span>
    </div>
    <div class="flex flex-wrap gap-1 items-center">
      <span class="faero-tag">Code-first mindset</span>
      <span class="faero-tag">Design system thinking</span>
      <span class="faero-tag">Observability</span>
    </div>
  </footer>
</div>

<script type="module">
  // Stato centrale: modifica i dati qui
  const state = {
    profile: {
      name: "[Il tuo nome]",
      baseRole: "AI systems & automation engineer",
      startYear: 2020, // usato per xp dinamico
      timezone: "Europe/Rome"
    },
    timeline: [
      {
        year: 2025,
        label: "Lead tecnico su piattaforme AI proprietarie",
        details: "WhatsApp bots, orchestrazione LLM, gestione lock concorrenti, flussi edit_* complessi."
      },
      {
        year: 2024,
        label: "Integrazione stack AI on-prem",
        details: "Ollama, modelli custom, audit log, controlli di coerenza e safe rollback."
      },
      {
        year: 2023,
        label: "Full-stack & sistemi real-time",
        details: "API Node/TS, interfacce dashboard, metriche live per booking e workload."
      }
    ],
    skills: [
      {
        area: "Backend & Systems",
        weight: 0.95,
        items: [
          ["Node.js / TypeScript", 0.94],
          ["Architetture a stati per chatbot", 0.96],
          ["Gestione concorrenza / locking", 0.9],
          ["Logging strutturato & tracing", 0.88]
        ]
      },
      {
        area: "AI & Automation",
        weight: 0.92,
        items: [
          ["Prompt engineering avanzato", 0.93],
          ["Ollama / LLM on-device", 0.9],
          ["Pipelines dati per training", 0.86],
          ["Modelli ibridi regole+LLM", 0.9]
        ]
      },
      {
        area: "Frontend & UX tecnica",
        weight: 0.85,
        items: [
          ["Web Components / SPA mirate", 0.86],
          ["Design system Frutiger Aero", 0.82],
          ["UI data-driven", 0.84]
        ]
      },
      {
        area: "Compliance & Reliability",
        weight: 0.82,
        items: [
          ["GDPR-ready design", 0.83],
          ["Versioning configurazioni", 0.8],
          ["Test end-to-end flussi complessi", 0.82]
        ]
      }
    ],
    focus: [
      "Refactoring di flussi di prenotazione con stati espliciti e idempotenti.",
      "Riduzione attrito utente: risposte brevi, precise, guidate dal contesto.",
      "Allineamento tra logica tecnica e requisiti legali dei clienti.",
      "Sperimentazione con modelli locali per ridurre latenza e dipendenze."
    ]
  };

  // Utilità
  const $ = (sel, root = document) => root.querySelector(sel);

  function setLiveClock() {
    const clockEl = $("#clock");
    if (!clockEl) return;
    const update = () => {
      const now = new Date();
      clockEl.textContent = new Intl.DateTimeFormat("it-IT", {
        hour: "2-digit",
        minute: "2-digit",
        second: "2-digit"
      }).format(now) + " • " + state.profile.timezone;
      requestAnimationFrame(() => {}); // no-op, solo a scopo dimostrativo
    };
    update();
    setInterval(update, 1000);
  }

  function setPresenceStatus() {
    const el = $("#live-status-label");
    if (!el) return;
    const hour = new Date().getHours();
    let status;
    if (hour >= 8 && hour < 13) status = "Online, in fase di sviluppo attivo.";
    else if (hour >= 13 && hour < 19) status = "In analisi, design di sistemi e debugging.";
    else if (hour >= 19 && hour < 23) status = "Operativo su revisioni e ottimizzazioni.";
    else status = "In modalità low-noise: solo task critici.";
    el.textContent = status;
  }

  function renderTimeline() {
    const container = $("#timeline");
    if (!container) return;
    container.innerHTML = "";
    state.timeline.forEach(t => {
      const item = document.createElement("div");
      item.className = "timeline-item";
      item.innerHTML = `
        <div class="text-blue-300 font-semibold">${t.year}</div>
        <div class="text-blue-100">${t.label}</div>
        <div class="text-blue-300 text-[0.7rem]">${t.details}</div>
      `;
      container.appendChild(item);
    });

    const years = state.timeline.length
      ? (state.timeline[0].year - state.profile.startYear + 1)
      : (new Date().getFullYear() - state.profile.startYear);
    $("#xp-years").textContent = `Experience matrix: ~${Math.max(years, 1)} anni`;
  }

  // Web Component: Skill Matrix con Shadow DOM
  class SkillMatrix extends HTMLElement {
    constructor() {
      super();
      this.attachShadow({ mode: "open" });
    }

    connectedCallback() {
      this.render();
      requestAnimationFrame(() => this.animateBars());
    }

    render() {
      const s = state.skills;
      const wrapper = document.createElement("div");
      wrapper.className = "space-y-3";
      wrapper.innerHTML = s.map(group => {
        const avg = Math.round(group.weight * 100);
        return `
          <div class="space-y-1">
            <div class="flex items-center justify-between gap-2">
              <div class="text-[0.8rem] text-blue-100 font-semibold">
                ${group.area}
              </div>
              <div class="matrix-badge">${avg}% depth</div>
            </div>
            ${group.items.map(([name, val]) => {
              const pct = Math.round(val * 100);
              return `
                <div class="space-y-0.5">
                  <div class="flex items-center justify-between">
                    <span class="skill-label">${name}</span>
                    <span class="skill-label">${pct}%</span>
                  </div>
                  <div class="skill-bar-track">
                    <div class="skill-bar-fill" data-pct="${pct}"></div>
                  </div>
                </div>
              `;
            }).join("")}
          </div>
        `;
      }).join("");

      const style = document.createElement("style");
      style.textContent = `
        :host {
          display: block;
        }
        .skill-bar-track {
          width: 100%;
          height: 7px;
          border-radius: 999px;
          background: rgba(9, 21, 46, 0.95);
          overflow: hidden;
          position: relative;
        }
        .skill-bar-fill {
          height: 100%;
          border-radius: 999px;
          background: linear-gradient(90deg, var(--faero-accent-1), var(--faero-accent-3));
          transform-origin: left center;
          transform: scaleX(0);
          transition: transform 420ms ease-out;
        }
        .skill-label {
          font-size: 0.72rem;
          color: #9fb8ff;
        }
        .matrix-badge {
          padding: 0.2rem 0.6rem;
          font-size: 0.65rem;
          border-radius: 999px;
          background: rgba(5, 14, 30, 0.98);
          border: 1px solid rgba(255,157,245,0.2);
          color: #ffdfff;
        }
      `;

      this.shadowRoot.innerHTML = "";
      this.shadowRoot.appendChild(style);
      this.shadowRoot.appendChild(wrapper);
    }

    animateBars() {
      const bars = this.shadowRoot.querySelectorAll(".skill-bar-fill");
      bars.forEach(bar => {
        const pct = Number(bar.dataset.pct || 0);
        requestAnimationFrame(() => {
          bar.style.transform = `scaleX(${pct / 100})`;
        });
      });
    }
  }

  customElements.define("skill-matrix", SkillMatrix);

  // Live focus rotante
  function renderLiveFocus() {
    const ul = $("#live-focus");
    const label = $("#focus-label");
    if (!ul || !label) return;
    ul.innerHTML = "";
    state.focus.forEach((item, i) => {
      const li = document.createElement("li");
      li.textContent = item;
      if (i === 0) li.classList.add("text-blue-50");
      ul.appendChild(li);
    });

    let idx = 0;
    setInterval(() => {
      idx = (idx + 1) % state.focus.length;
      label.textContent = "Focus: " + (idx + 1) + "/" + state.focus.length;
      [...ul.children].forEach((li, i) => {
        li.classList.toggle("text-blue-50", i === idx);
      });
    }, 4600);
  }

  // Riassunto dinamico
  function renderSummary() {
    const el = $("#dynamic-summary");
    if (!el) return;
    const areas = state.skills.map(s => s.area.split("&")[0].trim());
    el.textContent =
      `${state.profile.name || "Profilo"} opera su ` +
      `${areas.length} domini chiave con pipeline AI-driven, ` +
      `layer di automazione e attenzione strutturale alla resilienza.`;
  }

  // Orbita estetica cursore
  function initOrb() {
    const orb = $("#orb");
    if (!orb) return;
    let targetX = window.innerWidth * 0.8;
    let targetY = window.innerHeight * 0.2;
    let x = targetX;
    let y = targetY;

    window.addEventListener("pointermove", e => {
      targetX = e.clientX + 40;
      targetY = e.clientY - 40;
    });

    function loop() {
      x += (targetX - x) * 0.06;
      y += (targetY - y) * 0.06;
      orb.style.transform = `translate3d(${x}px, ${y}px, 0)`;
      requestAnimationFrame(loop);
    }
    loop();
  }

  // Reveal on scroll
  function initReveal() {
    const els = document.querySelectorAll(".reveal");
    const io = new IntersectionObserver(entries => {
      entries.forEach(e => {
        if (e.isIntersecting) {
          e.target.classList.add("reveal--visible");
          io.unobserve(e.target);
        }
      });
    }, { threshold: 0.12 });
    els.forEach(el => io.observe(el));
  }

  // Inizializzazione
  setLiveClock();
  setPresenceStatus();
  renderTimeline();
  renderLiveFocus();
  renderSummary();
  initOrb();
  initReveal();
</script>

</body>
</html>
