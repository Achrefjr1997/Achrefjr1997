<h1 align="center">Hi 👋, I'm Achref Jarray</h1>
<h3 align="center">Senior AI Engineer · Computer Vision · LLMs & RAG · Edge AI</h3>

<p align="center">
  <a href="https://www.linkedin.com/in/achrefjarray/"><img src="https://img.shields.io/badge/LinkedIn-achrefjarray-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
  <a href="mailto:achref.jarray1997@gmail.com"><img src="https://img.shields.io/badge/Email-Contact%20me-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"/></a>
  <a href="https://doi.org/10.1007/s43069-022-00163-7"><img src="https://img.shields.io/badge/Publication-Springer-4A90E2?style=for-the-badge&logo=springer&logoColor=white" alt="Publication"/></a>
</p>

---

### 🧠 About me

I build **production AI systems** end to end — from data and model training to optimized deployment and monitoring. Over the past 5+ years I've worked across **defense, sports analytics, and healthcare**, shipping computer vision pipelines, LLM-powered assistants, and fully offline edge AI.

- 🔭 Currently a **Senior AI Engineer at Perfanalysis Consulting**, building football performance analysis with CV + LLMs
- ⚽ Detection, multi-object tracking (ReID), and action recognition on match footage — **75% faster** processing via GPU batching & parallelization
- 🤖 MCP-based AI assistant over **PostgreSQL + Neo4j** with sub-3s answers to tactical queries
- 🩺 Agentic RAG & **GraphRAG** over medical and performance records
- 🛰️ Previously built **offline edge AI** for the Tunisian Armed Forces — 30 FPS at **<45 ms** latency with ONNX Runtime + INT8
- 🔄 Built **Cobpy**, an agentic COBOL → Python migrator with multi-tier validation and confidence scoring
- 🌦️ Author of a full-coverage **Open-Meteo MCP server** (33 tools) and its Streamlit AI client
- 🏆 **3rd place** in Solafune's Aerosol Optical Depth (AOD) estimation competition
- 📄 Published research on mini-UAV detection in low-visibility conditions

---

### 🛠️ Tech stack

**Languages & ML**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=flat-square&logo=tensorflow&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB)

**Computer Vision**

![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=flat-square&logo=opencv&logoColor=white)
![Ultralytics](https://img.shields.io/badge/Ultralytics%20YOLO-111F68?style=flat-square&logo=ultralytics&logoColor=white)
![ONNX](https://img.shields.io/badge/ONNX%20Runtime-005CED?style=flat-square&logo=onnx&logoColor=white)
![Supervision](https://img.shields.io/badge/Supervision-8315F9?style=flat-square)
![SAHI](https://img.shields.io/badge/SAHI-2E7D32?style=flat-square)

**LLMs & RAG**

![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square&logo=langchain&logoColor=white)
![LangGraph](https://img.shields.io/badge/LangGraph-1C3C3C?style=flat-square&logo=langgraph&logoColor=white)
![LlamaIndex](https://img.shields.io/badge/LlamaIndex-000000?style=flat-square)
![Ollama](https://img.shields.io/badge/Ollama-000000?style=flat-square&logo=ollama&logoColor=white)
![MCP](https://img.shields.io/badge/MCP-Model%20Context%20Protocol-6E56CF?style=flat-square)
![FAISS](https://img.shields.io/badge/FAISS-0467DF?style=flat-square&logo=meta&logoColor=white)
![Chroma](https://img.shields.io/badge/Chroma-FF6B6B?style=flat-square)

**MLOps, Data & Deployment**

![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![MLflow](https://img.shields.io/badge/MLflow-0194E2?style=flat-square&logo=mlflow&logoColor=white)
![W&B](https://img.shields.io/badge/Weights%20%26%20Biases-FFBE00?style=flat-square&logo=weightsandbiases&logoColor=black)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Neo4j](https://img.shields.io/badge/Neo4j-4581C3?style=flat-square&logo=neo4j&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=flat-square&logo=streamlit&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![Jira](https://img.shields.io/badge/Jira-0052CC?style=flat-square&logo=jira&logoColor=white)

---

### 📌 Featured projects

#### 🤖 Agentic AI & LLM tools

| Project | Description | Stack |
|---|---|---|
| 🔄 [**Cobpy**](https://github.com/Achrefjr1997/Cobpy) | **COBOL → Python agentic migrator.** A LangGraph multi-agent loop (analyze → plan → translate → test → reflect) that validates the COBOL with GnuCOBOL first, then iterates until the Python output matches. Four-tier validation — differential testing, property-based tests (Hypothesis), LLM-as-judge and static analysis — produces a final **confidence score**. Supports OpenAI, Claude, Gemini and Grok, with live agent reasoning over SSE | LangGraph · FastAPI · React · Monaco · SQLite |
| 🌦️ [**open-meteo-mcp**](https://github.com/Achrefjr1997/open-meteo-mcp) | Full **Model Context Protocol server** for the Open-Meteo API: **33 tools, 25 resources, 4 prompts** covering forecasts, historical data since 1940, air quality, marine weather and ensemble comparisons across 30+ weather models. Tested, Dockerized, with CI | Python · MCP · Docker · GitHub Actions |
| 💬 [**open-meteo-mcp-streamlit-client**](https://github.com/Achrefjr1997/open-meteo-mcp-streamlit-client) | Conversational weather assistant on top of the MCP server — the LLM picks tools automatically, charts results, and keeps persistent chat history and memory | Streamlit · Ollama · MCP · SQLite · Docker |

#### 👁️ Computer vision & remote sensing

| Project | Description | Stack |
|---|---|---|
| 🔍 [**Modified-YOLO-World**](https://github.com/Achrefjr1997/Modified-YOLO-World) | Open-vocabulary YOLO-World extended with **DCNv3**, **Coordinate Attention** and **AMFF** fusion, plus a reduced architecture, for anomaly detection in low-visibility drone footage — **+23% mAP@0.5** (68.4% → 84.1%), **+31% small-object recall**. Includes Colab demo | PyTorch · Ultralytics · DCNv3 |
| 🧩 [**SAHI-World**](https://github.com/Achrefjr1997/SAHI-World) | Extension of SAHI (Slicing Aided Hyper Inference) that adds **YOLO-World support**, enabling sliced open-vocabulary detection of small objects in large aerial images | SAHI · YOLO-World |
| 🌍 [**OAD**](https://github.com/Achrefjr1997/OAD) | **🥉 3rd-place solution** to Solafune's Aerosol Optical Depth challenge: a Vision Transformer fine-tuned for regression on 13-band Sentinel-2 imagery, 5-fold CV and a custom correlation-based loss (0.9893 private score) | PyTorch · ViT · Sentinel-2 |

---

### 💼 Experience highlights

**Senior AI Engineer — Perfanalysis Consulting** · Lac, Tunisia
- End-to-end football analysis pipeline (D-FINE, Norfair, DeepSORT, ReID) — 80–95% tracking accuracy with zero identity swaps in high-intensity sequences
- MLOps with MLflow & CI/CD retraining — iteration cycles cut from **3 weeks to 3 days**, action-recognition F1 **+18%**, RAG precision **+22%**
- GraphRAG medical assistant resolving **88%** of staff queries autonomously

**AI Engineer — Tunisian Armed Forces** · Tunis, Tunisia
- Offline Chrome Extension (Manifest V3) for secure Q&A and summarization of classified documents — **65% faster** review, zero data exfiltration
- Real-time edge video analytics (detection, tracking, anomaly detection) — **99.8% uptime** over 30-day zero-connectivity deployments

**AI Research — Military Research Center & Polytechnic School of Tunisia**
- Upgraded YOLOv5 for mini-UAV detection: **F1 88.5%**, 45 FPS on edge GPUs, 42% fewer false alarms

---

### 📄 Publication

**An Upgraded-YOLO with Object Augmentation: Mini-UAV Detection Under Low-Visibility Conditions by Improving Deep Neural Networks**
*Operations Research Forum* (Springer), 2022 · [DOI: 10.1007/s43069-022-00163-7](https://doi.org/10.1007/s43069-022-00163-7)

---

### 🎓 Education

- **Research Master's, Information System Techniques** — National Engineering School of Tunis (ENIT), 2023–2024
- **Geomatics Engineer** — Borj El Amri Aviation School (EABA), 2018–2021

---

### 📊 GitHub stats

<p align="center">
  <img height="165" src="https://github-readme-stats.vercel.app/api?username=Achrefjr1997&show_icons=true&theme=tokyonight&hide_border=true&count_private=true" alt="GitHub stats"/>
  <img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Achrefjr1997&layout=compact&theme=tokyonight&hide_border=true" alt="Top languages"/>
</p>

---

<p align="center">
  🌐 English · Français &nbsp;|&nbsp; 💡 Open to collaborations on computer vision, edge AI and LLM systems
</p>
