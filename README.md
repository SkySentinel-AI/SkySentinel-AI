<!-- README v5 - SkySentinel-AI -->

<p align="center">
  <img src="assets/main-banner.png" alt="Main Banner" width="100%"/>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/DEVSECOPS-EXPERT-000?style=for-the-badge&logo=dependabot&logoColor=white" alt="DevSecOps"/>
  <img src="https://img.shields.io/badge/CLOUDSECURITY-AWS%7CGCP%7CAZURE%7CIBM-0059ff?style=for-the-badge&logo=cloudflare&logoColor=white" alt="Cloud"/>
  <img src="https://img.shields.io/badge/AI_AUTOMATION-THREAT_DETECTION-f00000?style=for-the-badge&logo=tensorflow&logoColor=white" alt="AI"/>
</p>

# ☁️ J Rishikesh | SkySentinel-AI  
**DevSecOps • Cloud Security Engineer • AI-Driven Defensive Systems**

> _“AI-Driven Cloud Security is the future — and I’m building it.”_

---

## 🔥 Featured Visuals (replace/upgrade whenever you like)
<p align="center">
  <img src="assets/featured-projects.png" alt="Featured Projects" width="88%"/>
</p>

<p align="center">
  <img src="assets/fail2ban-aws.png" alt="Fail2Ban AWS Project" width="88%"/>
</p>

<p align="center">
  <img src="assets/tricloudsentinel-banner.png" alt="TriCloudSentinel Project" width="88%"/>
</p>

<p align="center">
  <img src="assets/tech-stack.png" alt="Tech Stack" width="90%"/>
</p>

<p align="center">
  <img src="assets/currently-building.png" alt="Currently Building" width="85%"/>
</p>

<p align="center">
  <!-- Contribution snake served from output branch -->
  <img src="https://raw.githubusercontent.com/SkySentinel-AI/SkySentinel-AI/output/github-contribution-grid-snake.svg" alt="contribution-snake" width="85%"/>
</p>

<p align="center">
  <img src="assets/live-activity-heatmap.png" alt="Live activity heatmap" width="85%"/>
</p>

---

## 📌 Quick Project Summary
**TriCloudSentinel** — AI-Driven Multi-Agent Threat Detection (demo)
- 3 independent Python detection agents (containerized)
- Central **Ensemble** engine: 60s sliding window, average threat scoring
- **Safety Gate**: simulated auto-remediation (Azure/GCP/IBM)
- Observability via **Prometheus** (scrapes `/metrics`) and **Grafana Cloud** (remote_write)
- Orchestrated by Docker Compose

**Featured demo projects**
1. `Fail2Ban AWS` — automated IP blocking PoC.  
2. `TriCloudSentinel` — multi-agent ensemble + metrics.

---

## 🚀 How to run (local)
From repo root:

```bash
# 1) bring up everything
docker compose up -d --force-recreate --build

# 2) confirm services
docker compose ps

# 3) verify ensemble health + endpoints
curl -i http://localhost:9000/health      
curl -i http://localhost:9000/metrics
