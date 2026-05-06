<div align="center">

<img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&weight=600&size=30&duration=3000&pause=1000&color=6366F1&center=true&vCenter=true&random=false&width=900&lines=Sarthak+Chauhan;AI+Engineer+%7C+ML+Systems+%7C+Research;Building+Reliable+LLM+Infrastructure;Production+GenAI+%7C+Vision+Robustness;FastAPI+%7C+RAG+%7C+Distributed+Inference" />

<br/>

<p>
  <em>
    AI Engineer focused on production GenAI systems, reliable LLM infrastructure,
    retrieval systems, and robustness evaluation under real-world constraints.
  </em>
</p>

<p>
  <a href="https://linkedin.com/in/sarthak-chauhan-dev">
    <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"/>
  </a>

  <a href="mailto:sarthak4156@gmail.com">
    <img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white"/>
  </a>

  <a href="https://github.com/CodeNinjaSarthak">
    <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white"/>
  </a>

  <a href="https://scholar.google.com/citations?user=O8izs44AAAAJ/">
    <img src="https://img.shields.io/badge/Google_Scholar-4285F4?style=for-the-badge&logo=google-scholar&logoColor=white"/>
  </a>
</p>

</div>

---

# About Me

```python
class SarthakChauhan:

    role = [
        "AI Engineer",
        "ML Systems Builder",
        "Research Engineer"
    ]

    interests = [
        "Reliable LLM Systems",
        "Distributed Inference",
        "Retrieval-Augmented Generation",
        "Vision Robustness",
        "Temporal Memory Systems",
        "Evaluation Under Distribution Shift"
    ]

    currently_building = [
        "Production-scale GenAI infrastructure",
        "Memory systems for conversational reasoning",
        "Robustness benchmarking pipelines",
        "Low-latency async AI systems"
    ]
```

---

# What I Work On

<table>
<tr>
<td width="50%" valign="top">

### ⚡ Production AI Systems

* Built production LLM systems serving **1000+ users**
* Reduced generation latency from **21s → 6s**
* Designed async orchestration using `asyncio.gather`
* Built provider fallback routing:
  `Azure → Claude / Gemini`
* Engineered Redis worker pipelines with bounded concurrency
* Implemented SSE streaming, rate limiting, and circuit breakers

</td>

<td width="50%" valign="top">

### 🔬 Research & Evaluation

* 3 IEEE publications (2 first-author)
* Working on memory systems for temporal reasoning
* Evaluating robustness under distribution shift
* Benchmarking calibration across vision architectures
* Researching retrieval quality and reranking systems
* Building RL environments for AI safety evaluation

</td>
</tr>
</table>

---

# Featured Work

<table>
<tr>

<td width="50%" valign="top">

## 🚀 SafeAct-Env

**AI Safety RL Environment**
*Finalist — Meta × Scaler PyTorch OpenEnv Hackathon (Top 2.6%)*

* Multi-task RL environment for reversible vs irreversible actions
* Deterministic graders with hidden risk classifier
* 164 passing tests with reproducible evaluation
* Built across infra, filesystem, DB, and medical safety tasks

**Stack:**
`Python` `FastAPI` `Docker` `RL`

<br/>

<a href="https://github.com/CodeNinjaSarthak/safeact-env">
  <img src="https://img.shields.io/badge/View_Project-6366F1?style=for-the-badge&logo=github&logoColor=white"/>
</a>

</td>

<td width="50%" valign="top">

## 🧠 Eidetic Memory

**Memory System for Conversational AI**

* Achieved **56.3% LoCoMo QA**
* +39.3 pp temporal improvement over RAG baseline
* Per-speaker memory isolation + neural reranking
* Averaged only **1.9 LLM calls/query**

**Focus Areas:**
Temporal reasoning • retrieval • reranking • memory systems

**Stack:**
`FastAPI` `Qdrant` `Cross-Encoder` `LLMs`

<br/>

<a href="https://github.com/CodeNinjaSarthak/eidetic-memory">
  <img src="https://img.shields.io/badge/Research_Work-6366F1?style=for-the-badge"/>
</a>

</td>

</tr>

<tr>

<td width="50%" valign="top">

## ⚡ StreamMind

**Real-Time Semantic Question Clustering**

* Reduced instructor response time by **68%**
* Designed fault-tolerant async processing pipeline
* Handled **100+ concurrent doubts**
* Semantic deduplication using online clustering

**Infra:**
Redis workers • pgvector • WebSockets • circuit breakers

**Stack:**
`FastAPI` `Redis` `pgvector` `Gemini`

<br/>

<a href="https://github.com/CodeNinjaSarthak/StreamMind">
  <img src="https://img.shields.io/badge/View_Project-6366F1?style=for-the-badge&logo=github&logoColor=white"/>
</a>

</td>

<td width="50%" valign="top">

## 🏫 Medha AI

**Production GenAI System @ Cograd**

* Serving curriculum-aligned generation workflows
* Reduced lesson-plan latency **3.5×**
* Reduced exam generation latency **2.5×**
* Multi-provider orchestration with graceful degradation
* Multi-HyDE retrieval + reranking pipeline

**Infra:**
Async orchestration • Redis • Qdrant • Azure OpenAI

**Stack:**
`FastAPI` `Redis` `Qdrant` `MongoDB`

<br/>

<a href="https://medha.cograd.in/">
  <img src="https://img.shields.io/badge/Production_System-6366F1?style=for-the-badge"/>
</a>

</td>

</tr>
</table>

---

# Selected Research

### Vision Robustness & Calibration

Evaluating 12 ImageNet-pretrained architectures across IN-Val, IN-V2, IN-R, IN-A, and IN-C using:

* ECE
* AURC
* selective prediction
* corruption robustness
* universal failure analysis

### Dense-Fog Highway Dehazing

Benchmarked 10 dehazing architectures and identified a **15–20 dB PSNR gap**
between synthetic benchmarks and real dense-fog highway conditions.

### Hinglish Abuse Detection

Improved F1 from **0.784 → 0.866** on a 700K-post dataset using:

* XLM-R transfer learning
* BiGRU attention fusion
* multilingual representation learning

---

# Publications

### 📄 Hinglish Abusive Comment Detection Using Transformer-Based Models

**AICAPS 2026 — IEEE Kerala Section**
First Author

### 📄 Image and Video Dehazing for Dense-Fog Indian Highway Scenarios

**DICCT 2026**
First Author

### 📄 Deep Learning-Based Brain Tumour Identification

**IC3SE 2025 — IEEE UP Section**
Second Author

---

# Tech Stack

<div align="center">

### Languages & ML

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge\&logo=python\&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge\&logo=pytorch\&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge\&logo=tensorflow\&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge\&logo=fastapi\&logoColor=white)

### LLM & Retrieval

![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=for-the-badge)
![LangGraph](https://img.shields.io/badge/LangGraph-2563EB?style=for-the-badge)
![Qdrant](https://img.shields.io/badge/Qdrant-DC382D?style=for-the-badge)
![pgvector](https://img.shields.io/badge/pgvector-4169E1?style=for-the-badge)

### Systems & Infra

![Redis](https://img.shields.io/badge/Redis-D82C20?style=for-the-badge\&logo=redis\&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-336791?style=for-the-badge\&logo=postgresql\&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge\&logo=docker\&logoColor=white)
![Azure](https://img.shields.io/badge/Azure-0078D4?style=for-the-badge\&logo=microsoftazure\&logoColor=white)

</div>

---

# Achievements

* 🏆 Meta × Scaler PyTorch OpenEnv Hackathon — Finalist (Top 2.6%)
* 🏆 Amazon ML Challenge 2024 — Top 0.5%
* 🏆 IIT Bombay Convolve — Top 50 / 4189 teams
* 🎓 Dean’s List — Top 10%
* 📚 GPA: 9.42 / 10.0

---

# GitHub Stats

<div align="center">


<p align="center">
  <img
    height="180em"
    src="https://github-profile-summary-cards.vercel.app/api/cards/stats?username=CodeNinjaSarthak&theme=tokyonight"
  />
</p>


<br/><br/>

<img height="180em" src="https://github-readme-streak-stats.herokuapp.com/?user=CodeNinjaSarthak&hide_border=true"/>

</div>

---

# Activity Graph

<div align="center">

<img src="https://github-readme-activity-graph.vercel.app/graph?username=CodeNinjaSarthak&hide_border=true"/>

</div>

---

# Connect

<div align="center">

Building reliable AI systems, retrieval infrastructure, and evaluation pipelines.

<br/><br/>

<a href="mailto:sarthak4156@gmail.com">
  <img src="https://img.shields.io/badge/Contact_Me-EA4335?style=for-the-badge&logo=gmail&logoColor=white"/>
</a>

</div>
