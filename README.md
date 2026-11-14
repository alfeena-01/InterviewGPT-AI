# 🎯 InterviewGPT AI

<div align="center">

https://img.shields.io/badge/Python-3.10+-blue?style=for-the-badge&logo=python

https://img.shields.io/badge/Streamlit-Framework-red?style=for-the-badge&logo=streamlit

https://img.shields.io/badge/Gemini-AI-orange?style=for-the-badge

https://img.shields.io/badge/NLP-Powered-green?style=for-the-badge

https://img.shields.io/badge/License-MIT-purple?style=for-the-badge

### 🚀 AI-Powered Interview Preparation Platform

Generate personalized interview questions, evaluate answers, identify skill gaps, and improve interview performance using AI.

</div>

---

## 📌 Overview

InterviewGPT AI is a complete interview preparation ecosystem designed for students, freshers, and professionals.

The platform analyzes resumes, extracts technical skills, generates personalized interview questions, evaluates answers using AI, conducts coding rounds, tracks performance, and provides learning recommendations.

Unlike traditional mock interview tools, InterviewGPT AI combines:

- Resume Analysis
- NLP-based Skill Extraction
- Gemini AI
- Semantic Skill Matching
- Coding Assessments
- Performance Analytics

into a single platform.

---

## ✨ Features

### 📄 Resume Analysis

- Upload Resume (PDF)
- Extract Resume Content
- Detect Technical Skills
- Identify Missing Skills
- Resume Insights

---

### 🤖 AI Question Generation

Generate personalized questions based on:

- Resume
- Skills
- Target Job Role
- Experience Level

Supported Roles:

- AI Engineer
- ML Engineer
- Data Scientist
- Data Analyst
- Full Stack Developer
- Backend Developer
- Frontend Developer

---

### 💬 Answer Evaluation

AI Reviews:

- Technical Accuracy
- Communication Clarity
- Confidence Level
- Completeness
- Industry Relevance

Provides:

✅ Score

✅ Strengths

✅ Weaknesses

✅ Suggested Improvements

✅ Model Answer

---

### 👨‍💼 HR Round

Practice HR questions including:

- Tell me about yourself
- Why should we hire you?
- Strengths and weaknesses
- Career goals
- Conflict management

---

### 💻 Coding Interview Round

Generate coding challenges.

Evaluate:

- Logic
- Optimization
- Time Complexity
- Space Complexity

Supported Topics:

- Arrays
- Strings
- Hash Maps
- Recursion
- Trees
- Graphs
- Dynamic Programming

---

### 📊 Analytics Dashboard

Track:

- Interview Scores
- Weak Areas
- Skill Progress
- Interview History

Visualized using interactive charts.

---

### 🎯 Skill Gap Detection

Compare:

Resume Skills

VS

Target Role Skills

Get personalized recommendations for missing technologies and concepts.

---

### 📑 Interview Report Generator

Generate downloadable reports containing:

- Technical Score
- HR Score
- Coding Score
- Weak Areas
- Recommended Learning Path

---

## 🏗️ System Architecture

```text
Resume Upload
      │
      ▼
Resume Parser
      │
      ▼
Skill Extraction
      │
      ▼
Gemini AI Engine
      │
 ┌────┼─────┬─────────┬────────┐
 ▼    ▼     ▼         ▼        ▼
Tech  HR  Coding  Evaluation Analytics
      Round
      │
      ▼
Report Generation
```

---

## 📂 Project Structure

```text
InterviewGPT-AI/
│
├── app.py
│
├── modules/
│   ├── parser.py
│   ├── skills.py
│   ├── generator.py
│   ├── evaluator.py
│   ├── coding.py
│   ├── analytics.py
│   ├── database.py
│   └── report.py
│
├── data/
│   ├── sqlite.db
│
├── reports/
│
├── assets/
│   ├── screenshots/
│
├── .env
│
├── requirements.txt
│
└── README.md
```

---

## 🛠️ Technology Stack

| Category | Technology |
|-----------|-----------|
| Frontend | Streamlit |
| Backend | Python |
| AI Model | Gemini |
| NLP | spaCy |
| Embeddings | SentenceTransformers |
| Resume Parsing | pdfplumber |
| Database | SQLite |
| Visualization | Plotly |
| Reports | ReportLab |

---

## 🚀 Installation

Clone repository

```bash
git clone https://github.com/USERNAME/InterviewGPT-AI.git

cd InterviewGPT-AI
```

Create virtual environment

```bash
python -m venv venv
```

Activate

```bash
venv\Scripts\activate
```

Install dependencies

```bash
pip install -r requirements.txt
```

---

## 🔑 Environment Setup

Create a `.env` file

```env
GEMINI_API_KEY=YOUR_API_KEY
```

Get Gemini API key from:

https://aistudio.google.com/

---

## ▶️ Run Project

```bash
streamlit run app.py
```

---

## 📈 Future Roadmap

### Version 2.0

- Voice Interview Simulation
- Speech-to-Text
- Text-to-Speech
- Multi-language Support
- AI Career Coach
- Job Description Analysis

### Version 3.0

- Video Interview Analysis
- Eye Contact Detection
- Confidence Detection
- Facial Expression Analysis
- Recruiter Dashboard

---

## 🤝 Contributions

Contributions are welcome.

Fork repository

Create feature branch

```bash
git checkout -b feature-name
```

Commit changes

```bash
git commit -m "Added feature"
```

Push code

```bash
git push origin feature-name
```

---

## 📜 License

MIT License

---
