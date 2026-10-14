<div align="center">

```
┌─────────────────────────────────────────────────────────┐
│                                                         │
│   > whoami                                              │
│   Christopher Cortes-Sanchez                            │
│   NYU Tandon CS '26  |  Security+  |  Cyber & Math      │
│   Security Engineer  |  AppSec  |  DevSecOps  |  Cloud  │
│                                                         │
└─────────────────────────────────────────────────────────┘
```

[![Portfolio](https://img.shields.io/badge/Portfolio-000000?style=for-the-badge&logo=github&logoColor=00ff88)](https://chriscortessanchez.com/)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/christopher-cortes-sanchez/)
[![Email](https://img.shields.io/badge/Email-cc7825@nyu.edu-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:cc7825@nyu.edu)

</div>

---

## 🔐 Security Projects

### [SafeBuyr — Automated Security Scanner for a Live E-Commerce App](https://github.com/ChrisCortesSanchez/SafeBuyr)
An 8-phase automated scanner for a Flask/Docker e-commerce app. It proves each vulnerability is exploitable, fixes it, then verifies the fix held, covering SQL injection, XSS, CSRF, session management, input validation, and password storage. Risk score dropped from **37/100 to 2/100** across 6 OWASP Top 10 classes. All 6 checks run in **GitHub Actions**, so no deployment ships without clearing every test.

`Python` `Flask` `Docker` `GitHub Actions` `OWASP Top 10`

---

### [AWS Cloud Security Posture Management (CSPM) Tool](https://github.com/ChrisCortesSanchez/AWS-CSPM)
Checks **26 CIS Benchmark v1.5.0 controls** across AWS IAM, S3, CloudTrail, EC2, and password policy, then generates a prioritized HTML/JSON remediation report with a 0-100 risk score. It found 4 real gaps in a live account, including disabled audit logging. CI runs **36 moto-mocked tests** on every push, so no credentials ever touch the pipeline.

`Python` `AWS` `boto3` `CIS Benchmarks` `GitHub Actions` `moto`

---

### [Honeypot Threat Intelligence Pipeline](https://github.com/ChrisCortesSanchez/Honeypot-Threat-Intelligence-Pipeline)
Multi-sensor honeypot on DigitalOcean (Cowrie, Dionaea, Honeytrap) plus an analysis pipeline over **193,139 real attack events** from 6,713 unique IPs. It surfaced two active campaigns, a Solana credential-harvesting operation and a Mirai-variant botnet, catalogued 62,201 malware samples, and grouped attacker activity into 8 clusters in HTML and JSON reports.

`Python` `Elasticsearch` `DigitalOcean` `Threat Intelligence`

---

## 🌍 Software Engineering Capstone

### [Project SENS — Geographic Food Discovery App](https://github.com/ninal1811/project-sens)
Full-stack web app built by a team under professor oversight. Click a country for its national dish, drill into a state for the regional dish, then into a city for a local restaurant serving it. Flask/MongoDB backend, React/Vite frontend, CI/CD, and Docker.

**My role: I was responsible for the project's security, from writing the security goals in January 2026 through the backend auth layer.** What I built:

- Session-based authentication with bcrypt password hashing, email login, registration, and password updates, wired end to end between the React frontend and the Flask backend
- Authentication on the CRUD endpoints, plus role-based access control (user vs. developer) enforced by a custom decorator that accepts either a session cookie or an API key header
- A developer-only log viewer restricted to an allowlist of specific log files, with compressed logs excluded and API-key auth in front of it
- Secrets moved out of source into environment variables, `Secure` session cookies, and a credentialed CORS configuration for the cross-origin frontend

[Backend](https://github.com/ninal1811/project-sens) · [Frontend](https://github.com/ninal1811/project-sens-frontend)

`Python` `Flask` `MongoDB` `React` `Vite` `REST APIs` `CI/CD` `Docker`

---

## 🛠️ Tech Stack

**Languages**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=flat-square&logo=cplusplus&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![Bash](https://img.shields.io/badge/Bash-4EAA25?style=flat-square&logo=gnubash&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=mysql&logoColor=white)

**Security Tools**

![Burp Suite](https://img.shields.io/badge/Burp_Suite-FF6633?style=flat-square&logo=portswigger&logoColor=white)
![Wireshark](https://img.shields.io/badge/Wireshark-1679A7?style=flat-square&logo=wireshark&logoColor=white)
![Nmap](https://img.shields.io/badge/Nmap-0E83CD?style=flat-square&logo=nmap&logoColor=white)
![Splunk](https://img.shields.io/badge/Splunk-000000?style=flat-square&logo=splunk&logoColor=white)
![Elasticsearch](https://img.shields.io/badge/Elasticsearch-005571?style=flat-square&logo=elasticsearch&logoColor=white)

**Cloud & Infrastructure**

![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonaws&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)

**Frameworks**

![Flask](https://img.shields.io/badge/Flask-000000?style=flat-square&logo=flask&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white)

---

## 📚 Currently

- 🎓 BS in Computer Science, NYU Tandon (May 2026), CompTIA Security+ (June 2026)
- 🔧 Expanding SafeBuyr with Trivy and Semgrep scanning in CI, plus Kubernetes deployment
- 🏁 CTFs: SHPE 2025 National Cybersecurity Challenge (8th place), Buckeye CTF
- 🔍 Looking for **Application Security**, **DevSecOps**, and **Cloud Security Engineer** roles in NYC or remote

---

<div align="center">
<sub>Built with curiosity. Secured with intent.</sub>
</div>
