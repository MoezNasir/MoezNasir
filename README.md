<h1 align="center">Hi, I'm Muhammad Moez Nasir 👋</h1>
<h3 align="center">AI/ML Engineer | Computer Vision & LLM Systems | Graduated in Computer Engineering</h3>

<p align="center">
  <a href="mailto:moeznasir111@gmail.com"><img src="https://img.shields.io/badge/Email-Contact-D14836?style=flat&logo=gmail&logoColor=white"/></a>
  <a href="www.linkedin.com/in/moez-nasir"><img src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=flat&logo=linkedin&logoColor=white"/></a>
  <img src="https://img.shields.io/badge/Based%20in-Lahore%2C%20Pakistan-2E7D32?style=flat"/>
</p>

---

### 🧑‍💻 About Me

I'm aComputer Engineering graduate from **FAST National University, Lahore**, currently working as an **AI/ML Intern. I build end-to-end AI systems — computer vision pipelines, retrieval-augmented generation (RAG) tools, LLM agent workflows, and business process automation — usually shipped under real hardware constraints (CPU-only, Intel Mac) that force disciplined, resourceful engineering.

---

### 🚀 Featured Projects

#### 🔍 [Mall Lost-Person Finder](#)
My strongest portfolio project — a computer vision system that finds a missing person in surveillance footage from a text description.
- **Pipeline:** OpenCV frame extraction → YOLOv8 person detection/cropping → CLIP embeddings → FAISS similarity search against a text query
- Video fingerprinting (MD5) auto-triggers pipeline rebuilds when footage changes
- Configurable YOLO model selection for A/B testing detection accuracy
- **Stack:** YOLOv8, CLIP, FAISS, Flask, OpenCV
- Debugged and resolved a FAISS/torch import-order segfault

#### 🎙️ AI Mock Interview Coach
A voice-based mock interview platform with real-time behavioral and technical evaluation.
- LangGraph state machine driving five distinct interview stages
- Real code execution in a sandboxed environment for technical rounds
- Client-side keystroke-based hesitation scoring
- On-device integrity checking via YOLOv8n (ONNX + onnxruntime-web)
- Speech-to-text via Groq's hosted Whisper-large-v3 API
- **Stack:** LangGraph, ONNX Runtime Web, Groq API, YOLOv8n

#### 🤖 RecruiterBot
A recruiter-facing conversational agent that answers questions about my background from a knowledge base.
- Four-branch LangGraph `StateGraph`: factual queries → FAISS retrieval, personal queries → direct prompt injection, sensitive/off-topic → deterministic fallback nodes
- API-based `HuggingFaceEndpointEmbeddings` to sidestep local PyTorch wheel issues
- Groq + Pydantic structured output (`json_schema` mode) for reliable responses
- **Stack:** LangGraph, FAISS, Flask, Groq, HuggingFace Inference API

#### ⚙️ n8n Cold Email Automation
A large-scale outbound automation system built for real client use.
- 271-node n8n workflow orchestrating 10 Gmail accounts
- Deployed on a Docker-based always-on server with an ngrok static tunnel
- **Stack:** n8n, Docker, Gmail API, ngrok

#### 📜 Pakistan Constitution — Vectorless RAG
A retrieval-augmented Q&A tool over the Constitution of Pakistan, built without a vector database.
- Four-stage pipeline: ingestion → Groq-based indexing → retrieval → generation
- **Stack:** Groq, pdfplumber, Pydantic — single Colab notebook

#### 🔧 PCB Defect Detection
A YOLOv8n model trained to classify 6 categories of PCB manufacturing defects.
- Trained on a Kaggle dataset (YOLO-format labels) on a dedicated GPU machine; inference runs locally
- **Stack:** YOLOv8n, PyTorch

---

### 🛠️ Other Work

- **MCP Weather Server** — FastMCP-based server exposing `get_weather` and `get_weather_by_coords` tools via Open-Meteo APIs
- **One Source Solutions Website** — four-page static business site, custom navy/slate/brass design with an SVG convergence diagram, deployed via Cloudflare Pages
- **AI Resume Screening Tool** — Flask + Groq
- **SEO Meta Tag Generator** — Flask + Groq + BeautifulSoup4
- **Research Contribution** — co-authored paper on defect detection in photovoltaic modules
- **Final-Year Project** — Smart Load Management System for solar microgrids (ESP32-S3, multi-sensor array, Random Forest–based predictive load shedding)

---

### 🧰 Tech Stack

**Languages & Core:** Python, JavaScript
**CV/ML:** YOLOv8, CLIP, ONNX Runtime, PyTorch
**LLM/Agents:** LangGraph, Groq API, Pydantic, RAG (vector & vectorless), HuggingFace Inference
**Retrieval/Infra:** FAISS, Flask, Docker (Colima), n8n, MCP/FastMCP
**Tooling:** VS Code, uv, Git, Cloudflare Pages

---

### 📫 Get in Touch

I'm currently open to **remote contract and full-time AI/ML engineering roles**. Feel free to reach out via email or LinkedIn above.

<p align="center"><i>Building under real constraints — CPU-only, resource-limited, and shipping anyway.</i></p>
