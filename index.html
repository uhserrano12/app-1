<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Discharge Complexity + Care Burden Scale</title>
<style>
  @import url('https://fonts.googleapis.com/css2?family=DM+Serif+Display:ital@0;1&family=DM+Sans:wght@300;400;500;600&display=swap');

  *, *::before, *::after { box-sizing: border-box; margin: 0; padding: 0; }

  :root {
    --navy: #0f2340;
    --teal: #1a7a8a;
    --teal-light: #e8f4f6;
    --gold: #c8972a;
    --red: #c0392b;
    --orange: #d35400;
    --green: #1e7e4e;
    --green-light: #e8f5ee;
    --red-light: #fdf0ee;
    --orange-light: #fef5ec;
    --gray: #f4f5f7;
    --gray-mid: #e2e5ea;
    --text: #1a2530;
    --text-light: #5a6a7a;
    --white: #ffffff;
    --shadow: 0 2px 12px rgba(15,35,64,0.08);
    --shadow-lg: 0 8px 32px rgba(15,35,64,0.12);
  }

  body {
    font-family: 'DM Sans', sans-serif;
    background: #f0f3f7;
    color: var(--text);
    min-height: 100vh;
    padding: 0 0 60px;
  }

  /* HEADER */
  .header {
    background: var(--navy);
    padding: 28px 32px 24px;
    position: sticky;
    top: 0;
    z-index: 100;
    box-shadow: 0 2px 16px rgba(15,35,64,0.25);
  }
  .header-inner {
    max-width: 960px;
    margin: 0 auto;
    display: flex;
    align-items: center;
    justify-content: space-between;
    gap: 20px;
    flex-wrap: wrap;
  }
  .header-title {
    font-family: 'DM Serif Display', serif;
    font-size: 1.5rem;
    color: var(--white);
    line-height: 1.2;
  }
  .header-sub {
    font-size: 0.78rem;
    color: rgba(255,255,255,0.55);
    margin-top: 3px;
    font-style: italic;
  }
  .score-badge {
    background: rgba(255,255,255,0.08);
    border: 1px solid rgba(255,255,255,0.15);
    border-radius: 12px;
    padding: 12px 20px;
    text-align: center;
    min-width: 160px;
  }
  .score-badge-label {
    font-size: 0.7rem;
    color: rgba(255,255,255,0.5);
    text-transform: uppercase;
    letter-spacing: 0.1em;
    font-weight: 500;
  }
  .score-badge-value {
    font-family: 'DM Serif Display', serif;
    font-size: 2.2rem;
    color: var(--white);
    line-height: 1.1;
    transition: color 0.3s;
  }
  .score-badge-max {
    font-size: 0.75rem;
    color: rgba(255,255,255,0.4);
  }
  .score-badge-verdict {
    font-size: 0.72rem;
    font-weight: 600;
    margin-top: 4px;
    padding: 2px 8px;
    border-radius: 4px;
    display: inline-block;
    transition: all 0.3s;
  }

  /* HARD STOP BANNER */
  .hard-stop-banner {
    background: #7b1a1a;
    border-left: 4px solid #e74c3c;
    color: #fff;
    padding: 12px 32px;
    font-size: 0.82rem;
    display: none;
    animation: slideDown 0.3s ease;
  }
  .hard-stop-banner.active { display: block; }
  .hard-stop-banner strong { font-weight: 600; }
  @keyframes slideDown { from { opacity: 0; transform: translateY(-8px); } to { opacity: 1; transform: translateY(0); } }

  /* MAIN */
  .main {
    max-width: 960px;
    margin: 0 auto;
    padding: 32px 20px 0;
  }

  /* HARD STOP CHECKLIST */
  .hard-stop-section {
    background: var(--white);
    border-radius: 12px;
    border: 2px solid #e8b4b0;
    margin-bottom: 28px;
    overflow: hidden;
    box-shadow: var(--shadow);
  }
  .hard-stop-header {
    background: #fdf2f1;
    padding: 14px 20px;
    display: flex;
    align-items: center;
    gap: 10px;
    border-bottom: 1px solid #f0d0cc;
  }
  .hard-stop-header .icon { font-size: 1.1rem; }
  .hard-stop-header h2 {
    font-family: 'DM Serif Display', serif;
    font-size: 1rem;
    color: #8b2020;
  }
  .hard-stop-header p {
    font-size: 0.75rem;
    color: #a04040;
    margin-top: 1px;
  }
  .hard-stop-items {
    padding: 16px 20px;
    display: grid;
    grid-template-columns: 1fr 1fr;
    gap: 8px;
  }
  @media (max-width: 600px) { .hard-stop-items { grid-template-columns: 1fr; } }
  .hard-stop-item {
    display: flex;
    align-items: flex-start;
    gap: 10px;
    padding: 10px 12px;
    border-radius: 8px;
    border: 1.5px solid var(--gray-mid);
    cursor: pointer;
    transition: all 0.2s;
    background: var(--white);
  }
  .hard-stop-item:hover { border-color: #e8b4b0; background: #fdf8f8; }
  .hard-stop-item.flagged { border-color: #e74c3c; background: #fff5f5; }
  .hard-stop-item input[type="checkbox"] { display: none; }
  .hs-check {
    width: 18px; height: 18px;
    border: 2px solid #ccc;
    border-radius: 4px;
    flex-shrink: 0;
    margin-top: 1px;
    display: flex; align-items: center; justify-content: center;
    transition: all 0.2s;
    font-size: 11px;
  }
  .hard-stop-item.flagged .hs-check {
    background: #e74c3c;
    border-color: #e74c3c;
    color: white;
  }
  .hs-text { font-size: 0.8rem; line-height: 1.4; color: var(--text); }
  .hard-stop-item.flagged .hs-text { color: #8b2020; font-weight: 500; }

  /* DOMAINS */
  .domains-grid {
    display: grid;
    gap: 16px;
  }

  .domain-card {
    background: var(--white);
    border-radius: 12px;
    border: 1.5px solid var(--gray-mid);
    overflow: hidden;
    box-shadow: var(--shadow);
    transition: border-color 0.2s, box-shadow 0.2s;
  }
  .domain-card.has-score { border-color: var(--teal); box-shadow: 0 2px 16px rgba(26,122,138,0.1); }
  .domain-card.high-score { border-color: var(--orange); box-shadow: 0 2px 16px rgba(211,84,0,0.1); }
  .domain-card.max-score { border-color: var(--red); box-shadow: 0 2px 16px rgba(192,57,43,0.1); }

  .domain-header {
    padding: 14px 18px 12px;
    display: flex;
    align-items: flex-start;
    gap: 12px;
    border-bottom: 1px solid var(--gray-mid);
    background: var(--gray);
  }
  .domain-info { flex: 1; }
  .domain-title {
    font-weight: 600;
    font-size: 0.92rem;
    color: var(--navy);
    display: flex;
    align-items: center;
    gap: 8px;
  }
  .weight-tag {
    font-size: 0.68rem;
    font-weight: 600;
    padding: 2px 7px;
    border-radius: 4px;
    letter-spacing: 0.05em;
  }
  .weight-3 { background: #fde8e6; color: #8b2020; }
  .weight-2 { background: #fef0e0; color: #8b5000; }
  .weight-1 { background: var(--teal-light); color: #0f6070; }
  .domain-subtitle { font-size: 0.73rem; color: var(--text-light); margin-top: 2px; }

  .domain-score-display {
    text-align: right;
    min-width: 80px;
  }
  .domain-raw { font-size: 0.68rem; color: var(--text-light); }
  .domain-weighted {
    font-family: 'DM Serif Display', serif;
    font-size: 1.4rem;
    color: var(--text-light);
    line-height: 1;
    transition: color 0.3s;
  }
  .domain-card.has-score .domain-weighted { color: var(--teal); }
  .domain-card.high-score .domain-weighted { color: var(--orange); }
  .domain-card.max-score .domain-weighted { color: var(--red); }
  .domain-pts { font-size: 0.68rem; color: var(--text-light); }

  /* LEVELS */
  .levels-list { padding: 12px 16px; display: flex; flex-direction: column; gap: 6px; }
  .level-option {
    display: flex;
    align-items: flex-start;
    gap: 10px;
    padding: 10px 12px;
    border-radius: 8px;
    border: 1.5px solid transparent;
    cursor: pointer;
    transition: all 0.18s;
    background: var(--gray);
  }
  .level-option:hover { background: var(--teal-light); border-color: rgba(26,122,138,0.3); }
  .level-option.selected { background: var(--teal-light); border-color: var(--teal); }
  .level-option.selected-high { background: #fef0e0; border-color: var(--orange); }
  .level-option.selected-max { background: #fdf0ee; border-color: var(--red); }
  .level-option input { display: none; }
  .level-dot {
    width: 20px; height: 20px;
    border-radius: 50%;
    border: 2px solid #ccc;
    flex-shrink: 0;
    margin-top: 1px;
    display: flex; align-items: center; justify-content: center;
    transition: all 0.18s;
    font-size: 10px;
    color: white;
    font-weight: 700;
  }
  .level-option.selected .level-dot { background: var(--teal); border-color: var(--teal); }
  .level-option.selected-high .level-dot { background: var(--orange); border-color: var(--orange); }
  .level-option.selected-max .level-dot { background: var(--red); border-color: var(--red); }
  .level-text { flex: 1; }
  .level-num { font-size: 0.7rem; font-weight: 600; color: var(--text-light); text-transform: uppercase; letter-spacing: 0.06em; }
  .level-desc { font-size: 0.82rem; color: var(--text); margin-top: 1px; line-height: 1.4; }
  .level-pts {
    font-size: 0.72rem;
    font-weight: 600;
    color: var(--text-light);
    white-space: nowrap;
    padding-top: 3px;
  }

  /* CONFIDENCE SECTION */
  .confidence-section {
    background: var(--white);
    border-radius: 12px;
    border: 1.5px solid var(--gray-mid);
    padding: 20px;
    margin-top: 16px;
    box-shadow: var(--shadow);
  }
  .confidence-title {
    font-family: 'DM Serif Display', serif;
    font-size: 1rem;
    color: var(--navy);
    margin-bottom: 4px;
  }
  .confidence-sub { font-size: 0.75rem; color: var(--text-light); margin-bottom: 14px; }
  .confidence-options {
    display: flex;
    gap: 10px;
    flex-wrap: wrap;
  }
  .conf-btn {
    flex: 1;
    min-width: 80px;
    padding: 12px 8px;
    border-radius: 8px;
    border: 1.5px solid var(--gray-mid);
    background: var(--gray);
    cursor: pointer;
    text-align: center;
    transition: all 0.18s;
    font-family: 'DM Sans', sans-serif;
  }
  .conf-btn:hover { border-color: var(--teal); background: var(--teal-light); }
  .conf-btn.selected { border-color: var(--teal); background: var(--teal-light); }
  .conf-btn.selected-warn { border-color: var(--red); background: var(--red-light); }
  .conf-abbr { font-size: 1.1rem; font-weight: 700; color: var(--navy); display: block; }
  .conf-label { font-size: 0.68rem; color: var(--text-light); margin-top: 2px; }

  /* RESULTS PANEL */
  .results-panel {
    background: var(--white);
    border-radius: 12px;
    border: 1.5px solid var(--gray-mid);
    margin-top: 28px;
    overflow: hidden;
    box-shadow: var(--shadow-lg);
  }
  .results-header {
    background: var(--navy);
    padding: 16px 22px;
    display: flex;
    align-items: center;
    justify-content: space-between;
  }
  .results-header h2 { font-family: 'DM Serif Display', serif; font-size: 1.1rem; color: var(--white); }
  .results-body { padding: 20px 22px; }

  .score-breakdown {
    display: grid;
    grid-template-columns: repeat(auto-fill, minmax(200px, 1fr));
    gap: 10px;
    margin-bottom: 20px;
  }
  .breakdown-item {
    padding: 10px 14px;
    border-radius: 8px;
    background: var(--gray);
    border-left: 3px solid var(--gray-mid);
  }
  .breakdown-item.scored { border-left-color: var(--teal); }
  .breakdown-item.scored-high { border-left-color: var(--orange); }
  .breakdown-item.scored-max { border-left-color: var(--red); }
  .bi-name { font-size: 0.75rem; font-weight: 600; color: var(--text-light); }
  .bi-score { font-size: 1rem; font-weight: 600; color: var(--text); margin-top: 2px; }
  .bi-score span { font-size: 0.7rem; color: var(--text-light); font-weight: 400; }

  .verdict-box {
    border-radius: 10px;
    padding: 18px 20px;
    margin-top: 8px;
    border: 2px solid;
  }
  .verdict-box.light { border-color: #27ae60; background: var(--green-light); }
  .verdict-box.moderate { border-color: var(--gold); background: #fdf8ec; }
  .verdict-box.high { border-color: var(--orange); background: var(--orange-light); }
  .verdict-box.critical { border-color: var(--red); background: var(--red-light); }
  .verdict-title { font-family: 'DM Serif Display', serif; font-size: 1.15rem; }
  .verdict-box.light .verdict-title { color: #1e6e40; }
  .verdict-box.moderate .verdict-title { color: #8b6a00; }
  .verdict-box.high .verdict-title { color: #8b3a00; }
  .verdict-box.critical .verdict-title { color: #8b1a1a; }
  .verdict-desc { font-size: 0.82rem; margin-top: 6px; line-height: 1.5; }
  .verdict-box.light .verdict-desc { color: #2d6040; }
  .verdict-box.moderate .verdict-desc { color: #6b5000; }
  .verdict-box.high .verdict-desc { color: #6b3000; }
  .verdict-box.critical .verdict-desc { color: #6b1010; }

  /* RESET BTN */
  .reset-btn {
    margin-top: 20px;
    padding: 10px 22px;
    border-radius: 8px;
    border: 1.5px solid var(--gray-mid);
    background: var(--white);
    font-family: 'DM Sans', sans-serif;
    font-size: 0.82rem;
    font-weight: 500;
    color: var(--text-light);
    cursor: pointer;
    transition: all 0.18s;
  }
  .reset-btn:hover { border-color: var(--navy); color: var(--navy); }

  /* PROGRESS BAR */
  .progress-bar-wrap {
    height: 4px;
    background: rgba(255,255,255,0.15);
    border-radius: 2px;
    margin-top: 10px;
    overflow: hidden;
  }
  .progress-bar-fill {
    height: 100%;
    border-radius: 2px;
    background: var(--gold);
    transition: width 0.4s ease;
  }

  @media print {
    body { background: white; }
    .header { position: static; }
    .hard-stop-banner { display: block !important; }
  }
</style>
</head>
<body>

<div class="header">
  <div class="header-inner">
    <div>
      <div class="header-title">Discharge Complexity + Care Burden Scale</div>
      <div class="header-sub">Pediatric Cardiac ICU — does not necessarily reflect medical readiness for discharge</div>
      <div class="progress-bar-wrap" style="max-width:360px;">
        <div class="progress-bar-fill" id="progressBar" style="width:0%"></div>
      </div>
    </div>
    <div class="score-badge">
      <div class="score-badge-label">Weighted Score</div>
      <div class="score-badge-value" id="totalScore">0</div>
      <div class="score-badge-max" id="scoreMax">/ max varies</div>
      <div class="score-badge-verdict" id="headerVerdict" style="background:rgba(255,255,255,0.1);color:rgba(255,255,255,0.5);">Not started</div>
    </div>
  </div>
</div>

<div class="hard-stop-banner" id="hardStopBanner">
  ⛔ <strong>HARD STOP flagged.</strong> One or more criteria below require reassessment before discharge can proceed, regardless of total score.
</div>

<div class="main">

  <!-- HARD STOPS -->
  <div class="hard-stop-section">
    <div class="hard-stop-header">
      <div class="icon">⛔</div>
      <div>
        <h2>Hard Stop Checklist</h2>
        <p>Flag any active concern — discharge paused regardless of total score</p>
      </div>
    </div>
    <div class="hard-stop-items" id="hardStopItems">
      <label class="hard-stop-item" onclick="toggleHardStop(this)">
        <input type="checkbox">
        <div class="hs-check">✓</div>
        <div class="hs-text">Brady or desats and/or requiring frequent suctioning or interventions</div>
      </label>
      <label class="hard-stop-item" onclick="toggleHardStop(this)">
        <input type="checkbox">
        <div class="hs-check">✓</div>
        <div class="hs-text">O₂ requirement not at expected discharge baseline</div>
      </label>
      <label class="hard-stop-item" onclick="toggleHardStop(this)">
        <input type="checkbox">
        <div class="hs-check">✓</div>
        <div class="hs-text">Caregiver not trained/checked off on emergency warning signs</div>
      </label>
      <label class="hard-stop-item" onclick="toggleHardStop(this)">
        <input type="checkbox">
        <div class="hs-check">✓</div>
        <div class="hs-text">Required DME not yet in home / not yet trained on use</div>
      </label>
      <label class="hard-stop-item" onclick="toggleHardStop(this)">
        <input type="checkbox">
        <div class="hs-check">✓</div>
        <div class="hs-text">Caregiver unable to demonstrate medication administration</div>
      </label>
    </div>
  </div>

  <!-- SCORING DOMAINS -->
  <div class="domains-grid" id="domainsGrid"></div>

  <!-- PARENT CONFIDENCE -->
  <div class="confidence-section">
    <div class="confidence-title">Parent Reported Discharge Confidence</div>
    <div class="confidence-sub">Clinician-observed rating at time of discharge discussion (0–4 scale)</div>
    <div class="confidence-options">
      <div class="conf-btn" onclick="selectConfidence(this, 'SD', true)">
        <span class="conf-abbr">SD</span>
        <span class="conf-label">Strongly Disagree</span>
      </div>
      <div class="conf-btn" onclick="selectConfidence(this, 'D', true)">
        <span class="conf-abbr">D</span>
        <span class="conf-label">Disagree</span>
      </div>
      <div class="conf-btn" onclick="selectConfidence(this, 'N', false)">
        <span class="conf-abbr">N</span>
        <span class="conf-label">Neutral</span>
      </div>
      <div class="conf-btn" onclick="selectConfidence(this, 'A', false)">
        <span class="conf-abbr">A</span>
        <span class="conf-label">Agree</span>
      </div>
      <div class="conf-btn" onclick="selectConfidence(this, 'SA', false)">
        <span class="conf-abbr">SA</span>
        <span class="conf-label">Strongly Agree</span>
      </div>
    </div>
  </div>

  <!-- RESULTS -->
  <div class="results-panel">
    <div class="results-header">
      <h2>Scoring Summary</h2>
      <div style="font-size:0.75rem;color:rgba(255,255,255,0.5);">Weighted totals reflect clinical risk differential</div>
    </div>
    <div class="results-body">
      <div class="score-breakdown" id="scoreBreakdown"></div>
      <div class="verdict-box light" id="verdictBox">
        <div class="verdict-title">Score all domains to see discharge recommendation</div>
        <div class="verdict-desc">Select a level for each domain above. Hard stop criteria are evaluated independently.</div>
      </div>
      <button class="reset-btn" onclick="resetAll()">↺ Reset All Scores</button>
    </div>
  </div>

</div>

<script>
const domains = [
  {
    id: 'parent_ability',
    title: 'Parent Ability Level',
    subtitle: 'Caregiver competency to independently manage care at home',
    weight: 3,
    weightLabel: '×3 HIGH',
    weightClass: 'weight-3',
    levels: [
      { pts: 0, desc: 'Fully competent and independently managing care' },
      { pts: 1, desc: 'Requiring some reinforcement' },
      { pts: 2, desc: 'Requiring a lot of reinforcement' },
      { pts: 3, desc: 'Not able to manage care at this time **', note: 'reassess if safe for discharge' },
    ]
  },
  {
    id: 'withdrawal_meds',
    title: 'Withdrawal Medications',
    subtitle: 'Active weaning regimens requiring caregiver administration',
    weight: 2,
    weightLabel: '×2',
    weightClass: 'weight-2',
    levels: [
      { pts: 0, desc: 'None' },
      { pts: 1, desc: '1 medicine' },
      { pts: 2, desc: '2 medicines' },
      { pts: 3, desc: '>2 medicines BID' },
      { pts: 4, desc: '>2 medicines and >BID **', note: 'reassess if safe for discharge' },
    ]
  },
  {
    id: 'dme',
    title: 'DME Needs',
    subtitle: 'GT/GJ/NG, O₂/pulse ox, suction, nebulizer, CPT vest, PICC+IV, wound vac',
    weight: 2,
    weightLabel: '×2',
    weightClass: 'weight-2',
    levels: [
      { pts: 0, desc: 'None' },
      { pts: 1, desc: 'Just one setup' },
      { pts: 2, desc: '1–3 setups' },
      { pts: 3, desc: '>3 setups' },
    ]
  },
  {
    id: 'social_stability',
    title: 'Social Stability',
    subtitle: 'Pyramid of discharge needs (basic → healthcare → logistical)',
    weight: 2,
    weightLabel: '×2',
    weightClass: 'weight-2',
    levels: [
      { pts: 0, desc: 'No concerns across all need categories' },
      { pts: 1, desc: '1 concern (basic, healthcare, or logistical need)' },
      { pts: 2, desc: '2–3 concerns' },
      { pts: 4, desc: '4–5 concerns' },
      { pts: 6, desc: '6–7 concerns' },
      { pts: 8, desc: '8+ concerns — each category: food, water, shelter, safe environment, insurance/uninsured, language barrier, transportation, distance >2hr from OKC/Tulsa, unable to seek follow-up or care due to preoccupation with drugs/alcohol/mental health' },
    ]
  },
  {
    id: 'social_support',
    title: 'Social Support',
    subtitle: 'Number and capacity of active caregivers',
    weight: 2,
    weightLabel: '×2',
    weightClass: 'weight-2',
    levels: [
      { pts: 0, desc: 'Multiple caregivers / strong support network' },
      { pts: 1, desc: 'Only 2 caregivers with no/minimal extra support, or 1 caregiver with good support' },
      { pts: 2, desc: 'Only 1 caregiver with no or minimal extra support' },
    ]
  },
  {
    id: 'specialty_fu',
    title: 'Specialty Follow-ups',
    subtitle: 'Number of outpatient specialty appointments needed post-discharge',
    weight: 1,
    weightLabel: '×1',
    weightClass: 'weight-1',
    levels: [
      { pts: 0, desc: 'Just cardiology' },
      { pts: 1, desc: '1–2 follow-ups' },
      { pts: 2, desc: '3–5 follow-ups' },
      { pts: 3, desc: '>5 follow-ups' },
    ]
  },
  {
    id: 'op_therapy',
    title: 'OP Therapy Needs',
    subtitle: 'Outpatient therapy requirements post-discharge',
    weight: 1,
    weightLabel: '×1',
    weightClass: 'weight-1',
    levels: [
      { pts: 0, desc: 'None or just SoonerStart' },
      { pts: 1, desc: 'OP therapy recommended' },
    ]
  },
  {
    id: 'num_meds',
    title: 'Number of Medications',
    subtitle: 'Total medication count at discharge',
    weight: 1,
    weightLabel: '×1',
    weightClass: 'weight-1',
    levels: [
      { pts: 0, desc: '1–5 medications' },
      { pts: 1, desc: '>5–10 medications' },
      { pts: 2, desc: '>10 medications **', note: 'reassess if safe for discharge' },
    ]
  },
  {
    id: 'child_temp',
    title: 'Child Temperament',
    subtitle: 'Behavioral factors affecting home care manageability',
    weight: 1,
    weightLabel: '×1',
    weightClass: 'weight-1',
    levels: [
      { pts: 0, desc: 'Calm and easily consoled' },
      { pts: 1, desc: 'Irritable at times or reflux/pukes at times' },
      { pts: 2, desc: 'Often irritable or often refluxing/puking' },
    ]
  },
  {
    id: 'recent_er',
    title: 'Recent Admission/ER Visits',
    subtitle: 'Not applicable to NBH patients',
    weight: 1,
    weightLabel: '×1',
    weightClass: 'weight-1',
    levels: [
      { pts: 0, desc: '0 visits in last 3 months' },
      { pts: 1, desc: '1 visit in last 3 months' },
      { pts: 2, desc: '2 visits in last 3 months' },
      { pts: 3, desc: '>2 visits in last 3 months' },
    ]
  },
];

const scores = {};
let confidenceWarn = false;
let hardStopActive = false;

function buildDomains() {
  const grid = document.getElementById('domainsGrid');
  domains.forEach(d => {
    const card = document.createElement('div');
    card.className = 'domain-card';
    card.id = `card-${d.id}`;

    const maxRaw = Math.max(...d.levels.map(l => l.pts));
    const maxWeighted = maxRaw * d.weight;

    let levelHTML = d.levels.map((l, i) => `
      <label class="level-option" id="opt-${d.id}-${i}" onclick="selectLevel('${d.id}', ${l.pts}, ${i}, ${d.weight}, ${d.levels.length - 1})">
        <input type="radio" name="${d.id}" value="${l.pts}">
        <div class="level-dot"></div>
        <div class="level-text">
          <div class="level-num">Level ${l.pts === 0 ? '0' : l.pts} ${l.note ? '⚠' : ''}</div>
          <div class="level-desc">${l.desc.replace('**','')}</div>
        </div>
        <div class="level-pts">${l.pts} pt${l.pts !== 1 ? 's' : ''}</div>
      </label>
    `).join('');

    card.innerHTML = `
      <div class="domain-header">
        <div class="domain-info">
          <div class="domain-title">
            ${d.title}
            <span class="weight-tag ${d.weightClass}">${d.weightLabel}</span>
          </div>
          <div class="domain-subtitle">${d.subtitle}</div>
        </div>
        <div class="domain-score-display">
          <div class="domain-raw" id="raw-${d.id}">— / ${maxRaw}</div>
          <div class="domain-weighted" id="weighted-${d.id}">—</div>
          <div class="domain-pts">wtd pts</div>
        </div>
      </div>
      <div class="levels-list">${levelHTML}</div>
    `;
    grid.appendChild(card);
  });
}

function selectLevel(domainId, pts, idx, weight, maxIdx) {
  scores[domainId] = pts;

  // Update option styles
  const domain = domains.find(d => d.id === domainId);
  domain.levels.forEach((l, i) => {
    const opt = document.getElementById(`opt-${domainId}-${i}`);
    opt.classList.remove('selected', 'selected-high', 'selected-max');
    const dot = opt.querySelector('.level-dot');
    dot.textContent = '';
  });

  const selected = document.getElementById(`opt-${domainId}-${idx}`);
  const isMax = idx === maxIdx;
  const isHigh = idx >= Math.floor(maxIdx * 0.6) && !isMax;
  if (isMax) selected.classList.add('selected-max');
  else if (isHigh) selected.classList.add('selected-high');
  else selected.classList.add('selected');
  selected.querySelector('.level-dot').textContent = '✓';

  // Update card style
  const card = document.getElementById(`card-${domainId}`);
  card.classList.remove('has-score', 'high-score', 'max-score');
  if (pts === 0) card.classList.add('has-score');
  else if (isMax) card.classList.add('max-score');
  else if (isHigh) card.classList.add('high-score');
  else card.classList.add('has-score');

  // Update domain score display
  const weighted = pts * weight;
  document.getElementById(`raw-${domainId}`).textContent = `${pts} / ${Math.max(...domain.levels.map(l=>l.pts))}`;
  const wEl = document.getElementById(`weighted-${domainId}`);
  wEl.textContent = weighted;

  updateTotals();
}

function selectConfidence(btn, code, isWarn) {
  document.querySelectorAll('.conf-btn').forEach(b => b.classList.remove('selected', 'selected-warn'));
  btn.classList.add(isWarn ? 'selected-warn' : 'selected');
  confidenceWarn = isWarn;
  updateTotals();
}

function toggleHardStop(label) {
  label.classList.toggle('flagged');
  const anyFlagged = document.querySelectorAll('.hard-stop-item.flagged').length > 0;
  hardStopActive = anyFlagged;
  document.getElementById('hardStopBanner').classList.toggle('active', anyFlagged);
  updateTotals();
}

function updateTotals() {
  let total = 0;
  let maxTotal = 0;
  let scored = 0;

  domains.forEach(d => {
    const maxRaw = Math.max(...d.levels.map(l => l.pts));
    maxTotal += maxRaw * d.weight;
    if (scores[d.id] !== undefined) {
      total += scores[d.id] * d.weight;
      scored++;
    }
  });

  const progress = (scored / domains.length) * 100;
  document.getElementById('progressBar').style.width = progress + '%';
  document.getElementById('totalScore').textContent = total;
  document.getElementById('scoreMax').textContent = `/ ${maxTotal} max`;

  updateBreakdown(total, maxTotal);
  updateVerdict(total, maxTotal, scored);
}

function updateBreakdown(total, maxTotal) {
  const container = document.getElementById('scoreBreakdown');
  container.innerHTML = '';
  domains.forEach(d => {
    const item = document.createElement('div');
    const pts = scores[d.id];
    const weighted = pts !== undefined ? pts * d.weight : null;
    const maxW = Math.max(...d.levels.map(l => l.pts)) * d.weight;
    const isHigh = weighted !== null && weighted >= maxW * 0.6 && weighted < maxW;
    const isMax = weighted === maxW && maxW > 0;
    item.className = `breakdown-item${weighted === null ? '' : isMax ? ' scored-max' : isHigh ? ' scored-high' : ' scored'}`;
    item.innerHTML = `
      <div class="bi-name">${d.title}</div>
      <div class="bi-score">${weighted !== null ? weighted : '—'} <span>/ ${maxW} wtd</span></div>
    `;
    container.appendChild(item);
  });
}

function updateVerdict(total, maxTotal, scored) {
  const box = document.getElementById('verdictBox');
  const headerVerdict = document.getElementById('headerVerdict');
  const scoreValue = document.getElementById('totalScore');

  if (scored < domains.length) {
    box.className = 'verdict-box light';
    box.innerHTML = `<div class="verdict-title">Score all ${domains.length} domains to see recommendation</div>
      <div class="verdict-desc">${scored} of ${domains.length} domains completed.</div>`;
    headerVerdict.textContent = `${scored}/${domains.length} scored`;
    headerVerdict.style.background = 'rgba(255,255,255,0.1)';
    headerVerdict.style.color = 'rgba(255,255,255,0.5)';
    scoreValue.style.color = 'white';
    return;
  }

  if (hardStopActive) {
    box.className = 'verdict-box critical';
    box.innerHTML = `<div class="verdict-title">⛔ HARD STOP — Discharge Paused</div>
      <div class="verdict-desc">One or more hard stop criteria are flagged. These must be resolved before discharge proceeds, regardless of the weighted score of ${total}.</div>`;
    headerVerdict.textContent = 'HARD STOP';
    headerVerdict.style.background = '#e74c3c';
    headerVerdict.style.color = 'white';
    scoreValue.style.color = '#e74c3c';
    return;
  }

  let cls, title, desc, verdictText, verdictColor, scoreColor;

  // NBH range is 11-28, general high 11-31
  if (total <= 10) {
    cls = total <= 5 ? 'light' : 'moderate';
    if (total <= 5) {
      title = '🟢 Light Complexity (0–5)';
      desc = 'Discharge home is appropriate with standard follow-up planning.';
      verdictText = 'Light Complexity';
      verdictColor = '#27ae60';
      scoreColor = '#27ae60';
    } else {
      title = '🟡 Moderate Complexity (6–10)';
      desc = 'Discharge home is appropriate. Consider Private Duty Nursing (PDN) evaluation. Ensure robust follow-up plan is in place.';
      verdictText = 'Moderate';
      verdictColor = '#c8972a';
      scoreColor = '#c8972a';
    }
  } else if (total <= 31) {
    cls = 'high';
    title = '🟠 High Complexity (11–31)';
    desc = 'Reassess patient safety for discharge. Consider PDN or Bridge to Care Coordination (BCC) referral. If score 11–28 (NBH pathway), apply NBH-specific criteria. Confidence and social stability scores should heavily inform next steps.';
    verdictText = 'High Complexity';
    verdictColor = '#d35400';
    scoreColor = '#d35400';
  } else {
    cls = 'critical';
    title = '🔴 Critical Complexity (>31)';
    desc = '** Reassess if patient is safe for discharge. BCC or PDN referral strongly indicated. Multidisciplinary review recommended before proceeding.';
    verdictText = 'Critical';
    verdictColor = '#c0392b';
    scoreColor = '#c0392b';
  }

  if (confidenceWarn) {
    desc += ' ⚠️ Parent confidence is low (SD or D) — this is an independent risk factor; address caregiver readiness before discharge.';
  }

  box.className = `verdict-box ${cls}`;
  box.innerHTML = `<div class="verdict-title">${title}</div><div class="verdict-desc">${desc}</div>`;
  headerVerdict.textContent = verdictText;
  headerVerdict.style.background = verdictColor + '33';
  headerVerdict.style.color = verdictColor === '#27ae60' ? '#b8f0d0' : '#ffe0b0';
  if (verdictColor === '#27ae60') { headerVerdict.style.color = '#90e8b0'; }
  else if (cls === 'critical') { headerVerdict.style.color = '#ffb0b0'; }
  else { headerVerdict.style.color = '#ffe0b0'; }
  scoreValue.style.color = scoreColor === '#27ae60' ? '#6fd9a0' : scoreColor === '#c8972a' ? '#ffc870' : scoreColor === '#d35400' ? '#ff9a60' : '#ff8080';
}

function resetAll() {
  Object.keys(scores).forEach(k => delete scores[k]);
  confidenceWarn = false;
  hardStopActive = false;
  document.getElementById('hardStopBanner').classList.remove('active');
  document.querySelectorAll('.hard-stop-item').forEach(i => i.classList.remove('flagged'));
  document.querySelectorAll('.level-option').forEach(o => o.classList.remove('selected','selected-high','selected-max'));
  document.querySelectorAll('.level-dot').forEach(d => d.textContent = '');
  document.querySelectorAll('.domain-card').forEach(c => c.classList.remove('has-score','high-score','max-score'));
  document.querySelectorAll('.domain-weighted').forEach(e => e.textContent = '—');
  document.querySelectorAll('.domain-raw').forEach(e => {
    const domainId = e.id.replace('raw-','');
    const d = domains.find(x => x.id === domainId);
    if (d) e.textContent = `— / ${Math.max(...d.levels.map(l=>l.pts))}`;
  });
  document.querySelectorAll('.conf-btn').forEach(b => b.classList.remove('selected','selected-warn'));
  document.getElementById('totalScore').textContent = '0';
  document.getElementById('totalScore').style.color = 'white';
  document.getElementById('headerVerdict').textContent = 'Not started';
  document.getElementById('headerVerdict').style.background = 'rgba(255,255,255,0.1)';
  document.getElementById('headerVerdict').style.color = 'rgba(255,255,255,0.5)';
  document.getElementById('progressBar').style.width = '0%';
  document.getElementById('scoreBreakdown').innerHTML = '';
  const box = document.getElementById('verdictBox');
  box.className = 'verdict-box light';
  box.innerHTML = `<div class="verdict-title">Score all domains to see discharge recommendation</div>
    <div class="verdict-desc">Select a level for each domain above. Hard stop criteria are evaluated independently.</div>`;
}

buildDomains();
</script>
</body>
</html>
