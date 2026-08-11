<h1 align="center">Hi, I'm Vipul Pandey </h1>

<p align="center">
  <b>Backend & Distributed Systems Engineer</b> · GSoC '26 @ Learning Unlimited · IIITM Gwalior '28
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/21vip/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"></a>
  <a href="mailto:vipulpandey7917@gmail.com"><img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"></a>
</p>

---

### About Me

I build backend systems that stay correct under load — distributed query engines, fault-tolerant schedulers, and the regression suites that keep them honest. Currently a **Google Summer of Code 2026 contributor at Learning Unlimited**, working on Django test infrastructure for a platform used by educational programs worldwide.

-  Building **[QueryForge](https://github.com/vipulpandey21/QueryForge)** — a distributed parallel SQL engine (gRPC, MapReduce-style aggregation, 1.7× speedup on 2M+ rows)
-  Deep-diving into **distributed systems, observability, and query optimization**
-  Open source contributor at **Learning Unlimited**, **Open Health Care Network**, and **CNCF (Krkn Chaos)**
-  **LeetCode Knight** (1881, top 5.44%) · **Codeforces Specialist** (1517) · 500+ DSA problems
-  Reach me at **vipulpandey7917@gmail.com**

---

### Tech Stack

**Languages**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Java](https://img.shields.io/badge/Java-007396?style=flat-square&logo=openjdk&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![C++](https://img.shields.io/badge/C++-00599C?style=flat-square&logo=cplusplus&logoColor=white)
![C](https://img.shields.io/badge/C-A8B9CC?style=flat-square&logo=c&logoColor=black)

**Backend & Distributed Systems**

![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white)
![Express](https://img.shields.io/badge/Express-000000?style=flat-square&logo=express&logoColor=white)
![Django](https://img.shields.io/badge/Django-092E20?style=flat-square&logo=django&logoColor=white)
![gRPC](https://img.shields.io/badge/gRPC-244c5a?style=flat-square&logo=google&logoColor=white)
![GraphQL](https://img.shields.io/badge/GraphQL-E10098?style=flat-square&logo=graphql&logoColor=white)
![WebSockets](https://img.shields.io/badge/WebSockets-010101?style=flat-square&logo=socketdotio&logoColor=white)

**Data & Storage**

![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)
![MinIO](https://img.shields.io/badge/MinIO-C72E49?style=flat-square&logo=minio&logoColor=white)

**Observability & DevOps**

![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![OpenTelemetry](https://img.shields.io/badge/OpenTelemetry-000000?style=flat-square&logo=opentelemetry&logoColor=white)
![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=flat-square&logo=prometheus&logoColor=white)
![Grafana](https://img.shields.io/badge/Grafana-F46800?style=flat-square&logo=grafana&logoColor=white)
![Nginx](https://img.shields.io/badge/Nginx-009639?style=flat-square&logo=nginx&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)

**Frontend & Testing**

![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black)
![Redux](https://img.shields.io/badge/Redux-764ABC?style=flat-square&logo=redux&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white)
![PyTest](https://img.shields.io/badge/PyTest-0A9EDC?style=flat-square&logo=pytest&logoColor=white)

---

### Featured Projects

| Project | What it does | Stack |
|---|---|---|
| **[QueryForge](https://github.com/vipulpandey21/QueryForge)** | Distributed parallel SQL engine across 3 worker nodes with gRPC streaming, predicate pushdown, and MapReduce-style partial aggregation. Fault-tolerant scheduler (5s heartbeats, 15s dead-node detection, auto partition reassignment) plus a PostgreSQL-style `/api/explain` endpoint. **1.7× speedup on 2M+ row datasets.** | gRPC · PostgreSQL · MinIO · OpenTelemetry · Prometheus · Grafana · Docker |
| **[FilesStorer](https://github.com/vipulpandey21/StoreFile)** | Cloud storage engine with hierarchical file management, RBAC, and Redis-cached session metadata. Chunk-based binary streaming handles 1GB+ uploads without memory exhaustion; stateless JWT rotation with atomic MongoDB transactions. | Node.js · MongoDB · Redis · JWT |
| **[Messy](https://github.com/vipulpandey21/Messy)** | Full-stack mess management portal serving **300+ production users** — automated billing, real-time notices, complaint tracking. Zero-downtime rolling deploys across independent microservice containers. | React · Node.js · Docker · Nginx |
| **[CricketShotQualityAI](https://github.com/vipulpandey21/CricketShotQualityAI)** | Quantifies cricket shot correctness from video using EfficientNetB0 + GRU classification with MediaPipe pose scoring. | Python · TensorFlow · MediaPipe |

---

### Open Source

**Google Summer of Code 2026** — *Learning Unlimited* (May–Aug 2026)

Selected as an official GSoC contributor, ranked **1st among 400+ global applicants**. Diagnosed and fixed a production data-corruption bug in the class-registration workflow, cut test setup effort by **80%** (10 → 2 lines) with reusable PyTest infrastructure across 8+ modules, and built the first invariant-based regression suite for a 1,000+ LOC lottery allocation system.

**Other contributions**

- **[Open Health Care Network](https://github.com/ohcnetwork)** — fixed 2 critical Django REST API validation bugs (PR #3430, #3434)
- **[CNCF / Krkn Chaos](https://github.com/krkn-chaos)** — automated Lunr.js search-index validation across 167+ docs pages (PR #464)
- **[Learning Unlimited](https://github.com/learning-unlimited)** — 10+ merged PRs: regression-test infrastructure, shared test factories, student-registration suites

---

### GitHub Stats

<p align="center">
  <img height="165" src="https://github-readme-stats.vercel.app/api?username=vipulpandey21&show_icons=true&theme=tokyonight&hide_border=true&count_private=true" alt="GitHub stats">
  <img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=vipulpandey21&layout=compact&theme=tokyonight&hide_border=true&langs_count=8" alt="Top languages">
</p>

---

<p align="center"><i>Open to backend / distributed systems internships and SWE roles.</i></p>
