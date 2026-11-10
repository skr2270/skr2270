# Hi there, I'm Sai Kumar Rayavarapu 👋

<div align="center">

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/sai-kumar-rayavarapu-167a6a2b0)
[![GitHub](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/skr2270)
[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:sk.r.2270@gmail.com)
[![Portfolio / Projects](https://img.shields.io/badge/Architecture-Portfolio-blueviolet?style=for-the-badge&logo=codeforces&logoColor=white)](#-flagship-projects)

**Lead Full-Stack Architect & Founding Engineer**  
Specializing in Distributed Microservices, Domain-Driven GraphQL Platforms, Headless Mobile Commerce, Document Intelligence & Cloud Systems.

</div>

---

### 👨‍💻 About Me

I am a **Lead Full-Stack Architect and Founding Engineer** with over 5 years of hands-on expertise delivering end-to-end digital ecosystems—spanning research, system design, distributed microservices, cross-platform mobile apps, cloud DevOps, and enterprise cybersecurity.

- 🎓 **Postgraduate Studies:** Currently pursuing **Master of Science (M.S.) in Computer Science** at **Scaler Neovarsity / Woolf** (Licensed Higher Education Institution in Europe, accredited by MFHEA / European Qualifications Framework).
- 💼 **Current Role:** Technical leadership at **Gig Jobs India Private Limited**, architecting an Nx monorepo of 9 NestJS microservices, gRPC inter-service communication, Next.js 16 portals, React Native mobile apps, and AWS FinOps optimization.
- 🏢 **Digital Transformation & Operations:** Served as Fractional CTO for multi-store retail brands (**The Horizon Collections**), leading headless commerce on Google Cloud Run, multi-vendor integrations (Zoho POS, Razorpay, PhonePe, Shiprocket, Breeze), and retail staff training.
- 🛡️ **Cybersecurity Foundation:** Former Cybersecurity Analyst (VAPT, Network Security, Digital Forensics & Incident Response) with an innate security-first approach to software design, authorization guards, and DPDPA 2023 compliance.
- ⚡ **AI-Augmented Velocity:** Utilizing AI development workflows across research, architecture, implementation, security auditing, and deployment.
- 📍 **Location:** Visakhapatnam, Andhra Pradesh, India.

---

### 🚀 Flagship Architectural Projects

#### 1. [Gig Jobs India (GJI)](https://github.com/skr2270)
*High-Throughput Gig Workforce & Marketplace Infrastructure*
- **Full-Stack Ecosystem:** 9 NestJS microservices in an Nx Monorepo (`gateway`, `auth`, `user`, `job`, `chat`, `notification`, `file`, `request`, `lookup`), Next.js 16 SSR web portal (`gji-portal`), static Next.js 16 operations console (`gji-admin`), and React Native `0.82.1` mobile client (`gji-mobile`).
- **Inter-Service gRPC, Queues & Observability:** Internal **gRPC (`Port 50051`)** RPCs (`CreditWallet`, `DebitWallet`), **BullMQ** + Bull Board queues, **Socket.IO Redis Adapter**, and **NestJS Observe** distributed tracing & flamegraphs.
- **AWS FinOps & Security:** Decommissioned unused Amazon MQ brokers to cut backend AWS costs by **64.5% (~$95/month)**, remediated 4 critical (P0) security vulnerabilities, fixed wallet payout ledger math, and deployed on **AWS EC2 (PM2 + Nginx SSL)**, **Amazon RDS PostgreSQL**, **ElastiCache Redis**, and **Netlify**.

#### 2. [The Horizon Collections (HC)](https://github.com/skr2270)
*Headless Mobile Commerce & Multi-Store Retail Digital Transformation*
- **Mobile & Security:** React Native / **Expo SDK 58 CNG** (`com.thehorizoncollections.app`) with Hermes, **21 Jest test suites (183 tests)**, ProGuard/R8, Android Keystore, **Expo Observe** telemetry, and **EAS Build / Update OTA**.
- **Cloud Run BFF & Integrations:** Containerized **Node.js 22 LTS Fastify BFF** on **Google Cloud Run (`asia-south1`)** with **Google Cloud Pub/Sub**, **Secret Manager**, **FCM HTTP v1**, dynamic multi-provider checkout (**Breeze / super.money, Razorpay Magic, GoKwik**), plus Zoho POS, PhonePe, Shiprocket, MyOperator, Bitespeed, and Linkfliq (Hey Pipr).
- **Business Operations:** Scaled digital operations across 4 physical retail stores (Visakhapatnam & Hyderabad), configured Google Merchant Center profiles, and trained store staff.

#### 3. [PDF Consolidator](https://github.com/skr2270)
*Enterprise Document Intelligence, Multi-ERP Parsing & Statutory Logistics Engine*
- **Core Engine:** Python 3.10+ document layout analyzer and **ReportLab** PDF generation engine built for The Horizon Collections, enforcing statutory **GST Rule 55** compliance with Indian currency words (`Crores/Lakhs/Paise`).
- **Parsing & Logistics:** Multi-ERP parsers (**Zoho POS/Inventory, Tally, Spatial**), circular ingestion guards, 3-tuple SKU consolidation `(SKU, Cost Price, HSN)`, fleet vehicle manifests, and 3-tab Excel (`.xlsx`) warehouse audit checklists.

#### 4. [Rate My Employee (RME)](https://github.com/skr2270)
*Enterprise Workforce Governance, Verification & Rating Ecosystem*
- **Architecture:** Domain-driven **NestJS v11** modular backend (**21 domain feature modules**), **Apollo Server v4 GraphQL**, **PostgreSQL 16 + PostGIS** (27 schema migrations), and **Next.js 15** App Router admin portal.
- **Mobile & Publishing:** **49-screen React Native (`v2.1.6`)** app published to **Google Play Store** (Android 15 16 KB ELF page alignment) and **Apple App Store** (Guideline 5.1.1(v)); automated DigiLocker Aadhaar KYC, GSTIN verification, deployed on **Ubuntu 24.04 LTS (`PM2` + `Nginx TLS 1.3`)**.

#### 5. [FluxRush & FluxRush Mobile](https://github.com/skr2270)
*Ultra-Low Latency Real-Time Finger-Tracking Arcade Game & CV Engine*
- **Threading Pipeline:** Decoupled dual-loop architecture running **MediaPipe** Hand Landmarker inference inside background Web Workers (20–30 FPS) while rendering at 60–120 FPS (<50ms input latency).
- **Signal Processing & Mobile Engine:** Adaptive 1Euro filter, kinematic dead-reckoning predictor, $O(1)$ spatial hash grid, **React Native Skia** C++ GPU rendering, **React Native Vision Camera**, zero-GC ring buffer, and procedural WebAudio synthesis.

#### 6. [Code My Resume (CMR)](https://github.com/skr2270/CodeMyResume)
*Automated Codebase Scanner, ATS Resume & Profile Generator*
- **Architecture:** Scan-first developer intelligence CLI (`src/cmr/`) that discovers all `*.md` files, detects structural topology (microservices vs. modular monolith), parses infra/git telemetry, and compiles a Single-Source `ResumeAST` into PDF, HTML, Markdown, and GitHub READMEs.

#### 7. [UWA 3D Experience](https://github.com/skr2270)
*Immersive Scroll-Driven WebGL 3D Cinematic Journey*
- **Visuals:** Three.js, React Three Fiber, Drei, and GLSL shaders illustrating a 5-Act "Source to Sip" narrative with dynamic liquid fill shaders, physical refraction, interactive SKU visualizers, and BIS/FSSAI regulatory showcases.

#### 8. [Kiki Photography](https://github.com/skr2270)
*Luxury Editorial Cinematography Brand Experience*
- **Creative Tech:** Built with **Vite, Modern Vanilla JS, Vanilla CSS, HTML5 Canvas 2D Engine, GSAP ScrollTrigger, Lenis, and Web Audio API**—featuring a Dual Aperture Engine (35mm vs. 85mm) with synthesized mechanical shutter acoustics, 2.5x gemstone macro loupe, 3D magazine spread physics, and 120fps video scrubber SMPTE console.

---

### 🛠️ Technical Stack & Skills

```
┌──────────────────────────┬──────────────────────────────────────────────────────────────────┐
│ Domain                   │ Technologies & Frameworks                                        │
├──────────────────────────┼──────────────────────────────────────────────────────────────────┤
│ Languages                │ TypeScript, JavaScript (ESNext), Python 3, SQL, PHP              │
│ Full-Stack & 3D Web      │ Next.js 16/15 (React 19), React 18, Three.js, React Three Fiber, │
│                          │ Tailwind CSS, GSAP, Lenis, HTML5 Canvas 2D, Web Audio API        │
│ Mobile Engineering       │ React Native (0.82–0.87, Expo SDK 58 CNG & Bare), Shopify Skia,  │
│                          │ Vision Camera, EAS Build/OTA, ProGuard/R8, Android Keystore      │
│ Backend & Distributed    │ NestJS v11 (Nx Monorepo & Modular Design), gRPC, Apollo GraphQL, │
│                          │ BullMQ, Fastify, Express, Socket.IO Redis Adapter, NestJS Observe│
│ Databases & Caching      │ PostgreSQL 16, PostGIS, Amazon RDS, Redis (ElastiCache), MongoDB,│
│                          │ TypeORM, MySQL, SQLite                                           │
│ Cloud, DevOps & Deploy   │ AWS (EC2, RDS, S3, ElastiCache), Google Cloud (Cloud Run,        │
│                          │ Pub/Sub, Secret Manager, FCM v1), Docker, Nginx TLS, PM2, Netlify│
│ Security & Compliance    │ VAPT (Burp Suite, Nessus, Nmap, OWASP ZAP), DigiLocker KYC,      │
│                          │ DPDPA 2023, GST Rule 55, OAuth 2.0 PKCE, JWT/Passport, Forensics │
│ Business Integrations    │ Zoho POS/Inventory, PhonePe, Razorpay, Shiprocket, Breeze        │
│                          │ (super.money), MyOperator, Bitespeed, Google Merchant Center     │
└──────────────────────────┴──────────────────────────────────────────────────────────────────┘
```

---

### 🎓 Education

- **Master of Science (M.S.) in Computer Science**  
  *Scaler Neovarsity / Woolf* (Licensed European Higher Education Institution, accredited by MFHEA / ECTS)  
  *Duration:* 2024 – Present (Expected: 2026 / 2027)  
  *Specialization: Advanced Distributed Systems, Scalable Cloud Architecture, Machine Learning, System Design*
- **Bachelor of Technology (B.Tech) in Computer Science & Engineering**  
  *Viswanadha Institute of Technology and Management (JNTUK)* | August 2015 – April 2022

---

### 📬 Let's Connect

- **Email:** [sk.r.2270@gmail.com](mailto:sk.r.2270@gmail.com)
- **LinkedIn:** [linkedin.com/in/sai-kumar-rayavarapu-167a6a2b0](https://www.linkedin.com/in/sai-kumar-rayavarapu-167a6a2b0)
- **GitHub:** [@skr2270](https://github.com/skr2270)
- **Location:** Visakhapatnam, India
