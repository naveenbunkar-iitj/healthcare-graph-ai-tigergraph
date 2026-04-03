# 🧠 AI Healthcare Graph Intelligence (TigerGraph)

## 📌 Overview
This project is an AI-powered healthcare system that uses **TigerGraph** to model relationships between patients, symptoms, and diseases.

It leverages graph-based analysis to provide:
- Disease prediction
- Relationship insights
- Smart recommendations

---

## 🚀 Features
- Graph-based disease prediction
- Multi-hop relationship analysis
- Real-time recommendations
- Scalable graph architecture

---

## 🧩 Graph Use Case

### Nodes:
- Patient
- Symptom
- Disease
- Treatment

### Edges:
- HAS_SYMPTOM
- INDICATES
- TREATED_BY

---

## ⚙️ Tech Stack
- Frontend: Next.js
- Backend: Node.js / FastAPI
- Database: TigerGraph
- AI: Python (optional)

---

## 🗄️ TigerGraph Integration
This project uses TigerGraph as the **core database**:
- Graph schema creation
- Data modeling
- Multi-hop query execution
- Recommendation logic using graph traversal

---

## ▶️ Setup Instructions

### 1. Clone Repo
```bash
git clone https://github.com/your-username/healthcare-graph-ai-tigergraph.git
cd healthcare-graph-ai-tigergraph
```

### 2. Backend
```bash
cd backend
npm install
node server.js
```

### 3. Frontend
```bash
cd frontend
npm install
npm run dev
```

### 🐯 TigerGraph Setup
```bash
# Create a graph in TigerGraph Savanna
RUN SCHEMA CHANGE JOB healthcare_schema

# Load data
LOAD DATA FROM sample_data.csv

# Run queries
RUN QUERY predictDisease()
```

---

## 🎥 Demo
See `/demo/demo.mp4`

---

## 📊 Architecture
Frontend → Backend → TigerGraph → AI Model

---

## 🌍 Impact
- Faster diagnosis support
- Better healthcare insights
- Scalable medical intelligence system

---

## 👨‍💻 Team
Naveen (Developer)
