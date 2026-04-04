# Hi 👋, I'm Kevin (Cheng-Hsun Hsu)
**Data Engineer · ML/AI Engineer · M.S. Data Analytics Engineering @ George Mason University**

---

## 🙋‍♂️ About Me

- 🎓 M.S. **Data Analytics Engineering** @ George Mason University (graduating May 2026)
- 🚀 Currently building a **production-grade Space Weather Aviation Risk platform** — 150GB/month telemetry pipeline with PostgreSQL/PostGIS, Prefect, Redis, FastAPI + SSE, and GitHub Actions CI/CD
- 🤖 Former **AI & Data Consultant** — built RAG chatbots, custom OCR models (96% accuracy), and automation workflows that saved clients $12K+/year
- 🔭 Exploring **LLM fine-tuning** (LoRA/QLoRA), **geospatial data engineering**, and **real-time streaming architectures**
- 🌱 Passionate about turning raw, messy data into reliable, scalable production systems
- 🏠 Homelab enthusiast — self-hosted Proxmox cluster with TrueNAS, Intel Arc GPU inference server, and 10+ Docker stacks
- 💬 Ask me about **PostgreSQL optimization**, **ETL pipelines**, **RAG systems**, or **self-hosted infrastructure**
- 📫 Reach me at **chenghsunhsu911@gmail.com**
- ⚡ Fun fact: I run my own GPU inference server at home for experimenting with AI models before they hit production

---

## 🛠️ Tech Stack

**Languages:** Python · SQL · R · JavaScript · Go

**Data Engineering & Databases:** PostgreSQL · PostGIS · Redis · Prefect · PySpark · Elasticsearch · Qdrant · asyncpg

**ML & AI:** PyTorch · scikit-learn · LangChain · LangGraph · HuggingFace · BERT · LoRA/QLoRA · RAG · DSPY · OpenCV

**Cloud & DevOps:** Docker · GitHub Actions · AWS (EC2, Lambda) · Terraform · Linux · Proxmox · TrueNAS

**Visualization:** Tableau · Power BI · Matplotlib · Seaborn · ggplot2

---

## 🌟 Featured Projects

### 🛰️ [Space Weather Aviation Risk Dashboard](https://github.com/kevin000001505) — GMU Capstone
> Production data platform assessing HF communication disruption risk for aviation from space weather events.
- Processes **150GB/month** of NOAA telemetry via 10 concurrent Prefect pipelines with automated retry & failover
- **70% storage reduction** via PostgreSQL partitioning, indexing strategy, and data lifecycle management
- **50% API speedup** through Redis caching layer eliminating redundant DB queries
- Real-time updates via **Server-Sent Events (SSE)** + async FastAPI backend (asyncpg)
- Full **CI/CD with GitHub Actions + pytest** — zero production crashes since adoption
- PostGIS-powered geospatial flight path pipeline with COPY-based bulk ingestion

---

### 🤖 [Multimodal RAG Optimization](https://github.com/kevin000001505) — University Project
> Research project benchmarking and improving multimodal retrieval-augmented generation pipelines.
- **10% accuracy gain** over Llama 3.2 baseline via LoRA fine-tuning on 4-bit quantized model
- **5% RAG accuracy boost** by integrating Florence-2 image captioning for semantic retrieval
- Manual ELIP framework implementation in low-level PyTorch for rigorous architectural benchmarking

---

### 💬 [George Mason University AI Chatbot](https://github.com/kevin000001505) — Personal Project
> Real-time RAG chatbot for GMU information, deployed on AWS with fully automated infrastructure.
- **40% response latency reduction** using LangGraph + DSPY optimization + C-RAG continuous pipeline
- Containerized with Docker, deployed on **AWS EC2** via **Terraform** IaC
- Vector search powered by Qdrant for high-speed semantic retrieval

---

### 🏆 [Restaurant Recommender](https://github.com/kevin000001505) — GDG GMU Hackathon (3rd Place)
> Cold-start recommendation system using clustering + review embeddings for personalized ranking.
- Solved cold-start problem with **K-Prototypes clustering** + review embedding fusion
- Multi-threaded background processing for seamless real-time inference

---

### 🏠 [Self-Hosted Homelab Infrastructure](https://github.com/kevin000001505) — Personal Project
> Full-stack self-hosted Proxmox cluster for media, monitoring, and AI inference.
- Manages **10+ Docker Compose stacks** across VMs: Plex, Jellyfin, Immich, AdGuard, Grafana/Loki
- Intel Arc GPU AI inference server with **OpenVINO** for accelerated ML model serving
- TrueNAS RAIDZ2 storage, Tailscale VPN, Nginx Proxy Manager, automated backups

---



## 🔗 Connect with Me

- 💼 [LinkedIn](https://www.linkedin.com/in/cheng-hsun-hsu-a24517280/)
- 📧 [chenghsunhsu911@gmail.com](mailto:chenghsunhsu911@gmail.com)
- 🐙 [GitHub](https://github.com/kevin000001505)

---

> *"Build systems that are boring to operate and exciting to build."*
