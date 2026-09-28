# Hi, I'm Tanmoy Chowdhury Turjo 👋

**Full-stack & AI systems engineer · 3rd-year CSE undergraduate at AUST, Dhaka**

I build systems where precision, concurrency, and real-world constraints matter — hyper-local routing engines, microgrid LP optimization, high-throughput transactional databases, and verifiable multi-LLM evaluation pipelines. Most of what's here started at a hackathon and ended up deployed.

🌐 [**turjo-portfolio.onrender.com**](https://turjo-portfolio.onrender.com) &nbsp;·&nbsp; 💼 [LinkedIn](https://linkedin.com) &nbsp;·&nbsp; ✉️ [turjo5892@gmail.com](mailto:turjo5892@gmail.com)

---

## 🚀 Featured Projects

### 🚦 [Goli Transit (EZZ GO)](https://github.com/Turjo101365/Goli-Transit) · [Live ↗](https://frontend-nine-ashen-17.vercel.app)
Multi-modal urban routing platform engineered to resolve Dhaka's mobility bottlenecks across narrow alleyways (*golis*), Metro Rail (MRT-6), and arterial roads. Computes multi-modal paths across car, bus, CNG, rickshaw, and walking using Dijkstra / A* with configurable mode-switch penalties over high-density road networks. Features dynamic fare estimation, 3D transit corridor simulations, and real-time disruption rerouting.

`Node.js` `Express` `React` `Three.js` `Leaflet GIS` `MySQL` `Redis` `Zod`

---

### ⚡ [GridWise](https://github.com/fairuz-anadi/gridWise) · [Live ↗](https://gridwise-hampton.onrender.com)
Smart campus microgrid energy scheduling service uniting natural language processing, deterministic safety guardrails, and exact mathematical optimization. Decouples linguistic extraction from numerical optimization: an LLM parses unstructured operator directives into structured overrides, validates them via strict guardrails, and solves a 24-hour cost minimization schedule using a SciPy HiGHS linear programming solver across battery storage and solar tariffs.

`Python` `FastAPI` `SciPy (HiGHS LP)` `NumPy` `Pydantic` `OpenAI / Groq` `React` `TypeScript` `Docker`  
🏆 **BUP CSE Fest 2026 Software & AI Hackathon**

---

### 🎓 [AcadIQ](https://github.com/Turjo101365/AcadIQ) · [Live ↗](https://acadiq-platform.onrender.com)
AI-powered academic decision-support and question moderation platform. Audits syllabus coverage, balances Bloom's taxonomy, and detects historical exam redundancy. Features a zero-cloud local AI engine powered by Ollama for PDF RAG, alongside an automated Multi-LLM Jury evaluation pipeline cross-evaluating student answers against marking schemes across Qwen2.5, Phi3.5, and Mistral to detect scoring discrepancies.

`TypeScript` `Node.js` `Express` `React` `Prisma ORM` `MySQL` `Ollama` `Docker Compose`  
🏆 **AUST CSE Carnival AI Build Hackathon**

---

### 🎪 [MELA](https://github.com/Turjo101365/MELA) · [Live ↗](https://mela.runasp.net)
High-concurrency digital fair and commercial stall leasing platform engineered to eliminate double-booking race conditions during high-volume event surges. Built on a dual-ORM architecture pairing Dapper for high-speed stored procedures with Entity Framework Core for entity relations. Enforces atomic stall reservations using explicit SQL Server row-level update locks (`UPDLOCK, ROWLOCK`), admission capacity safety triggers, and automated xUnit CI/CD.

`C#` `.NET 8` `ASP.NET Core MVC` `SQL Server 2022` `Dapper` `EF Core` `Tailwind CSS` `Docker`

---

### 🫀 [Human Bio-Simulator 3D](https://github.com/Turjo101365/DNA) · [Live ↗](https://human-bio-simulator-dna.onrender.com)
Zero-cloud, browser-native biomedical simulation platform integrating touchless computer vision with volumetric 3D anatomical rendering. Runs Google MediaPipe Vision compiled to WebAssembly directly on the client's GPU to track 21 hand landmarks for touchless rotation, zoom, and spatial freeze. Drives real-time Three.js shaders across five physiological systems (cardiac cycle, synaptic brain waves, lungs, visceral tract, 36-bp DNA double-helix uncoiling) with an on-device Ollama medical telemetry assistant.

`JavaScript` `Three.js` `MediaPipe (WASM)` `React` `Ollama LLM` `Tailwind CSS`

---

### 🍳 [FridgeMama (Leftover Chef)](https://github.com/Turjo101365/FridgeMama) · [Live ↗](https://fridgemama.vercel.app)
Smart fridge vision and culinary companion that answers "what can I cook right now with what's in my fridge?". Integrates fine-tuned YOLO object detection models (`best.pt`) for ingredient identification, automated shelf-life prediction, and an overlap ranking engine that matches recipes to on-hand ingredients to reduce household food waste.

`Python` `YOLO` `FastAPI` `React` `Tailwind CSS` `Adminer`

---

### 💬 [OmniChat AI](https://github.com/Turjo101365/ai-chatbot-web)
Modular conversational AI gateway and retrieval-augmented generation engine engineered to eliminate vendor lock-in. Unifies OpenRouter, Hugging Face Serverless, and Botpress behind an abstract provider layer. Includes a LangChain.js document processing pipeline that parses PDFs, performs recursive text splitting, and executes vector similarity searches with persistent session history backed by MySQL.

`Node.js` `Express` `React` `LangChain.js` `MySQL` `Docker Compose` `Tailwind CSS`

---

## 🔬 Empirical Research

### [Is Quantization Language-Neutral?](https://github.com/Turjo101365)
Empirical evaluation benchmarking quantization degradation across low-resource South Asian languages (Bengali, Sinhala, Assamese, Nepali) against English. Tests `Qwen2.5-3B-Instruct` across FP16, INT8, and NF4 precisions on the BELEBELE benchmark using logit-level scoring to measure disproportionate accuracy drop in non-Latin scripts.

`Python` `PyTorch` `Hugging Face` `bitsandbytes` `BELEBELE Benchmark`

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

**Backend & Architecture**  
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

**Databases & Caching**  
![SQL Server](https://img.shields.io/badge/SQL_Server-CC292B?style=flat&logo=microsoftsqlserver&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat&logo=mysql&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat&logo=postgresql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat&logo=redis&logoColor=white)
![Prisma](https://img.shields.io/badge/Prisma-2D3748?style=flat&logo=prisma&logoColor=white)

**Tools & DevOps**  
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat&logo=git&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat&logo=githubactions&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat&logo=linux&logoColor=black)
![Postman](https://img.shields.io/badge/Postman-FF6C37?style=flat&logo=postman&logoColor=white)

---

## 🏆 Hackathons & Recognition

- 🥇 **Winner / Co-Developer**, BUP CSE Fest 2026 Software & AI Hackathon — *GridWise* (Campus Microgrid Optimization)
- 🚀 **Finalist / Lead AI**, AUST CSE Carnival AI Build Hackathon — *AcadIQ* (Multi-LLM Jury & Local RAG Moderation)

---

## 📊 GitHub Activity

<div align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=Turjo101365&show_icons=true&theme=tokyonight&hide_border=true&count_private=true" height="165" alt="GitHub Stats" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=Turjo101365&layout=compact&theme=tokyonight&hide_border=true" height="165" alt="Top Languages" />
</div>

---

<div align="center">
  <p>Crafted by Tanmoy Chowdhury Turjo · Powered by code and caffeine ☕</p>
  <p>
    <a href="https://turjo-portfolio.onrender.com">Portfolio</a> &nbsp;•&nbsp;
    <a href="mailto:turjo5892@gmail.com">Email</a> &nbsp;•&nbsp;
    <a href="https://github.com/Turjo101365">GitHub</a>
  </p>
</div>
