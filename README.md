<html lang="de">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>CHIMERA-ID // ELIAS VANT</title>
<link href="https://fonts.googleapis.com/css2?family=Share+Tech+Mono&family=Orbitron:wght@400;600;700;900&family=Rajdhani:wght@300;400;600&display=swap" rel="stylesheet">
<link rel="stylesheet" type="text/css" href="styles.css">
</head>
<body>
<div class="main-wrapper">
  <!-- HEADER -->
  <div class="header">
    <div class="header-left">
      <div class="header-sys">SYSTEM // CHIMERA-DB v4.7.2 // ZUGRIFF GEWÄHRT</div>
      <div class="header-title">ELIAS &bdquo;DER DOCHT&ldquo; VANT</div>
      <div class="header-sub">INFILTRATIONSAKTE // KLASSIFIZIERUNG: ULTRAGEHEIM // SEKTION 9-DELTA</div>
    </div>
    <div class="header-right">
      <div class="status-badge">▶ AKTIV // EINSATZBEREIT</div>
      <div class="threat-level">BEDROHUNGSSTUFE: <span class="threat-val">KRITISCH [9/10]</span></div>
      <div class="barcode">|||||||| ||| |||||| ||||| |||||||| ||| CHIMERA-#7741-V</div>
    </div>
  </div>

  <!-- <div class="edit-hint">⟨ <span>ALLE FELDER EDITIERBAR</span> — KLICKEN UM ZU BEARBEITEN ⟩</div> -->

  <div class="layout">
	  <!-- LEFT COLUMN -->
    <div class="col-left">
      <!-- ID PHOTO PANEL -->
      <div class="panel" style="padding:0;">
        <div class="panel-header">
          <span class="panel-title">BIOMETRIE // FOTO-ID</span>
          <span class="panel-id">IMG-#7741</span>
        </div>
        <div class="id-photo-wrap">
          <!-- <img src="data:image/svg+xml,%3Csvg xmlns='http://www.w3.org/2000/svg' width='280' height='370' viewBox='0 0 280 370'%3E%3Crect fill='%23080c10' width='280' height='370'/%3E%3Ctext x='140' y='160' text-anchor='middle' font-family='monospace' font-size='60' fill='%231e3040'%3E👤%3C/text%3E%3Ctext x='140' y='210' text-anchor='middle' font-family='monospace' font-size='12' fill='%235a7a8a'%3EFOTO LADEN...%3C/text%3E%3Ctext x='140' y='230' text-anchor='middle' font-family='monospace' font-size='10' fill='%231e3040'%3EODER URL EINFÜGEN%3C/text%3E%3C/svg%3E" id="char-photo" alt="Charakterfoto"> -->
          <img src="Portrait.png" alt="Portrait" width="500" height="600">
		  <div class="id-overlay"></div>
          <div class="scan-line"></div>
          <div class="id-corner tl"></div><div class="id-corner tr"></div>
          <div class="id-corner bl"></div><div class="id-corner br"></div>
          <div class="id-tag"><!--◈-->&nbsp;GESTALTWANDLER // BIO-NANO AKTIV</div>
        </div>
        <!--<div class="panel-body" style="padding-top:10px;">
          <div style="font-family:'Share Tech Mono',monospace;font-size:9px;color:var(--text-dim);margin-bottom:4px;">FOTO-URL EINGEBEN:</div>
          <input type="text" id="photo-url" placeholder="https://..." style="width:100%;background:var(--panel2);border:1px solid var(--border);color:var(--text);font-family:'Share Tech Mono',monospace;font-size:10px;padding:5px 8px;outline:none;" oninput="updatePhoto(this.value)">
        </div> -->
      </div>
      <!-- IDENTITY -->
      <div class="panel cyan-accent">
        <div class="panel-header">
          <span class="panel-title" style="color:var(--cyan);">IDENTITÄTSDATEN</span>
          <span class="panel-id">ID-CORE</span>
        </div>
        <div class="panel-body">
          <div class="identity-field">
            <div class="field-label">BEZEICHNUNG // KAMPFNAME</div>
            <input class="field-value highlight" value="ELIAS &bdquo;DER DOCHT&ldquo; VANT">
          </div>
          <div class="identity-field">
            <div class="field-label">SPEZIES // KLASSE</div>
            <input class="field-value" value="Mensch (Gen-mod. Gestaltwandler)">
          </div>
          <div class="identity-field">
            <div class="field-label">OPERATIVE ROLLE</div>
            <input class="field-value" value="Infiltrator & Terminierungsexperte">
          </div>
          <div class="identity-field">
            <div class="field-label">HEIMATWELT</div>
            <input class="field-value" value="Kepler-186f (Industrie-Ödland)">
          </div>
          <div class="identity-field">
            <div class="field-label">URSPRUNG // PROJEKT</div>
            <input class="field-value" value="Project Chimera (FEHLGESCHLAGEN)">
          </div>
          <div class="identity-field">
            <div class="field-label">OPERATIVES MOTTO</div>
            <input class="field-value italic-field" value="&bdquo;Jedes Gesicht ist eine Maske, und jede Maske brennt.&ldquo;">
          </div>
          <div class="divider"><div class="divider-line"></div><div class="divider-label">MARKIERUNGEN</div><div class="divider-line"></div></div>
          <div class="tag-row" id="tag-row">
            <span class="tag active">PYROMANE</span>
            <span class="tag active">SÖLDNER</span>
            <span class="tag active">GESTALTWANDLER</span>
            <span class="tag">VERBANNT</span>
            <span class="tag">GEJAGT</span>
            <span class="tag active">NANO-IMPLANTATE</span>
          </div>
        </div>
      </div>
    </div>
    <!-- RIGHT COLUMN -->
    <div class="col-right">
      <!-- STATS GRID -->
      <div style="display:grid;grid-template-columns:1fr 1fr;gap:16px;">
        <!-- PRIMÄRWERTE -->
        <div class="panel">
          <div class="panel-header">
            <span class="panel-title">PRIMÄRWERTE</span>
            <span class="panel-id">ATTR-A</span>
          </div>
          <div class="panel-body" id="primary-stats">
            <!-- stats injected by JS -->
          </div>
        </div>
        <!-- SEKUNDÄRWERTE -->
        <div class="panel cyan-accent">
          <div class="panel-header">
            <span class="panel-title" style="color:var(--cyan);">SEKUNDÄRWERTE</span>
            <span class="panel-id">ATTR-B</span>
          </div>
          <div class="panel-body" id="secondary-stats">
          </div>
        </div>
      </div>
      <!-- NANO-STATUS -->
      <div class="panel green-accent">
        <div class="panel-header">
          <span class="panel-title" style="color:var(--green);">NANOBOT-SYSTEM // VITALDATEN</span>
          <span class="panel-id">BIO-SYS</span>
        </div>
        <div class="panel-body">
          <div class="nano-grid" id="nano-grid">
            <!-- injected by JS -->
          </div>
          <div class="divider"><div class="divider-line"></div><div class="divider-label">PYROMANISCHER TRIEB</div><div class="divider-line"></div></div>
          <div style="display:flex;align-items:center;flex-wrap:wrap;gap:4px;">
            <span class="pyro-label">INTENSITÄT:</span>
            <div class="pyro-meter" id="pyro-meter"></div>
            <span class="pyro-val" id="pyro-display">7/10</span>
          </div>
        </div>
      </div>
      <!-- FÄHIGKEITEN & AUSRÜSTUNG -->
      <div class="panel">
        <div class="panel-header">
          <span class="panel-title">FÄHIGKEITEN & AUSRÜSTUNG</span>
          <span class="panel-id">CAP-SYS</span>
        </div>
        <div class="panel-body">
          <div class="ability-card cyan">
            <div class="ability-top">
              <input class="ability-name" value="PHÄNOTYP-SHIFT">
              <span class="ability-tag cyan">PRIMÄR</span>
            </div>
            <textarea class="ability-desc" rows="2">Vollständige optische Mimikry einer Zielperson inkl. Stimme. Erfordert DNA-Probe oder neuronalen Scan. Aktivierung via bewusste Muskelkontraktion.</textarea>
          </div>
          <div class="ability-card">
            <div class="ability-top">
              <input class="ability-name" value="PRÄZISIONSKAMPF">
              <span class="ability-tag">KAMPF</span>
            </div>
            <textarea class="ability-desc" rows="2">Klingenarbeit auf chirurgischem Niveau kombiniert mit taktischer Brandstiftung. Bevorzugt lautlose Elimination mit Spurenbeseitigung durch Feuer.</textarea>
          </div>
          <div class="ability-card red">
            <div class="ability-top">
              <input class="ability-name" value="IGNIS-DORN">
              <span class="ability-tag red">SIGNATURWAFFE</span>
            </div>
            <textarea class="ability-desc" rows="2">Versteckte Handgelenksklinge. Injiziert beim Eindringen hochentzündliches Gel (Zündverzögerung: 0–120 Sek. einstellbar).</textarea>
          </div>
          <div class="ability-card green">
            <div class="ability-top">
              <input class="ability-name" value="THERMIT-AUSRÜSTUNG">
              <span class="ability-tag green">GADGETS</span>
            </div>
            <textarea class="ability-desc" rows="2">Miniaturisierte Thermit-Ladungen // Brandbeschleuniger (Sprayform) // Feuerfeste synthetische Unterwäsche // Plasma-Feuerzeug (mechanisch).</textarea>
          </div>
        </div>
      </div>
      <!-- SCHWÄCHEN & NOTIZEN -->
      <div style="display:grid;grid-template-columns:1fr 1fr;gap:16px;">
        <div class="panel red-accent">
          <div class="panel-header">
            <span class="panel-title" style="color:var(--red);">SCHWACHSTELLEN</span>
            <span class="panel-id">VULN-LOG</span>
          </div>
          <div class="panel-body">
            <div class="weakness-item">
              <div class="weakness-icon">🌡</div>
              <div class="weakness-text-wrap">
                <input class="weakness-name" value="THERMISCHE SIGNATUR">
                <textarea class="weakness-desc" rows="2">Nanobot-Aktivität erhöht Körpertemperatur. Auf Wärmebildkameras klar sichtbar.</textarea>
              </div>
            </div>
            <div class="weakness-item">
              <div class="weakness-icon">❄</div>
              <div class="weakness-text-wrap">
                <input class="weakness-name" value="LÖSCHSYSTEMPHOBIE">
                <textarea class="weakness-desc" rows="2">Irrationale Panik bei Halon-Löschanlagen und Vakuum-Sperren. Kampfleistung -60%.</textarea>
              </div>
            </div>
            <div class="weakness-item">
              <div class="weakness-icon">⚡</div>
              <div class="weakness-text-wrap">
                <input class="weakness-name" value="POST-SHIFT KOLLAPS">
                <textarea class="weakness-desc" rows="2">Zellregeneration nach Verwandlung kostet enorm Energie. Kaloriendefizit = komatöser Schlaf.</textarea>
              </div>
            </div>
          </div>
        </div>
        <div class="panel cyan-accent">
          <div class="panel-header">
            <span class="panel-title" style="color:var(--cyan);">FELDNOTIZEN // SPIELLEITER</span>
            <span class="panel-id">NOTE-SYS</span>
          </div>
          <div class="panel-body">
            <textarea class="notes-area" rows="4">Spricht in der 3. Person über aktuelles Gesicht. Wirkt kalt & kalkulierend – ausser bei Feuer. Dann: kindliche, beunruhigende Begeisterung.</textarea>
            <div class="divider"><div class="divider-line"></div><div class="divider-label">WILDCARD-STATUS</div><div class="divider-line"></div></div>
            <textarea class="notes-area" rows="3">Kann Gruppe in jedes Hochsicherheitsgefängnis schleusen. Wird wahrscheinlich halben Block niederbrennen um Beweise zu vernichten.</textarea>
            <div class="divider"><div class="divider-line"></div><div class="divider-label">MARKENZEICHEN</div><div class="divider-line"></div></div>
            <textarea class="notes-area" rows="2">Hinterlässt stets Geruch nach Schwefel / Ozon. Kleine Flamme am Tatort, die beim Abflug erlischt.</textarea>
          </div>
        </div>
      </div>
    </div>
  </div>
  <!-- BOTTOM BAR -->
  <div class="bottom-bar">
    <div>CHIMERA-DB // AKTE #7741-VANE // REV.3.2 // KEPLER-SEKTOR</div>
    <div class="blink">● LIVE-EDIT AKTIV</div>
    <div>LETZTE ÄNDERUNG: <span id="last-edit">—</span> UHR</div>
  </div>

</div>

<script>
// ====== DATA ======
const primaryStats = [
  { label: "STÄRKE",       val: 52, color: "default" },
  { label: "GESCHICK",     val: 91, color: "default" },
  { label: "INTELLIGENZ",  val: 84, color: "default" },
  { label: "WAHRNEHMUNG",  val: 78, color: "default" },
  { label: "CHARISMA",     val: 65, color: "default" },
  { label: "WILLENSKRAFT", val: 70, color: "default" },
];

const secondaryStats = [
  { label: "INFILTRATION",  val: 97, color: "cyan" },
  { label: "TÄUSCHUNG",     val: 93, color: "cyan" },
  { label: "KLINGENKUNST",  val: 88, color: "cyan" },
  { label: "BIONANOKONTRL", val: 85, color: "cyan" },
  { label: "BRANDSTIFTUNG", val: 95, color: "cyan" },
  { label: "STEALTH",       val: 90, color: "cyan" },
];

const nanoData = [
  { label: "NANOBOT-LEVEL",   val: "94%",  cls: "ok" },
  { label: "KÖRPERTEMP",      val: "38.7°C", cls: "warn" },
  { label: "PIGMENT-SHIFT",   val: "BEREIT", cls: "ok" },
  { label: "KNOCHEN-FLEX",    val: "AKTIV",  cls: "ok" },
  { label: "KALORIENINDEX",   val: "61%",   cls: "warn" },
  { label: "SHIFT-COOLDOWN",  val: "0 SEK",  cls: "info" },
];

// ====== RENDER STATS ======
function renderStats(containerId, stats) {
  const el = document.getElementById(containerId);
  el.innerHTML = '';
  stats.forEach((s, i) => {
    const row = document.createElement('div');
    row.className = 'stat-row';
    const pct = Math.min(100, Math.max(0, s.val));
    row.innerHTML = `
      <span class="stat-label">${s.label}</span>
      <div class="stat-bar-wrap">
        <div class="stat-bar-fill ${s.color === 'cyan' ? 'cyan-bar' : ''}" style="width:${pct}%" data-idx="${i}" data-cont="${containerId}"></div>
      </div>
      <span class="stat-val" title="Klicken zum Bearbeiten">
        <input type="number" min="0" max="100" value="${s.val}"
          style="width:36px;background:transparent;border:none;border-bottom:1px solid transparent;color:${s.color==='cyan'?'var(--cyan)':'var(--accent2)'};font-family:'Orbitron',sans-serif;font-size:11px;font-weight:700;text-align:right;outline:none;"
          oninput="updateStat('${containerId}',${i},this.value)"
          onfocus="this.style.borderBottomColor='var(--accent)'"
          onblur="this.style.borderBottomColor='transparent'"
        >
      </span>
    `;
    el.appendChild(row);
  });
}

function updateStat(containerId, idx, val) {
  const data = containerId === 'primary-stats' ? primaryStats : secondaryStats;
  val = Math.min(100, Math.max(0, parseInt(val) || 0));
  data[idx].val = val;
  const bar = document.querySelector(`[data-idx="${idx}"][data-cont="${containerId}"]`);
  if (bar) bar.style.width = val + '%';
  markEdit();
}

// ====== RENDER NANO ======
function renderNano() {
  const el = document.getElementById('nano-grid');
  el.innerHTML = '';
  nanoData.forEach((n, i) => {
    const cell = document.createElement('div');
    cell.className = 'nano-cell';
    cell.innerHTML = `
      <div class="nano-cell-label">${n.label}</div>
      <div>
        <input class="nano-edit ${n.cls}" value="${n.val}" oninput="nanoData[${i}].val=this.value;markEdit()">
      </div>
    `;
    el.appendChild(cell);
  });
}

// ====== PYRO METER ======
let pyroLevel = 7;
function renderPyro() {
  const meter = document.getElementById('pyro-meter');
  meter.innerHTML = '';
  for (let i = 1; i <= 10; i++) {
    const pip = document.createElement('div');
    pip.className = 'pyro-pip' + (i <= pyroLevel ? ' lit' : '');
    pip.onclick = () => { pyroLevel = i; renderPyro(); markEdit(); };
    meter.appendChild(pip);
  }
  document.getElementById('pyro-display').textContent = pyroLevel + '/10';
}

// ====== TAGS ======
document.querySelectorAll('.tag').forEach(t => {
  t.onclick = () => { t.classList.toggle('active'); markEdit(); };
});

// ====== PHOTO ======
function updatePhoto(url) {
  if (url.trim()) {
    document.getElementById('char-photo').src = url;
  }
}

// ====== EDIT TIMESTAMP ======
function markEdit() {
  const now = new Date();
  document.getElementById('last-edit').textContent =
    now.toTimeString().slice(0,5);
}

// Listen to all inputs/textareas for edit tracking
document.addEventListener('input', markEdit);

// ====== INIT ======
renderStats('primary-stats', primaryStats);
renderStats('secondary-stats', secondaryStats);
renderNano();
renderPyro();
</script>
</body>
</html>
