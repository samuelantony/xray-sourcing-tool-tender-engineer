<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>XRay Sourcing — Tender Engineers</title>
<link href="https://fonts.googleapis.com/css2?family=Space+Mono:wght@400;700&family=Syne:wght@400;600;800&display=swap" rel="stylesheet">
<style>
  :root {
    --bg: #0a0a0f;
    --surface: #111118;
    --border: #1e1e2e;
    --accent: #00e5ff;
    --accent2: #ff6b35;
    --accent3: #7c3aed;
    --text: #e2e8f0;
    --muted: #64748b;
    --card: #13131e;
    --hover: #1a1a2e;
  }

  * { box-sizing: border-box; margin: 0; padding: 0; }

  body {
    background: var(--bg);
    color: var(--text);
    font-family: 'Syne', sans-serif;
    min-height: 100vh;
    overflow-x: hidden;
  }

  /* Grid background */
  body::before {
    content: '';
    position: fixed;
    inset: 0;
    background-image:
      linear-gradient(rgba(0,229,255,0.03) 1px, transparent 1px),
      linear-gradient(90deg, rgba(0,229,255,0.03) 1px, transparent 1px);
    background-size: 40px 40px;
    pointer-events: none;
    z-index: 0;
  }

  .container {
    max-width: 1200px;
    margin: 0 auto;
    padding: 0 24px;
    position: relative;
    z-index: 1;
  }

  /* Header */
  header {
    padding: 40px 0 32px;
    border-bottom: 1px solid var(--border);
    margin-bottom: 40px;
  }

  .header-inner {
    display: flex;
    align-items: flex-start;
    justify-content: space-between;
    flex-wrap: wrap;
    gap: 16px;
  }

  .tag {
    font-family: 'Space Mono', monospace;
    font-size: 10px;
    letter-spacing: 3px;
    text-transform: uppercase;
    color: var(--accent);
    background: rgba(0,229,255,0.08);
    border: 1px solid rgba(0,229,255,0.2);
    padding: 4px 12px;
    border-radius: 2px;
    display: inline-block;
    margin-bottom: 12px;
  }

  h1 {
    font-size: clamp(28px, 4vw, 48px);
    font-weight: 800;
    line-height: 1.1;
    letter-spacing: -1px;
  }

  h1 span {
    color: var(--accent);
  }

  .subtitle {
    font-family: 'Space Mono', monospace;
    font-size: 12px;
    color: var(--muted);
    margin-top: 10px;
    letter-spacing: 0.5px;
  }

  .cities {
    display: flex;
    gap: 8px;
    flex-wrap: wrap;
    margin-top: 12px;
  }

  .city-badge {
    font-family: 'Space Mono', monospace;
    font-size: 11px;
    padding: 5px 14px;
    border-radius: 20px;
    font-weight: 700;
    letter-spacing: 1px;
  }

  .city-badge.frankfurt { background: rgba(255,107,53,0.15); border: 1px solid rgba(255,107,53,0.4); color: #ff6b35; }
  .city-badge.london    { background: rgba(0,229,255,0.1);  border: 1px solid rgba(0,229,255,0.3);  color: var(--accent); }
  .city-badge.amsterdam { background: rgba(124,58,237,0.15); border: 1px solid rgba(124,58,237,0.4); color: #a78bfa; }

  /* Controls */
  .controls {
    display: flex;
    gap: 12px;
    margin-bottom: 32px;
    flex-wrap: wrap;
    align-items: center;
  }

  .filter-btn {
    font-family: 'Space Mono', monospace;
    font-size: 11px;
    padding: 8px 18px;
    background: var(--surface);
    border: 1px solid var(--border);
    color: var(--muted);
    border-radius: 4px;
    cursor: pointer;
    transition: all 0.2s;
    letter-spacing: 0.5px;
  }

  .filter-btn:hover, .filter-btn.active {
    border-color: var(--accent);
    color: var(--accent);
    background: rgba(0,229,255,0.06);
  }

  .filter-btn.active { font-weight: 700; }

  .count {
    font-family: 'Space Mono', monospace;
    font-size: 11px;
    color: var(--muted);
    margin-left: auto;
  }

  .count span {
    color: var(--accent);
    font-weight: 700;
  }

  /* Source Cards Grid */
  .grid {
    display: grid;
    grid-template-columns: repeat(auto-fill, minmax(340px, 1fr));
    gap: 16px;
    margin-bottom: 60px;
  }

  .card {
    background: var(--card);
    border: 1px solid var(--border);
    border-radius: 8px;
    padding: 24px;
    position: relative;
    overflow: hidden;
    transition: all 0.25s;
    animation: fadeUp 0.4s ease both;
    cursor: default;
  }

  @keyframes fadeUp {
    from { opacity: 0; transform: translateY(16px); }
    to   { opacity: 1; transform: translateY(0); }
  }

  .card::before {
    content: '';
    position: absolute;
    top: 0; left: 0; right: 0;
    height: 2px;
    background: var(--card-accent, var(--accent));
    transform: scaleX(0);
    transform-origin: left;
    transition: transform 0.3s;
  }

  .card:hover {
    border-color: rgba(0,229,255,0.25);
    background: var(--hover);
    transform: translateY(-2px);
    box-shadow: 0 8px 32px rgba(0,0,0,0.4);
  }

  .card:hover::before { transform: scaleX(1); }

  .card-header {
    display: flex;
    align-items: flex-start;
    justify-content: space-between;
    gap: 12px;
    margin-bottom: 14px;
  }

  .source-icon {
    width: 40px; height: 40px;
    border-radius: 8px;
    display: flex; align-items: center; justify-content: center;
    font-size: 18px;
    flex-shrink: 0;
    background: var(--icon-bg, rgba(0,229,255,0.1));
    border: 1px solid var(--icon-border, rgba(0,229,255,0.2));
  }

  .source-meta {
    flex: 1;
  }

  .source-name {
    font-weight: 700;
    font-size: 15px;
    letter-spacing: -0.3px;
  }

  .source-category {
    font-family: 'Space Mono', monospace;
    font-size: 10px;
    color: var(--muted);
    margin-top: 2px;
    text-transform: uppercase;
    letter-spacing: 1px;
  }

  .source-query {
    font-family: 'Space Mono', monospace;
    font-size: 11px;
    background: rgba(0,0,0,0.3);
    border: 1px solid var(--border);
    border-radius: 4px;
    padding: 10px 12px;
    color: #94a3b8;
    line-height: 1.6;
    margin-bottom: 14px;
    word-break: break-word;
  }

  .source-query strong {
    color: var(--accent);
  }

  .city-tags {
    display: flex;
    gap: 6px;
    flex-wrap: wrap;
    margin-bottom: 14px;
  }

  .ct {
    font-family: 'Space Mono', monospace;
    font-size: 9px;
    padding: 3px 8px;
    border-radius: 3px;
    letter-spacing: 0.5px;
    text-transform: uppercase;
  }

  .ct.f { background: rgba(255,107,53,0.1); color: #ff6b35; border: 1px solid rgba(255,107,53,0.3); }
  .ct.l { background: rgba(0,229,255,0.08); color: var(--accent); border: 1px solid rgba(0,229,255,0.2); }
  .ct.a { background: rgba(124,58,237,0.1); color: #a78bfa; border: 1px solid rgba(124,58,237,0.3); }

  .links {
    display: flex;
    gap: 8px;
    flex-wrap: wrap;
  }

  .link-btn {
    font-family: 'Space Mono', monospace;
    font-size: 10px;
    padding: 6px 14px;
    border-radius: 4px;
    text-decoration: none;
    letter-spacing: 0.5px;
    transition: all 0.2s;
    display: inline-flex;
    align-items: center;
    gap: 4px;
  }

  .link-btn.primary {
    background: rgba(0,229,255,0.1);
    border: 1px solid rgba(0,229,255,0.3);
    color: var(--accent);
  }

  .link-btn.primary:hover {
    background: rgba(0,229,255,0.2);
    border-color: var(--accent);
  }

  .link-btn.secondary {
    background: transparent;
    border: 1px solid var(--border);
    color: var(--muted);
  }

  .link-btn.secondary:hover {
    border-color: var(--muted);
    color: var(--text);
  }

  /* Section headers */
  .section-label {
    font-family: 'Space Mono', monospace;
    font-size: 10px;
    letter-spacing: 3px;
    text-transform: uppercase;
    color: var(--muted);
    margin-bottom: 16px;
    display: flex;
    align-items: center;
    gap: 10px;
  }

  .section-label::after {
    content: '';
    flex: 1;
    height: 1px;
    background: var(--border);
  }

  /* Tips section */
  .tips {
    background: var(--card);
    border: 1px solid var(--border);
    border-left: 3px solid var(--accent);
    border-radius: 8px;
    padding: 24px;
    margin-bottom: 40px;
  }

  .tips h3 {
    font-size: 14px;
    font-weight: 700;
    margin-bottom: 14px;
    color: var(--accent);
    font-family: 'Space Mono', monospace;
    letter-spacing: 1px;
  }

  .tips-grid {
    display: grid;
    grid-template-columns: repeat(auto-fill, minmax(280px, 1fr));
    gap: 12px;
  }

  .tip-item {
    font-size: 13px;
    color: #94a3b8;
    line-height: 1.5;
    display: flex;
    gap: 10px;
    align-items: flex-start;
  }

  .tip-item::before {
    content: '→';
    color: var(--accent);
    font-family: 'Space Mono', monospace;
    font-size: 12px;
    flex-shrink: 0;
    margin-top: 1px;
  }

  .tip-item code {
    font-family: 'Space Mono', monospace;
    font-size: 11px;
    background: rgba(0,0,0,0.3);
    padding: 1px 5px;
    border-radius: 3px;
    color: #c084fc;
  }

  /* hidden card for filter */
  .card.hidden { display: none; }

  footer {
    border-top: 1px solid var(--border);
    padding: 24px 0;
    text-align: center;
    font-family: 'Space Mono', monospace;
    font-size: 11px;
    color: var(--muted);
    letter-spacing: 0.5px;
  }
</style>
</head>
<body>

<div class="container">

  <header>
    <div class="header-inner">
      <div>
        <div class="tag">⚡ XRay Sourcing Tool</div>
        <h1>Tender <span>Engineers</span><br>Boolean Hunter</h1>
        <p class="subtitle">// Sourcing across LinkedIn · Job Boards · GitHub · Communities · Databases</p>
        <div class="cities">
          <span class="city-badge frankfurt">🇩🇪 Frankfurt</span>
          <span class="city-badge london">🇬🇧 London</span>
          <span class="city-badge amsterdam">🇳🇱 Amsterdam</span>
        </div>
      </div>
    </div>
  </header>

  <!-- Tips -->
  <div class="tips">
    <h3>// XRay Boolean Cheat Sheet</h3>
    <div class="tips-grid">
      <div class="tip-item">Use <code>site:</code> to restrict Google to one domain only</div>
      <div class="tip-item">Use <code>intitle:</code> to find pages with keyword in their title</div>
      <div class="tip-item">Use <code>inurl:</code> to target specific URL patterns (e.g. <code>inurl:/in/</code> for LinkedIn profiles)</div>
      <div class="tip-item">Use <code>filetype:pdf</code> to find CVs/resumes on open web</div>
      <div class="tip-item">Combine city variants: <code>"Frankfurt" OR "Frankfurt am Main"</code></div>
      <div class="tip-item">Tender roles often use: Tendering, Bid, Pre-sales, Proposals, Estimation</div>
    </div>
  </div>

  <!-- Filters -->
  <div class="controls">
    <button class="filter-btn active" onclick="filterCards('all', this)">All Sources</button>
    <button class="filter-btn" onclick="filterCards('linkedin', this)">LinkedIn</button>
    <button class="filter-btn" onclick="filterCards('jobboards', this)">Job Boards</button>
    <button class="filter-btn" onclick="filterCards('cv', this)">CV Databases</button>
    <button class="filter-btn" onclick="filterCards('community', this)">Communities</button>
    <button class="filter-btn" onclick="filterCards('social', this)">Social / Dev</button>
    <div class="count">Showing <span id="count">18</span> sources</div>
  </div>

  <div class="section-label">Professional Networks</div>
  <div class="grid" id="grid">

    <!-- LINKEDIN GOOGLE XRAY - Frankfurt -->
    <div class="card" data-cat="linkedin" style="--card-accent:#0077b5;animation-delay:0.05s">
      <div class="card-header">
        <div class="source-icon" style="--icon-bg:rgba(0,119,181,0.12);--icon-border:rgba(0,119,181,0.25)">💼</div>
        <div class="source-meta">
          <div class="source-name">LinkedIn XRay — Frankfurt</div>
          <div class="source-category">LinkedIn · Google XRay</div>
        </div>
      </div>
      <div class="source-query">
        site:linkedin.com/in <strong>("Tender Engineer" OR "Bid Engineer" OR "Tendering Engineer" OR "Proposal Engineer")</strong> ("Frankfurt" OR "Frankfurt am Main") ("construction" OR "engineering" OR "infrastructure" OR "energy")
      </div>
      <div class="city-tags"><span class="ct f">Frankfurt</span></div>
      <div class="links">
        <a class="link-btn primary" href='https://www.google.com/search?q=site:linkedin.com/in+("Tender+Engineer"+OR+"Bid+Engineer"+OR+"Tendering+Engineer"+OR+"Proposal+Engineer")+("Frankfurt"+OR+"Frankfurt+am+Main")' target="_blank">🔍 Search Google</a>
      </div>
    </div>

    <!-- LINKEDIN XRAY - London -->
    <div class="card" data-cat="linkedin" style="--card-accent:#0077b5;animation-delay:0.1s">
      <div class="card-header">
        <div class="source-icon" style="--icon-bg:rgba(0,119,181,0.12);--icon-border:rgba(0,119,181,0.25)">💼</div>
        <div class="source-meta">
          <div class="source-name">LinkedIn XRay — London</div>
          <div class="source-category">LinkedIn · Google XRay</div>
        </div>
      </div>
      <div class="source-query">
        site:linkedin.com/in <strong>("Tender Engineer" OR "Bid Engineer" OR "Proposals Engineer" OR "Tendering Manager")</strong> "London" ("rail" OR "infrastructure" OR "oil" OR "power" OR "utilities" OR "construction")
      </div>
      <div class="city-tags"><span class="ct l">London</span></div>
      <div class="links">
        <a class="link-btn primary" href='https://www.google.com/search?q=site:linkedin.com/in+("Tender+Engineer"+OR+"Bid+Engineer"+OR+"Proposals+Engineer")+("London")' target="_blank">🔍 Search Google</a>
      </div>
    </div>

    <!-- LINKEDIN XRAY - Amsterdam -->
    <div class="card" data-cat="linkedin" style="--card-accent:#0077b5;animation-delay:0.15s">
      <div class="card-header">
        <div class="source-icon" style="--icon-bg:rgba(0,119,181,0.12);--icon-border:rgba(0,119,181,0.25)">💼</div>
        <div class="source-meta">
          <div class="source-name">LinkedIn XRay — Amsterdam</div>
          <div class="source-category">LinkedIn · Google XRay</div>
        </div>
      </div>
      <div class="source-query">
        site:linkedin.com/in <strong>("Tender Engineer" OR "Bid Engineer" OR "Offertemanager" OR "Aanbestedingsingenieur")</strong> ("Amsterdam" OR "Noord-Holland") ("energy" OR "offshore" OR "construction" OR "rail")
      </div>
      <div class="city-tags"><span class="ct a">Amsterdam</span></div>
      <div class="links">
        <a class="link-btn primary" href='https://www.google.com/search?q=site:linkedin.com/in+("Tender+Engineer"+OR+"Bid+Engineer"+OR+"Offertemanager")+("Amsterdam"+OR+"Noord-Holland")' target="_blank">🔍 Search Google</a>
      </div>
    </div>

    <!-- XING - DACH Region -->
    <div class="card" data-cat="linkedin" style="--card-accent:#006567;animation-delay:0.2s">
      <div class="card-header">
        <div class="source-icon" style="--icon-bg:rgba(0,101,103,0.12);--icon-border:rgba(0,101,103,0.3)">🇩🇪</div>
        <div class="source-meta">
          <div class="source-name">XING XRay — Frankfurt</div>
          <div class="source-category">XING · Google XRay · DACH</div>
        </div>
      </div>
      <div class="source-query">
        site:xing.com/profile <strong>("Tender Engineer" OR "Ausschreibungsingenieur" OR "Angebotsingenieur" OR "Bid Engineer")</strong> "Frankfurt"
      </div>
      <div class="city-tags"><span class="ct f">Frankfurt</span></div>
      <div class="links">
        <a class="link-btn primary" href='https://www.google.com/search?q=site:xing.com/profile+("Tender+Engineer"+OR+"Ausschreibungsingenieur"+OR+"Angebotsingenieur")+"Frankfurt"' target="_blank">🔍 Search Google</a>
      </div>
    </div>

  </div>

  <div class="section-label">Job Boards & Career Sites</div>
  <div class="grid">

    <!-- Indeed XRay -->
    <div class="card" data-cat="jobboards" style="--card-accent:#2164f3;animation-delay:0.05s">
      <div class="card-header">
        <div class="source-icon" style="--icon-bg:rgba(33,100,243,0.1);--icon-border:rgba(33,100,243,0.25)">🌐</div>
        <div class="source-meta">
          <div class="source-name">Indeed — All 3 Cities</div>
          <div class="source-category">Job Board · Profile XRay</div>
        </div>
      </div>
      <div class="source-query">
        site:indeed.com/r <strong>("Tender Engineer" OR "Bid Engineer" OR "Proposal Engineer")</strong> ("Frankfurt" OR "London" OR "Amsterdam")
      </div>
      <div class="city-tags"><span class="ct f">Frankfurt</span><span class="ct l">London</span><span class="ct a">Amsterdam</span></div>
      <div class="links">
        <a class="link-btn primary" href='https://www.google.com/search?q=site:indeed.com/r+("Tender+Engineer"+OR+"Bid+Engineer")+("Frankfurt"+OR+"London"+OR+"Amsterdam")' target="_blank">🔍 Search Google</a>
        <a class="link-btn secondary" href="https://www.indeed.com" target="_blank">↗ Indeed</a>
      </div>
    </div>

    <!-- StepStone Germany -->
    <div class="card" data-cat="jobboards" style="--card-accent:#e8470a;animation-delay:0.1s">
      <div class="card-header">
        <div class="source-icon" style="--icon-bg:rgba(232,71,10,0.1);--icon-border:rgba(232,71,10,0.3)">🪜</div>
        <div class="source-meta">
          <div class="source-name">StepStone DE — Frankfurt</div>
          <div class="source-category">Job Board · Germany</div>
        </div>
      </div>
      <div class="source-query">
        site:stepstone.de <strong>"Tender Engineer" OR "Bid Engineer" OR "Angebotsingenieur"</strong> Frankfurt
      </div>
      <div class="city-tags"><span class="ct f">Frankfurt</span></div>
      <div class="links">
        <a class="link-btn primary" href='https://www.google.com/search?q=site:stepstone.de+("Tender+Engineer"+OR+"Bid+Engineer"+OR+"Angebotsingenieur")+Frankfurt' target="_blank">🔍 Search Google</a>
        <a class="link-btn secondary" href="https://www.stepstone.de" target="_blank">↗ StepStone</a>
      </div>
    </div>

    <!-- Glassdoor XRay -->
    <div class="card" data-cat="jobboards" style="--card-accent:#0caa41;animation-delay:0.15s">
      <div class="card-header">
        <div class="source-icon" style="--icon-bg:rgba(12,170,65,0.1);--icon-border:rgba(12,170,65,0.25)">🏢</div>
        <div class="source-meta">
          <div class="source-name">Glassdoor Profiles</div>
          <div class="source-category">Job Board · Employer Reviews</div>
        </div>
      </div>
      <div class="source-query">
        site:glassdoor.com/member <strong>("Tender Engineer" OR "Bid Engineer" OR "Tendering")</strong> ("Frankfurt" OR "London" OR "Amsterdam")
      </div>
      <div class="city-tags"><span class="ct f">Frankfurt</span><span class="ct l">London</span><span class="ct a">Amsterdam</span></div>
      <div class="links">
        <a class="link-btn primary" href='https://www.google.com/search?q=site:glassdoor.com/member+("Tender+Engineer"+OR+"Bid+Engineer")+("Frankfurt"+OR+"London"+OR+"Amsterdam")' target="_blank">🔍 Search Google</a>
      </div>
    </div>

    <!-- Reed.co.uk -->
    <div class="card" data-cat="jobboards" style="--card-accent:#d0021b;animation-delay:0.2s">
      <div class="card-header">
        <div class="source-icon" style="--icon-bg:rgba(208,2,27,0.1);--icon-border:rgba(208,2,27,0.25)">📋</div>
        <div class="source-meta">
          <div class="source-name">Reed.co.uk — London</div>
          <div class="source-category">Job Board · UK Focused</div>
        </div>
      </div>
      <div class="source-query">
        site:reed.co.uk <strong>"Tender Engineer" OR "Bid Engineer" OR "Proposals Engineer"</strong> London
      </div>
      <div class="city-tags"><span class="ct l">London</span></div>
      <div class="links">
        <a class="link-btn primary" href='https://www.google.com/search?q=site:reed.co.uk+("Tender+Engineer"+OR+"Bid+Engineer")+"London"' target="_blank">🔍 Search Google</a>
        <a class="link-btn secondary" href="https://www.reed.co.uk" target="_blank">↗ Reed</a>
      </div>
    </div>

    <!-- Monsterboard.nl -->
    <div class="card" data-cat="jobboards" style="--card-accent:#7209b7;animation-delay:0.25s">
      <div class="card-header">
        <div class="source-icon" style="--icon-bg:rgba(114,9,183,0.1);--icon-border:rgba(114,9,183,0.3)">🔮</div>
        <div class="source-meta">
          <div class="source-name">Monsterboard.nl — Amsterdam</div>
          <div class="source-category">Job Board · Netherlands</div>
        </div>
      </div>
      <div class="source-query">
        site:monsterboard.nl <strong>"Tender Engineer" OR "Bid Engineer" OR "Offertemanager"</strong> Amsterdam
      </div>
      <div class="city-tags"><span class="ct a">Amsterdam</span></div>
      <div class="links">
        <a class="link-btn primary" href='https://www.google.com/search?q=site:monsterboard.nl+("Tender+Engineer"+OR+"Offertemanager")+"Amsterdam"' target="_blank">🔍 Search Google</a>
        <a class="link-btn secondary" href="https://www.monsterboard.nl" target="_blank">↗ Monsterboard</a>
      </div>
    </div>

    <!-- Engineering job boards -->
    <div class="card" data-cat="jobboards" style="--card-accent:#f59e0b;animation-delay:0.3s">
      <div class="card-header">
        <div class="source-icon" style="--icon-bg:rgba(245,158,11,0.1);--icon-border:rgba(245,158,11,0.3)">⚙️</div>
        <div class="source-meta">
          <div class="source-name">EngineeringJobs / Jobsite</div>
          <div class="source-category">Niche Job Board · Engineering</div>
        </div>
      </div>
      <div class="source-query">
        site:engineeringjobs.co.uk OR site:jobsite.co.uk <strong>"Tender Engineer" OR "Bid Engineer"</strong> "London"
      </div>
      <div class="city-tags"><span class="ct l">London</span></div>
      <div class="links">
        <a class="link-btn primary" href='https://www.google.com/search?q=(site:engineeringjobs.co.uk+OR+site:jobsite.co.uk)+("Tender+Engineer"+OR+"Bid+Engineer")+"London"' target="_blank">🔍 Search Google</a>
      </div>
    </div>

  </div>

  <div class="section-label">CV & Resume Databases</div>
  <div class="grid">

    <!-- Open CV XRay -->
    <div class="card" data-cat="cv" style="--card-accent:#06b6d4;animation-delay:0.05s">
      <div class="card-header">
        <div class="source-icon" style="--icon-bg:rgba(6,182,212,0.1);--icon-border:rgba(6,182,212,0.25)">📄</div>
        <div class="source-meta">
          <div class="source-name">Open Web CV Hunt</div>
          <div class="source-category">Google XRay · PDF CVs</div>
        </div>
      </div>
      <div class="source-query">
        filetype:pdf <strong>("Tender Engineer" OR "Bid Engineer" OR "Tendering")</strong> ("Frankfurt" OR "London" OR "Amsterdam") ("CV" OR "resume" OR "curriculum vitae")
      </div>
      <div class="city-tags"><span class="ct f">Frankfurt</span><span class="ct l">London</span><span class="ct a">Amsterdam</span></div>
      <div class="links">
        <a class="link-btn primary" href='https://www.google.com/search?q=filetype:pdf+("Tender+Engineer"+OR+"Bid+Engineer")+("Frankfurt"+OR+"London"+OR+"Amsterdam")+("CV"+OR+"resume")' target="_blank">🔍 Search Google</a>
      </div>
    </div>

    <!-- CV Library UK -->
    <div class="card" data-cat="cv" style="--card-accent:#3b82f6;animation-delay:0.1s">
      <div class="card-header">
        <div class="source-icon" style="--icon-bg:rgba(59,130,246,0.1);--icon-border:rgba(59,130,246,0.25)">📚</div>
        <div class="source-meta">
          <div class="source-name">CV-Library — London</div>
          <div class="source-category">CV Database · UK</div>
        </div>
      </div>
      <div class="source-query">
        site:cv-library.co.uk <strong>"Tender Engineer" OR "Bid Engineer" OR "Proposals Engineer"</strong> London
      </div>
      <div class="city-tags"><span class="ct l">London</span></div>
      <div class="links">
        <a class="link-btn primary" href='https://www.google.com/search?q=site:cv-library.co.uk+("Tender+Engineer"+OR+"Bid+Engineer")+"London"' target="_blank">🔍 Search Google</a>
        <a class="link-btn secondary" href="https://www.cv-library.co.uk" target="_blank">↗ CV-Library</a>
      </div>
    </div>

    <!-- XING Lebenslauf Germany -->
    <div class="card" data-cat="cv" style="--card-accent:#006567;animation-delay:0.15s">
      <div class="card-header">
        <div class="source-icon" style="--icon-bg:rgba(0,101,103,0.12);--icon-border:rgba(0,101,103,0.3)">🗂️</div>
        <div class="source-meta">
          <div class="source-name">XING Lebenslauf — Frankfurt</div>
          <div class="source-category">CV Database · DACH</div>
        </div>
      </div>
      <div class="source-query">
        site:xing.com <strong>("Tender" OR "Ausschreibung" OR "Angebot" OR "Bid")</strong> ("Ingenieur" OR "Engineer") "Frankfurt" filetype:pdf OR inurl:lebenslauf
      </div>
      <div class="city-tags"><span class="ct f">Frankfurt</span></div>
      <div class="links">
        <a class="link-btn primary" href='https://www.google.com/search?q=site:xing.com+("Tender"+OR+"Angebotsingenieur")+"Frankfurt"' target="_blank">🔍 Search Google</a>
      </div>
    </div>

  </div>

  <div class="section-label">Developer & Community Platforms</div>
  <div class="grid">

    <!-- GitHub -->
    <div class="card" data-cat="social" style="--card-accent:#f0f6fc;animation-delay:0.05s">
      <div class="card-header">
        <div class="source-icon" style="--icon-bg:rgba(240,246,252,0.06);--icon-border:rgba(240,246,252,0.15)">🐙</div>
        <div class="source-meta">
          <div class="source-name">GitHub Profiles</div>
          <div class="source-category">Developer Platform</div>
        </div>
      </div>
      <div class="source-query">
        site:github.com <strong>("Tender Engineer" OR "Bid Engineer" OR "Proposal Engineer")</strong> ("Frankfurt" OR "London" OR "Amsterdam")
      </div>
      <div class="city-tags"><span class="ct f">Frankfurt</span><span class="ct l">London</span><span class="ct a">Amsterdam</span></div>
      <div class="links">
        <a class="link-btn primary" href='https://www.google.com/search?q=site:github.com+("Tender+Engineer"+OR+"Bid+Engineer")+("Frankfurt"+OR+"London"+OR+"Amsterdam")' target="_blank">🔍 Search Google</a>
        <a class="link-btn secondary" href="https://github.com/search?q=tender+engineer+location%3AFrankfurt&type=users" target="_blank">↗ GitHub Search</a>
      </div>
    </div>

    <!-- Twitter/X -->
    <div class="card" data-cat="social" style="--card-accent:#1d9bf0;animation-delay:0.1s">
      <div class="card-header">
        <div class="source-icon" style="--icon-bg:rgba(29,155,240,0.1);--icon-border:rgba(29,155,240,0.25)">𝕏</div>
        <div class="source-meta">
          <div class="source-name">X (Twitter) Profiles</div>
          <div class="source-category">Social · Passive Candidates</div>
        </div>
      </div>
      <div class="source-query">
        site:twitter.com OR site:x.com <strong>"Tender Engineer" OR "Bid Engineer" OR "Tendering"</strong> ("Frankfurt" OR "London" OR "Amsterdam")
      </div>
      <div class="city-tags"><span class="ct f">Frankfurt</span><span class="ct l">London</span><span class="ct a">Amsterdam</span></div>
      <div class="links">
        <a class="link-btn primary" href='https://www.google.com/search?q=(site:twitter.com+OR+site:x.com)+("Tender+Engineer"+OR+"Bid+Engineer")+("Frankfurt"+OR+"London"+OR+"Amsterdam")' target="_blank">🔍 Search Google</a>
      </div>
    </div>

    <!-- Meetup / Events -->
    <div class="card" data-cat="community" style="--card-accent:#f64060;animation-delay:0.15s">
      <div class="card-header">
        <div class="source-icon" style="--icon-bg:rgba(246,64,96,0.1);--icon-border:rgba(246,64,96,0.3)">🎪</div>
        <div class="source-meta">
          <div class="source-name">Meetup.com Communities</div>
          <div class="source-category">Events · Networking</div>
        </div>
      </div>
      <div class="source-query">
        site:meetup.com <strong>("engineering" OR "construction" OR "infrastructure" OR "procurement")</strong> ("Frankfurt" OR "London" OR "Amsterdam")
      </div>
      <div class="city-tags"><span class="ct f">Frankfurt</span><span class="ct l">London</span><span class="ct a">Amsterdam</span></div>
      <div class="links">
        <a class="link-btn primary" href='https://www.google.com/search?q=site:meetup.com+("engineering"+OR+"construction")+("Frankfurt"+OR+"London"+OR+"Amsterdam")' target="_blank">🔍 Search Google</a>
      </div>
    </div>

    <!-- ResearchGate -->
    <div class="card" data-cat="community" style="--card-accent:#40c0b4;animation-delay:0.2s">
      <div class="card-header">
        <div class="source-icon" style="--icon-bg:rgba(64,192,180,0.1);--icon-border:rgba(64,192,180,0.25)">🔬</div>
        <div class="source-meta">
          <div class="source-name">ResearchGate Profiles</div>
          <div class="source-category">Academic · Senior Engineers</div>
        </div>
      </div>
      <div class="source-query">
        site:researchgate.net <strong>("Tender" OR "Bid" OR "Proposal" OR "tendering")</strong> "engineer" ("Frankfurt" OR "London" OR "Amsterdam")
      </div>
      <div class="city-tags"><span class="ct f">Frankfurt</span><span class="ct l">London</span><span class="ct a">Amsterdam</span></div>
      <div class="links">
        <a class="link-btn primary" href='https://www.google.com/search?q=site:researchgate.net+("Tender"+OR+"Bid")+engineer+("Frankfurt"+OR+"London"+OR+"Amsterdam")' target="_blank">🔍 Search Google</a>
      </div>
    </div>

    <!-- IStructE / ICE -->
    <div class="card" data-cat="community" style="--card-accent:#00b4d8;animation-delay:0.25s">
      <div class="card-header">
        <div class="source-icon" style="--icon-bg:rgba(0,180,216,0.1);--icon-border:rgba(0,180,216,0.25)">🏗️</div>
        <div class="source-meta">
          <div class="source-name">ICE / IStructE / IMechE</div>
          <div class="source-category">Professional Bodies · UK</div>
        </div>
      </div>
      <div class="source-query">
        site:ice.org.uk OR site:istructe.org OR site:imeche.org <strong>"Tender" OR "Bid" OR "Tendering"</strong> "engineer"
      </div>
      <div class="city-tags"><span class="ct l">London</span></div>
      <div class="links">
        <a class="link-btn primary" href='https://www.google.com/search?q=(site:ice.org.uk+OR+site:istructe.org)+("Tender"+OR+"Bid")+"engineer"' target="_blank">🔍 Search Google</a>
      </div>
    </div>

    <!-- Stack Overflow / Engineering forums -->
    <div class="card" data-cat="social" style="--card-accent:#f48024;animation-delay:0.3s">
      <div class="card-header">
        <div class="source-icon" style="--icon-bg:rgba(244,128,36,0.1);--icon-border:rgba(244,128,36,0.3)">📦</div>
        <div class="source-meta">
          <div class="source-name">Stack Overflow / Dev Profiles</div>
          <div class="source-category">Developer Community</div>
        </div>
      </div>
      <div class="source-query">
        site:stackoverflow.com/users <strong>("Tender" OR "Bid" OR "Proposal")</strong> ("Frankfurt" OR "London" OR "Amsterdam")
      </div>
      <div class="city-tags"><span class="ct f">Frankfurt</span><span class="ct l">London</span><span class="ct a">Amsterdam</span></div>
      <div class="links">
        <a class="link-btn primary" href='https://www.google.com/search?q=site:stackoverflow.com/users+("Tender"+OR+"Bid")+("Frankfurt"+OR+"London"+OR+"Amsterdam")' target="_blank">🔍 Search Google</a>
      </div>
    </div>

  </div>

  <footer>
    ⚡ XRay Sourcing Tool · Tender Engineers · Frankfurt · London · Amsterdam &nbsp;|&nbsp; Click any button to open live Google search
  </footer>

</div>

<script>
  function filterCards(cat, btn) {
    document.querySelectorAll('.filter-btn').forEach(b => b.classList.remove('active'));
    btn.classList.add('active');

    const cards = document.querySelectorAll('.card');
    let visible = 0;
    cards.forEach(card => {
      if (cat === 'all' || card.dataset.cat === cat) {
        card.classList.remove('hidden');
        visible++;
      } else {
        card.classList.add('hidden');
      }
    });
    document.getElementById('count').textContent = visible;
  }
</script>
</body>
</html>
