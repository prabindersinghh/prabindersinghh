<!-- ══════════════════════════════════════════════════════════ HEADER -->
<img src="https://capsule-render.vercel.app/api?type=waving&color=0:000000,50:0a0a0a,100:111827&height=160&section=header&text=Prabinder%20Singh&fontSize=46&fontColor=ffffff&fontAlignY=60&desc=AI%20Systems%20Engineer%20%E2%80%A2%20Building%20%E2%80%A2%20Open%20Source&descAlignY=80&descSize=17&animation=fadeIn" width="100%"/>

<!-- ══════════════════════════════════════════════════════════ TYPING BANNER -->
<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=700&size=19&duration=2600&pause=900&color=FFFFFF&center=true&vCenter=true&width=860&lines=Founder+%40+Leorit.ai+%E2%80%94+World%27s+first+Uber+for+factories+in+India;AI+Systems+Engineer+%7C+Multi-Modal+%7C+Agentic+AI+%7C+Production+ML;OpenSource+2026+Contributor+%E2%80%94+Kubeflow+OTel+%7C+Metaflow+Nomad;3%C3%97+International+Hackathon+Podium+%C2%B7+3%C3%97+Global+Finalist;Building+systems+that+move+from+research+%E2%86%92+real+industry" />
</p>

<!-- ══════════════════════════════════════════════════════════ BADGES -->
<p align="center">
  <img src="https://komarev.com/ghpvc/?username=prabindersinghh&label=Profile+Views&color=0969da&style=flat-square&labelColor=0969da"/>
  &nbsp;
  <a href="https://www.linkedin.com/in/prabinder-singh-6856a431a/">
    <img src="https://img.shields.io/badge/LinkedIn-Connect-white?style=flat-square&logo=linkedin&logoColor=0A66C2&labelColor=white&color=0A66C2"/>
  </a>
  &nbsp;
  <a href="https://prabindersinghhh-website.vercel.app/">
    <img src="https://img.shields.io/badge/Website-prabindersinghh.com-000000?style=flat-square&logo=vercel&logoColor=white&labelColor=000000"/>
  </a>
  &nbsp;
  <a href="https://huggingface.co/prabindersinghh">
    <img src="https://img.shields.io/badge/HuggingFace-prabindersinghh-FFD21F?style=flat-square&logo=huggingface&logoColor=black"/>
  </a>
  &nbsp;
  <a href="mailto:prabindersinghh@gmail.com">
    <img src="https://img.shields.io/badge/Gmail-prabindersinghh-EA4335?style=flat-square&logo=gmail&logoColor=white"/>
  </a>
</p>

---

## ◈ Who I Am

```text
🏭  Building @ Leorit.ai      World's first Uber for factories — built on real production data
🎓  B.Tech CS + Business      Thapar Institute of Engineering & Technology (2024–2028)
🔬  Research                  IEEE paper under review — RAG-ST (Spatial Transcriptomics)
🏆  Hackathons                3× International Podium · 3× Global Finalist
☁️  Ambassador                Google Gemini Student Ambassador
🧠  Philosophy                Execution > Experimentation · Systems > Isolated Models
```

> **I don't build models. I build systems around models — systems that solve real execution problems.**
>
> Before writing a single line of code for Leorit, I personally executed thousands of manufacturing orders. That data became the moat. That experience became the product.

---

## ◈ Leorit.ai — My Company

<table>
<tr>
<td width="58%" valign="top">

### 🏭 Leorit Manufacturer OS
`Founder & CEO · May 2025 – Present`

India's garment manufacturing industry runs on WhatsApp, Excel, and verbal commitments. Every order is a coordination nightmare. **Leorit ends that.**

**What we're building:**
- Commission-based order management OS for garment manufacturers (Ludhiana · Tirupur · Ahmedabad)
- Structured execution data captured across every order lifecycle
- Three-role platform: Buyer · Manufacturer · Admin
- Four order types with full traceability + 3D mockup engine (Three.js / GLB)

**Stack:** React 18 + TypeScript + Vite + shadcn/ui + Supabase + Three.js

**Goal:** 5 manufacturers · 20+ orders · zero WhatsApp coordination

</td>
<td width="42%" valign="top">

### Metrics & Vision

| Metric | Status |
|---|---|
| Phase 1 target | 5 manufacturers onboarded |
| Orders goal | 20+ structured orders |
| Data strategy | Every order = ML signal |
| Revenue model | Hybrid commission |
| Long-term | AI routes orders autonomously |

### Three Non-Negotiable Pillars
```
"World's first Uber for factories in India"
"Built on real production data"
"World's first production AI for manufacturing"
```

</td>
</tr>
</table>

---

## ◈ GSoC 2026 — Open Source Contributions

<table>
<tr>
<td width="50%" valign="top">

### ⚙️ Kubeflow — OTel Integration
`Project 7: Integrate Kubeflow SDK with OpenTelemetry · 350hrs · Hard`

| PR | Status | What It Does |
|---|---|---|
| [`#341`](https://github.com/kubeflow/sdk/pull/341) | ✅ `/ok-to-test` | Cluster-scoped runtime fallback |
| [`#401`](https://github.com/kubeflow/sdk/pull/401) | 📬 Under Review | `telemetry.py` — 15 unit tests |
| [`#402`](https://github.com/kubeflow/sdk/pull/402) | ✅ **Merged** | Polling validation fix — all backends |

**Architecture decisions:**
- Centralized `kubeflow/common/telemetry.py`
- Per-iteration child spans for `wait_for_job_status()` polling
- `max_traced_iterations` cap to prevent span explosion
- `opentelemetry-api` as core dependency · Verified OTel JSON PoC

**Mentors:** @kramaranya · @dhanishaphadate · @jaiakash

</td>
<td width="50%" valign="top">

### 🔁 Metaflow — Nomad Backend
`Nomad Executor Integration · 350hrs`

- Built `metaflow-nomad` repo with working backend decorator
- Improved `nomad_decorator.py` + `setup.py` + example flows
- Active PR [`#3018`](https://github.com/Netflix/metaflow/pull/3018) in Netflix/metaflow

**Mentor:** Madhur Tandon

---

### 🔓 Beyond GSoC

| Project | Contribution |
|---|---|
| **MLflow** (Linux Foundation AI) | Entity validation + protobuf serialization in Feedback/Assessment; union-type validation, tracing tests, backward compatibility |
| **OpenMined Syft** | Persistent dataset discovery bug — sync idempotency analysis across in-memory vs persistent storage; proposed minimal fix |

</td>
</tr>
</table>

---

## ◈ Featured Projects

<table>
<tr>
<td width="50%" valign="top">

### 🔎 TruthShield Pro
**Multi-Modal AI Forensics Engine** · `2025`

🥉 *3rd Place — BIOS Hackathon 2025, IEEE × CSED, Thapar*

| Layer | Model |
|---|---|
| Vision | ViT + diffusion artifact fingerprinting |
| Audio | Wav2Vec2 + ECAPA-TDNN voice clone detection |
| Text | LLaMA3 forensics pipeline |
| Engine | Cross-Modal Consistency Scoring |
| Retrieval | FAISS provenance graphs + explainability |

</td>
<td width="50%" valign="top">

### 🛡 CyberSentinel
**Hybrid Agentic Intrusion Detection System** · `2025`

🥉 *3rd Place — Agentic AI Hackathon, University of Ulster, UK*

- Hybrid IDS: rule-based + ML anomaly · **92%+ accuracy**
- MITM · DNS spoofing · ARP attack detection
- NLP phishing engine + UEBA drift analysis
- Raspberry Pi edge deployment · **sub-2s** threat blocking

> Deployed to real edge hardware. Not just classification — active threat response.

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 📊 RAG-ST
**Retrieval-Augmented Deep Learning · Spatial Transcriptomics** · `2025`

*📄 Paper under review — IEEE ICAIB 2025*

- 9-stage end-to-end pipeline
- EfficientNet + FAISS patch retrieval + MLP gene expression prediction
- PCA / t-SNE / UMAP interpretability stack

</td>
<td width="50%" valign="top">

### 🤖 ProcurenAI
**Multi-Agent RFP Automation System** · `2025`

🏅 *Finalist — Vibestate/ByteWars, Derby, UK*

- Sales · Technical · Pricing · Master autonomous agents
- SentenceTransformer SKU matching
- **4 hours → <5 minutes** RFP processing time

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 🏙 CIVITAS-INTEL
**Urban Decision Intelligence Engine** · `2026`

🥉 *3rd Place + Innovation Award — AI for Sustainability Hackathon, Canadian University Dubai*

- Distributed multi-agent platform for AI-driven city management
- Real-time urban decision optimization

</td>
<td width="50%" valign="top">

### 🔐 QuantumSight
**AI-Augmented Cryptographic Intelligence Platform** · `2026`

*PSB Hackathon 2026 — PNB Cybersecurity*

- Addresses Harvest Now, Decrypt Later (HNDL) quantum threat
- Stack: FastAPI + React 18 + PostgreSQL + Docker
- 12 pre-seeded demo assets · Full SRS + working prototype

</td>
</tr>
</table>

---

## ◈ Hackathon Record

| Result | Event | Project |
|---|---|---|
| 🥉 3rd + Innovation Award | AI for Sustainability 2026 — Canadian University Dubai | CIVITAS-INTEL |
| 🥉 3rd Place | BIOS Hackathon 2025 — IEEE × CSED, Thapar | TruthShield Pro |
| 🥉 3rd Place | Agentic AI Hackathon 2025 — University of Ulster, UK | CyberSentinel |
| 🏅 Finalist | Indo-Israel International Hackathon 2025 | MediFlow Vita |
| 🏅 Finalist | Sabka AI 2026 — TIET-UQ | FairHire360 |
| 🏅 Finalist | ByteWars / Vibestate 2025 — Derby, UK | ProcurenAI |

> **6 international competitions. 3 podiums. All in Year 1 to 2 of college.**

---

## ◈ Tech Stack

### 🧠 AI / ML
<p>
<img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white"/>
<img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white"/>
<img src="https://img.shields.io/badge/HuggingFace-FFD21F?style=for-the-badge&logo=huggingface&logoColor=black"/>
<img src="https://img.shields.io/badge/LLMs-6B21A8?style=for-the-badge&logoColor=white"/>
<img src="https://img.shields.io/badge/RAG-1d4ed8?style=for-the-badge&logoColor=white"/>
<img src="https://img.shields.io/badge/FAISS-0f766e?style=for-the-badge&logoColor=white"/>
<img src="https://img.shields.io/badge/Vision%20Transformers-be185d?style=for-the-badge&logoColor=white"/>
<img src="https://img.shields.io/badge/Agentic%20AI-111827?style=for-the-badge&logoColor=white"/>
<img src="https://img.shields.io/badge/OpenTelemetry-425CC7?style=for-the-badge&logo=opentelemetry&logoColor=white"/>
</p>

### ⚙️ Systems & Backend
<p>
<img src="https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white"/>
<img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white"/>
<img src="https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazonaws&logoColor=white"/>
<img src="https://img.shields.io/badge/GCP-4285F4?style=for-the-badge&logo=googlecloud&logoColor=white"/>
<img src="https://img.shields.io/badge/Kubeflow-1a73e8?style=for-the-badge&logoColor=white"/>
<img src="https://img.shields.io/badge/Metaflow-FF6B6B?style=for-the-badge&logoColor=white"/>
<img src="https://img.shields.io/badge/n8n-ea4b71?style=for-the-badge&logo=n8n&logoColor=white"/>
<img src="https://img.shields.io/badge/Microservices-374151?style=for-the-badge&logoColor=white"/>
</p>

### 🌐 Product & Data
<p>
<img src="https://img.shields.io/badge/React%2018-20232A?style=for-the-badge&logo=react&logoColor=61DAFB"/>
<img src="https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white"/>
<img src="https://img.shields.io/badge/Vite-646CFF?style=for-the-badge&logo=vite&logoColor=white"/>
<img src="https://img.shields.io/badge/shadcn%2Fui-000000?style=for-the-badge&logoColor=white"/>
<img src="https://img.shields.io/badge/Three.js-000000?style=for-the-badge&logo=threedotjs&logoColor=white"/>
<img src="https://img.shields.io/badge/Supabase-3ECF8E?style=for-the-badge&logo=supabase&logoColor=white"/>
<img src="https://img.shields.io/badge/PostgreSQL-336791?style=for-the-badge&logo=postgresql&logoColor=white"/>
<img src="https://img.shields.io/badge/SQL-CC2927?style=for-the-badge&logoColor=white"/>
</p>

---

## ◈ Leadership & Recognition

<table>
<tr>
<td width="33%" align="center">

**☁️ Google Gemini**
**Student Ambassador**

Gemini adoption · Developer workshops
Community building

</td>
<td width="33%" align="center">

**📋 McKinsey Forward**
**Program Fellow**

Global cohort
Leadership + digital transformation

</td>
<td width="33%" align="center">

**🏗 CollabSphere**
**Founder**

72-member student ecosystem
₹90,000 in projects in week one

</td>
</tr>
<tr>
<td width="33%" align="center">

**📐 JEE Mains 2024**
**94.2 Percentile**

Top engineering entrance exam
in India

</td>
<td width="33%" align="center">

**📍 Innovation Mission Punjab**
**Campus Ambassador**

State-level innovation
& startup ecosystem

</td>
<td width="33%" align="center">

**🎙 TEDx · SAR · Virsa**
**Marketing Lead**

PR, outreach, data-backed
event planning @ Thapar

</td>
</tr>
</table>

---

## ◈ GitHub Analytics

<p align="center">
  <img height="180em" src="https://github-readme-stats.vercel.app/api?username=prabindersinghh&show_icons=true&theme=github_dark&hide_border=true&bg_color=0d1117&title_color=58a6ff&text_color=8b949e&icon_color=58a6ff&include_all_commits=true&count_private=true&rank_icon=github&cache_seconds=1"/>
  &nbsp;
  <img height="180em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=prabindersinghh&layout=compact&theme=github_dark&hide_border=true&bg_color=0d1117&title_color=58a6ff&text_color=8b949e&langs_count=8&cache_seconds=1"/>
</p>

<p align="center">
  <img src="https://streak-stats.demolab.com?user=prabindersinghh&theme=github-dark-blue&hide_border=true&background=0d1117&ring=58a6ff&fire=58a6ff&currStreakLabel=58a6ff&sideLabels=8b949e&dates=8b949e" width="60%"/>
</p>

<!-- Profile Summary Cards — pulls directly from GitHub API, more reliable -->
<p align="center">
  <img src="https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=prabindersinghh&theme=github_dark" width="100%"/>
</p>
<p align="center">
  <img src="https://github-profile-summary-cards.vercel.app/api/cards/repos-per-language?username=prabindersinghh&theme=github_dark"/>
  &nbsp;
  <img src="https://github-profile-summary-cards.vercel.app/api/cards/most-commit-language?username=prabindersinghh&theme=github_dark"/>
  &nbsp;
  <img src="https://github-profile-summary-cards.vercel.app/api/cards/stats?username=prabindersinghh&theme=github_dark"/>
  &nbsp;
  <img src="https://github-profile-summary-cards.vercel.app/api/cards/productive-time?username=prabindersinghh&theme=github_dark&utcOffset=5.5"/>
</p>

<p align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=prabindersinghh&bg_color=0d1117&color=58a6ff&line=1f6feb&point=58a6ff&area=true&area_color=1f6feb&hide_border=true&custom_title=Contribution+Graph" width="100%"/>
</p>

---

## ◈ What I'm Building Toward

```
Manufacturing AI  →  Leorit captures structured execution data at scale
                      Every order = a training signal for autonomous routing
                      Long-term: software verifies manufacturing outcomes without human judgment

Open Source       →  Kubeflow OTel instrumentation shipping into production
                      Metaflow Nomad backend enabling HPC + cloud-native ML workflows

Research          →  IEEE ICAIB 2025 paper (RAG-ST) under review
                      Bridging spatial biology + retrieval-augmented deep learning

Trajectory        →  From India's garment factories → global manufacturing intelligence platform
```

---

## ◈ Connect

<p align="center">
  <a href="https://prabindersinghhh-website.vercel.app/">
    <img src="https://img.shields.io/badge/🌐%20Website-prabindersinghh.com-000000?style=for-the-badge"/>
  </a>
  &nbsp;
  <a href="https://www.linkedin.com/in/prabinder-singh-6856a431a/">
    <img src="https://img.shields.io/badge/LinkedIn-Prabinder%20Singh-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"/>
  </a>
  &nbsp;
  <a href="mailto:prabindersinghh@gmail.com">
    <img src="https://img.shields.io/badge/Email-prabindersinghh%40gmail.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white"/>
  </a>
  &nbsp;
  <a href="https://huggingface.co/prabindersinghh">
    <img src="https://img.shields.io/badge/HuggingFace-prabindersinghh-FFD21F?style=for-the-badge&logo=huggingface&logoColor=black"/>
  </a>
</p>

---

<!-- ══════════════════════════════════════════════════════════ FOOTER -->
<img src="https://capsule-render.vercel.app/api?type=waving&color=0:111827,100:000000&height=100&section=footer" width="100%"/>

<p align="center">
  <i>"Most people build models. I build systems around models — systems that change how industries operate."</i>
</p>
