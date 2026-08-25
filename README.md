<div align="center">

# 👋 Hi, I'm Hà Tấn Phong

### AI Engineer | Computer Vision | Deep Learning | Agentic AI

**Building practical AI systems with Computer Vision, Deep Learning, LLMs and AI Agents.**

<br>

![Profile Views](https://komarev.com/ghpvc/?username=hatanphong44\&label=Profile%20Views\&color=0e75b6\&style=flat)

</div>

---

## 🚀 About Me

* 🤖 **AI Engineer** with approximately **6 months of internship and professional experience** at **FPT Software Quy Nhơn — AI Valley**
* 🎓 Studying **Information Technology / Artificial Intelligence** at **FPT University HCM**
* 👁️ Focused on **Computer Vision & Deep Learning**
* 🧠 Interested in **LLM, AI Agents & Agentic AI**
* 🔍 Experienced in **Object Detection, Human Pose Estimation, OCR and License Plate Recognition**
* ⚙️ Experienced in integrating AI models and agents into **backend systems and real-world applications**
* 🐍 Main programming language: **Python**
* 🚀 Interested in building reliable and production-oriented AI systems

---

## 🛠️ Tech Stack

### 🤖 AI / Machine Learning

<p>
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white"/>
  <img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white"/>
  <img src="https://img.shields.io/badge/Computer%20Vision-111111?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/Deep%20Learning-6A1B9A?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/YOLO-111111?style=for-the-badge"/>
</p>

### 👁️ Computer Vision

<p>
  <img src="https://img.shields.io/badge/Object%20Detection-1976D2?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/Pose%20Estimation-00897B?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/OCR-455A64?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/License%20Plate%20Recognition-37474F?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/Multi--Object%20Tracking-5E35B1?style=for-the-badge"/>
</p>

### 🧠 LLM / Agentic AI

<p>
  <img src="https://img.shields.io/badge/LLM-412991?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/AI%20Agents-FF6F00?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/LangGraph-1C1C1C?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/Prompt%20Engineering-5E35B1?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/Tool%20Calling-00897B?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/Guardrails-D84315?style=for-the-badge"/>
</p>

### ⚙️ Backend / Infrastructure

<p>
  <img src="https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white"/>
  <img src="https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white"/>
  <img src="https://img.shields.io/badge/SQLite-003B57?style=for-the-badge&logo=sqlite&logoColor=white"/>
  <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white"/>
  <img src="https://img.shields.io/badge/CUDA-76B900?style=for-the-badge&logo=nvidia&logoColor=white"/>
  <img src="https://img.shields.io/badge/Git-181717?style=for-the-badge&logo=git&logoColor=white"/>
</p>

---

# ⭐ Featured Projects

## 🚇 Crowd Behavior Analysis System at Metro Station

A **Computer Vision and Deep Learning** system for analyzing crowds, passenger density and abnormal behavior in metro stations.

### Focus

`Object Detection` `Human Pose Estimation` `Keypoint Detection`

`Multi-Object Tracking` `Crowd Analysis` `Deep Learning`

### Responsibilities

* Developed object detection models for passenger detection and localization.
* Developed human pose estimation and keypoint detection models.
* Prepared, annotated and processed datasets.
* Trained, evaluated and fine-tuned deep learning models.
* Optimized models for crowded scenes.
* Integrated detection and keypoint outputs into tracking and behavior-analysis pipelines.

🔗 **[View Repository](https://github.com/khoa150/Crowd-Behavior-Analysis-System-atMetro-Station)**

---

## 🅿️ SmartParking AI

A natural-language **AI Parking Assistant** designed to help users find and rank suitable parking slots based on vehicle information, location preferences and EV charging requirements.

### AI Agent Architecture

```text
User Request
     │
     ▼
┌─────────────┐
│  Guardrail  │
└──────┬──────┘
       ▼
┌─────────────┐
│  Understand │
└──────┬──────┘
       ▼
┌─────────────┐
│   Vehicle   │
└──────┬──────┘
       ▼
┌─────────────┐
│Search Parking│
└──────┬──────┘
       ▼
┌─────────────┐
│   Respond   │
└─────────────┘
```

### Features

* 🤖 LangGraph-based AI Agent
* 🛡️ Input validation and guardrails
* 🔐 Prompt-injection detection
* 🅿️ Parking slot recommendation
* 📍 Distance-based ranking
* ⚡ EV compatibility
* 🧭 Dijkstra-based routing
* 🔌 FastAPI integration
* 🧪 Pytest and async testing
* 🔎 LangSmith observability

### Technology

`Python` `LangGraph` `FastAPI` `Pydantic`

`PostgreSQL` `SQLAlchemy` `Docker` `Dijkstra`

---

## 🚗 Vietnamese License Plate Recognition

A real-time **Vietnamese License Plate Recognition** system designed for camera and RTSP streams.

### Pipeline

```text
Camera / RTSP
      │
      ▼
YOLO Plate Detection
      │
      ▼
Plate Crop
      │
      ▼
PaddleOCR
      │
      ▼
Text Recognition
      │
      ▼
Validation
      │
      ▼
Aggregation
      │
      ▼
Majority Vote
      │
      ▼
Deduplication
      │
      ▼
HTTP Event Publisher
```

### Technology

`Python` `YOLO` `PaddleOCR` `OCR`

`Computer Vision` `CUDA` `Docker` `RTSP`

🔗 **[View Repository](https://github.com/hatanphong44/vn-license-plat)**

---

## 🤝 CV Compass

An **AI-powered recruitment platform** designed to help candidates find suitable jobs and support recruiters with automated candidate screening, matching and ranking.

### Features

* 📄 CV Analysis
* 💼 Job Description Analysis
* 🔗 Candidate-Job Matching
* 🏆 Candidate Ranking
* 🤖 AI Agent Workflows
* 🔌 RESTful API
* 🗄️ Backend & Database Integration

### Technology

`AI Agent` `LLM` `CV Analysis`

`Candidate Matching` `Candidate Ranking`

`RESTful API` `Backend Development`

🔗 **[View Repository](https://github.com/huyhoang20451/cvcompassai.id.vn.git)**

---

## 💬 AI-Powered Inventory Management Chatbot

An AI-powered chatbot for inventory management.

### Features

* 📦 Inventory status checking
* 📥 Inventory movement tracking
* 📤 Import / export tracking
* 💬 Conversational workflows
* 🌐 Web application integration

### Technology

`Python` `Dialogflow` `Node.js` `React`

---

# 🧠 Areas of Interest

### Computer Vision

```text
Computer Vision
      │
      ├── Object Detection
      ├── Human Pose Estimation
      ├── Keypoint Detection
      ├── OCR / LPR
      ├── Multi-Object Tracking
      └── Crowd Behavior Analysis
```

### Agentic AI

```text
Agentic AI
      │
      ├── LLM Applications
      ├── AI Agents
      ├── LangGraph
      ├── Tool Calling
      ├── Guardrails
      ├── Natural Language Understanding
      └── Recommendation Systems
```

### AI System Engineering

```text
AI Model
   │
   ▼
Inference
   │
   ▼
AI Agent / Service
   │
   ▼
FastAPI
   │
   ▼
Database
   │
   ▼
Docker / GPU
   │
   ▼
Production System
```

---

# 📚 Technical Skills

| Category            | Technologies                                            |
| ------------------- | ------------------------------------------------------- |
| **Languages**       | Python, JavaScript, SQL                                 |
| **AI / ML**         | Machine Learning, Deep Learning, LLM, AI Agent          |
| **Computer Vision** | Object Detection, Pose Estimation, OCR, LPR, Tracking   |
| **Agentic AI**      | LangGraph, Prompt Engineering, Tool Calling, Guardrails |
| **Backend**         | FastAPI, REST API, SQLAlchemy                           |
| **Database**        | PostgreSQL, SQLite                                      |
| **Algorithms**      | Dijkstra, Ranking, Recommendation, Matching             |
| **Deployment**      | Docker, Docker Compose, CUDA, GPU Inference, RTSP       |
| **Frontend**        | React, Node.js                                          |

---

# 📊 GitHub

<div align="center">

![Followers](https://img.shields.io/github/followers/hatanphong44?style=for-the-badge\&logo=github\&label=Followers)

![Stars](https://img.shields.io/github/stars/hatanphong44?style=for-the-badge\&logo=github\&label=Stars)

![Repositories](https://img.shields.io/badge/Public%20Repositories-17-181717?style=for-the-badge\&logo=github)

![GitHub](https://img.shields.io/badge/GitHub-hatanphong44-181717?style=for-the-badge\&logo=github)

</div>

---

# 🎓 Education

### FPT University — Ho Chi Minh City

**Information Technology / Artificial Intelligence**

**GPA: 2.97 / 4.0**

---

# 🏢 Experience

### FPT Software Quy Nhơn — AI Valley

**AI Engineer Intern / AI Engineer**

Approximately **6 months of internship and professional working experience**.

Experience includes:

* Computer Vision
* Deep Learning
* Object Detection
* Human Pose Estimation
* Dataset Processing
* Model Training & Evaluation
* AI Agent Development
* LLM Applications
* Backend Integration
* AI System Integration

---

# 📜 Certifications

* **Building AI-Powered Chatbots Without Programming**
* **Artificial Intelligence Privacy and Convenience**
* **Algorithms, Models and Limitations**

---

# 🤝 Connect With Me

<div align="center">

<a href="mailto:hatanphong@gmail.com">
<img src="https://img.shields.io/badge/Email-hatanphong%40gmail.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white"/>
</a>

<a href="https://github.com/hatanphong44">
<img src="https://img.shields.io/badge/GitHub-hatanphong44-181717?style=for-the-badge&logo=github&logoColor=white"/>
</a>

</div>

<br>

<div align="center">

### 💡 Building AI systems that solve real-world problems.

</div>
