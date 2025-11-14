<!-- README.md — SkySentinel-AI — Full Cyber Theme (paste entire file) -->

<p align="center">
  <img src="docs/images/banner.svg" alt="SkySentinel-AI banner" width="100%"/>
</p>

<!--
  Note: GitHub may sanitize some <style> blocks in profile READMEs.
  For full effect view this file via GitHub Pages or the repository page.
-->

<!-- Theme styles (works best on GitHub Pages / raw HTML view) -->
<style>
  :root{
    --cyber-bg: linear-gradient(90deg,#021124,#00172b 35%,#05283b 100%);
    --neon: #00f0ff;
    --accent: #2ee6c6;
    --muted: #8a9aa6;
    --card: rgba(255,255,255,0.03);
    --glass: rgba(255,255,255,0.03);
    --sep: linear-gradient(90deg,#05283b,#00293c);
  }

  /* Container */
  .cyber-wrap { max-width: 980px; margin: 18px auto; font-family: Inter, system-ui, -apple-system, "Segoe UI", Roboto, "Helvetica Neue", Arial; color: #111; }

  /* Floating 3D Card behind name */
  .floating-card {
    position: relative;
    display: block;
    margin: 18px auto 28px;
    width: calc(100% - 120px);
    max-width: 880px;
    padding: 28px 36px;
    border-radius: 12px;
    background: linear-gradient(180deg, rgba(255,255,255,0.02), rgba(255,255,255,0.01));
    box-shadow: 0 6px 24px rgba(0,0,0,0.35), inset 0 1px 0 rgba(255,255,255,0.02);
    transform-style: preserve-3d;
    perspective: 1000px;
    overflow: visible;
  }
  .floating-card::before{
    content:"";
    position:absolute;
    left:-18px; top:-18px;
    width:120%; height:120%;
    background: radial-gradient(circle at 10% 10%, rgba(0,255,255,0.04), transparent 10%),
                radial-gradient(circle at 90% 90%, rgba(0,120,255,0.03), transparent 12%);
    transform: rotateX(12deg) rotateY(-6deg) translateZ(-40px);
    border-radius:14px;
    z-index:-1;
    filter: blur(14px);
  }

  .name-row { display:flex; align-items:center; gap:20px; justify-content:center; flex-wrap:wrap; }
  .name-title { font-size:28px; font-weight:700; letter-spacing: -0.6px; margin:0; }
  .name-sub { font-size:14px; color:var(--muted); margin-top:4px; font-weight:600 }

  /* Neon separators */
  .neon-sep { height:4px; border-radius:4px; margin:28px 0; background: linear-gradient(90deg,#00eaff,#2ee6c6,#0047ff); box-shadow:0 6px 24px rgba(2,20,40,0.25) inset; }

  /* Typing intro (AI-like) */
  .typing {
    font-family: ui-monospace, SFMono-Regular, Menlo, Monaco, "Roboto Mono", monospace;
    color:#00eaff;
    margin: 6px 0 14px;
    font-weight:600;
  }
  .typebox{
    display:inline-block;
    border-right: 2px solid rgba(0,230,255,0.9);
    padding-right:6px;
    animation: blink 1s steps(2,end) infinite;
  }
  @keyframes blink { 50% { border-color: transparent; } }

  /* 3D spinning cube (SVG embed area) */
  .cube-wrap{ display:flex; justify-content:center; margin:16px 0; }
  .cube { width:120px; height:120px; transform-style:preserve-3d; animation:cubeSpin 7s linear infinite; }
  @keyframes cubeSpin { from { transform: rotateX(-18deg) rotateY(0deg);} to { transform: rotateX(-18deg) rotateY(360deg);} }

  /* Dark mode */
  @media (prefers-color-scheme: dark) {
    :root { color-scheme: dark; }
    body, .cyber-wrap { background: #01040a; color: #d7eaf0; }
    .floating-card { background: linear-gradient(180deg, rgba(255,255,255,0.02), rgba(0,0,0,0.05)); box-shadow: 0 12px 36px rgba(0,0,0,0.6); }
    .typing { color: #7fffd4; }
  }

  /* Responsive */
  @media (max-width:720px) {
    .floating-card { padding:22px; width:calc(100% - 36px); }
    .name-title { font-size:22px; }
  }

  /* Buttons/pill */
  .pill { display:inline-block; padding:6px 10px; border-radius:999px; background: rgba(0,240,255,0.08); color:var(--neon); font-weight:700; font-size:13px; border: 1px solid rgba(0,240,255,0.06); }
</style>

<div class="cyber-wrap">

<!-- Floating card behind name -->
<div class="floating-card" aria-hidden="false">
  <div class="name-row">
    <div style="text-align:center;">
      <h1 class="name-title">🚀 SkySentinel-AI</h1>
      <div class="name-sub">DevSecOps Engineer · Cloud Security · AI-Driven Automation · SRE mindset</div>
    </div>

    <!-- 3D cube (SVG) -->
    <div class="cube-wrap" aria-hidden="true" style="width:160px;">
      <!-- Spinning cube rendered as SVG faces (works in GitHub Pages/raw view) -->
      <svg class="cube" viewBox="0 0 100 100" xmlns="http://www.w3.org/2000/svg" role="img" aria-label="3D cube">
        <defs>
          <linearGradient id="g1" x1="0" x2="1"><stop offset="0" stop-color="#00243b"/><stop offset="1" stop-color="#003b5c"/></linearGradient>
          <linearGradient id="g2" x1="0" x2="1"><stop offset="0" stop-color="#00eaff"/><stop offset="1" stop-color="#2ee6c6"/></linearGradient>
          <filter id="glow" x="-50%" y="-50%" width="200%" height="200%"><feGaussianBlur stdDeviation="3" result="b"/><feMerge><feMergeNode in="b"/><feMergeNode in="SourceGraphic"/></feMerge></filter>
        </defs>

        <!-- cube faces -->
        <g transform="translate(50,50)">
          <rect x="-26" y="-26" width="48" height="48" fill="url(#g1)" opacity="0.95" rx="6" ry="6" filter="url(#glow)" />
          <rect x="-6" y="-6" width="12" height="12" fill="url(#g2)" rx="2"/>
          <text x="0" y="36" font-family="Inter, Arial" font-size="8" text-anchor="middle" fill="#a6f8ff">SS</text>
        </g>
      </svg>
    </div>
  </div>

  <!-- AI-like typing intro (graceful fallback: static text) -->
  <p style="text-align:center; margin-top:14px; line-height:1.45;">
    <span class="typing"> <span class="typebox">I build secure, scalable, automated cloud ecosystems…</span> </span>
    <br/><span style="color:var(--muted);">Focused on AWS Security, AI-enabled detection, DevSecOps pipelines, and self-healing infra.</span>
  </p>
</div>

<!-- Neon separator -->
<div class="neon-sep" role="presentation"></div>

<!-- About / Core Expertise -->
<h2>🧠 About / Core Expertise</h2>
<ul>
  <li><strong>Detect → Respond → Auto-remediate:</strong> autonomous security workflows and runbooks</li>
  <li><strong>Cloud & DevSecOps:</strong> AWS (EC2, Lambda, CloudWatch, SNS, IAM), Terraform, GitHub Actions</li>
  <li><strong>Automation:</strong> Python, Bash, CI/CD pipelines, containerization</li>
  <li><strong>Observability:</strong> dashboards, metrics, and anomaly detection</li>
</ul>

<!-- Featured Project -->
<h2>🔥 Featured Project — Fail2Ban AWS</h2>
<p><em>Automated Cloud Security System: Detect → Block → Alert</em></p>
<ul>
  <li>Real-time intrusion detection & auto IP banning</li>
  <li>Lambda-based remediation & CloudWatch alerts</li>
  <li>24/7 hands-free cloud protection</li>
</ul>
<p>
  🔗 <strong>Live Project:</strong> <a href="https://skysentinel-ai.github.io/fail2ban-aws-project">fail2ban-aws-project</a><br/>
  🔗 <strong>Repo:</strong> <a href="https://github.com/SkySentinel-AI/fail2ban-aws-project">github.com/SkySentinel-AI/fail2ban-aws-project</a>
</p>

<!-- Tech stack table -->
<h2>🧩 Tech Stack</h2>
<table>
  <tr><td><strong>Cloud</strong></td><td>AWS (EC2, Lambda, CloudWatch, SNS, IAM)</td></tr>
  <tr><td><strong>DevOps</strong></td><td>GitHub Actions, Docker, CI/CD</td></tr>
  <tr><td><strong>Security</strong></td><td>Fail2Ban, CloudWatch Alerts, IAM automation</td></tr>
  <tr><td><strong>Languages</strong></td><td>Python, Bash</td></tr>
  <tr><td><strong>IaC</strong></td><td>Terraform</td></tr>
</table>

<!-- GitHub Analytics / Widgets -->
<div style="text-align:center; margin:22px 0;">
  <h2>📊 GitHub Analytics (Premium UI)</h2>
  <p align="center">
    <img src="https://github-readme-stats.vercel.app/api?username=SkySentinel-AI&show_icons=true&theme=tokyonight&hide_border=true" width="60%" alt="GitHub stats"/>
  </p>
  <p align="center">
    <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=SkySentinel-AI&layout=compact&theme=tokyonight&hide_border=true" width="40%" alt="Top languages"/>
  </p>
</div>

<!-- Cyber-Blue Contribution Snake -->
<h2>🐍 Cyber-Blue Contribution Snake</h2>
<p align="center">
  <img src="https://raw.githubusercontent.com/SkySentinel-AI/SkySentinel-AI/output/github-contribution-grid-snake.svg" alt="Contribution snake" style="max-width:100%; border-radius:8px; box-shadow: 0 8px 36px rgba(2,30,40,0.25);" />
</p>
<p style="color:var(--muted)"><em>If the snake image is blank: allow GitHub Actions to push the `output` or `gh-pages` branch so the generated SVG is available.</em></p>

<!-- Activity Graph -->
<h2>📈 Activity Graph</h2>
<p align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=SkySentinel-AI&theme=react-dark&hide_border=true&area=true" width="70%" alt="activity graph"/>
</p>

<!-- 3D Interactive Visualization link -->
<h2>🎛️ Interactive 3D Dashboard (Live)</h2>
<p>
  Experience the 3D Fail2Ban Security Visualization (attacks, blocks, alerts in 3D):<br/>
  <a href="https://skysentinel-ai.github.io/SkySentinel-AI/interactive-3d.html" class="pill">Open 3D Visualization</a>
</p>
<p style="color:var(--muted)">Note: 3D / interactive charts require GitHub Pages or a static host to run JavaScript-based viewers (three.js / Plotly). The README contains a link to the live page where full interactivity runs.</p>

<!-- Dark-mode-first banner suggestion -->
<div style="margin:18px 0; padding:14px; border-radius:10px; background: linear-gradient(90deg,#00172b,#002b40); color:white; text-align:center;">
  <strong>Dark-mode recommendation:</strong> I recommend using a dark-first banner &assets for the GitHub Pages site (users with dark preference get the full neon cyber look).
</div>

<!-- Contact -->
<h2>🌐 Connect</h2>
<p>
  [![LinkedIn](https://img.shields.io/badge/LinkedIn-Rishikesh_Jogdand-blue?style=for-the-badge&logo=linkedin)](https://linkedin.com/in/jrishikesh-j-306ba635b)<br/>
  📍 Pune, India — 📧 <a href="mailto:jogdandrishikesh05@gmail.com">jogdandrishikesh05@gmail.com</a>
</p>

<!-- Currently building & motto -->
<h2>⚡ Currently Building</h2>
<ul>
  <li>Multi-cloud security automation (AWS + Azure + GCP + IBM)</li>
  <li>AI-driven threat detection & autonomous remediation</li>
  <li>Real-time cloud monitoring dashboards and self-healing playbooks</li>
</ul>

<h2>🛡️ Motto</h2>
<div style="text-align:center; margin:18px 0; font-weight:700; font-size:18px;">“Secure everything. Automate anything.”</div>

<!-- Footer notes -->
<hr/>
<p style="color:var(--muted); font-size:13px;">
  <strong>Implementation notes:</strong>
  <ul>
    <li>GitHub profile READMEs may strip some `<style>` contents — for full animations visit the <em>GitHub Pages</em> live site.</li>
    <li>3D & interactive charts (three.js / Plotly) are included on the project Pages site at <code>/interactive-3d.html</code>. That file can host advanced JS visualizations not permitted in README.</li>
    <li>If any images appear blank, make sure the Action that generates them has permission to push to your chosen branch (e.g. `output` or `gh-pages`).</li>
  </ul>
</p>

</div>
