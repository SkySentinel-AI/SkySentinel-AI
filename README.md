<p align="center">
  <a href="https://github.com/SkySentinel-AI">
    <img src="assets/main-banner.png" alt="SkySentinel-AI — J Rishikesh" width="100%"/>
  </a>
</p>

<div align="center">
  <img src="https://img.shields.io/badge/DEVSECOPS-ELITE-000?style=for-the-badge&logo=dependabot&logoColor=white" alt="DevSecOps"/>
  <img src="https://img.shields.io/badge/CLOUD_SECURITY-AWS%7CGCP%7CAZURE%7CIBM-0059ff?style=for-the-badge&logo=cloudflare&logoColor=white" alt="Cloud"/>
  <img src="https://img.shields.io/badge/AI_AUTOMATION-THREAT_DETECTION-f00000?style=for-the-badge&logo=tensorflow&logoColor=white" alt="AI"/>
</div>

# <div align="center">☁️ J Rishikesh — SkySentinel-AI</div>
### <div align="center">Senior Cloud Security Engineer • DevSecOps • AI-Driven Defensive Systems</div>

<div align="center"><i>“AI-Driven Cloud Security is the future — and I’m building it.”</i></div>

---

## ✨ Featured Visuals
<p align="center">
  <a href="https://github.com/SkySentinel-AI">
    <img src="assets/featured-projects.png" width="88%" alt="Featured projects banner"/>
  </a>
</p>

<p align="center">
  <a href="https://github.com/SkySentinel-AI/fail2ban-aws">
    <img src="assets/fail2ban-aws.png" width="44%" alt="Fail2Ban AWS"/>
  </a>
  &nbsp;&nbsp;
  <a href="https://github.com/SkySentinel-AI/TriCloudSentinel-demo">
    <img src="assets/tricloudsentinel-banner.png" width="44%" alt="TriCloudSentinel"/>
  </a>
</p>

<p align="center">
  <img src="assets/tech-stack.png" width="90%" alt="Tech stack"/>
</p>

<p align="center">
  <img src="assets/currently-building.png" width="85%" alt="Currently building"/>
</p>

---

## 📊 Live GitHub Insights (production-grade)
> I prefer **live**, stable visual embeds so recruiters see real activity & language usage.

<p align="center">
  <!-- GitHub Stats: live from vercel app -->
  <img src="https://github-readme-stats.vercel.app/api?username=SkySentinel-AI&show_icons=true&theme=tokyonight" width="60%" alt="GitHub Stats"/>
</p>

<p align="center">
  <!-- Top languages (live) -->
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=SkySentinel-AI&layout=compact&theme=tokyonight" width="42%" alt="Top Languages"/>
</p>

<p align="center">
  <!-- Activity graph (live) — hosted by vercel readme activity graph -->
  <img src="https://activity-graph.herokuapp.com/graph?username=SkySentinel-AI&theme=react-dark" width="95%" alt="Activity Graph"/>
</p>

> **Note:** If you prefer the animated "snake" & "heatmap" visuals, those can be generated and published to the `output` branch (I included instructions below). If they remain flaky, keep the stable live embeds above — these look more professional for recruiters.

---

## 🚀 Project Snapshot

### **TriCloudSentinel — AI Multi-Agent Threat Detection (demo)**
- **Three** independent Python detection agents (containerized).
- **Ensemble engine**: 60-second sliding window, average threat scoring → anomaly detection.
- **Safety Gate**: simulated automated remediation for cloud providers (Azure / GCP / IBM).
- **Observability**: Prometheus `/metrics`. Optional Grafana Cloud via `remote_write`.
- Orchestrated using **Docker Compose** for a realistic end-to-end demo.

### **Key featured repos**
1. **fail2ban-aws** — PoC for automated IP blocking in cloud hosts.  
2. **TriCloudSentinel-demo** — Multi-agent ensemble, safety gate, Prometheus metrics.

---

## 🛠️ Quick local setup (developer preview)
From repository root:

```bash
# 1) build & run everything locally
docker compose up -d --force-recreate --build

# 2) confirm containers
docker compose ps

# 3) verify ensemble & metrics
curl -i http://localhost:9000/health     # should return "ok"
curl -i http://localhost:9000/metrics    # Prometheus exposition format

---

<p align="center">
  <a href="https://linkedin.com/in/j-r-306ba635b">
    <img src="https://cdn-icons-png.flaticon.com/512/174/174857.png" width="48" alt="LinkedIn"/>
  </a>
  &nbsp;&nbsp;
  <a href="mailto:jogdandrishikesh05@gmail.com">
    <img src="https://cdn-icons-png.flaticon.com/512/732/732200.png" width="48" alt="Email"/>
  </a>
</p>
