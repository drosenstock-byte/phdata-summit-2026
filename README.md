[phdata-snowflake-summit-2026_2 (1).html](https://github.com/user-attachments/files/27372841/phdata-snowflake-summit-2026_2.1.html)
# phdata-summit-2026
Summit landing page<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>phData at Snowflake Summit 2026 – Booth #2202</title>
<meta name="description" content="Meet phData at Snowflake Summit 2026, Booth #2202 in San Francisco. Talk AI, data modernization, and Snowflake strategy with a 6x Partner of the Year. Book time with our experts.">
<style>
  *, *::before, *::after { box-sizing: border-box; margin: 0; padding: 0; }

  body {
    font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Helvetica, Arial, sans-serif;
    background: #f5f5f3;
    color: #1a1a1a;
  }

  .page {
    max-width: 1200px;
    margin: 0 auto;
    background: #fff;
    border: 1px solid #d0d0d0;
  }

  .placeholder {
    background: #e8e8e8;
    border: 1px dashed #bbb;
    border-radius: 4px;
    display: flex;
    align-items: center;
    justify-content: center;
    font-size: 11px;
    color: #999;
    font-weight: 500;
    letter-spacing: 0.5px;
  }

  /* ── SITE NAV ── */
  .site-nav {
    background: #111;
    padding: 0 40px;
    display: flex;
    align-items: center;
    height: 60px;
    position: sticky;
    top: 0;
    z-index: 100;
  }

  .nav-logo {
    color: #fff;
    font-size: 20px;
    font-weight: 700;
    letter-spacing: -0.5px;
    margin-right: 16px;
    white-space: nowrap;
    text-decoration: none;
  }

  .nav-forge {
    background: rgba(255,255,255,0.1);
    border: 1px solid rgba(255,255,255,0.2);
    border-radius: 100px;
    padding: 4px 14px;
    font-size: 11px;
    color: rgba(255,255,255,0.8);
    margin-right: 28px;
    white-space: nowrap;
    text-decoration: none;
  }

  .nav-links {
    display: flex;
    align-items: center;
    gap: 2px;
    flex: 1;
  }

  .nav-link {
    color: rgba(255,255,255,0.75);
    font-size: 13px;
    font-weight: 500;
    padding: 6px 12px;
    white-space: nowrap;
    display: flex;
    align-items: center;
    gap: 4px;
    text-decoration: none;
    border-radius: 4px;
    transition: background 0.15s;
  }

  .nav-link:hover { background: rgba(255,255,255,0.08); }

  .nav-link svg {
    width: 10px;
    height: 10px;
    flex-shrink: 0;
  }

  .nav-cta {
    background: #fff;
    color: #111;
    border-radius: 100px;
    padding: 8px 20px;
    font-size: 13px;
    font-weight: 600;
    white-space: nowrap;
    margin-left: auto;
    text-decoration: none;
    transition: opacity 0.15s;
  }

  .nav-cta:hover { opacity: 0.85; }

  /* ── JUMP LINKS BAR ── */
  .jump-bar {
    background: #fff;
    border-bottom: 1px solid #e0e0e0;
    padding: 0 40px;
    display: flex;
    align-items: center;
    position: sticky;
    top: 60px;
    z-index: 99;
  }

  .jump-link {
    font-size: 13px;
    font-weight: 500;
    color: #444;
    padding: 13px 18px;
    border-bottom: 2px solid transparent;
    white-space: nowrap;
    text-decoration: none;
    transition: color 0.15s, border-color 0.15s;
  }

  .jump-link:hover { color: #3366cc; }
  .jump-link.active { color: #3366cc; border-bottom-color: #3366cc; }

  .jump-divider {
    width: 1px;
    height: 16px;
    background: #e0e0e0;
    margin: 0 4px;
    flex-shrink: 0;
  }

  /* ── HERO ── */
  .hero {
    padding: 96px 40px 72px;
    text-align: center;
    border-bottom: 1px solid #e8e8e8;
  }

  .hero-eyebrow {
    display: inline-block;
    background: #eef4ff;
    border: 1px solid #c0d4f5;
    border-radius: 100px;
    padding: 6px 18px;
    font-size: 12px;
    color: #3366cc;
    font-weight: 500;
    letter-spacing: 0.5px;
    margin-bottom: 28px;
  }

  .hero h1 {
    font-size: 56px;
    font-weight: 700;
    line-height: 1.1;
    letter-spacing: -2px;
    color: #111;
    margin-bottom: 20px;
  }

  .hero h1 span { color: #3366cc; }

  .hero-sub {
    font-size: 18px;
    color: #666;
    max-width: 500px;
    margin: 0 auto 44px;
    line-height: 1.6;
  }

  .hero-btns {
    display: flex;
    gap: 12px;
    justify-content: center;
    flex-wrap: wrap;
  }

  .btn-primary {
    background: #3366cc;
    color: #fff;
    border-radius: 100px;
    padding: 14px 32px;
    font-size: 15px;
    font-weight: 500;
    text-decoration: none;
    transition: background 0.15s;
    display: inline-block;
  }

  .btn-primary:hover { background: #2255bb; }

  .btn-secondary {
    background: #fff;
    border: 1px solid #ccc;
    border-radius: 100px;
    padding: 14px 32px;
    font-size: 15px;
    color: #333;
    text-decoration: none;
    transition: border-color 0.15s;
    display: inline-block;
  }

  .btn-secondary:hover { border-color: #999; }

  /* ── STATS STRIP ── */
  .stats {
    display: grid;
    grid-template-columns: repeat(4, 1fr);
    border-bottom: 1px solid #e8e8e8;
  }

  .stat {
    padding: 36px 20px;
    text-align: center;
    border-right: 1px solid #e8e8e8;
  }

  .stat:last-child { border-right: none; }

  .stat-val {
    font-size: 32px;
    font-weight: 700;
    color: #111;
    letter-spacing: -1px;
    margin-bottom: 6px;
  }

  .stat-lbl {
    font-size: 11px;
    color: #888;
    text-transform: uppercase;
    letter-spacing: 1px;
    font-weight: 500;
  }

  /* ── SECTIONS ── */
  .section {
    padding: 80px 40px;
    border-bottom: 1px solid #e8e8e8;
  }

  .section-tag {
    font-size: 11px;
    font-weight: 600;
    letter-spacing: 2px;
    text-transform: uppercase;
    color: #3366cc;
    margin-bottom: 12px;
  }

  .section-h {
    font-size: 36px;
    font-weight: 700;
    letter-spacing: -1px;
    color: #111;
    line-height: 1.2;
    margin-bottom: 16px;
  }

  .section-p {
    font-size: 16px;
    color: #555;
    line-height: 1.75;
    max-width: 600px;
  }

  /* ── BOOTH SECTION ── */
  .booth-grid {
    display: grid;
    grid-template-columns: 1fr 1fr;
    gap: 60px;
    align-items: start;
    margin-top: 48px;
  }

  .booth-card {
    background: #f7f7f5;
    border: 1px solid #e0e0e0;
    border-radius: 12px;
    padding: 40px;
  }

  .booth-number {
    font-size: 80px;
    font-weight: 800;
    letter-spacing: -4px;
    color: #d0d5df;
    line-height: 1;
    margin-bottom: 4px;
  }

  .booth-sublabel {
    font-size: 11px;
    color: #3366cc;
    font-weight: 600;
    letter-spacing: 2px;
    text-transform: uppercase;
    margin-bottom: 28px;
  }

  .perk-list {
    list-style: none;
    display: flex;
    flex-direction: column;
    gap: 12px;
  }

  .perk-list li {
    display: flex;
    align-items: center;
    gap: 12px;
    font-size: 14px;
    color: #444;
  }

  .dot {
    width: 6px;
    height: 6px;
    background: #3366cc;
    border-radius: 50%;
    flex-shrink: 0;
  }

  /* ── FORM SECTION ── */
  .form-grid {
    display: grid;
    grid-template-columns: 1fr 1fr;
    gap: 60px;
    align-items: start;
    margin-top: 48px;
  }

  .expert-list {
    display: flex;
    flex-direction: column;
    gap: 12px;
    margin-top: 8px;
  }

  .expert-row {
    display: flex;
    align-items: center;
    gap: 14px;
    background: #f7f7f5;
    border: 1px solid #e0e0e0;
    border-radius: 8px;
    padding: 14px 18px;
  }

  .avatar {
    width: 40px;
    height: 40px;
    border-radius: 50%;
    background: #dde4f0;
    flex-shrink: 0;
    display: flex;
    align-items: center;
    justify-content: center;
    font-size: 12px;
    font-weight: 600;
    color: #3366cc;
  }

  .expert-name {
    font-size: 14px;
    font-weight: 500;
    color: #111;
    margin-bottom: 2px;
  }

  .expert-role {
    font-size: 12px;
    color: #888;
  }

  .hubspot-placeholder {
    height: 300px;
    flex-direction: column;
    gap: 8px;
    border-radius: 8px;
  }

  /* ── SESSIONS ── */
  .sessions-list {
    display: flex;
    flex-direction: column;
    gap: 24px;
    margin-top: 48px;
  }

  .session-card {
    border: 1px solid #e0e0e0;
    border-left: 3px solid #3366cc;
    border-radius: 0 10px 10px 0;
    padding: 36px;
  }

  .session-meta {
    display: flex;
    gap: 12px;
    align-items: center;
    margin-bottom: 16px;
    flex-wrap: wrap;
  }

  .session-code {
    background: #eef4ff;
    border: 1px solid #c0d4f5;
    border-radius: 100px;
    padding: 4px 12px;
    font-size: 11px;
    font-weight: 600;
    color: #3366cc;
    letter-spacing: 1px;
    text-transform: uppercase;
  }

  .session-time {
    font-size: 13px;
    color: #888;
  }

  .session-h {
    font-size: 20px;
    font-weight: 600;
    color: #111;
    line-height: 1.3;
    margin-bottom: 12px;
    letter-spacing: -0.3px;
  }

  .session-p {
    font-size: 14px;
    color: #666;
    line-height: 1.7;
    margin-bottom: 24px;
  }

  .session-footer {
    display: flex;
    align-items: center;
    justify-content: space-between;
    flex-wrap: wrap;
    gap: 12px;
  }

  .speakers { display: flex; gap: 8px; flex-wrap: wrap; }

  .speaker-pill {
    background: #f0f0ee;
    border: 1px solid #ddd;
    border-radius: 100px;
    padding: 4px 12px;
    font-size: 12px;
    color: #444;
  }

  .add-btn {
    display: inline-flex;
    align-items: center;
    gap: 6px;
    border: 1px solid #c0d4f5;
    background: #eef4ff;
    border-radius: 100px;
    padding: 9px 18px;
    font-size: 13px;
    color: #3366cc;
    font-weight: 500;
    text-decoration: none;
    transition: background 0.15s;
  }

  .add-btn:hover { background: #ddeaff; }

  /* ── RESOURCE CENTER ── */
  .resource-grid {
    display: grid;
    grid-template-columns: repeat(3, 1fr);
    gap: 20px;
    margin-top: 48px;
  }

  .resource-card {
    border: 1px solid #e0e0e0;
    border-radius: 10px;
    overflow: hidden;
    display: flex;
    flex-direction: column;
    transition: box-shadow 0.2s;
  }

  .resource-card:hover { box-shadow: 0 4px 16px rgba(0,0,0,0.08); }

  .resource-thumb {
    height: 120px;
    background: #e8e8e8;
    border-bottom: 1px solid #e0e0e0;
    display: flex;
    align-items: center;
    justify-content: center;
    font-size: 12px;
    color: #aaa;
    font-weight: 500;
  }

  .resource-body {
    padding: 20px;
    flex: 1;
    display: flex;
    flex-direction: column;
    gap: 10px;
  }

  .resource-type {
    display: inline-block;
    font-size: 10px;
    font-weight: 600;
    letter-spacing: 1.5px;
    text-transform: uppercase;
    padding: 3px 10px;
    border-radius: 100px;
    align-self: flex-start;
  }

  .type-blog      { background: #eef4ff; color: #3366cc; border: 1px solid #c0d4f5; }
  .type-datasheet { background: #edfaf4; color: #1a7a52; border: 1px solid #b0e0cc; }
  .type-whitepaper{ background: #fdf3e8; color: #9a5c10; border: 1px solid #f0cfa0; }
  .type-casestudy { background: #f5eeff; color: #6633cc; border: 1px solid #d4b0f5; }

  .resource-title {
    font-size: 14px;
    font-weight: 600;
    color: #111;
    line-height: 1.4;
    flex: 1;
  }

  .resource-link {
    font-size: 13px;
    color: #3366cc;
    font-weight: 500;
    text-decoration: none;
    display: flex;
    align-items: center;
    gap: 4px;
    margin-top: 4px;
  }

  .resource-link:hover { text-decoration: underline; }

  .resource-link svg {
    width: 11px;
    height: 11px;
    stroke: #3366cc;
    fill: none;
    flex-shrink: 0;
  }

  /* ── FOOTER CTA ── */
  .footer-cta {
    padding: 96px 40px;
    text-align: center;
    background: #f7f7f5;
  }

  .footer-star {
    font-size: 13px;
    color: #888;
    letter-spacing: 1px;
    margin-bottom: 20px;
  }

  .footer-h {
    font-size: 44px;
    font-weight: 700;
    letter-spacing: -1.5px;
    color: #111;
    margin-bottom: 14px;
  }

  .footer-sub {
    font-size: 16px;
    color: #666;
    margin-bottom: 40px;
  }

  /* ── PAGE FOOTER ── */
  .page-footer {
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding: 24px 40px;
    border-top: 1px solid #e0e0e0;
    font-size: 13px;
    color: #aaa;
    background: #fff;
    flex-wrap: wrap;
    gap: 8px;
  }

  @media (max-width: 768px) {
    .site-nav { padding: 0 20px; }
    .jump-bar { padding: 0 20px; overflow-x: auto; }
    .hero { padding: 60px 24px 48px; }
    .hero h1 { font-size: 36px; }
    section, .section { padding: 56px 24px; }
    .stats { grid-template-columns: repeat(2, 1fr); }
    .stat:nth-child(2) { border-right: none; }
    .booth-grid, .form-grid { grid-template-columns: 1fr; gap: 32px; }
    .resource-grid { grid-template-columns: 1fr; }
    .footer-cta { padding: 60px 24px; }
    .footer-h { font-size: 32px; }
    .page-footer { padding: 20px 24px; flex-direction: column; text-align: center; }
  }
</style>
</head>
<body>

<div class="page">

  <!-- SITE NAV — matches phdata.io -->
  <nav class="site-nav">
    <a href="https://www.phdata.io" class="nav-logo">phData</a>
    <a href="https://www.phdata.io/phdata-forge/" class="nav-forge">phData Forge</a>
    <div class="nav-links">
      <a href="https://www.phdata.io/ai-machine-learning/" class="nav-link">
        Services
        <svg viewBox="0 0 10 6" fill="none"><path d="M1 1l4 4 4-4" stroke="rgba(255,255,255,0.5)" stroke-width="1.5" stroke-linecap="round"/></svg>
      </a>
      <a href="https://www.phdata.io/solutions/snowflake-native-applications/" class="nav-link">
        Solutions
        <svg viewBox="0 0 10 6" fill="none"><path d="M1 1l4 4 4-4" stroke="rgba(255,255,255,0.5)" stroke-width="1.5" stroke-linecap="round"/></svg>
      </a>
      <a href="https://www.phdata.io/industries/hcls/" class="nav-link">
        Industries
        <svg viewBox="0 0 10 6" fill="none"><path d="M1 1l4 4 4-4" stroke="rgba(255,255,255,0.5)" stroke-width="1.5" stroke-linecap="round"/></svg>
      </a>
      <a href="https://www.phdata.io/blog/" class="nav-link">
        Resources
        <svg viewBox="0 0 10 6" fill="none"><path d="M1 1l4 4 4-4" stroke="rgba(255,255,255,0.5)" stroke-width="1.5" stroke-linecap="round"/></svg>
      </a>
      <a href="https://www.phdata.io/phdata-toolkit" class="nav-link">Software</a>
      <a href="https://www.phdata.io/about-us/" class="nav-link">
        About
        <svg viewBox="0 0 10 6" fill="none"><path d="M1 1l4 4 4-4" stroke="rgba(255,255,255,0.5)" stroke-width="1.5" stroke-linecap="round"/></svg>
      </a>
    </div>
    <a href="#book" class="nav-cta">Contact Us</a>
  </nav>

  <!-- JUMP LINKS BAR -->
  <div class="jump-bar">
    <a href="#overview" class="jump-link active">Overview</a>
    <span class="jump-divider"></span>
    <a href="#booth" class="jump-link">Visit Us at Booth #2202</a>
    <span class="jump-divider"></span>
    <a href="#book" class="jump-link">Book a Meeting</a>
    <span class="jump-divider"></span>
    <a href="#sessions" class="jump-link">Sessions</a>
    <span class="jump-divider"></span>
    <a href="#resources" class="jump-link">Resources</a>
  </div>

  <!-- HERO -->
  <div class="hero" id="overview">
    <div class="hero-eyebrow">Snowflake Summit 2026 · San Francisco · June 1–5</div>
    <h1>phData at<br><span>Snowflake Summit</span></h1>
    <p class="hero-sub">Six-time Snowflake Partner of the Year.<br>Find us at Booth #2202.</p>
    <div class="hero-btns">
      <a href="#book" class="btn-primary">Book Time with Our Experts</a>
      <a href="#sessions" class="btn-secondary">View Our Sessions</a>
    </div>
  </div>

  <!-- STATS STRIP -->
  <div class="stats">
    <div class="stat"><div class="stat-val">#2202</div><div class="stat-lbl">Our Booth</div></div>
    <div class="stat"><div class="stat-val">6×</div><div class="stat-lbl">Partner of the Year</div></div>
    <div class="stat"><div class="stat-val">2</div><div class="stat-lbl">Summit Sessions</div></div>
    <div class="stat"><div class="stat-val">Jun 1–5</div><div class="stat-lbl">Event Dates</div></div>
  </div>

  <!-- SECTION 1: BOOTH -->
  <div class="section" id="booth">
    <div class="section-tag">San Francisco</div>
    <h2 class="section-h">See you in San Francisco at Booth #2202</h2>
    <p class="section-p">We're excited to be at Snowflake Summit 2026. Stop by to talk data modernization, AI on Snowflake, and how to turn your data strategy into a production-ready Intelligence Platform. Our team brings real-world project experience, so come with your toughest questions. Plus, don't miss the giveaways.</p>
    <div class="booth-grid">
      <p class="section-p">Whether you're tackling a complex Snowflake migration or exploring how to put AI to work in your organization, you'll walk away with clear, practical answers.</p>
      <div class="booth-card">
        <div class="booth-number">#2202</div>
        <div class="booth-sublabel">Booth Number</div>
        <ul class="perk-list">
          <li><span class="dot"></span>Data modernization strategy</li>
          <li><span class="dot"></span>AI on Snowflake deep dives</li>
          <li><span class="dot"></span>Intelligence Platform demos</li>
          <li><span class="dot"></span>Real-world project expertise</li>
          <li><span class="dot"></span>Giveaways &amp; surprises</li>
        </ul>
      </div>
    </div>
  </div>

  <!-- SECTION 2: BOOK A MEETING -->
  <div class="section" id="book">
    <div class="section-tag">Book a Meeting</div>
    <h2 class="section-h">Book Time with Our Experts</h2>
    <p class="section-p">phData brings together some of the sharpest and most approachable minds in Data Engineering, AI, and Machine Learning. Summit is a rare chance to get face time with people who've solved problems like yours.</p>
    <div class="form-grid">
      <div>
        <div class="expert-list">
          <div class="expert-row">
            <div class="avatar">VY</div>
            <div>
              <div class="expert-name">Vincent Yates</div>
              <div class="expert-role">Chief Solutions Officer – AI</div>
            </div>
          </div>
          <div class="expert-row">
            <div class="avatar">JB</div>
            <div>
              <div class="expert-name">Julianna Bond</div>
              <div class="expert-role">Data Governance Principal</div>
            </div>
          </div>
          <div class="expert-row">
            <div class="avatar">+</div>
            <div>
              <div class="expert-name">And more phData experts</div>
              <div class="expert-role">Data Engineering · ML · Strategy</div>
            </div>
          </div>
        </div>
      </div>
      <div class="placeholder hubspot-placeholder" style="height:300px;flex-direction:column;gap:8px;">
        <div style="font-size:14px;color:#bbb;">HubSpot Form</div>
        <div style="font-size:12px;color:#ccc;">Embed meeting booking form here</div>
      </div>
    </div>
  </div>

  <!-- SECTION 3: SESSIONS -->
  <div class="section" id="sessions">
    <div class="section-tag">Summit Schedule</div>
    <h2 class="section-h">Don't Miss Our Sessions</h2>
    <p class="section-p">Snowflake Summit is packed with forward-thinking sessions and real stories of data innovation. Here's where to find us.</p>
    <div class="sessions-list">

      <div class="session-card">
        <div class="session-meta">
          <span class="session-code">BI110</span>
          <span class="session-time">Monday, June 1 · 1:00 PM – 1:20 PM PDT</span>
        </div>
        <div class="session-h">Future-Ready by Design: Boston Scientific's Self-Service D&amp;A Op Model</div>
        <p class="session-p">In medical devices, product parity is the norm; advantage comes from how fast you turn data into decisions. This session covers how Boston Scientific's cardiology division and phData built a self-service data &amp; analytics operating model on Snowflake, shifting data product ownership to the business and enabling thousands of users with trusted, timely insights on a durable, scalable, AI-ready foundation.</p>
        <div class="session-footer">
          <div class="speakers">
            <span class="speaker-pill">Jon Sandquist · Boston Scientific</span>
            <span class="speaker-pill">Julianna Bond · phData</span>
          </div>
          <a href="https://reg.snowflake.com/flow/snowflake/summit26/sessions/page/catalog/session/1768237001649001yYBj" class="add-btn" target="_blank" rel="noopener">
            Add to Schedule →
          </a>
        </div>
      </div>

      <div class="session-card">
        <div class="session-meta">
          <span class="session-code">AI216</span>
          <span class="session-time">Tuesday, June 2 · 1:00 PM – 1:45 PM PDT</span>
        </div>
        <div class="session-h">Someone Will: Building AI Agents on Snowflake Before Your Competitors Do</div>
        <p class="session-p">Data teams on Snowflake are at an inflection point: keep AI as a smarter BI layer or use Cortex Agents to roam their Snowflake estates, test hypotheses, and surface revenue, savings, and risk signals. Vincent Yates, Chief Solutions Officer – AI at phData (and former data leader at Uber, GE, and Microsoft), will share how he uses agents and the Snowflake AI Data Cloud to encode business logic, wrap it in governance guardrails, and measure impact so agents don't just answer questions—they create compounding advantage.</p>
        <div class="session-footer">
          <div class="speakers">
            <span class="speaker-pill">Vincent Yates · phData</span>
          </div>
          <a href="https://reg.snowflake.com/flow/snowflake/summit26/sessions/page/catalog/session/1768237001649001yYBj" class="add-btn" target="_blank" rel="noopener">
            Add to Schedule →
          </a>
        </div>
      </div>

    </div>
  </div>

  <!-- SECTION 4: RESOURCE CENTER -->
  <div class="section" id="resources">
    <div class="section-tag">Resource Center</div>
    <h2 class="section-h">Explore Our Latest Content</h2>
    <p class="section-p">Datasheets, blog posts, whitepapers, and case studies to help you get the most out of your data and AI investment.</p>

    <div class="resource-grid">

      <div class="resource-card">
        <div class="resource-thumb">Thumbnail</div>
        <div class="resource-body">
          <span class="resource-type type-datasheet">Datasheet</span>
          <div class="resource-title">phData Intelligence Platform Overview</div>
          <a href="#" class="resource-link">
            Read more
            <svg viewBox="0 0 10 10" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round"><path d="M1 9L9 1M9 1H4M9 1v5"/></svg>
          </a>
        </div>
      </div>

      <div class="resource-card">
        <div class="resource-thumb">Thumbnail</div>
        <div class="resource-body">
          <span class="resource-type type-blog">Blog</span>
          <div class="resource-title">Why Enterprise AI Fails: The Context Gap</div>
          <a href="https://www.phdata.io/blog/why-enterprise-ai-fails-the-context-gap/" class="resource-link" target="_blank" rel="noopener">
            Read more
            <svg viewBox="0 0 10 10" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round"><path d="M1 9L9 1M9 1H4M9 1v5"/></svg>
          </a>
        </div>
      </div>

      <div class="resource-card">
        <div class="resource-thumb">Thumbnail</div>
        <div class="resource-body">
          <span class="resource-type type-casestudy">Case Study</span>
          <div class="resource-title">How Thrive Pet Healthcare Built on Snowflake with phData</div>
          <a href="#" class="resource-link">
            Read more
            <svg viewBox="0 0 10 10" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round"><path d="M1 9L9 1M9 1H4M9 1v5"/></svg>
          </a>
        </div>
      </div>

      <div class="resource-card">
        <div class="resource-thumb">Thumbnail</div>
        <div class="resource-body">
          <span class="resource-type type-whitepaper">Whitepaper</span>
          <div class="resource-title">Building an AI-Ready Data Foundation on Snowflake</div>
          <a href="#" class="resource-link">
            Read more
            <svg viewBox="0 0 10 10" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round"><path d="M1 9L9 1M9 1H4M9 1v5"/></svg>
          </a>
        </div>
      </div>

      <div class="resource-card">
        <div class="resource-thumb">Thumbnail</div>
        <div class="resource-body">
          <span class="resource-type type-blog">Blog</span>
          <div class="resource-title">Ship Snowflake Cortex Agents Faster: A Skills-First Workflow</div>
          <a href="https://www.phdata.io/blog/ship-snowflake-cortex-agents-faster-a-skills-first-workflow-with-cortex-code-trulens/" class="resource-link" target="_blank" rel="noopener">
            Read more
            <svg viewBox="0 0 10 10" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round"><path d="M1 9L9 1M9 1H4M9 1v5"/></svg>
          </a>
        </div>
      </div>

      <div class="resource-card">
        <div class="resource-thumb">Thumbnail</div>
        <div class="resource-body">
          <span class="resource-type type-datasheet">Datasheet</span>
          <div class="resource-title">phData Toolkit: Automation for Snowflake Migrations</div>
          <a href="https://www.phdata.io/phdata-toolkit/" class="resource-link" target="_blank" rel="noopener">
            Read more
            <svg viewBox="0 0 10 10" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round"><path d="M1 9L9 1M9 1H4M9 1v5"/></svg>
          </a>
        </div>
      </div>

    </div>
  </div>

  <!-- FOOTER CTA -->
  <div class="footer-cta">
    <div class="footer-star">★ ★ ★ ★ ★ ★ &nbsp; Six-time Snowflake Partner of the Year</div>
    <div class="footer-h">Ready to connect?</div>
    <p class="footer-sub">Bring your toughest data and AI questions. We'll bring the answers.</p>
    <a href="#book" class="btn-primary">Book Time at Booth #2202</a>
  </div>

  <!-- PAGE FOOTER -->
  <div class="page-footer">
    <span>© 2026 phData. All rights reserved.</span>
    <span>Snowflake Summit 2026 · Booth #2202 · San Francisco</span>
  </div>

</div>

<script>
  const links = document.querySelectorAll('.jump-link');
  const sections = ['overview','booth','book','sessions','resources'];

  window.addEventListener('scroll', () => {
    let current = 'overview';
    sections.forEach(id => {
      const el = document.getElementById(id);
      if (el && window.scrollY >= el.offsetTop - 140) current = id;
    });
    links.forEach(link => {
      link.classList.toggle('active', link.getAttribute('href') === '#' + current);
    });
  });
</script>

</body>
</html>

