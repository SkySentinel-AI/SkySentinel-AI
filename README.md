<!-- ================================================= -->
<!--  Global Cloud / DevSecOps Engineer – Profile README -->
<!--  Optimized for Japan 🇯🇵 & Germany 🇩🇪 -->
<!-- ================================================= -->

<h1 align="center">Cloud / DevSecOps Engineer</h1>

<p align="center">
  <img src="https://img.shields.io/badge/AWS-FF9900?style=for-the-badge&logo=amazonaws&logoColor=white"/>
  <img src="https://img.shields.io/badge/Azure-0078D4?style=for-the-badge&logo=microsoftazure&logoColor=white"/>
  <img src="https://img.shields.io/badge/GCP-4285F4?style=for-the-badge&logo=googlecloud&logoColor=white"/>
  <img src="https://img.shields.io/badge/IBM_Cloud-1261FE?style=for-the-badge&logo=ibmcloud&logoColor=white"/>
</p>

<p align="center">
  <i>Security is designed into the architecture — not added later.</i>
</p>

---

## 👤 About Me

Cloud / DevSecOps Engineer with experience designing **secure, scalable, and automated cloud environments** across **AWS, Azure, GCP, and IBM Cloud**.

I focus on **security-by-design**, infrastructure reliability, and automation using **infrastructure as code** and **CI/CD pipelines**.  
My work emphasizes **clarity, stability, and long-term maintainability** of cloud systems.

I am comfortable working in **globally distributed teams** and structured engineering environments where documentation, reviews, and continuous improvement are valued.

---

## 🎯 Technical Focus

- Multi-cloud infrastructure architecture (AWS, Azure, GCP, IBM Cloud)
- Identity & access management (IAM) and Zero Trust principles
- DevSecOps pipelines with policy-as-code
- Cloud-native threat detection and automated response
- Kubernetes security and workload hardening
- Observability, metrics, and SIEM-ready pipelines

---

## 🧠 Core Engineering Domains

### ☁️ Cloud Infrastructure & Security
- VPC / VNet / IBM VPC design, private endpoints, zero-trust routing
- AWS Security Hub & GuardDuty
- Azure Defender
- GCP Security Command Center (SCC)
- IBM Cloud Security & Compliance Center
- Encryption lifecycle management:
  - AWS KMS
  - Azure Key Vault
  - GCP KMS
  - IBM Key Protect / Hyper Protect Crypto Services

---

### 🔐 Identity & Access Management (IAM)
- RBAC / ABAC and IAM boundary design
- MFA enforcement
- Privilege hardening and continuous verification
- Least-privilege access across cloud platforms

---

### ⚙️ DevSecOps, CI/CD & Automation
- Terraform with policy-as-code
- Secure CI/CD pipelines (GitHub Actions)
- Infrastructure and container scanning (Trivy, tfsec, Grype)
- Kubernetes governance and workload security
- Automated compliance validation

---

## 🚀 Projects

### 🔥 TriCloudSentinel — Multi-Cloud Security Detection Platform
AI-assisted, multi-agent system for detecting and processing security signals across **AWS, Azure, GCP, and IBM Cloud**.

**Purpose**
- Demonstrate a practical and reproducible architecture for centralized multi-cloud security detection.

**Features**
- Distributed Python-based detection agents
- Sliding-window ensemble scoring
- Automated remediation logic
- `/metrics` endpoint for Prometheus
- Containerized architecture (Docker Compose)

**Outcome**
- Unified security signal processing across multiple cloud providers
- Monitoring-ready design suitable for SIEM integration
- Local-first development with production-oriented architecture

🔗 https://github.com/SkySentinel-AI/TriCloudSentinel-demo

---

### 🛡️ fail2ban-aws — Automated Cloud IP Blocking
Lightweight automation for detecting suspicious log events and blocking malicious IPs using AWS Security Groups.

**Highlights**
- CloudWatch log monitoring
- Automated IP blocking
- CI/CD-integrated deployment

🔗 https://github.com/SkySentinel-AI/fail2ban-aws-project

---

## 📊 GitHub Activity & Metrics

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=SkySentinel-AI&show_icons=true&theme=tokyonight&hide_border=true" width="55%"/>
</p>

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=SkySentinel-AI&layout=compact&theme=tokyonight&hide_border=true" width="40%"/>
</p>

<p align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=SkySentinel-AI&theme=react-dark&hide_border=true&area=true" width="95%"/>
</p>

---

## ▶️ Run Locally (TriCloudSentinel)

```bash
docker compose up -d --force-recreate --build
docker compose ps

curl http://localhost:9000/health     # health check
curl http://localhost:9000/metrics    # Prometheus metrics


---

<p align="center">
  <a href="https://linkedin.com/in/j-r-306ba635b" target="_blank">
    <img src="https://cdn-icons-png.flaticon.com/512/174/174857.png" width="48"/>
  </a>
  &nbsp;&nbsp;
  <a href="mailto:jogdandrishikesh05@gmail.com">
    <img src="https://cdn-icons-png.flaticon.com/512/732/732200.png" width="48"/>
  </a>
  &nbsp;&nbsp;
  <a href="https://x.com/RishiAIXCloud" target="_blank">
    <img src="https://cdn-icons-png.flaticon.com/512/733/733579.png" width="48"/>
  </a>
</p>

