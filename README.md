# Jinesh Nanal

**Applied AI Engineer at Gruve AI · Founder of [AthleteIQ](https://athleteiqhq.com)**

I build AI systems that run in production under real constraints — multi-tenant isolation, data-residency rules, cost ceilings — rather than research prototypes.

[Portfolio](https://jsn04.github.io) · [LinkedIn](https://linkedin.com/in/jinesh-nanal-60b76a254) · [jineshnanal04@gmail.com](mailto:jineshnanal04@gmail.com)

---

## Currently

### Gruve AI — Applied AI Engineer
`Jun 2026 – present`

- Built runtime proxy layers on the PulseAI platform, cutting token latency across multi-tenant GPU clusters.
- Deployed agentic AI assistants into the Cisco Secure AI Factory pipeline, with no client data leaving the customer environment.

### AthleteIQ — Founder & Lead Engineer
`Jan 2026 – present` · **[athleteiqhq.com](https://athleteiqhq.com)** · [repo](https://github.com/Jsn04/AthleteIQ)

- Multi-tenant sports AI platform, live since January 2026 across **21 academies** and **596 registered athletes**.
- Solo full-stack build: React, FastAPI, PostgreSQL with row-level security, Groq LLM.
- Wrote the risk engine — ACWR, a personalised baseline-deviation method covering ACWR's 28-day cold start, and a coach-versus-athlete consistency check.
- Believed to be the first documented deployment of ACWR injury-risk monitoring at an Indian grassroots academy; written up as a deployment study.

---

## Previously

### NVIDIA, Quadro Team — Tools Development Intern
`Jul – Dec 2025`

- Found and fixed a deep-learning verification model failing under changing ambient lighting in a production GPU-driver test pipeline, unblocking regression checks that had been failing silently.
- Built the Python test automation across 150+ testcases, retained as the team's standard QA tooling.

### Persistent Systems — Software Development Intern
`Oct 2024 – Apr 2025`

- Built and evaluated ML pipelines for enterprise clients: classification and time-series forecasting on client datasets.
- Shipped production modules in Agile sprints with full unit-test coverage.

---

## Publications

First author on all four.

| Paper | Venue | Status |
| :--- | :--- | :--- |
| **Subject-Disjoint Cross-Dataset Evaluation of CNN and CNN-LSTM Models for Visual Driver Drowsiness Detection**<br><sub>Exposes a 17.52% drowsy-frame miss rate hidden by standard within-dataset splits. · [code](https://github.com/Jsn04/Dl_project)</sub> | MAI 2026<br><sub>Springer LNEE</sub> | **Presented**<br><sub>Sept 2026</sub> |
| **When Prompt-Injection Detectors Meet New Data: A Leakage-Free Cross-Corpus Evaluation**<br><sub>Attack recall falls from 0.92 in-distribution to 0.61 cross-corpus across five independently sourced corpora.</sub> | IEEE TPS 2026 | Under review |
| **A Smart Helmet for Two-Wheeler Navigation under GNSS Denial: Route-Aware Dead Reckoning and Road-Scene Segmentation**<br><sub>19.7% lower peak position error than unaided dead reckoning across 47 paired GNSS blackouts (p = 0.002); 0.856 road IoU on unseen BDD100K.</sub> | IEEE INDICON 2026 | Under review |
| **A Reversible PII-Redacting Proxy for DPDP-Compliant Use of Third-Party LLM APIs**<br><sub>Redacts and restores PII around third-party LLM calls, for India's DPDP Act 2023. · [code](https://github.com/Jsn04/dpdp-llm-proxy)</sub> | IEEE DELCON 2026 | Under review |

> A theme runs through these: models that look strong on standard benchmarks lose much of their accuracy once the evaluation is made honest. That is also how I build.

---

## Selected repositories

| Repository | What it does |
| :--- | :--- |
| **[AthleteIQ](https://github.com/Jsn04/AthleteIQ)** | The production platform above. React · FastAPI · PostgreSQL (RLS) · Groq |
| **[dpdp-llm-proxy](https://github.com/Jsn04/dpdp-llm-proxy)** | Reversible PII redaction around third-party LLM calls, for India's DPDP Act 2023. Indian identifier set, check-digit matchers, streaming rehydration |
| **[Dl_project](https://github.com/Jsn04/Dl_project)** | The MAI 2026 drowsiness-detection evaluation. PyTorch · CNN · CNN-LSTM |
| **[SkillMatch](https://github.com/Jsn04/SkillMatch)** | Two-sided hiring marketplace. Availability-aware k-NN and semantic matching with explainable scores; contact gated behind mutual interest |

---

## Stack

| | |
| :--- | :--- |
| **Languages** | Python, JavaScript, C++, SQL |
| **ML & AI** | PyTorch, TensorFlow, scikit-learn, XGBoost, OpenCV, SHAP |
| **LLMs & GenAI** | Groq, LangChain, HuggingFace, RAG, prompt engineering |
| **Systems** | FastAPI, React, PostgreSQL, Supabase, Docker, GitHub Actions, PyTest |

---

## Education

**B.Tech, Computer Science and Engineering** — MIT World Peace University, Pune · `2022 – 2026`
CGPA 7.96/10, First Class with Distinction. Best All-Rounder Award (University Gold Medal).

---

## Elsewhere

I skate for Team India in inline skating — Silver and Bronze at the World Games 2024, and the Shiv Chhatrapati Award, Maharashtra's highest sporting honour.

AthleteIQ exists because I spent a decade being the athlete whose training load nobody was tracking.
