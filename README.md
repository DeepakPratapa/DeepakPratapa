<div align="center">

# Hey, I'm Deepak 👋

**Full-Stack Engineer building distributed systems**

Microservices • Blockchain • Cloud • Security

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin)](https://www.linkedin.com/in/deepak-pratapa-b6316b178)
[![Portfolio](https://img.shields.io/badge/Portfolio-FF5722?style=flat-square&logo=google-chrome)](https://deepakpratapa.com)
[![Email](https://img.shields.io/badge/Email-deepakpratapa2@gmail.com-EA4335?style=flat-square&logo=gmail)](mailto:deepakpratapa2@gmail.com)

</div>

---

## 🚀 Featured Projects

### [PayChain](https://github.com/DeepakPratapa/paychain) - Blockchain Escrow Platform
**Microservices • Smart Contracts • Real-time WebSockets**

Freelance escrow system with 5 independent FastAPI services and Solidity contracts. Login with your wallet, create jobs, blockchain releases payment automatically.

- **Stack:** React, FastAPI, PostgreSQL, Redis, Solidity, Docker
- **Features:** MetaMask auth (no passwords), WebSocket real-time updates, dual refund logic
- **Try it:** `docker-compose up` → Full stack running

<details>
<summary>View Architecture</summary>

```
┌─────────────┐    ┌─────────────┐    ┌──────────────┐
│ User Service│───▶│ Job Service │───▶│Payment Service│
│  (JWT Auth) │    │  (CRUD API) │    │  (Blockchain) │
└─────────────┘    └─────────────┘    └──────────────┘
       │                  │                    │
       └──────────────────┼────────────────────┘
                          ▼
                 ┌─────────────────┐
                 │ WebSocket Server│
                 │ (Real-time Push)│
                 └─────────────────┘
```

</details>

---

### [Blockchain Portfolio](https://github.com/DeepakPratapa/personal-portfolio-blockchain)
**Cryptographic Verification • Polygon • Automated CI/CD**

Portfolio with on-chain verification. Every file gets a SHA-256 hash stored on Polygon—anyone can verify deployed code matches source.

- **Stack:** Solidity, Hardhat, React, Vite, Tailwind
- **Features:** Pre-deployment security scan, reproducible builds, public auditability
- **Verify:** `npm run verify:codebase` → Check integrity

---

### [AWS Serverless Image Processor](https://github.com/DeepakPratapa/serverless-img-proc-aws)
**Lambda • S3 • CloudFormation IaC**

Auto-scaling image processing. Upload triggers Lambda, processes image, outputs to S3. Zero server management.

- **Stack:** AWS Lambda (Python), S3, API Gateway, CloudFormation
- **Pipeline:** GitHub Actions → CloudFormation → Auto-deploy
- **Infrastructure:** 100% code (CloudFormation YAML)

---

### [Firebase Task Manager](https://github.com/DeepakPratapa/serverless-task-manager-firebase)
**Real-time Sync • Cloud Functions • Automated Emails**

Collaborative task app with live updates. Cloud Functions send deadline reminders automatically.

- **Stack:** React, Firestore, Firebase Auth, Cloud Functions
- **Real-time:** Changes sync instantly across all clients
- **Automation:** Event-driven email notifications

---

## 🛠️ Tech Stack

**Languages**  
JavaScript/TypeScript • Python • Solidity • Go • C++

**Frontend**  
React • TanStack Query • Tailwind CSS • Vite

**Backend**  
Node.js • FastAPI • Django • Flask

**Blockchain**  
Solidity • Hardhat • Ethers.js • Web3.py • Polygon

**Databases**  
PostgreSQL • MongoDB • Redis • Firestore

**Cloud & DevOps**  
AWS (Lambda, S3, CloudFormation) • Firebase • Docker • GitHub Actions

**Security**  
Metasploit • Wireshark • Burp Suite • Nmap • Kali Linux

---

## 📊 GitHub Stats

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=DeepakPratapa&show_icons=true&theme=dark&hide_border=true&bg_color=0d1117&title_color=58a6ff&icon_color=1f6feb&text_color=c9d1d9" width="48%" />
<img src="https://github-readme-streak-stats.herokuapp.com/?user=DeepakPratapa&theme=dark&hide_border=true&background=0d1117&ring=58a6ff&fire=ff6e96&currStreakLabel=c9d1d9" width="48%" />

<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=DeepakPratapa&layout=compact&theme=dark&hide_border=true&bg_color=0d1117&title_color=58a6ff&text_color=c9d1d9&langs_count=8" width="48%" />

</div>

---

## 💼 What I'm Doing

**Teaching Assistant @ UCO** (Jan 2025 - Present)  
Leading pen-testing labs, mentoring 30+ students in secure coding and network security.

**Previously:**
- **Research Assistant @ UCO** - Built Django HTTPS app, engineered network monitoring with OPNsense/Suricata
- **Developer Intern @ Precistat** - Automated Python workflows (30% time reduction), cryptographic data protection

**Published Research:**  
[Secure Data Encryption for ATM Transactions](https://www.irjet.net/archives/V9/i9/IRJET-V9I9127.pdf) - IRJET, 2022

---

## 🎯 Philosophy

```js
while (learning) {
  build();
  test();
  break();
  fix();
  deploy();
}
```

> Security is architecture, not an afterthought  
> Monitoring > Hoping  
> Code that works in production > Code that works on my machine

---

## 📫 Connect

Open to discussing **full-stack development, microservices architecture, blockchain engineering, and cloud infrastructure**.

- **Portfolio:** [deepakpratapa.com](https://deepakpratapa.com)
- **Email:** deepakpratapa2@gmail.com
- **LinkedIn:** [deepak-pratapa](https://www.linkedin.com/in/deepak-pratapa-b6316b178)

---

<div align="center">

![visitors](https://komarev.com/ghpvc/?username=DeepakPratapa&color=58a6ff&style=flat-square)

</div>
