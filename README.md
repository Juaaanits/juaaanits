<h1 align="center">
  Hi, I'm Juanito M. Ramos II 👋
</h1>

<p align="center">
  <strong>System Engineer | Aspiring DevSecOps & Cloud Security Engineer</strong>
</p>

<p align="center">
  AWS • Azure • Kubernetes • Terraform • Docker • Linux • CI/CD • Observability
</p>

<div align="center">

<a href="https://www.linkedin.com/in/juanitoramos/" target="_blank">
  <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" />
</a>

</div>

---

## 👨‍💻 About Me

I'm a System Engineer building toward a career in **DevSecOps and Cloud Security**, with hands-on projects across cloud infrastructure, Kubernetes, Infrastructure as Code, CI/CD security, observability, backend systems, and application security.

My current focus is understanding how systems are **built, deployed, monitored, secured, broken, troubleshot, and improved** rather than simply completing tool-based tutorials.

I also have a background in backend development, AI/ML engineering, and database-driven applications, which helps me understand the applications and services that cloud and security engineering ultimately support.

### 🎯 Career Direction

> Build secure, observable, automated cloud-native platforms as a **DevSecOps / Cloud Security Engineer**.

---

## 🔐 Current DevSecOps & Cloud Security Focus

* ☸️ Kubernetes and k3s platform engineering
* ☁️ AWS and Azure cloud infrastructure
* 🏗️ Infrastructure as Code with Terraform
* 🔄 CI/CD and GitOps
* 🔎 Container and dependency vulnerability management
* 🔑 Secrets management and workload hardening
* 📊 Monitoring, alerting, and observability
* 🛡️ Application and cloud security fundamentals
* 🐧 Linux systems administration and troubleshooting

---

## 🚀 Featured Engineering Projects

### ☸️ [K3s DevSecOps & Observability Homelab](https://github.com/Juaaanits/homelab)

A Kubernetes platform engineering homelab running on repurposed hardware with:

`k3s` • `Prometheus` • `Grafana` • `Alertmanager` • `node-exporter` • `Traefik` • `Python`

Current work includes Kubernetes networking, persistent storage, custom application metrics, alerting, controlled failure testing, workload hardening, and troubleshooting.

**Next phases:** Helm → GitHub Actions → Trivy → GHCR → Argo CD → Kyverno → Sealed Secrets → Terraform

🔗 **[View Repository](https://github.com/Juaaanits/homelab)**

---

### 🔐 [Secure Container Supply Chain Pipeline](https://github.com/Juaaanits/security-container-delivery-pipeline)

A practical DevSecOps workflow demonstrating:

`GitHub Actions` • `Docker` • `detect-secrets` • `Docker Scout` • `SARIF` • `Bash`

Includes secret detection, container builds, vulnerability scanning, severity-based security gates, security reporting, remediation validation, and automated notifications.

🔗 **[View Repository](https://github.com/Juaaanits/security-container-delivery-pipeline)**

---

### ☁️ [Secure AWS Static Web Platform with Terraform](https://github.com/Juaaanits/Automated-AWS-Web-Hosting-with-Terraform)

Infrastructure as Code project provisioning a secure AWS static web architecture using:

`Terraform` • `Amazon S3` • `CloudFront` • `Route 53` • `ACM` • `CodePipeline` • `CodeBuild`

Current improvements focus on Terraform state management, infrastructure security scanning, IAM, and deployment automation.

🔗 **[View Repository](https://github.com/Juaaanits/Automated-AWS-Web-Hosting-with-Terraform)**

---

### 🧪 [.NET Backend Reliability, DevSecOps & Azure Lab](https://github.com/Juaaanits/sakenny-backend-qa-devsecops-cloud-lab)

Engineering extension of an MIT-licensed .NET 8 backend focused on:

`.NET 8` • `SQL Server` • `Docker` • `xUnit` • `Postman/Newman` • `CodeQL` • `Trivy` • `Dependabot` • `Terraform` • `Azure`

The project combines backend testing, QA, vulnerability scanning, database validation, containerization, observability, and cloud infrastructure work.

🔗 **[View Repository](https://github.com/Juaaanits/sakenny-backend-qa-devsecops-cloud-lab)**

---

### 🧠 [CerebraSense Cloud ML Inference Platform](https://github.com/Juaaanits/Cerebrasense-Web)

Cloud-deployed MRI classification application using:

`Astro` • `FastAPI` • `PyTorch` • `Supabase` • `PostgreSQL` • `Vercel` • `Railway`

The system separates frontend, API, ML inference, database, and object-storage responsibilities while maintaining prediction history and calibrated model results.

🔗 **[View Repository](https://github.com/Juaaanits/Cerebrasense-Web)**

---

### 🛡️ [Web Application Security & WAF Lab](https://github.com/Juaaanits/web-app-security-waf-lab)

A practical web application security homelab focused on understanding how attacks move through a web application stack and how defensive controls detect, block, and log malicious traffic.

`SafeLine WAF` • `Kali Linux` • `Ubuntu` • `DVWA` • `Apache` • `MySQL` • `TLS`

**Focus areas:**

- WAF deployment and reverse-proxy architecture
- TLS termination and HTTPS traffic inspection
- Controlled SQL injection and web-attack testing
- WAF detection and blocking
- Security event logging and analysis
- Rate limiting and custom security rules
- Legitimate-traffic validation
- Direct-backend bypass testing
- Security hardening
- Root-cause analysis and troubleshooting

### Architecture

```text
Kali Linux
    │
    │ HTTPS :8443
    ▼
SafeLine WAF
    │
    │ HTTP :8080
    ▼
Apache / DVWA
    │
    ▼
MySQL
```

The lab runs alongside an existing `k3s + Traefik` environment, providing additional hands-on experience with reverse-proxy routing, TLS, listener conflicts, and troubleshooting in a shared homelab.

🔗 **[View Repository](https://github.com/Juaaanits/web-app-security-waf-lab)**

---

### 🏗️ Lab Architecture

```text
Kali Linux
    │
    │ HTTPS :8443
    ▼
SafeLine WAF
    │
    │ HTTP :8080
    ▼
Apache / DVWA
    │
    ▼
MySQL
```

The lab also operates alongside an existing `k3s + Traefik` environment, providing hands-on experience with reverse-proxy and ingress conflicts in a shared homelab.

### 🎯 Objective

The goal is not simply to deploy a WAF, but to understand how web attacks travel through an application stack, how defensive controls detect and prevent them, and how to troubleshoot failures across the network, TLS, proxy, WAF, and application layers.

> **Repository will be published once the first working and documented lab version is complete.**
---

## 🛠️ Technical Stack

### ☁️ Cloud

AWS • Microsoft Azure

### 🏗️ Infrastructure & DevOps

Terraform • Docker • Kubernetes • k3s • GitHub Actions • Linux • Bash • Git • Ansible

### 🔐 DevSecOps & Security

Secret Scanning • Vulnerability Scanning • SAST • Container Security • Kubernetes Secrets • TLS • WAF • IAM • Security Hardening

### 📊 Observability

Prometheus • Grafana • Alertmanager • node-exporter • Custom Metrics

### 💻 Development

Python • JavaScript • TypeScript • PHP • SQL • Java • C++

### 🌐 Backend & Web

FastAPI • Flask • Node.js • Express.js • NestJS • Laravel • React • Vue • Astro

### 🗄️ Databases

PostgreSQL • SQL Server • MySQL • MongoDB • Supabase • Firebase

### 🤖 AI / Machine Learning

PyTorch • TensorFlow • Scikit-learn • Pandas • NumPy • Azure AI • LLM Integration • OCR Pipelines

---

## 🏅 Certifications

- **AWS Certified Cloud Practitioner** — Amazon Web Services, Sep 2026
- **AWS Certified AI Practitioner** — Amazon Web Services, Aug 2026
- **Microsoft Certified: Azure Fundamentals (AZ-900)** — Microsoft, Oct 2025
- **Oracle Cloud Infrastructure 2025 Certified Foundations Associate** — Oracle, Oct 2025
- **Data Engineer Associate** — DataCamp, Jan 2026

---

## 📚 Selected Technical Training

- **Google Cybersecurity Certificate** — Google
- **DevOps Essentials** — Google Cloud Skills Boost
- **CyberOps Associate** — Cisco Networking Academy
- **DevNet Associate** — Cisco Networking Academy
- **Enterprise Networking, Security, and Automation** — Cisco Networking Academy
- **Switching and Routing Essentials** — Cisco Networking Academy
- **Gremlin Enterprise Chaos Engineering Certification** — Gremlin
- **AWS Solutions Architecture Job Simulation** — Forage

<details>
<summary><strong>Additional Training</strong></summary>

<br>

- Google IT Support
- Data Analysis with Python — freeCodeCamp
- AWS AI Practitioner Challenge — Udacity
- Introduction to Cybersecurity — Cisco

</details>

---

## 📚 Current Learning Roadmap

```text
AWS Solutions Architecture
        ↓
Security Fundamentals
        ↓
Azure Administration
        ↓
Terraform / Infrastructure as Code
        ↓
Application Security
        ↓
Kubernetes Administration
        ↓
Cloud & Kubernetes Security
```

### Planned Certification Path

`AWS SAA` → `Security+` → `AZ-104` → `Terraform Associate` → `CKA`

With hands-on security learning through **TryHackMe** and continued DevSecOps project development.

---

## 🧭 Engineering Philosophy

I try to avoid treating a successful deployment as proof that I understand a system.

For every project, I aim to understand:

```text
Build
  ↓
Deploy
  ↓
Observe
  ↓
Break
  ↓
Troubleshoot
  ↓
Secure
  ↓
Validate
  ↓
Improve
```

I document failures, root causes, security decisions, tradeoffs, and validation steps because understanding **why something works or fails** is more valuable than simply making it run.

---

## 📌 Current Goals

* Transition into a **DevOps, DevSecOps, Cloud, or Cloud Security Engineering** role
* Earn AWS Solutions Architect Associate
* Deepen AWS and Azure infrastructure experience
* Strengthen Kubernetes and Terraform proficiency
* Build practical cloud and application security skills
* Develop production-oriented GitOps and software supply chain security experience
* Continue building projects that demonstrate real troubleshooting and engineering decisions

---

<div align="center">

### Building toward secure cloud-native infrastructure, one failure at a time.

</div>
