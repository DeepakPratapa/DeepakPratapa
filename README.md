<div align="center">

# 👋 Deepak Balaji Pratapa

### Full-Stack Engineer • Cloud Architect • Security Researcher

*Building production systems across blockchain, cloud, and distributed architectures*

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/deepak-pratapa-b6316b178)
[![Email](https://img.shields.io/badge/Email-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:deepakpratapa2@gmail.com)
[![Portfolio](https://img.shields.io/badge/Portfolio-FF5722?style=flat-square&logo=google-chrome&logoColor=white)](https://deepakpratapa.com)

</div>

---

## 🔧 What I Build

I architect **production-ready systems** that solve real problems—from decentralized escrow platforms to serverless cloud infrastructure. My work spans blockchain smart contracts, microservices backends, cloud-native applications, and cybersecurity research.

**Current focus:**
- Microservices architectures with real-time communication
- Smart contract development and blockchain integration
- Cloud-native serverless platforms (AWS, Firebase)
- Security tooling and penetration testing automation

---

## 🚀 Featured Projects

### [PayChain](https://github.com/DeepakPratapa/paychain) - Blockchain Escrow Platform
**5-microservice architecture | Smart contracts | Real-time WebSockets**

A production-grade freelance escrow system eliminating payment disputes through blockchain automation.

- **Backend:** 5 independent FastAPI services (User, Job, Payment, Gateway, WebSocket)
- **Smart Contracts:** Solidity 0.8.20 with dual refund logic (instant cancel vs. deadline expiry)
- **Auth:** JWT + Redis blacklist + MetaMask signature verification (no passwords stored)
- **Real-time:** WebSocket events trigger React Query cache invalidation for instant UI updates
- **Stack:** React 18, FastAPI, PostgreSQL, Redis, Hardhat, Docker Compose

**Key innovation:** Centralized auth guard shared across all microservices with 6-layer security validation.

---

### [Blockchain-Verified Portfolio](https://github.com/DeepakPratapa/personal-portfolio-blockchain)
**Cryptographic integrity | Automated verification | Polygon deployment**

A portfolio application with **on-chain code verification**—proving deployed code matches source through SHA-256 hashing.

- **Two-layer blockchain:** Portfolio data + cryptographic hash storage on Polygon
- **Verification pipeline:** Pre-deployment security checks, reproducible builds, Git integrity validation
- **Public auditability:** Anyone can verify the deployed app against source code
- **Stack:** Solidity, Hardhat, React, Vite, Tailwind CSS, ethers.js

**Key innovation:** Automated codebase verification system with deterministic build validation.

---

### [Serverless Image Processor](https://github.com/DeepakPratapa/serverless-img-proc-aws)
**AWS Lambda | S3 event triggers | CloudFormation IaC**

Auto-scaling image processing platform handling concurrent uploads without server management.

- **Serverless pipeline:** S3 upload → Lambda trigger → automated processing → output bucket
- **CI/CD:** GitHub Actions + CloudFormation for automated deployment
- **Monitoring:** CloudWatch metrics and logging for performance tracking
- **Stack:** AWS Lambda, S3, API Gateway, Amplify, React, CloudFormation

**Key innovation:** Infrastructure-as-Code approach with reproducible, version-controlled AWS resources.

---

### [Firebase Task Manager](https://github.com/DeepakPratapa/serverless-task-manager-firebase)
**Real-time sync | Cloud Functions | Automated notifications**

Collaborative task management with live data synchronization and smart notifications.

- **Real-time database:** Firestore with instant cross-client updates
- **Automation:** Cloud Functions trigger email reminders on task deadlines
- **Auth:** Firebase Auth with social logins and secure access control
- **Stack:** React, Firebase (Firestore, Auth, Cloud Functions, Hosting)

**Key innovation:** Event-driven notifications improving task completion rates through automated engagement.

---

## 🛠️ Tech Stack

**Languages:** JavaScript/TypeScript • Python • Solidity • Go • C++ • Bash  
**Frontend:** React • Vite • Tailwind CSS • TanStack Query • WebSockets  
**Backend:** Node.js • FastAPI • Django • Flask • .NET  
**Blockchain:** Ethereum • Polygon • Hardhat • Truffle • Web3.js • Ethers.js  
**Databases:** PostgreSQL • MongoDB • Redis • MySQL • Firestore  
**Cloud:** AWS (Lambda, S3, API Gateway, CloudFormation) • Firebase • GCP  
**DevOps:** Docker • GitHub Actions • CI/CD • Git  
**Security:** Wireshark • Nmap • Metasploit • Burp Suite • Kali Linux • Suricata

---

## 📊 GitHub Activity

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=DeepakPratapa&show_icons=true&theme=tokyonight&hide_border=true&bg_color=0d1117&title_color=58a6ff&icon_color=1f6feb&text_color=c9d1d9&count_private=true" width="49%" />
<img src="https://github-readme-streak-stats.herokuapp.com/?user=DeepakPratapa&theme=tokyonight&hide_border=true&background=0d1117&ring=58a6ff&fire=1f6feb&currStreakLabel=c9d1d9" width="49%" />

<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=DeepakPratapa&layout=compact&theme=tokyonight&hide_border=true&bg_color=0d1117&title_color=58a6ff&text_color=c9d1d9&langs_count=8" width="49%" />

</div>

---

## 🎓 Background

**MS Computer Science** @ University of Central Oklahoma (3.72 GPA) • 2023-2025  
**B.Tech Computer Science (Information Security)** @ VIT (7.94 GPA) • 2019-2023  
**President's Honor Roll** - Fall 2023

**Current Role:**  
🧑‍🏫 **Graduate Teaching Assistant** @ UCO - Leading penetration testing labs, mentoring 30+ students in secure coding and network security

**Previously:**  
💼 **Application Developer Intern** @ Precistat IT Solutions - Automated Python workflows with cryptographic protection, reducing manual time by 30%  
🔬 **Graduate Research Assistant** @ UCO - Built Django app with HTTPS, engineered OPNsense/Suricata monitoring system, simulated IEEE 2030.5 smart grid protocols

---

## 📝 Research & Publications

**[Secure Data Encryption for ATM Transactions](https://www.irjet.net/archives/V9/i9/IRJET-V9I9127.pdf)**  
*International Research Journal of Engineering and Technology (IRJET) • September 2022*

- Proposed advanced encryption scheme for ATM security
- Developed Python prototype using Hash + RSA algorithms
- Validated improved resistance to MITM and reconnaissance attacks

---

## 🏆 Certifications

- **Cyber Operations** - University of Central Oklahoma (Dec 2024)
- **Incident Analysis and Response** - University of Central Oklahoma (May 2024)
- **JavaScript for Front-End Web** - University of Central Oklahoma (Dec 2023)
- **Web Application Technologies and Django** - University of Michigan/Coursera (Mar 2022)

---

## 💡 What Drives Me

I believe in building **systems that scale, code that's secure, and architectures that are elegant**. Whether it's designing microservices that communicate in real-time, writing smart contracts that enforce fairness, or deploying serverless infrastructure that handles unpredictable load—I focus on **production-ready solutions** that solve real problems.

**Core principles:**
- Security isn't optional—it's architectural
- Documentation is as important as implementation
- Automated testing catches what code reviews miss
- Monitoring tells you what really happens in production

---

## 🔬 Currently Exploring

- Zero-knowledge proofs for privacy-preserving systems
- Layer 2 scaling solutions and gas optimization patterns
- Post-quantum cryptography and future-proof security
- Kubernetes orchestration for microservices at scale

---

## 📫 Let's Connect

Open to discussing **full-stack development, blockchain architecture, cloud infrastructure, and security engineering**.

**Email:** deepakpratapa2@gmail.com  
**LinkedIn:** [linkedin.com/in/deepak-pratapa-b6316b178](https://www.linkedin.com/in/deepak-pratapa-b6316b178)  
**Portfolio:** [deepakpratapa.com](https://deepakpratapa.com)

---

<div align="center">

![Profile Views](https://komarev.com/ghpvc/?username=DeepakPratapa&color=58a6ff&style=flat-square&label=Profile+Views)

*Building systems where reliability is engineered, not assumed.*

</div>
