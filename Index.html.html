<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>AEGIS Public — Whitepaper v1.0</title>
<style>
  @import url('https://fonts.googleapis.com/css2?family=Syne:wght@400;600;700;800&family=Space+Mono:wght@400;700&family=Inter:wght@300;400;500&display=swap');

  :root {
    --black: #040406;
    --white: #F0EEE8;
    --accent: #00FF94;
    --accent2: #FF3B57;
    --accent3: #3B8BFF;
    --glass: rgba(255,255,255,0.04);
    --border: rgba(255,255,255,0.08);
    --muted: rgba(240,238,232,0.45);
  }

  * { margin: 0; padding: 0; box-sizing: border-box; }

  html { scroll-behavior: smooth; }

  body {
    background: var(--black);
    color: var(--white);
    font-family: 'Inter', sans-serif;
    font-weight: 300;
    line-height: 1.7;
    overflow-x: hidden;
  }

  /* Background grid */
  body::before {
    content: '';
    position: fixed;
    inset: 0;
    background-image:
      linear-gradient(rgba(0,255,148,0.03) 1px, transparent 1px),
      linear-gradient(90deg, rgba(0,255,148,0.03) 1px, transparent 1px);
    background-size: 60px 60px;
    pointer-events: none;
    z-index: 0;
  }

  /* Ambient glow */
  body::after {
    content: '';
    position: fixed;
    top: -200px;
    left: 50%;
    transform: translateX(-50%);
    width: 800px;
    height: 800px;
    background: radial-gradient(circle, rgba(0,255,148,0.06) 0%, transparent 70%);
    pointer-events: none;
    z-index: 0;
  }

  /* ─── COVER ─── */
  .cover {
    position: relative;
    min-height: 100vh;
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    text-align: center;
    padding: 60px 24px;
    z-index: 1;
    border-bottom: 1px solid var(--border);
  }

  .cover-tag {
    font-family: 'Space Mono', monospace;
    font-size: 11px;
    letter-spacing: 4px;
    color: var(--accent);
    text-transform: uppercase;
    margin-bottom: 40px;
    padding: 8px 20px;
    border: 1px solid rgba(0,255,148,0.3);
    display: inline-block;
    animation: pulse-border 3s infinite;
  }

  @keyframes pulse-border {
    0%, 100% { border-color: rgba(0,255,148,0.3); }
    50% { border-color: rgba(0,255,148,0.8); }
  }

  .cover-logo {
    font-family: 'Syne', sans-serif;
    font-weight: 800;
    font-size: clamp(72px, 15vw, 140px);
    letter-spacing: -4px;
    line-height: 0.9;
    background: linear-gradient(135deg, var(--white) 0%, var(--accent) 100%);
    -webkit-background-clip: text;
    -webkit-text-fill-color: transparent;
    background-clip: text;
    margin-bottom: 8px;
    animation: logo-in 1s ease forwards;
  }

  @keyframes logo-in {
    from { opacity: 0; transform: translateY(30px); }
    to { opacity: 1; transform: translateY(0); }
  }

  .cover-sub {
    font-family: 'Syne', sans-serif;
    font-size: clamp(14px, 3vw, 22px);
    font-weight: 600;
    letter-spacing: 6px;
    color: var(--muted);
    text-transform: uppercase;
    margin-bottom: 48px;
  }

  .cover-desc {
    max-width: 560px;
    font-size: 17px;
    color: var(--muted);
    line-height: 1.8;
    margin-bottom: 60px;
  }

  .cover-desc strong {
    color: var(--white);
    font-weight: 500;
  }

  .cover-meta {
    font-family: 'Space Mono', monospace;
    font-size: 11px;
    color: rgba(240,238,232,0.25);
    letter-spacing: 2px;
  }

  .cover-stats {
    display: flex;
    gap: 48px;
    margin-bottom: 60px;
    flex-wrap: wrap;
    justify-content: center;
  }

  .stat {
    text-align: center;
  }

  .stat-num {
    font-family: 'Syne', sans-serif;
    font-size: 36px;
    font-weight: 800;
    color: var(--accent);
    display: block;
  }

  .stat-label {
    font-size: 11px;
    letter-spacing: 2px;
    color: var(--muted);
    text-transform: uppercase;
  }

  /* ─── SECTIONS ─── */
  .section {
    position: relative;
    z-index: 1;
    max-width: 860px;
    margin: 0 auto;
    padding: 80px 24px;
    border-bottom: 1px solid var(--border);
  }

  .section-num {
    font-family: 'Space Mono', monospace;
    font-size: 11px;
    letter-spacing: 3px;
    color: var(--accent);
    text-transform: uppercase;
    margin-bottom: 20px;
    display: flex;
    align-items: center;
    gap: 12px;
  }

  .section-num::after {
    content: '';
    flex: 1;
    height: 1px;
    background: rgba(0,255,148,0.2);
    max-width: 80px;
  }

  .section-title {
    font-family: 'Syne', sans-serif;
    font-weight: 800;
    font-size: clamp(28px, 5vw, 48px);
    letter-spacing: -1px;
    line-height: 1.1;
    margin-bottom: 32px;
  }

  .section-title span {
    color: var(--accent);
  }

  p {
    color: var(--muted);
    margin-bottom: 20px;
    font-size: 16px;
  }

  p strong {
    color: var(--white);
    font-weight: 500;
  }

  /* ─── CALLOUT BOXES ─── */
  .callout {
    background: var(--glass);
    border: 1px solid var(--border);
    border-left: 3px solid var(--accent);
    padding: 24px 28px;
    margin: 32px 0;
    font-family: 'Space Mono', monospace;
    font-size: 13px;
    color: var(--white);
    line-height: 1.9;
  }

  .callout.red {
    border-left-color: var(--accent2);
  }

  .callout.blue {
    border-left-color: var(--accent3);
  }

  /* ─── COMPARISON TABLE ─── */
  .compare {
    width: 100%;
    border-collapse: collapse;
    margin: 32px 0;
    font-size: 14px;
  }

  .compare th {
    font-family: 'Space Mono', monospace;
    font-size: 11px;
    letter-spacing: 2px;
    text-transform: uppercase;
    color: var(--accent);
    padding: 12px 16px;
    border-bottom: 1px solid var(--border);
    text-align: left;
  }

  .compare td {
    padding: 14px 16px;
    border-bottom: 1px solid var(--border);
    color: var(--muted);
    vertical-align: top;
  }

  .compare tr:last-child td { border-bottom: none; }

  .compare td:first-child {
    color: var(--white);
    font-weight: 500;
  }

  .yes { color: var(--accent) !important; }
  .no { color: var(--accent2) !important; }
  .partial { color: #FFB800 !important; }

  /* ─── ARCHITECTURE LAYERS ─── */
  .layers {
    margin: 40px 0;
    display: flex;
    flex-direction: column;
    gap: 2px;
  }

  .layer {
    background: var(--glass);
    border: 1px solid var(--border);
    padding: 20px 24px;
    display: flex;
    gap: 20px;
    align-items: flex-start;
    transition: border-color 0.3s;
  }

  .layer:hover { border-color: rgba(0,255,148,0.3); }

  .layer-num {
    font-family: 'Space Mono', monospace;
    font-size: 11px;
    color: var(--accent);
    min-width: 32px;
    padding-top: 2px;
  }

  .layer-title {
    font-family: 'Syne', sans-serif;
    font-weight: 700;
    font-size: 15px;
    margin-bottom: 6px;
    color: var(--white);
  }

  .layer-desc {
    font-size: 13px;
    color: var(--muted);
    margin: 0;
    line-height: 1.6;
  }

  /* ─── PRINCIPLES ─── */
  .principles {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(240px, 1fr));
    gap: 16px;
    margin: 32px 0;
  }

  .principle {
    background: var(--glass);
    border: 1px solid var(--border);
    padding: 24px;
    transition: all 0.3s;
  }

  .principle:hover {
    border-color: rgba(0,255,148,0.4);
    transform: translateY(-2px);
  }

  .principle-icon {
    font-size: 24px;
    margin-bottom: 12px;
    display: block;
  }

  .principle-title {
    font-family: 'Syne', sans-serif;
    font-weight: 700;
    font-size: 15px;
    margin-bottom: 8px;
    color: var(--white);
  }

  .principle-desc {
    font-size: 13px;
    color: var(--muted);
    margin: 0;
    line-height: 1.6;
  }

  /* ─── PHASES ─── */
  .phases {
    margin: 40px 0;
    position: relative;
  }

  .phase {
    display: flex;
    gap: 24px;
    margin-bottom: 32px;
    position: relative;
  }

  .phase-line {
    display: flex;
    flex-direction: column;
    align-items: center;
  }

  .phase-dot {
    width: 12px;
    height: 12px;
    border-radius: 50%;
    background: var(--accent);
    flex-shrink: 0;
    margin-top: 4px;
    box-shadow: 0 0 12px var(--accent);
  }

  .phase-connector {
    width: 1px;
    flex: 1;
    background: var(--border);
    margin: 4px 0;
    min-height: 40px;
  }

  .phase-content {
    flex: 1;
    padding-bottom: 8px;
  }

  .phase-tag {
    font-family: 'Space Mono', monospace;
    font-size: 10px;
    letter-spacing: 2px;
    color: var(--accent);
    text-transform: uppercase;
    margin-bottom: 6px;
  }

  .phase-title {
    font-family: 'Syne', sans-serif;
    font-weight: 700;
    font-size: 18px;
    margin-bottom: 8px;
    color: var(--white);
  }

  .phase-desc {
    font-size: 14px;
    color: var(--muted);
    margin: 0;
  }

  /* ─── VICTIM HIGHLIGHT ─── */
  .victim-box {
    background: rgba(255,59,87,0.07);
    border: 1px solid rgba(255,59,87,0.2);
    padding: 32px;
    margin: 40px 0;
    text-align: center;
  }

  .victim-quote {
    font-family: 'Syne', sans-serif;
    font-size: clamp(18px, 3vw, 26px);
    font-weight: 700;
    line-height: 1.4;
    color: var(--white);
    margin-bottom: 16px;
  }

  .victim-quote span { color: var(--accent2); }

  .victim-sub {
    font-size: 13px;
    color: var(--muted);
    margin: 0;
  }

  /* ─── TOKEN MODEL ─── */
  .token-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
    gap: 16px;
    margin: 32px 0;
  }

  .token-card {
    background: var(--glass);
    border: 1px solid var(--border);
    padding: 20px;
    text-align: center;
  }

  .token-action {
    font-family: 'Space Mono', monospace;
    font-size: 12px;
    color: var(--accent);
    margin-bottom: 8px;
    display: block;
  }

  .token-reward {
    font-family: 'Syne', sans-serif;
    font-size: 28px;
    font-weight: 800;
    color: var(--white);
    display: block;
    margin-bottom: 4px;
  }

  .token-desc {
    font-size: 12px;
    color: var(--muted);
    margin: 0;
  }

  /* ─── MANIFESTO ─── */
  .manifesto {
    background: linear-gradient(135deg, rgba(0,255,148,0.05) 0%, rgba(59,139,255,0.05) 100%);
    border: 1px solid rgba(0,255,148,0.15);
    padding: 48px;
    margin: 40px 0;
    text-align: center;
  }

  .manifesto p {
    font-family: 'Syne', sans-serif;
    font-size: clamp(16px, 2.5vw, 22px);
    font-weight: 600;
    color: var(--white);
    line-height: 1.7;
    margin-bottom: 0;
  }

  .manifesto p + p {
    margin-top: 20px;
    color: var(--muted);
    font-size: clamp(14px, 2vw, 17px);
    font-weight: 400;
    font-family: 'Inter', sans-serif;
  }

  /* ─── FOOTER ─── */
  .footer {
    position: relative;
    z-index: 1;
    text-align: center;
    padding: 60px 24px;
    border-top: 1px solid var(--border);
  }

  .footer-logo {
    font-family: 'Syne', sans-serif;
    font-weight: 800;
    font-size: 32px;
    background: linear-gradient(135deg, var(--white) 0%, var(--accent) 100%);
    -webkit-background-clip: text;
    -webkit-text-fill-color: transparent;
    background-clip: text;
    margin-bottom: 16px;
  }

  .footer-text {
    font-family: 'Space Mono', monospace;
    font-size: 11px;
    letter-spacing: 2px;
    color: rgba(240,238,232,0.2);
    text-transform: uppercase;
  }

  /* ─── SCROLLBAR ─── */
  ::-webkit-scrollbar { width: 4px; }
  ::-webkit-scrollbar-track { background: var(--black); }
  ::-webkit-scrollbar-thumb { background: rgba(0,255,148,0.3); }

  @media (max-width: 600px) {
    .cover-stats { gap: 28px; }
    .stat-num { font-size: 28px; }
    .manifesto { padding: 28px 20px; }
    .callout { padding: 18px 20px; }
  }
</style>
</head>
<body>

<!-- ═══════════════════════════════════════════ COVER -->
<section class="cover">
  <div class="cover-tag">Whitepaper v1.0 — June 2026</div>
  <div class="cover-logo">AEGIS</div>
  <div class="cover-sub">Public</div>
  <p class="cover-desc">
    A <strong>decentralized, borderless, free</strong> intelligence system that hunts scammers, 
    protects victims, and delivers justice — owned by nobody, accessible to everybody.
  </p>
  <div class="cover-stats">
    <div class="stat">
      <span class="stat-num">$9.9B</span>
      <span class="stat-label">Lost to scams annually</span>
    </div>
    <div class="stat">
      <span class="stat-num">0%</span>
      <span class="stat-label">Protection for small victims</span>
    </div>
    <div class="stat">
      <span class="stat-num">1%</span>
      <span class="stat-label">Scammers ever caught</span>
    </div>
    <div class="stat">
      <span class="stat-num">∞</span>
      <span class="stat-label">People who need this</span>
    </div>
  </div>
  <div class="cover-meta">AEGIS PUBLIC · OPEN SOURCE · NO GOVERNMENT CONTROL · FREE FOREVER</div>
</section>

<!-- ═══════════════════════════════════════════ 01 PROBLEM -->
<section class="section">
  <div class="section-num">01 — The Problem</div>
  <h2 class="section-title">The System Is <span>Broken</span></h2>

  <p>Every day, millions of people — from elderly pensioners to young workers in developing nations — lose their savings to scammers. The technology to catch most of these criminals already exists. The will to protect ordinary people does not.</p>

  <div class="victim-box">
    <div class="victim-quote">An elderly man on disability pay lost <span>$1,200</span> — money meant for food — before anyone told him it was a scam.</div>
    <p class="victim-sub">Source: FBI Operation Level Up, March 2026. 93 victims in this program alone were referred for suicide intervention.</p>
  </div>

  <p>The global anti-scam infrastructure is built for <strong>institutions, not people.</strong> Chainalysis charges six figures per year. TRM Labs serves governments and banks. Elliptic focuses on compliance teams. The FBI prioritizes cases above $10 million.</p>

  <p>The grandmother who lost $3,000. The migrant worker who lost $500. The student who lost $200. <strong>They have nothing.</strong></p>

  <div class="callout red">
    CURRENT SYSTEM IN PRACTICE:
    
    Rich victim → Lawyer → Court → Maybe justice → Years later
    Poor victim → Police report → File closed → Nothing
    
    The same crime. Completely different outcomes. Based only on wealth.
  </div>

  <table class="compare">
    <thead>
      <tr>
        <th>Platform</th>
        <th>Free?</th>
        <th>Public Access?</th>
        <th>Proactive?</th>
        <th>Decentralized?</th>
        <th>Victim Focused?</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td>Chainalysis</td>
        <td class="no">No</td>
        <td class="no">No</td>
        <td class="partial">Partial</td>
        <td class="no">No</td>
        <td class="no">No</td>
      </tr>
      <tr>
        <td>TRM Labs</td>
        <td class="no">No</td>
        <td class="no">No</td>
        <td class="partial">Partial</td>
        <td class="no">No</td>
        <td class="no">No</td>
      </tr>
      <tr>
        <td>Chainabuse</td>
        <td class="yes">Yes</td>
        <td class="yes">Yes</td>
        <td class="no">No</td>
        <td class="no">No</td>
        <td class="partial">Partial</td>
      </tr>
      <tr>
        <td>FBI/Interpol</td>
        <td class="yes">Yes</td>
        <td class="no">No</td>
        <td class="partial">Partial</td>
        <td class="no">No</td>
        <td class="partial">Partial</td>
      </tr>
      <tr>
        <td style="color: var(--accent); font-weight: 700;">AEGIS Public</td>
        <td class="yes">Yes</td>
        <td class="yes">Yes</td>
        <td class="yes">Yes</td>
        <td class="yes">Yes</td>
        <td class="yes">Yes</td>
      </tr>
    </tbody>
  </table>
</section>

<!-- ═══════════════════════════════════════════ 02 VISION -->
<section class="section">
  <div class="section-num">02 — The Vision</div>
  <h2 class="section-title">Justice for <span>Everyone</span></h2>

  <p>AEGIS Public is built on a single radical idea: <strong>protection from fraud is a human right, not a premium service.</strong></p>

  <p>Just as Bitcoin returned financial sovereignty to ordinary people — removing banks as gatekeepers — AEGIS Public returns justice to ordinary people, removing governments and institutions as gatekeepers of protection.</p>

  <div class="manifesto">
    <p>"The same system that protects a billionaire losing $10 million should protect the migrant worker losing $200."</p>
    <p>Not because it is profitable. Not because a government decided it. Because it is right — and because technology now makes it possible.</p>
  </div>

  <div class="principles">
    <div class="principle">
      <span class="principle-icon">⚖️</span>
      <div class="principle-title">Borderless Justice</div>
      <p class="principle-desc">No jurisdiction. No politics. A victim in Nigeria gets the same protection as a victim in New York.</p>
    </div>
    <div class="principle">
      <span class="principle-icon">🔓</span>
      <div class="principle-title">Permanently Free</div>
      <p class="principle-desc">Like Wikipedia. Like WhatsApp at launch. Core access never monetized. Ever.</p>
    </div>
    <div class="principle">
      <span class="principle-icon">🌐</span>
      <div class="principle-title">Decentralized</div>
      <p class="principle-desc">No central server. No single point of failure. No government can shut it down.</p>
    </div>
    <div class="principle">
      <span class="principle-icon">⚡</span>
      <div class="principle-title">Proactive Not Reactive</div>
      <p class="principle-desc">Stops scams before victims lose money. Not after. Detection before destruction.</p>
    </div>
    <div class="principle">
      <span class="principle-icon">👁️</span>
      <div class="principle-title">Radical Transparency</div>
      <p class="principle-desc">Open source. Publicly auditable. No black boxes. No hidden agendas.</p>
    </div>
    <div class="principle">
      <span class="principle-icon">🤝</span>
      <div class="principle-title">Community Governed</div>
      <p class="principle-desc">Owned by its users like Bitcoin itself. No corporation. No government. No single authority.</p>
    </div>
  </div>
</section>

<!-- ═══════════════════════════════════════════ 03 HOW IT WORKS -->
<section class="section">
  <div class="section-num">03 — How It Works</div>
  <h2 class="section-title">The <span>Architecture</span></h2>

  <p>AEGIS Public operates as four interconnected intelligence layers, each feeding the next — creating a continuous, self-improving protection loop that requires no human intervention once deployed.</p>

  <div class="layers">
    <div class="layer">
      <div class="layer-num">L1</div>
      <div>
        <div class="layer-title">Detection Engine</div>
        <p class="layer-desc">Monitors all new token contract deployments in real time. AI scans smart contract code for honeypot mechanisms, disabled sell functions, hidden admin keys, and ownership concentration patterns. Flags suspicious tokens before they reach victims.</p>
      </div>
    </div>
    <div class="layer">
      <div class="layer-num">L2</div>
      <div>
        <div class="layer-title">Pattern Recognition</div>
        <p class="layer-desc">Machine learning models trained on millions of historical scam transactions identify wash trading, coordinated pump activity, pig butchering communication patterns, and wallet clustering that indicates organized criminal networks.</p>
      </div>
    </div>
    <div class="layer">
      <div class="layer-num">L3</div>
      <div>
        <div class="layer-title">Community Intelligence</div>
        <p class="layer-desc">Victim reports are cross-referenced with on-chain data, weighted by community verification, and added to a tamper-proof public ledger. Every report strengthens the network. Every verified scammer profile is permanent and globally accessible.</p>
      </div>
    </div>
    <div class="layer">
      <div class="layer-num">L4</div>
      <div>
        <div class="layer-title">Autonomous Neutralization</div>
        <p class="layer-desc">Confirmed scammer wallets trigger automatic API alerts to 50+ exchanges worldwide. Profiles are published publicly. Connected wallets receive automatic warnings. Payment processors and DeFi protocols are notified. Economic isolation — without any government involvement.</p>
      </div>
    </div>
  </div>

  <div class="callout">
    FOR A POTENTIAL VICTIM:
    
    → Open AEGIS Public app (free, any phone)
    → Paste any wallet address or token contract
    → Receive instant risk assessment in seconds
    → "⚠️ This wallet linked to 47 scam reports across 12 countries"
    → Transaction cancelled. Victim protected. Before losing anything.
  </div>

  <div class="callout blue">
    FOR A SCAMMER AFTER DETECTION:
    
    → Every exchange automatically notified
    → Wallet publicly flagged on global ledger
    → All connected wallets warned automatically
    → Payment processors refuse transactions
    → Economically neutralized — no government required
    → Profile permanently on public record
  </div>
</section>

<!-- ═══════════════════════════════════════════ 04 TOKEN -->
<section class="section">
  <div class="section-num">04 — Community & Token Model</div>
  <h2 class="section-title">Governed by <span>Nobody.</span> Powered by <span>Everybody.</span></h2>

  <p>AEGIS Public introduces the <strong>SHIELD token</strong> — not for speculation, but purely for governance and community incentivization. The token cannot be bought by corporations or governments in bulk. It can only be earned by contributing to the network.</p>

  <div class="token-grid">
    <div class="token-card">
      <span class="token-action">Report a scam</span>
      <span class="token-reward">+10</span>
      <p class="token-desc">Verified scam report submitted with evidence</p>
    </div>
    <div class="token-card">
      <span class="token-action">Verify a report</span>
      <span class="token-reward">+3</span>
      <p class="token-desc">Community verification of submitted reports</p>
    </div>
    <div class="token-card">
      <span class="token-action">Develop the platform</span>
      <span class="token-reward">+50</span>
      <p class="token-desc">Open source code contributions accepted</p>
    </div>
    <div class="token-card">
      <span class="token-action">Prevent a scam</span>
      <span class="token-reward">+25</span>
      <p class="token-desc">Your report directly stopped a confirmed fraud attempt</p>
    </div>
  </div>

  <p>SHIELD tokens grant <strong>voting rights on platform decisions</strong> — which scammer categories to prioritize, which exchanges to integrate, which features to build next. No company decides. The community decides.</p>

  <p>False reports result in token slashing. Bad actors are automatically disincentivized. The system self-regulates without any moderator needed.</p>
</section>

<!-- ═══════════════════════════════════════════ 05 ROADMAP -->
<section class="section">
  <div class="section-num">05 — Roadmap</div>
  <h2 class="section-title">From <span>Idea</span> to <span>Infrastructure</span></h2>

  <div class="phases">
    <div class="phase">
      <div class="phase-line">
        <div class="phase-dot"></div>
        <div class="phase-connector"></div>
      </div>
      <div class="phase-content">
        <div class="phase-tag">Phase 0 · Now · Cost: $0</div>
        <div class="phase-title">Whitepaper & Community</div>
        <p class="phase-desc">Publish whitepaper open source. Share with crypto communities globally. Find 5 founding developers who believe in the mission. Begin building community around the idea before a single line of code is written.</p>
      </div>
    </div>
    <div class="phase">
      <div class="phase-line">
        <div class="phase-dot"></div>
        <div class="phase-connector"></div>
      </div>
      <div class="phase-content">
        <div class="phase-tag">Phase 1 · Months 1-6 · Cost: ~$100,000</div>
        <div class="phase-title">MVP — Wallet Checker</div>
        <p class="phase-desc">Basic wallet risk scanner. Community scam report database. Simple mobile app. First exchange API integrations. Community fundraise to cover development costs. Open source from day one.</p>
      </div>
    </div>
    <div class="phase">
      <div class="phase-line">
        <div class="phase-dot"></div>
        <div class="phase-connector"></div>
      </div>
      <div class="phase-content">
        <div class="phase-tag">Phase 2 · Months 6-18 · Community Funded</div>
        <div class="phase-title">AI Intelligence Layer</div>
        <p class="phase-desc">Machine learning pattern recognition. Real time token monitoring. Honeypot detection. Pig butchering network mapping. Cross-chain analysis across 50+ blockchains. SHIELD token launch.</p>
      </div>
    </div>
    <div class="phase">
      <div class="phase-line">
        <div class="phase-dot"></div>
        <div class="phase-connector"></div>
      </div>
      <div class="phase-content">
        <div class="phase-tag">Phase 3 · Year 2+ · Self-Sustaining</div>
        <div class="phase-title">Global Deployment</div>
        <p class="phase-desc">50+ exchange integrations. Enterprise API revenue funds free public tier. Available in 50+ languages. 100 million users. The WhatsApp moment for global justice.</p>
      </div>
    </div>
    <div class="phase">
      <div class="phase-line">
        <div class="phase-dot" style="background: var(--accent3); box-shadow: 0 0 12px var(--accent3);"></div>
      </div>
      <div class="phase-content">
        <div class="phase-tag">Phase 4 · Year 3+ · The Goal</div>
        <div class="phase-title">Public Justice Infrastructure</div>
        <p class="phase-desc">AEGIS Public becomes as fundamental to internet safety as HTTPS. Not owned by any company. Not controlled by any government. A permanent piece of global public infrastructure — like Bitcoin, like Wikipedia — that simply exists to protect people.</p>
      </div>
    </div>
  </div>
</section>

<!-- ═══════════════════════════════════════════ 06 SUSTAINABILITY -->
<section class="section">
  <div class="section-num">06 — Sustainability</div>
  <h2 class="section-title">Free Forever. <span>Funded Smartly.</span></h2>

  <p>AEGIS Public will never charge victims or reporters. The free tier is permanent and non-negotiable. Sustainability comes from those who benefit most from a scam-free ecosystem — exchanges, banks, and payment processors.</p>

  <table class="compare">
    <thead>
      <tr>
        <th>Revenue Stream</th>
        <th>Who Pays</th>
        <th>Amount</th>
        <th>Public Access Affected?</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td>Exchange API Access</td>
        <td>Crypto exchanges</td>
        <td>$50K-500K/year</td>
        <td class="no">Never</td>
      </tr>
      <tr>
        <td>Bank Fraud Screening</td>
        <td>Financial institutions</td>
        <td>$100K-1M/year</td>
        <td class="no">Never</td>
      </tr>
      <tr>
        <td>Community Donations</td>
        <td>Anyone who values it</td>
        <td>Variable</td>
        <td class="no">Never</td>
      </tr>
      <tr>
        <td>Grant Funding</td>
        <td>Web3 foundations</td>
        <td>$500K-5M</td>
        <td class="no">Never</td>
      </tr>
      <tr>
        <td>Public Users</td>
        <td>You</td>
        <td class="yes">$0 · Always Free</td>
        <td class="no">Never</td>
      </tr>
    </tbody>
  </table>
</section>

<!-- ═══════════════════════════════════════════ 07 CLOSING -->
<section class="section">
  <div class="section-num">07 — Closing</div>
  <h2 class="section-title">The <span>Satoshi Moment</span> for Justice</h2>

  <p>Bitcoin was created because the financial system failed ordinary people. Banks held the power. Access was denied to billions. One whitepaper changed everything.</p>

  <p>The justice system is failing ordinary people in exactly the same way. Courts are expensive. Jurisdictions are limited. Governments are slow. Billions of victims have no protection.</p>

  <p><strong>AEGIS Public is that whitepaper.</strong></p>

  <div class="manifesto">
    <p>A transparent, accessible, victim-focused, borderless, proactive system that prioritizes the millions of small victims who currently have zero protection.</p>
    <p>Governed by nobody. Powered by everybody. Free forever. Stopped by no one.</p>
  </div>

  <div class="callout">
    THIS IS AN OPEN INVITATION.

    Developers → Build with us. The code will be open source from day one.
    Designers  → Shape how justice looks for a billion users.
    Researchers → Help us map the scam networks nobody else will touch.
    Victims    → Your story is why this exists.
    Believers  → Share this whitepaper. That is how it begins.

    The system that protects everyone starts with anyone.
    It starts now.
  </div>
</section>

<!-- ═══════════════════════════════════════════ FOOTER -->
<footer class="footer">
  <div class="footer-logo">AEGIS Public</div>
  <p class="footer-text">Open Source · Decentralized · Free Forever · Version 1.0 · June 2026</p>
  <br>
  <p class="footer-text" style="color: rgba(240,238,232,0.1);">No rights reserved. Copy it. Share it. Build it. This belongs to everyone.</p>
</footer>

</body>
</html>
