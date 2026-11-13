# Mohammad Anas Africawala

<div align="center">

**AI/ML Engineer & Systems Researcher**  
B.Tech in Artificial Intelligence & Data Science · Uka Tarsadia University (CGPIT)  
**Cumulative CGPA: 9.25 / 10.0** (Ranked **2nd** in Department) · **Final-Year GPA: 9.78 / 10.0** (Sem VII: 9.57 · Sem VIII: 10.00)

[Email](mailto:mohammad.anas.1367@gmail.com) • [LinkedIn](https://linkedin.com/in/mohammad-anas-africawala) • [GitHub](https://github.com/Anas18102004) • Gujarat, India

</div>

---

## 🔬 Engineering Focus & Research Philosophy

I build robust, reproducible software systems that bridge algorithmic machine learning with production software engineering. My technical focus spans:

- **Self-Supervised Representation Learning & Vision:** Investigating architecture-native representations in transformer and convolutional vision backbones, multi-scale geometric losses, and attention gradient diagnostics under severe labeling constraints.
- **Geospatial & Ecological AI:** Engineering multi-source Earth observation pipelines (Copernicus Marine NetCDF, ETOPO bathymetry) paired with spatial group cross-validation to prevent spatial autocorrelation leakage in environmental suitability modeling.
- **Information Retrieval & Agentic Systems:** Designing dense vector search microservices (SentenceTransformers, FAISS $L_2$-normalized inner product) and stateful multi-agent deliberation graphs (LangGraph, Model Context Protocol) with strict citation grounding to suppress hallucination.
- **Production Systems & Edge Computing:** Deploying high-throughput containerized microservices (FastAPI, Docker, CI/CD automated gates), edge computer vision with Raspberry Pi hardware actuation, and commercial desktop software published on the Microsoft Store.

---

## 🏛️ Core Technical Competencies

| Domain | Methodologies & Frameworks | Applied Systems & Architectures |
| :--- | :--- | :--- |
| **Machine Learning & Deep Learning** | PyTorch, TensorFlow, Scikit-Learn, XGBoost, YOLO (v5/v8/v12), Self-Supervised Learning (SimSiam, DenseCL), Representation Probing (CKA), Isotonic Calibration | Low-budget SSL pretraining, spatial cross-validation, gradient magnitude forensics, classification & detection |
| **NLP, LLMs & Retrieval (RAG)** | SentenceTransformers, LangChain, LangGraph, CrewAI, FAISS, Qdrant, Model Context Protocol (MCP), PEFT/LoRA | Grounded QA microservices, adversarial deliberation graphs, multi-tenant vector databases, clinical decision support |
| **Computer Vision & Geospatial** | OpenCV, MediaPipe, Copernicus Marine NetCDF, xarray, ETOPO Bathymetry, Rasterio, GDAL | Real-time optical gesture control, traffic density estimation, multi-temporal oceanographic feature grids |
| **Backend, Cloud & Embedded** | Python, C/C++, TypeScript, FastAPI, Flask, Docker, DigitalOcean, AWS, GitHub Actions CI/CD, Linux, Raspberry Pi GPIO | Asynchronous REST APIs, zero-downtime CI/CD deployment gates, hardware motor actuation, native C recompilation |

---

## 🚀 Featured Flagship Projects

| Project | Domain & Architecture | Key Engineering Highlights & Verified Metrics | Codebase |
| :--- | :--- | :--- | :---: |
| **[native-attention-ssl](https://github.com/Anas18102004/native-attention-ssl)** | **Vision Representation Research**<br>`YOLOv12n` · `Area-Attention` · `PyTorch Hooks` · `VOC 2007` | Investigated architecture-native SSL extracting Query/Key relations from YOLOv12's Area-Attention blocks under a fixed **500-image labeled budget** with all 4,952 test images strictly quarantined. Across 3 seeds on a 0–100% mAP scale, downstream validation showed an inconclusive delta of **+0.0416 percentage points in mAP50-95** (SD 0.2266 pp). Diagnostic gradient audits revealed native attention contributed ~1.16% of dense gradient magnitude, identifying signal attenuation in low-data regimes. | [Repository](https://github.com/Anas18102004/native-attention-ssl) |
| **[Strong-Seaweed](https://github.com/Anas18102004/Strong-Seaweed)** | **Geospatial Ecological AI**<br>`XGBoost` · `Copernicus NetCDF` · `ETOPO` · `Spatial CV` | Fused 23 physical oceanographic predictors across 246 marine occurrences along the Gulf of Mannar shelf. Mitigated spatial autocorrelation leakage via **5-fold Spatial Group Cross-Validation**. Achieved internal **spatial-CV ROC-AUC of 0.9288 ± 0.1226**, spatial AP of 0.9042, and out-of-fold Brier score of 0.0944 with automated CI release gates. | [Repository](https://github.com/Anas18102004/Strong-Seaweed) |
| **[MedRag](https://github.com/Anas18102004/MedRag)** | **Biomedical RAG Microservice**<br>`SentenceTransformers` · `FAISS IndexFlatIP` · `Flask` · `Docker` | Containerized semantic search microservice over curated PubMed clinical abstracts. Generates 768-D embeddings (`all-mpnet-base-v2`) with unit $L_2$ normalization for exact inner-product cosine search. Measured an average cosine-similarity margin of **0.138 between top-1 matching citations and nearest non-matching distractors**, maintaining **sub-50ms query vector retrieval latency**. | [Repository](https://github.com/Anas18102004/MedRag) |
| **[NyaySetu](https://github.com/Anas18102004/NyaySetu)** | **Multi-Agent Legal Deliberation Platform**<br>`LangGraph` · `Dense RAG` · `FastAPI` · `React` · `Docker` | Full-stack legal reasoning platform pairing retrieval-augmented generation with a multi-agent adversarial deliberation graph (opposing counsel, neutral judge, client advocate). Features case-session memory, multi-turn state persistence, bilingual support, and Twilio/IVR telephone gateway integration. | [Repository](https://github.com/Anas18102004/NyaySetu) |
| **[Robo (Jerry)](https://github.com/Anas18102004/Robo)** | **Autonomous Vision Robot**<br>`Raspberry Pi 4` · `YOLO` · `OpenCV` · `MediaPipe` · `GPIO` | Physical autonomous mobile robot equipped with optical vision tracking and motor-driven actuation arm. Maps spoken natural language commands to real-time YOLO visual object detection and MediaPipe hand/face gesture recognition with low-latency GPIO pulse-width modulation (PWM). | [Repository](https://github.com/Anas18102004/Robo) |
| **[mindmesh-traffic-vision](https://github.com/Anas18102004/mindmesh-traffic-vision)** | **Intelligent Traffic Vision System**<br>`OpenCV` · `Object Tracking` · `TypeScript` · `Vite` | Edge-capable computer vision system for intersection traffic analytics. Processes real-time multi-lane video streams to estimate vehicle density, queue lengths, optical flow velocities, and dynamic congestion indexes with interactive telemetry visualization. | [Repository](https://github.com/Anas18102004/mindmesh-traffic-vision) |
| **[cricket-legacy](https://github.com/Anas18102004/cricket-legacy)** | **Systems Engine Recompilation**<br>`C/C++` · `Android NDK` · `OpenGL ES` · `Memory Layout` | Low-level static recompilation and native Android port of a legacy 3D game engine. Reconstructs binary memory layouts, endianness translation, asset packaging pipelines, and cross-compilation toolchains for modern ARM64-v8a architectures. | [Repository](https://github.com/Anas18102004/cricket-legacy) |
| **CertiStock** | **Commercial Document AI (AinzaTechLabs)**<br>`Python` · `OpenCV` · `Node.js` · `Microsoft Store` | Commercial production desktop software published on the **Microsoft Store** for textile manufacturing supply chains. Implements automated OCR alignment and inventory reconciliation pipelines, processing 500+ weekly certification sheets with 92%+ field-extraction accuracy across non-standard layouts. | [Commercial Software](https://github.com/Anas18102004/certistock) |

---

## 🏆 Selected Honors & Competitive Achievements

- **Google Student Ambassador:** Selected through a competitive national process to lead campus AI innovation workshops and Google Gemini technology initiatives.
- **National Hackathon Distinctions:**
  - **Winner** — Innosprint (2025)
  - **Top 7 Finalist** — ML-Fiesta, IIIT Bangalore
  - **Top 10 Finalist** — Codeversity Hackathon, IIT Gandhinagar
- **Competitive Innovation Awards:**
  - **Finalist (2024 and 2025)** — The Maverick Effect AI Challenge (NASSCOM / DMFT)
  - **Shortlisted Finalist** — Odoo National Hackathon 2025 (24-hr Offline Finals, Gandhinagar)
- **Technical Bootcamps:** Short-Term Training Program (STTP) on AI & Robotics (SVNIT) · Drone Technology Bootcamp (SVNIT).

---

## 📂 Portfolio Repository Navigation

```
├── 🔬 Research & Machine Learning
│   ├── native-attention-ssl     # Self-supervised YOLOv12 area-attention representation learning
│   ├── Strong-Seaweed           # Geospatial Earth observation & XGBoost suitability modeling
│   ├── MedRag                   # High-throughput biomedical vector retrieval microservice
│   ├── DeepFake                 # Media forensics & deepfake video verification pipeline
│   └── RAG-Conflict             # Empirical document conflict reconciliation benchmark
│
├── 🤖 Autonomous Agents & Full-Stack AI
│   ├── NyaySetu                 # LangGraph adversarial courtroom deliberation platform
│   ├── Law_Ivr                  # Twilio telephony & Whisper voice consultation gateway
│   ├── orbix-your-ai-team-navigator # Multi-agent workflow coordination workspace
│   └── Prompt-To-animation      # Natural language to parametric animation engine
│
├── 👁️ Computer Vision & Robotics
│   ├── Robo (Jerry)             # Raspberry Pi 4 autonomous vision robot with GPIO arm
│   ├── mindmesh-traffic-vision  # Real-time traffic queue & density analytics platform
│   └── Flappy-Bird-Using-CV     # Optical gesture control interface via MediaPipe
│
└── ⚙️ Systems & Low-Level Engineering
    └── cricket-legacy           # C/C++ native game engine port for modern Android ARM64
```

---

<div align="center">

*Maintained with rigorous engineering standards, verified reproducibility, and empirical integrity.*

</div>
