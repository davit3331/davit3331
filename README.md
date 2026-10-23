# 👋 Hi, I am Davit!

🎓 Computer Science student at York University
🤖 Machine Learning Research Assistant focused on reliable AI for high-stakes applications
🧠 Interested in machine learning, data engineering, backend systems, and applied AI
🚀 I enjoy turning raw, messy data into reproducible models and real-world products

---

## 💻 Tech Stack

### Languages
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=postgresql&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![C](https://img.shields.io/badge/C-00599C?style=for-the-badge&logo=c&logoColor=white)

### Machine Learning & Data
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white)
![XGBoost](https://img.shields.io/badge/XGBoost-189FDD?style=for-the-badge&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-11557C?style=for-the-badge&logoColor=white)

### Backend, Databases & Tools
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![Prisma](https://img.shields.io/badge/Prisma-2D3748?style=for-the-badge&logo=prisma&logoColor=white)
![NestJS](https://img.shields.io/badge/NestJS-E0234E?style=for-the-badge&logo=nestjs&logoColor=white)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)

---

## 🔬 Research: Sepsis Prediction from ICU Data

Research Assistant at York University's Lassonde School of Engineering (ARISEN-Shock Project)

- Building preprocessing pipelines for ICU time-series datasets containing more than **40,000 patient records**
- Developing and evaluating models with **XGBoost, Random Forest, and PyTorch**
- Built a **KA-Transformer** that recovered 10 previously excluded clinical features and improved AUROC from **0.78 to 0.85**
- Fixed four evaluation flaws (normalization leakage, non-functional class weighting, unseeded training, and test-set threshold tuning) to establish the project's **first reproducible baseline**
- Built a two-agent system (ML predictor + LLM explainer) and limited the LLM to explanation-only after measuring that its overrides reduced F1 from **0.82 to 0.68**

📂 **Code:** [septic-shock-research](https://github.com/davit3331/septic-shock-research)

---

## 🛠️ Featured Project

### ReconSila: Bordereaux Reconciliation Platform

A multi-tenant SaaS platform for Canadian insurance brokerages. I am the founder and sole developer, and the first customer is **live in production**.

- Designed a **26-model PostgreSQL schema** with JWT-scoped tenant isolation
- Built an **LLM-powered ingestion pipeline** (Claude API) that turns scanned bordereaux into structured data, unified with CSV/XLSX parsing through a per-organization mapping layer, with concurrency-limited queuing and per-call cost metering
- Built a **migration engine** that onboards a brokerage's full policy history, where one classification function drives both the dry-run preview and the commit, with round-scoped rollback
- Maintains **1,350 passing tests**, including characterization tests and mutation probes that prove the tests fail when behaviour changes
- Tracked down and fixed **two production race conditions** using atomic conditional database updates

**Stack:** TypeScript, NestJS, Next.js, Prisma, PostgreSQL, Docker, Claude API

🔒 **Private repository:** ReconSila is my company, so the source is private. I am happy to walk through the architecture, testing approach, and code in an interview.

---

## 📱 Also Building

### Offline-First Cross-Platform Mobile App (Work in Progress)

A Flutter app with no backend or hosting, built with a small team. All content is bundled and searchable on the device.

- Architected the app in Flutter/Dart (28K lines, 120 automated tests), with unified search over 4,000+ documents and a verse-mapping schema that reconciles two incompatible numbering systems
- Built a Python OCR pipeline for 540 scanned pages: two independent LLM transcriptions diffed word by word (1–7% disagreement), flagged spans routed to human review, and unverified data excluded from release builds
- Led the team using interfaces that let each developer build and test in parallel; implemented a reading-plan generator that splits chapters evenly across user-chosen days

**Stack:** Flutter, Dart, Python

---

## 📫 Connect With Me

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](YOUR_LINKEDIN_URL)
[![Email](https://img.shields.io/badge/Email-davit.piruzyan%40gmail.com-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:davit.piruzyan@gmail.com)
