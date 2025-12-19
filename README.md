<h1 align="center">Hi, I'm Mark 👋</h1>

<p align="center">
  <a href="https://www.markdeguzman.com">Portfolio</a> ·
  <a href="https://www.linkedin.com/in/mark-p7">LinkedIn</a> ·
  <a href="mailto:markdeguzman204@gmail.com">Email</a>
</p>

---

## 🧠 What I like building

- End-to-end **security tools** – supply chain attack detection, encrypted traffic monitoring, malware scanning.
- **ML-powered developer tooling** – graph neural networks over package ecosystems, intelligent document parsing.
- **Full-stack products** – TypeScript/React/Next.js frontends backed by robust APIs in Node.js or C#/.NET.
- Systems that turn manual, error-prone workflows into **repeatable pipelines with tests, metrics, and docs**.

I’m currently finishing my BSc in Computer Science at the **British Columbia Institute of Technology (BCIT)** and actively working on security + ML heavy projects, alongside real-world web apps.

---

## 🚀 Featured projects

### Sentinel – GNN Supply Chain Attack Detection (npm)
**Repo:** [GNN-Supply-Chain-Attack-Detection](https://github.com/mark-p7/GNN-Supply-Chain-Attack-Detection)

Graph-neural-network-based tooling to detect suspicious packages and dependencies in the **npm** ecosystem.

- Builds a **dependency graph** over npm packages and release metadata, then uses a GNN to flag anomalous nodes.
- Pipeline in **Python** with **Neo4j** (graph store), **PyTorch Geometric** (GNN), and **ONNX** (for portable inference).
- Targets patterns like **supply-chain attacks**: sudden maintainer changes, typosquats, unusual fan-out/fan-in, and odd versioning behaviour.

---

### CoDefend – Chrome Extension for Decentralized Malware Analysis
**Repo:** [CoDefend](https://github.com/mark-p7/CoDefend)

A security-first Chrome extension that scans downloads **before they hit disk**.

- Intercepts browser downloads and forwards files/URLs to a **Node.js backend** for scanning with multiple AV and reputation engines.
- Designed to **decentralize malware analysis**: the extension stays lightweight while the backend fans out to external scanners.
- Built with **JavaScript/TypeScript, Node, Express**, and REST APIs, with a strong focus on user safety and clear risk reporting.

---

### HarbourFile – Real Estate Document Intelligence (WIP)

Early-stage B2B SaaS aimed at **property managers, landlords, and regulators**.

- Extracts structured data from leases, invoices, compliance forms, and scanned PDFs using **OCR + LLMs**.
- Uses tools like **Surya-OCR**, **Azure Document Intelligence**, and a **vector database (e.g., Qdrant)** for semantic search over documents.
- Focused on real-world pain points: compliance checks, expiry tracking, and reducing the time required to find critical clauses.

---

### Mellow – Mental Health Journaling Web App  
**Repo:** [Melloww](https://github.com/mark-p7/Melloww)

A mobile-first **mental health journaling + social** platform built with a small team.

- Led both design and development in a semi-agile process; guided junior teammates through bugs, PRs, and reviews.
- Features journaling, mood tracking, and community-style interactions.
- Stack: **TypeScript, Next.js, Tailwind CSS, shadcn/ui, Node.js, Express, MongoDB**.

---

### EngineerIn.tech – “Tinder for Engineers”  
**Repo:** [EngineerInTech](https://github.com/mark-p7/EngineerInTech)

A platform for engineers to meet by **teaching each other skills** instead of swiping on job posts.

- Full-stack TypeScript project with a separate `client` and `server` codebase.
- Matching flow focuses on **skills you’d like to teach** and **skills you’d like to learn**.
- Stack: TypeScript SPA client + Node backend; deployed at **engineerin.tech**.

---

### NoteTed – SSR Note-Taking App  
**Repo:** [NoteTed](https://github.com/mark-p7/NoteTed)

Fast note-taking app with **Next.js SSR** and Firebase.

- Users can register/login and create notes that sync across devices.
- Achieves instant load times via **server-side rendering** and efficient data fetching.
- Stack: **Next.js, React, MUI, Firebase Auth, Firebase Firestore**.

---

## 🧰 Tech I use a lot

**Languages**  
TypeScript · C# · Python · JavaScript · C/C++ · Java · SQL

**Backend**  
Node.js · Express · FastAPI · .NET · REST APIs · WebSockets

**Frontend & Mobile**  
React · Next.js (App Router) · React Native · Tailwind CSS · shadcn/ui · MUI

**Data, ML & Storage**  
PyTorch Geometric · XGBoost · Neo4j · SQL Server · MongoDB · Firebase (Auth/Firestore) · Vector DBs (Qdrant)

**DevOps & Tooling**  
Docker · GitHub Actions · Azure DevOps · Vercel · Cloudflare · npm/yarn/pnpm · Jest · React Testing Library · pytest

---

## 📌 A few other things I've built

- **EventPrompt** – Discord bot for timed reminders using **Discord.js, Express, Firebase Firestore**.
- **Anonymous Confession App** – Android app with **Firebase Auth** + **Cloud Firestore** and privacy-preserving login.
- **UBC Solar Website** – Mobile-first React site for the UBC Solar team, built with **HTML, CSS, JavaScript, React**.

---

## 👀 What I’m looking for

I’m excited about roles where I can:

- Work close to **security, ML, or developer tooling**.
- Own features end-to-end – from design docs and data pipelines to tests, dashboards, and production readiness.
- Collaborate with strong engineers who care about **code quality, observability, and long-term maintainability**.

If you’re building something in this space and need someone who loves **TypeScript, C#/.NET, Python, ML, and security**, I’d love to chat.
