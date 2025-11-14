<!-- README.md — SkySentinel-AI — Dark Cloud Security Theme (paste entire file) -->

<p align="center">
  <img src="docs/images/banner.svg" alt="SkySentinel-AI banner" width="100%"/>
</p>

<!--
  Dark-first README: some <style> blocks may be sanitized in GitHub profile README.
  For full effect, view via GitHub Pages (https://<username>.github.io/<repo>/interactive-3d.html)
-->

<style>
:root{
  --bg-dark: #05070a;
  --panel: rgba(255,255,255,0.02);
  --neon-cyan: #00eaff;
  --neon-teal: #2ee6c6;
  --muted: #94a6b0;
  --accent: linear-gradient(90deg,#00172b,#002b40);
  --glass: rgba(255,255,255,0.02);
}
body, .dark-wrap { background: var(--bg-dark); color: #d6eef5; font-family: Inter, system-ui, -apple-system, "Segoe UI", Roboto, "Helvetica Neue", Arial; }
.dark-wrap { max-width: 980px; margin: 18px auto; padding: 18px; }
.profile-card {
  background: linear-gradient(180deg, rgba(255,255,255,0.02), rgba(255,255,255,0.01));
  border-radius: 12px; padding: 26px; box-shadow: 0 10px 40px rgba(0,0,0,0.6);
  position: relative; overflow: visible;
}
.title { font-size: 34px; font-weight:800; letter-spacing:-0.6px; margin:0; color:#ffffff; display:inline-block; }
.subtitle { color:var(--muted); margin-top:6px; font-weight:600; }
.neon-line { height:4px; border-radius:4px; margin:18px 0; background: linear-gradient(90deg,var(--neon-cyan),var(--neon-teal),#0047ff); box-shadow:0 8px 36px rgba(0,0,0,0.45) inset; }
.cube { width:110px; height:110px; transform-style:preserve-3d; animation: spin 7s linear infinite; margin-left:18px; }
@keyframes spin { from { transform: rotateX(-18deg) rotateY(0deg);} to { transform: rotateX(-18deg) rotateY(360deg);} }
.typebox{ font-family: ui-monospace, SFMono-Regular, Menlo, Monaco, "Roboto Mono", monospace; color:var(--neon-cyan); border-right:2px solid rgba(0,230,255,0.9); padding-right:8px; animation: blink 1s steps(2,end) infinite; font-weight:600; }
@keyframes blink { 50% { border-color: transparent; } }
.panel { margin-top:8px; background: linear-gradient(180deg, rgba(255,255,255,0.01), rgba(255,255,255,0.00)); padding:14px; border-radius:8px; border: 1px solid rgba(255,255,255,0.02); }
.small { color:var(--muted); font-size:14px; }
.pill { display:inline-block; padding:6px 10px; border-radius:999px; background: rgba(0,240,255,0.04); color:var(--neon-cyan); font-weight:700; font-size:13px; border: 1px solid rgba(0,240,255,0.05); }
.footer-note { color: #a3c7d1; font-size:13px; margin-top:10px; }
/* responsive */
@media (max-width:720px){ .title { font-size:24px; } .cube { display:none; } }
</style>

<div class="dark-wrap">

<div class="profile-card" role="banner">
  <div style="display:flex; align-items:center; gap:18px; flex-wrap:wrap; justify-content:center;">
    <div style="text-align:left;">
      <h1 class="title">🚀 SkySentinel-AI</h1>
      <div class="subtitle">DevSecOps Engineer • Cloud Security • AI-Driven Automation • SRE Mindset</div>
    </div>

    <!-- 3D spinning cube (SVG fallback) -->
    <div aria-hidden="true">
      <svg class="cube" viewBox="0 0 100 100" xmlns="http://www.w3.org/2000/svg" role="img" aria-label="3D cube">
        <defs>
          <linearGradient id="cg1" x1="0" x2="1"><stop offset="0" stop-color="#00172b"/><stop offset="1" stop-color="#003b5c"/></linearGradient>
          <linearGradient id="cg2" x1="0" x2="1"><stop offset="0" stop-color="#00eaff"/><stop offset="1" stop-color="#2ee6c6"/></linearGradient>
          <filter id="glo" x="-50%" y="-50%" width="200%" height="200%"><feGaussianBlur stdDeviation="3" result="b"/><feMerge><feMergeNode in="b"/><feMergeNode in="SourceGraphic"/></feMerge></filter>
        </defs>
        <g transform="translate(50,50)">
          <rect x="-28" y="-28" width="56" height="56" rx="8" fill="url(#cg1)" opacity="0.96" filter="url(#glo)"/>
          <rect x="-10" y="-10" width="20" height="20" rx="3" fill="url(#cg2)"/>
          <text x="0" y="36" font-family="Inter, Arial" font-size="8" text-anchor="middle" fill="#a6f8ff">SS</text>
        </g>
      </svg>
    </div>
  </div>

  <p style="text-align:center; margin-top:14px;">
    <span class="typebox">I build secure, automated cloud systems that detect → respond → auto-remediate…</span><br/>
    <span class="small">Focused on AWS Security, DevSecOps pipelines, AI-driven detection, and self-healing infra.</span>
  </p>
</div>

<div class="neon-line" role="presentation"></div>

<!-- About -->
<div class="panel">
<h2 id="about">🧠 About / Core Expertise</h2>
<ul>
  <li><strong>Detect → Respond → Auto-remediate</strong> — autonomous security workflows & runbooks</li>
  <li><strong>Cloud & Security</strong> — AWS (Lambda, EC2, CloudWatch, SNS, IAM), fail2ban automation</li>
  <li><strong>Infra & CI</strong> — Terraform, GitHub Actions, Docker, CI/CD</li>
  <li><strong>Automation</strong> — Python, Bash, serverless remediation</li>
  <li><strong>Observability</strong> — dashboards, metrics, anomaly detection (Prometheus/CloudWatch)</li>
</ul>
</div>

<!-- Featured project -->
<div class="panel" style="margin-top:14px;">
<h2>🔥 Featured Project — Fail2Ban AWS</h2>
<p><em>Automated Cloud Security System: Detect → Block → Alert</em></p>
<ul>
  <li>Real-time intrusion detection & automatic IP banning</li>
  <li>Lambda-based remediation + CloudWatch → SNS alert pipeline</li>
  <li>Fully automated, hands-free cloud defense (24/7)</li>
</ul>
<p class="small">
🔗 <strong>Live:</strong> <a href="https://skysentinel-ai.github.io/fail2ban-aws-project">skysentinel-ai.github.io/fail2ban-aws-project</a><br/>
🔗 <strong>Repo:</strong> <a href="https://github.com/SkySentinel-AI/fail2ban-aws-project">github.com/SkySentinel-AI/fail2ban-aws-project</a>
</p>
</div>

<!-- Tech stack -->
<div class="panel" style="margin-top:14px;">
<h2>🧩 Tech Stack</h2>
<table>
  <tr><td><strong>Cloud</strong></td><td>AWS (Lambda, EC2, CloudWatch, SNS, IAM)</td></tr>
  <tr><td><strong>Automation</strong></td><td>Python, Bash, Serverless</td></tr>
  <tr><td><strong>Infra</strong></td><td>Terraform, IaC, VCS</td></tr>
  <tr><td><strong>CI / Security</strong></td><td>GitHub Actions, Fail2Ban, CloudWatch Alerts</td></tr>
</table>
</div>

<!-- Analytics -->
<div style="text-align:center; margin:20px 0;">
<h2>📊 GitHub Analytics (Dark UI)</h2>
<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=SkySentinel-AI&show_icons=true&theme=dark&hide_border=true" width="62%" alt="GitHub stats"/>
</p>
<p align="center">
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=SkySentinel-AI&layout=compact&theme=dark&hide_border=true" width="42%" alt="Top languages"/>
</p>
</div>

<!-- Contribution snake + activity graph -->
<div class="panel" style="margin-top:10px;">
<h2>🐍 Cyber-Blue Contribution Snake</h2>
<p align="center">
  <img src="https://raw.githubusercontent.com/SkySentinel-AI/SkySentinel-AI/output/github-contribution-grid-snake.svg" alt="contribution snake" style="max-width:100%; border-radius:8px; box-shadow:0 8px 36px rgba(0,0,0,0.45)"/>
</p>
<p class="small" style="text-align:center;">If blank: allow the Action that generates the snake to push to `output` or `gh-pages` branch.</p>

<h2>📈 Activity Graph</h2>
<p align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=SkySentinel-AI&theme=react-dark&hide_border=true&area=true" width="72%" alt="activity graph"/>
</p>
</div>

<!-- Interactive 3D -->
<div class="panel" style="margin-top:14px;">
<h2>🎛️ Interactive 3D Dashboard (Live)</h2>
<p>Experience the 3D Fail2Ban Security Visualization (attacks, blocks, alerts mapped in interactive 3D):</p>
<p style="text-align:center;">
  <a class="pill" href="https://skysentinel-ai.github.io/SkySentinel-AI/interactive-3d.html">Open 3D Visualization (Pages)</a>
</p>
<p class="small">Note: interactive 3D uses three.js / Plotly and must run on GitHub Pages (static host) — README itself cannot run advanced JS inside the GitHub profile preview.</p>
</div>

<!-- Connect -->
<div class="panel" style="margin-top:14px;">
<h2>🌐 Connect</h2>
<p>
  <a href="https://linkedin.com/in/jrishikesh-j-306ba635b"><img src="https://img.shields.io/badge/LinkedIn-Rishikesh_Jogdand-blue?style=for-the-badge&logo=linkedin" alt="LinkedIn"/></a><br/>
  📍 Pune, India — 📧 <a href="mailto:jogdandrishikesh05@gmail.com">jogdandrishikesh05@gmail.com</a>
</p>
</div>

<!-- Currently building / motto -->
<div class="panel" style="margin-top:14px;">
<h2>⚡ Currently Building</h2>
<ul>
  <li>Multi-cloud security automation (AWS + Azure + GCP + IBM)</li>
  <li>AI-powered threat detection & autonomous remediation</li>
  <li>Real-time cloud monitoring dashboards & self-healing playbooks</li>
</ul>

<h2>🛡️ Motto</h2>
<div style="text-align:center; font-weight:700; font-size:18px; margin-top:8px;">“Secure everything. Automate anything.”</div>
</div>

<!-- Implementation notes -->
<div class="footer-note">
<hr/>
**Implementation notes & quick checklist (read before committing)**:
- GitHub profile READMEs may strip some `<style>`/JS. The dark theme & cube SVG remain useful in **raw / Pages** view. For full animation use **GitHub Pages**.
- To show generated images (contribution snake / charts) ensure your GitHub Actions workflow has **write permission** and can push to `output` or `gh-pages`. (Check *Settings → Actions → Workflow permissions* — set "Read and write permissions" and allow actions to create & approve PRs if needed).
- 3D interactive page is served from `interactive-3d.html` under GitHub Pages (push to `gh-pages` or configure Pages from `main`/`docs`).
- If an image is blank: open Actions logs → confirm the step pushed the file and branch permissions were allowed.
</div>

</div>
