# Hi 👋, I'm Kevin (Cheng-Hsun Hsu)
**Data Engineer · ML/AI Engineer · M.S. Data Analytics Engineering @ George Mason University (May 2026)**

---

## 🙋‍♂️ About Me

- 🎓 M.S. **Data Analytics Engineering** @ George Mason University — graduating May 2026
- 🚀 Currently building a **production-grade Space Weather Aviation Risk platform** — 150GB/month telemetry pipeline with TimescaleDB/PostGIS, Prefect, Redis, FastAPI + SSE, and GitHub Actions CI/CD
- 🤖 Former **AI & Data Science Consultant** — shipped a 96%-accuracy custom OCR system, RAG chatbots, and LLM cost-optimization workflows saving clients **$12K+/year**
- 🔭 Exploring **LLM fine-tuning** (LoRA/QLoRA), **geospatial data engineering**, and **real-time streaming architectures**
- 🌱 Passionate about turning raw, messy data into reliable, scalable production systems
- 🏠 Homelab enthusiast — self-hosted Proxmox cluster with TrueNAS, Intel Arc GPU inference server, and 10+ Docker stacks
- 💬 Ask me about **PostgreSQL/TimescaleDB optimization**, **ETL pipelines**, **RAG systems**, or **self-hosted infrastructure**
- 📫 Reach me at **chenghsunhsu911@gmail.com**
- 🌐 Portfolio: [kevin-personal.shiba-toast.com](https://kevin-personal.shiba-toast.com/)
- ⚡ Fun fact: I run my own GPU inference server at home for experimenting with AI models before they hit production

---

## 🛠️ Tech Stack

**Languages:** Python · SQL · R · JavaScript · Go

**Data Engineering & Databases:** PostgreSQL · PostGIS · TimescaleDB · Redis · Prefect · PySpark · Elasticsearch · Qdrant · asyncpg

**ML & AI:** PyTorch · scikit-learn · LangChain · LangGraph · HuggingFace · BERT · LoRA/QLoRA · RAG · DSPY · OpenCV · Florence-2

**Cloud & DevOps:** Docker · GitHub Actions · AWS (EC2, Lambda) · Terraform · Linux · Proxmox · TrueNAS

**Visualization:** Tableau · Power BI · Matplotlib · Seaborn · ggplot2

---

## 🌟 Featured Projects

### 🛰️ [Space Weather Aviation Risk Dashboard](https://github.com/kevin000001505/Capstone.git) — GMU Capstone
> Production data platform assessing HF communication disruption risk for aviation from space weather events.
- Processed **150GB/month** of NOAA telemetry reliably via 10 concurrent Prefect pipelines with automated retry & failover
- **70% storage reduction** with zero data loss via migration to TimescaleDB hypertables with native compression
- **80% API speedup** through Redis caching layer eliminating redundant database queries
- **40% query performance gain** via PostgreSQL tuning (shared_buffers, WAL, checkpoints) and indexing strategy
- Real-time frontend updates via **Server-Sent Events (SSE)** replacing client-side polling
- **Zero production crashes** since adopting GitHub Actions CI/CD with full pytest coverage + branch protection
- PostGIS-powered geospatial flight path pipeline with COPY-based bulk ingestion

---

### 🤖 [Multimodal RAG Optimization](https://github.com/kevin000001505/Skynet.git) — University Project
> Research project benchmarking and improving multimodal retrieval-augmented generation pipelines.
- **10% accuracy gain** over Llama 3.2 baseline via LoRA fine-tuning on 4-bit quantized model
- **5% RAG accuracy boost** by integrating Florence-2 image captioning for semantic retrieval
- Manual ELIP framework implementation in low-level PyTorch for rigorous architectural benchmarking

---

### 💬 [George Mason University AI Chatbot](https://github.com/kevin000001505/GMU-chatbot.git) — Personal Project
> Real-time RAG chatbot for GMU information, deployed on AWS with fully automated infrastructure.
- **40% response latency reduction** using LangGraph + DSPY optimization + C-RAG continuous pipeline
- Containerized with Docker, deployed on **AWS EC2** via **Terraform** IaC
- Vector search powered by Qdrant for high-speed semantic retrieval

---

### 🏆 [Restaurant Recommender](https://github.com/kevin000001505/Hackathon-Tinder-Restaurant.git) — GDG GMU Hackathon (3rd Place)
> Cold-start recommendation system using clustering + review embeddings for personalized ranking.
- Solved cold-start problem with **K-Prototypes clustering** + review embedding fusion
- Multi-threaded background processing for seamless real-time inference

---

### 🏠 [Self-Hosted Homelab Infrastructure](https://github.com/kevin000001505) — Personal Project
> Full-stack self-hosted Proxmox cluster for media, monitoring, and AI inference.
- Manages **10+ Docker Compose stacks** across VMs: Plex, Jellyfin, Immich, AdGuard, Grafana/Loki/Promtail
- Intel Arc GPU AI inference server with **OpenVINO** for accelerated ML model serving
- TrueNAS RAIDZ2 storage, Tailscale VPN, NPMplus reverse proxy, Komodo-managed CI/CD-style deployments

---

## 🔗 Connect with Me

- 💼 [LinkedIn](https://www.linkedin.com/in/cheng-hsun-hsu-a24517280/)
- 🌐 [Portfolio](https://kevin-personal.shiba-toast.com/)
- 📧 [chenghsunhsu911@gmail.com](mailto:chenghsunhsu911@gmail.com)
- 🐙 [GitHub](https://github.com/kevin000001505)

---

> *"Build systems that are boring to operate and exciting to build."*
