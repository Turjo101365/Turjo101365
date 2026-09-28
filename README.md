# Hi, I'm Tanmoy Chowdhury Turjo 👋

**Computer Science & Engineering student building AI-powered systems, high-concurrency backend architectures, and intelligent algorithmic platforms.**

---

### 👨‍💻 About Me

I am a software engineer and AI researcher focused on designing reliable, data-driven systems that bridge complex algorithms with production-ready software. My work spans **full-stack and backend engineering** (distributed architectures, concurrency-safe database design, and graph-based routing engines) and **applied artificial intelligence** (Retrieval-Augmented Generation, multi-LLM jury evaluation pipelines, on-device WebAssembly computer vision, and exact linear programming). 

Whether engineering real-time routing engines for high-density urban environments, preventing race conditions in high-throughput transactional services, or investigating cross-lingual degradation in quantized large language models, I prioritize architectural rigor, deterministic guardrails, and real-world impact.

---

### 🚀 Featured Projects

#### [EZZ GO (Goli-Transit) — Multi-Modal Urban Routing Engine & Command Center](https://github.com/Turjo101365/Goli-Transit)
A hyper-local transit routing platform engineered to resolve Dhaka's mobility bottlenecks across alleyways (*golis*), multi-modal networks (MRT-6 Metro, city buses, CNGs, rickshaws), and arterial corridors. Implements graph-based shortest path routing (A* / Dijkstra) with real-time disruption rerouting, dynamic congestion penalties, and crowdsourced incident verification. Features a database-driven dynamic fare engine, 3D Three.js transit corridor simulations, bilingual localization (English/Bengali), and an administrative operations command center.  
*Key Contribution: Primary architect and author (85 commits); engineered the graph routing core, dynamic fare calculator, and full-stack API integration.*

`Node.js` · `Express.js` · `React 18` · `Three.js` · `Leaflet GIS` · `MySQL 8` · `Redis` · `Zod`  
[Live Demo ↗](https://frontend-nine-ashen-17.vercel.app) · 🏆 **Champion**, IEEE WIE Day 2026 National Idea Presentation · 🎖️ **4th Place**, AUST CSE Carnival Hackathon

---

#### [GridWise — Smart Campus Energy Optimization Engine](https://github.com/fairuz-anadi/gridWise)
An intelligent microgrid scheduling service uniting natural language processing, deterministic safety guardrails, and exact mathematical optimization to orchestrate 24-hour campus energy dispatch. Solves LLM arithmetic hallucination by decoupling linguistic extraction from numerical optimization: language models parse unstructured operator directives ("derate feeder 5 PM–8 PM", "reserve 40% battery") into structured overrides, validate them via strict guardrails, and submit them to a SciPy HiGHS linear programming solver that minimizes electricity purchase costs across battery storage, solar self-consumption, and fluctuating tariffs.  
*Key Contribution: Co-developed the system; authored the LLM Semantic Interpretation layer, structured prompt engineering, and deterministic constraint validation guardrails.*

`Python 3.12` · `FastAPI` · `SciPy (HiGHS LP)` · `NumPy` · `Pydantic` · `OpenAI / Groq` · `React 19` · `TypeScript` · `Docker`  
[Live Demo ↗](https://gridwise-hampton.onrender.com) · 🏆 **BUP CSE Fest 2026 Software & AI Hackathon**

---

#### [AcadIQ — Academic Intelligence & Multi-LLM Exam Moderation Platform](https://github.com/Turjo101365/AcadIQ)
An AI-powered academic decision-support platform designed to assist university faculty in syllabus coverage auditing, Bloom's taxonomy balancing, and historical question redundancy detection. Features a privacy-preserving local AI engine powered by Ollama for zero-cloud PDF RAG and question generation, alongside a Multi-LLM Jury evaluation pipeline that cross-evaluates student answers against marking schemes across diverse models (Qwen2.5, Phi3.5, Mistral) to detect scoring discrepancies with transparent attribution.  
*Key Contribution: Primary contributor (33 commits); architected the local Ollama RAG subsystem, multi-model evaluation pipeline, BeSTRaP dataset integration, and Docker containerization.*

`TypeScript` · `Node.js` · `Express` · `React 18` · `Prisma ORM` · `MySQL 8` · `Ollama` · `Docker Compose`  
🏆 **AUST CSE Carnival AI Build Hackathon**

---

#### [MELA — High-Concurrency Digital Fair & Event Management System](https://github.com/Turjo101365/MELA)
An enterprise festival coordination and commercial stall leasing platform engineered to eliminate double-booking race conditions during high-volume event surges. Built on a dual-ORM architecture pairing Dapper for high-speed stored procedures and analytical views with Entity Framework Core for entity relations. Enforces atomic stall reservations under millisecond concurrency using explicit SQL Server row-level update locks (`UPDLOCK, ROWLOCK`), admission capacity safety triggers, and automated xUnit CI/CD pipelines.  
*Key Contribution: Lead database & backend architect; designed the concurrency-safe transactional model, stored procedures, triggers, role-based security layers, and CI/CD pipelines.*

`C# 12` · `.NET 8` · `ASP.NET Core MVC` · `SQL Server 2022` · `Dapper` · `EF Core` · `Tailwind CSS` · `Docker` · `GitHub Actions`  
[Live Demo ↗](https://mela.runasp.net)

---

#### [Human Bio-Simulator 3D — On-Device Computer Vision & Biomedical Simulation](https://github.com/Turjo101365/DNA)
A zero-cloud, browser-native biomedical simulation platform integrating touchless computer vision with volumetric 3D anatomical rendering. Runs Google MediaPipe Vision compiled to WebAssembly directly on the client's GPU to track 21 hand landmarks, deriving kinematic rotations, optical zooms, and spatial freezes for touchless manipulation. Drives real-time Three.js shaders across five physiological systems (4-chamber cardiac cycle, EEG synaptic brain waves, bronchial lungs, visceral tract, 36-bp DNA double-helix uncoiling), supplemented by a live biophysical telemetry HUD and a local context-aware Ollama medical AI assistant with English and Bengali localization.  
*Key Contribution: Single author; engineered the MediaPipe WASM tracking pipeline, kinematic smoothing, Three.js procedural shaders, and local LLM telemetry injection.*

`JavaScript` · `Three.js (WebGL 2.0)` · `MediaPipe Vision (WASM)` · `React 18` · `Ollama LLM` · `Tailwind CSS`

---

#### [OmniChat AI — Multi-Provider Conversational AI & LangChain RAG Orchestrator](https://github.com/Turjo101365/ai-chatbot-web)
A modular conversational AI gateway and retrieval-augmented generation engine engineered to eliminate vendor lock-in and client-side secret exposure. Unifies OpenRouter, Hugging Face Serverless, and Botpress behind an abstract provider layer. Includes a LangChain.js document processing pipeline that parses PDFs, performs recursive text splitting, and executes in-memory vector similarity searches, with persistent session history, token usage telemetry, and rate limiting backed by MySQL 8.0.  
*Key Contribution: Single author; built the provider abstraction framework, vector retrieval pipeline, Docker containerization, and sanitized credential isolation.*

`Node.js` · `Express.js` · `React 18` · `LangChain.js` · `MySQL 8.0` · `Docker Compose` · `Tailwind CSS`

---

## 🛠️ Tech Stack

**Languages**  
![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)
![C#](https://img.shields.io/badge/C%23-239120?style=flat&logo=csharp&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=flat&logo=cplusplus&logoColor=white)
![PHP](https://img.shields.io/badge/PHP-777BB4?style=flat&logo=php&logoColor=white)

**AI / Machine Learning & Optimization**  
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat&logo=langchain&logoColor=white)
![Ollama](https://img.shields.io/badge/Ollama-000000?style=flat&logo=ollama&logoColor=white)
![MediaPipe](https://img.shields.io/badge/MediaPipe-0097A7?style=flat&logo=google&logoColor=white)
![SciPy](https://img.shields.io/badge/SciPy-8CAAE6?style=flat&logo=scipy&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat&logo=numpy&logoColor=white)
![Hugging Face](https://img.shields.io/badge/Hugging_Face-FFD21E?style=flat&logo=huggingface&logoColor=black)
![OpenAI](https://img.shields.io/badge/OpenAI-412991?style=flat&logo=openai&logoColor=white)

**Backend**  
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat&logo=nodedotjs&logoColor=white)
![Express](https://img.shields.io/badge/Express-000000?style=flat&logo=express&logoColor=white)
![ASP.NET Core](https://img.shields.io/badge/ASP.NET_Core-512BD4?style=flat&logo=dotnet&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat&logo=fastapi&logoColor=white)
![Laravel](https://img.shields.io/badge/Laravel-FF2D20?style=flat&logo=laravel&logoColor=white)

**Frontend & 3D**  
![React](https://img.shields.io/badge/React-61DAFB?style=flat&logo=react&logoColor=black)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=flat&logo=vite&logoColor=white)
![Three.js](https://img.shields.io/badge/Three.js-000000?style=flat&logo=threedotjs&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=flat&logo=tailwindcss&logoColor=white)

**Databases**  
![SQL Server](https://img.shields.io/badge/SQL_Server-CC292B?style=flat&logo=microsoftsqlserver&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat&logo=mysql&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat&logo=postgresql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat&logo=redis&logoColor=white)
![Prisma](https://img.shields.io/badge/Prisma-2D3748?style=flat&logo=prisma&logoColor=white)

**Tools & Other**  
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat&logo=git&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat&logo=githubactions&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat&logo=linux&logoColor=black)
![Postman](https://img.shields.io/badge/Postman-FF6C37?style=flat&logo=postman&logoColor=white)

---

### 🔬 Research & Technical Interests

- **Multilingual LLM Evaluation & Quantization**: Investigating whether bitsandbytes quantization degrades model accuracy disproportionately for low-resource languages compared to English. Actively evaluating models such as `Qwen/Qwen2.5-3B-Instruct` across FP16, INT8, and NF4 on the BELEBELE benchmark across South Asian languages (Bangla, Sinhala, Assamese, Nepali).
- **Constrained Optimization & Neuro-Symbolic Guardrails**: Bridging probabilistic language models with deterministic mathematical solvers (combining LLM semantic parsing with exact linear programming solvers like SciPy HiGHS) to solve resource-scheduling and microgrid dispatch problems without arithmetic hallucinations.
- **On-Device Vision & Privacy-Preserving AI**: Deploying client-side WebAssembly models (Google MediaPipe, local Ollama endpoints, fine-tuned YOLO sidecars) to enable zero-latency, private, touchless interaction without transmitting sensitive telemetry to cloud providers.

---

### 🏅 Achievements & Hackathons



- 🚀 **BUP CSE Fest 2026 Software & AI Hackathon** — *GridWise*  
  Co-developer: Built the LLM semantic parser, prompt engineering schemas, and deterministic validation guardrails for campus microgrid energy optimization.
- 🚀 **AUST CSE Carnival AI Build Hackathon** — *AcadIQ*  
  Lead AI & Backend Developer: Engineered the local Ollama RAG system, 4-model multi-LLM jury evaluation pipeline, and BeSTRaP dataset benchmarks.
- 🔬 **Is Quantization Language-Neutral? (Research Pipeline)**  
  Collaborative empirical study evaluating quantization precision degradation (FP16 vs. INT8 vs. NF4) on low-resource languages using logit-level scoring and the BELEBELE benchmark.
- 🍳 **FridgeMama (Leftover Chef)** — *Smart Fridge Vision Companion*  
  Integrated fine-tuned YOLO object detection models (`best.pt`), vocabulary mapping, and Adminer service for automated ingredient shelf-life prediction and recipe matching. [Live Demo ↗](https://fridgemama.vercel.app)

---

### 📊 GitHub Activity & Statistics

<div align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=Turjo101365&show_icons=true&theme=tokyonight&hide_border=true&count_private=true" height="165" alt="GitHub Stats" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=Turjo101365&layout=compact&theme=tokyonight&hide_border=true" height="165" alt="Top Languages" />
</div>

---

### 🔭 Current Focus

- 🤖 **Multi-Model AI Evaluation & Agentic RAG**: Scaling multi-LLM jury architectures combining local models (Ollama) with cloud gateways for automated domain assessment.
- ⚡ **High-Throughput Concurrency & Operations**: Hardening transaction safety using pessimistic locking patterns in relational databases and algorithmic dispatch optimization.
- 📐 **Edge AI & Quantization Trade-offs**: Analyzing downstream task performance across quantized model topologies for under-represented languages.

---

### 📫 Get in touch

<div align="center">

[![Portfolio](https://img.shields.io/badge/Portfolio-000000?style=for-the-badge&logo=vercel&logoColor=white)](https://github.com/Turjo101365/portfolio)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](YOUR_LINKEDIN_URL)
[![Email](https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:acd776959@gmail.com)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Turjo101365)

</div>
