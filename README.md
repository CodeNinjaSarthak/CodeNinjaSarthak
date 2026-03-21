<div align="center">
  
<!-- Animated Header -->
<img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&weight=600&size=28&duration=3000&pause=1000&color=6366F1&center=true&vCenter=true&random=false&width=600&lines=Hey%2C+I'm+Sarthak+Chauhan+%F0%9F%91%8B;AI%2FML+Engineer+%26+Researcher;ML+Researcher+%7C+Vision+Robustness;Building+Intelligent+Systems;LLM+Agents+%7C+RAG+%7C+Computer+Vision" alt="Typing SVG" />

<br/>

<!-- Subtitle -->
<p>
  <em>AI/ML Engineer & Researcher — from vision robustness evaluation to production LLM systems 🚀</em>
</p>

<!-- Social Badges -->
<p>
  <a href="https://www.linkedin.com/in/sarthak-chauhan-dev/">
    <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/>
  </a>
  <a href="mailto:sarthak4156@gmail.com">
    <img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"/>
  </a>
  <a href="https://github.com/CodeNinjaSarthak">
    <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub"/>
  </a>
  <a href="https://kaggle.com/sarthak4156">
    <img src="https://img.shields.io/badge/Kaggle-20BEFF?style=for-the-badge&logo=kaggle&logoColor=white" alt="Kaggle"/>
  </a>
  <a href="https://www.leetcode.com/sarthak4156">
    <img src="https://img.shields.io/badge/LeetCode-FFA116?style=for-the-badge&logo=leetcode&logoColor=black" alt="LeetCode"/>
  </a>
</p>

<img src="https://komarev.com/ghpvc/?username=CodeNinjaSarthak&style=flat-square&color=6366f1" alt="Profile Views"/>

</div>

---

## 🧠 About Me

```python
class SarthakChauhan:
    def __init__(self):
        self.role = "AI/ML Engineer & Researcher"
        self.education = "B.Tech CSE (AI/ML) @ Bennett University"
        self.achievements = "CGPA: 9.42/10.0 | Dean's List (Top 10%)"
        self.location = "India 🇮🇳"
        
    def current_work(self):
        return [
            "🔬 Vision model robustness: benchmarking 12 architectures across IN-Val/V2/R/A (ECE, NLL, per-class dispersion)",
            "🚗 Fog-highway dehazing benchmark: 10 architectures, 15–20 dB PSNR gap finding (DICCT 2026)",
            "🏫 Production RAG pipeline @ Cograd: 50+ teachers, 6 schools, 42% prep-time reduction",
            "💬 Hinglish abuse detection: XLM-R + BiGRU, F1 0.866 on 700K posts (IEEE AICAPS 2026)"
        ]
    
    def skills(self):
        return {
            "AI/ML": ["Deep Learning", "NLP", "Computer Vision", "RAG", "PINNs"],
            "LLM Stack": ["LangChain", "LlamaIndex", "CrewAI", "AutoGen", "LangGraph"],
            "Frameworks": ["PyTorch", "TensorFlow", "Hugging Face", "FastAPI"],
            "MLOps": ["Docker", "MLflow", "W&B", "ONNX", "TensorRT"]
        }
    
    def fun_fact(self):
        return "I think my GPU works harder than I do 😄"
```

---

## 🔬 Research Focus

<div align="center">
<table>
<tr>
<td width="50%" valign="top">

**Distribution Shift & Model Calibration**
Investigating how natural and rendition-based shifts expose calibration failures in vision
models. Found training recipe dominates over architecture family: ResNet-50-V1 (ECE=0.039)
vs V2 (ECE=0.410) at comparable Top-1 accuracy.

</td>
<td width="50%" valign="top">

**Evaluation Beyond Average Accuracy**
Building benchmarking frameworks that measure worst-group robustness, per-class dispersion,
ECE, and NLL across architecture families (ResNets, ViTs, Swin-T, ConvNeXt, MaxViT)
on IN-Val, IN-V2, IN-R, IN-A.

</td>
</tr>
</table>
</div>

---

## 🚀 Featured Projects

<table>
  <tr>
    <td width="50%">
      <h3 align="center">DataWhiz</h3>
      <p align="center">
        <a href="https://vskai.cograd.in/">
          <img src="https://img.shields.io/badge/Production-6366F1?style=for-the-badge"/>
        </a>
      </p>
      <p><strong>Text-to-SQL System with Multi-Agent Orchestration</strong></p>
      <p>🗃️ Handles 200+ table databases with GPT-4o + LangChain<br/>🎯 35% error reduction via vector schema retrieval over full-schema prompting<br/>📊 3.2× faster insights with LIDA auto-visualization (N=12 user study)<br/>☁️ Deployed on Azure with CI/CD pipeline</p>
      <p><code>FastAPI</code> <code>LangChain</code> <code>DuckDB</code> <code>Neo4j</code> <code>Azure</code></p>
    </td>
    <td width="50%">
      <h3 align="center">StreamMind</h3>
      <p align="center">
        <img src="https://img.shields.io/badge/Completed-6366F1?style=for-the-badge"/>
      </p>
      <p><strong>Real-time AI Doubt Clustering for Live Classes</strong></p>
      <p>⚡ 6-stage async pipeline with dedicated Redis workers per stage<br/>📉 68% reduction in instructor response time (200-doubt benchmark)<br/>🔍 pgvector ANN search collapses semantic duplicates before answer generation<br/>🔴 WebSocket layer supports 100+ concurrent doubts on YouTube Live</p>
      <p><code>FastAPI</code> <code>Redis</code> <code>pgvector</code> <code>WebSocket</code> <code>LLMs</code></p>
    </td>
  </tr>
  <tr>
    <td width="50%">
      <h3 align="center">Medha AI</h3>
      <p align="center">
        <a href="https://medha.cograd.in/">
          <img src="https://img.shields.io/badge/Production-6366F1?style=for-the-badge"/>
        </a>
      </p>
      <p><strong>Enterprise RAG System @ Cograd <em>(Team Project)</em></strong></p>
      <p>🏫 Deployed across 50+ teachers in 6 schools<br/>✅ 78% of content required minimal editing<br/>⚡ 2.5–3.5× latency cut via asyncio parallelization + SSE stream merging (~1s TTFT)<br/>💰 25–30% LLM cost reduction via prompt compression & quantization</p>
      <p><code>Qdrant</code> <code>MongoDB</code> <code>FastAPI</code> <code>PostgreSQL</code> <code>Redis</code></p>
    </td>
    <td width="50%">
      <h3 align="center">Aurigen</h3>
      <p align="center">
        <a href="https://github.com/CodeNinjaSarthak/Aurigen-AI-Powered-Jewelry-Design-Studio">
          <img src="https://img.shields.io/badge/View_Code-6366F1?style=for-the-badge&logo=github&logoColor=white"/>
        </a>
      </p>
      <p><strong>AI Jewelry Design Studio</strong></p>
      <p>💎 Fine-tuned SDXL via LoRA (FP16, 10K steps) on self-curated 6,157-image dataset<br/>🎨 ControlNet Canny preserves geometric constraints where vanilla SDXL drifted<br/>⚡ 3.9× latency reduction (8.2s → 2.1s) via attention caching + FP16</p>
      <p><code>SDXL</code> <code>ControlNet</code> <code>LoRA</code> <code>PyTorch</code> <code>Streamlit</code></p>
    </td>
  </tr>
</table>

<div align="center">
  <a href="https://github.com/CodeNinjaSarthak?tab=repositories">
    <img src="https://img.shields.io/badge/View_All_Projects-6366F1?style=for-the-badge&logo=github&logoColor=white" alt="View All Projects"/>
  </a>
  <br/><sub>📌 Ongoing Research: <strong>Vision Model Robustness Evaluation</strong> — benchmarking 12 architectures (ResNets, ViTs, Swin-T, ConvNeXt, MaxViT) across IN-Val, IN-V2, IN-R, IN-A · Measuring ECE, NLL & per-class dispersion · <a href="https://api.wandb.ai/links/project2034acc-n-a/4lxdl31r">W&B Report ↗</a> · PyTorch · <em>In Progress</em></sub>
</div>
---

## 🎯 Skills

<table>
<tr>
<td width="50%" valign="top">

### 🧠 AI/ML & Research
- Machine Learning, Deep Learning
- Natural Language Processing (NLP)
- Computer Vision (YOLOv8, Dehazing, Detection)
- Transformers, LLMs, RAG Systems
- Physics-Informed Neural Networks (PINNs)
- Diffusion Models (SDXL, ControlNet)
- Optimization, Feature Engineering, Statistical Modeling

</td>
<td width="50%" valign="top">

### 🤖 LLM & Agents
- LangChain, LlamaIndex, LangGraph
- AutoGen, CrewAI, JinaAI
- Prompt Engineering & Retrieval Optimization
- Multi-Agent Systems for SQL, Automation & Pipelines
- Vector Search & Embeddings
- OpenAI API Integration

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 📚 Frameworks & Libraries
- PyTorch, TensorFlow, Hugging Face
- HuggingFace Diffusers, SciPy
- scikit-learn, OpenCV, NumPy, Pandas
- FastAPI, Streamlit, DuckDB, MongoDB
- Qdrant, Neo4j, PostgreSQL, MySQL

</td>
<td width="50%" valign="top">

### ⚙️ MLOps & Systems
- Docker, MLflow, Weights & Biases
- ONNX, TensorRT (FP16/INT8 optimization)
- GGUF Quantization, Model Compression
- Azure, GCP, Linux
- Grafana, Prometheus, CI/CD
- Experiment Tracking, Profiling & Deployment
- CUDA, LaTeX

</td>
</tr>
</table>

---

## 🛠️ Tech Stack

<div align="center">

### 💻 Languages
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=cplusplus&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=postgresql&logoColor=white)

### 🧠 Deep Learning & AI
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white)
![Hugging Face](https://img.shields.io/badge/Hugging%20Face-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black)
![Transformers](https://img.shields.io/badge/Transformers-FF6F00?style=for-the-badge&logo=huggingface&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikitlearn&logoColor=white)
![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=for-the-badge&logo=opencv&logoColor=white)
![Stable Diffusion](https://img.shields.io/badge/Stable%20Diffusion-FF6B6B?style=for-the-badge)
![ControlNet](https://img.shields.io/badge/ControlNet-8B5CF6?style=for-the-badge)
![PINNs](https://img.shields.io/badge/PINNs-10B981?style=for-the-badge)

### 🤖 LLM Ecosystem
![LangChain](https://img.shields.io/badge/🦜_LangChain-1C3C3C?style=for-the-badge)
![LlamaIndex](https://img.shields.io/badge/🦙_LlamaIndex-8B5CF6?style=for-the-badge)
![LangGraph](https://img.shields.io/badge/🔗_LangGraph-2563EB?style=for-the-badge)
![CrewAI](https://img.shields.io/badge/🚀_CrewAI-FF6B6B?style=for-the-badge)
![AutoGen](https://img.shields.io/badge/⚡_AutoGen-10B981?style=for-the-badge)
![JinaAI](https://img.shields.io/badge/🔍_JinaAI-FF6B6B?style=for-the-badge)
![OpenAI](https://img.shields.io/badge/OpenAI-412991?style=for-the-badge&logo=openai&logoColor=white)
![Embeddings](https://img.shields.io/badge/Embeddings-6366F1?style=for-the-badge)
![Vector Search](https://img.shields.io/badge/Vector%20Search-EC4899?style=for-the-badge)

### 🚀 Backend & Deployment
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=for-the-badge&logo=streamlit&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white)
![DuckDB](https://img.shields.io/badge/DuckDB-FFF000?style=for-the-badge&logo=duckdb&logoColor=black)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-336791?style=for-the-badge&logo=postgresql&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Azure](https://img.shields.io/badge/Azure-0078D4?style=for-the-badge&logo=microsoftazure&logoColor=white)
![GCP](https://img.shields.io/badge/GCP-4285F4?style=for-the-badge&logo=googlecloud&logoColor=white)

### 📊 MLOps & Optimization
![MLflow](https://img.shields.io/badge/MLflow-0194E2?style=for-the-badge&logo=mlflow&logoColor=white)
![Weights & Biases](https://img.shields.io/badge/W&B-FFBE00?style=for-the-badge&logo=weightsandbiases&logoColor=black)
![Grafana](https://img.shields.io/badge/Grafana-F46800?style=for-the-badge&logo=grafana&logoColor=white)
![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=for-the-badge&logo=prometheus&logoColor=white)
![ONNX](https://img.shields.io/badge/ONNX-005CED?style=for-the-badge&logo=onnx&logoColor=white)
![TensorRT](https://img.shields.io/badge/TensorRT-76B900?style=for-the-badge&logo=nvidia&logoColor=white)
![CUDA](https://img.shields.io/badge/CUDA-76B900?style=for-the-badge&logo=nvidia&logoColor=white)
![Qdrant](https://img.shields.io/badge/Qdrant-DC382D?style=for-the-badge)
![Neo4j](https://img.shields.io/badge/Neo4j-4581C3?style=for-the-badge&logo=neo4j&logoColor=white)

### 🔧 Tools
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)
![MATLAB](https://img.shields.io/badge/MATLAB-0076A8?style=for-the-badge&logo=mathworks&logoColor=white)
![LaTeX](https://img.shields.io/badge/LaTeX-008080?style=for-the-badge&logo=latex&logoColor=white)

</div>

---

## 📊 GitHub Profile Stats

<div align="center">

### 🔥 Streak Stats
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://nirzak-streak-stats.vercel.app/?user=CodeNinjaSarthak&theme=dark&hide_border=true&background=0D1117&stroke=6366F1&ring=6366F1&fire=FF6B6B&currStreakLabel=FFFFFF&sideLabels=6366F1" />
  <source media="(prefers-color-scheme: light)" srcset="https://nirzak-streak-stats.vercel.app/?user=CodeNinjaSarthak&theme=default&hide_border=true&stroke=6366F1&ring=6366F1&fire=FF6B6B&currStreakLabel=333333&sideLabels=6366F1" />
  <img src="https://nirzak-streak-stats.vercel.app/?user=CodeNinjaSarthak&theme=dark&hide_border=true&background=0D1117&stroke=6366F1&ring=6366F1&fire=FF6B6B&currStreakLabel=FFFFFF&sideLabels=6366F1" alt="GitHub Streak" width="100%"/>
</picture>


<br/><br/>



### 📈 Contribution Graph
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://github-readme-activity-graph.vercel.app/graph?username=CodeNinjaSarthak&theme=tokyo-night&hide_border=true&bg_color=0D1117&color=6366F1&line=6366F1&point=FF6B6B" />
  <source media="(prefers-color-scheme: light)" srcset="https://github-readme-activity-graph.vercel.app/graph?username=CodeNinjaSarthak&theme=minimal&hide_border=true&color=6366F1&line=6366F1&point=FF6B6B" />
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=CodeNinjaSarthak&theme=tokyo-night&hide_border=true&bg_color=0D1117&color=6366F1&line=6366F1&point=FF6B6B" alt="Contribution Graph" width="100%"/>
</picture>

</div>
<!-- <div align="center">
  <img src="https://github-profile-trophy.vercel.app/?username=CodeNinjaSarthak&v=1&theme=discord&no-frame=true&no-bg=true&column=7&margin-w=10" alt="GitHub Trophies"/>
</div> -->

---

## 🐍 Contribution Graph

<div align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/CodeNinjaSarthak/CodeNinjaSarthak/output/github-snake-dark.svg" />
    <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/CodeNinjaSarthak/CodeNinjaSarthak/output/github-snake.svg" />
    <img alt="github-snake" src="https://raw.githubusercontent.com/CodeNinjaSarthak/CodeNinjaSarthak/output/github-snake.svg" />
  </picture>
</div>

---

## 🏆 Achievements

<div align="center">

| 🥇 Hackathons & Competitions | 🎓 Academic | 📜 Certifications |
|:---:|:---:|:---:|
| **Amazon ML Challenge 2024**<br/>Top 0.5% (409/74,823) | **Dean's List Award**<br/>Top 10% | IBM Machine Learning |
| **IIT Bombay Convolve**<br/>Top 50/4,189 Teams | CGPA: **9.42/10.0** | Deep Learning Specialization (Andrew Ng) |
| **Kharagpur Data Science**<br/>Semi-finalist | Published @ **IC3SE 2025** | GenAI with LLMs |
| | | AI Agents Intensive — Google × Kaggle 2025 |

</div>

---

## 📚 Research & Publications

<div align="center">

📄 **"Hinglish Abusive Comment Detection Using Transformer-Based Models"** (First Author)
*Accepted at AICAPS 2026, IEEE Kerala Section — XLM-R + BiGRU, F1 0.866 on 700K+ code-mixed posts*

📄 **"Image and Video Dehazing for Dense-Fog Indian Highway Scenarios"** (First Author)
*Accepted at DICCT 2026 — Benchmarked 10 dehazing methods; identified 15–20 dB PSNR gap between synthetic benchmarks and real dense-fog conditions*

📄 **"Deep Learning-Based Brain Tumour Identification"** (Second Author)
*Accepted & Presented at IC3SE 2025, IEEE UP Section — Residual CNN, 97.10% accuracy at 5M parameters*

</div>

---

## 💭 Dev Quote

<div align="center">
  <img src="https://quotes-github-readme.vercel.app/api?type=horizontal&theme=tokyonight" alt="Dev Quote"/>
</div>

---

## 🤝 Let's Connect!

<div align="center">
  
<p>I'm always excited to collaborate on innovative AI/ML projects!</p>

💼 **Open to:** Research Collaborations | Open Source | AI/ML Internships

📧 **Reach me at:** [sarthak4156@gmail.com](mailto:sarthak4156@gmail.com)

<br/>

[![](https://visitcount.itsvg.in/api?id=CodeNinjaSarthak&icon=6&color=6)](https://visitcount.itsvg.in)

</div>

---

<div align="center">
  
<img src="https://capsule-render.vercel.app/api?type=waving&color=6366F1&height=100&section=footer"/>

</div>
