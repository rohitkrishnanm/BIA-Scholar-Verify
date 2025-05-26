# BIA-Scholar-Verify
BIA ScholarVerify™ is an AI-powered assignment evaluation system built for students of the Boston Institute of Analytics. It streamlines the submission, analysis, scoring, and feedback process using OpenAI GPT, automates grading of .py, .ipynb, and .pdf submissions, and provides downloadable feedback reports. Developed by Rohit Krishnan.

# BIA ScholarVerify™ 🎓
### AI-Powered Assignment Evaluation System for BIA Students  
**Developed by [Rohit Krishnan](https://rohitkrishnan.co.in)**

---

## 📌 Overview

**BIA ScholarVerify™** is a Streamlit-based smart submission and analysis app designed for the **Boston Institute of Analytics (BIA)**. It allows students to upload assignments, receive instant feedback powered by **OpenAI GPT**, and download a personalized report.

This system is built to automate:
- Assignment submission validation
- GPT-driven content analysis
- Intelligent grading and classification (Pass / Rework / Can Improve)
- Trainer analytics and admin control

---

## 🚀 Features

### 🎓 Student Features
- Enter name & select institution (BIA Kottayam / Trivandrum)
- Upload assignment question (file or text)
- Optional upload of supporting documents
- Upload final answer (PDF, `.ipynb`, `.py`)
- Get **AI-generated feedback, score (0–10)**, and result classification
- Download **PDF report** with analysis

### 🧠 AI Evaluation
- Uses **OpenAI GPT** to analyze:
  - Relevance to question
  - Technical correctness
  - Structure and clarity
- Automatically scores submission out of 10
- Classifies as:
  - ✅ Pass (Score ≥ 6)
  - ⚠️ Can Improve (Score 4–5)
  - ❌ Rework (Score < 4)

### 🔐 Trainer Dashboard
- Trainer login (via password)
- View all student submissions
- Visualize trends (weekly charts, result stats)
- Leaderboard view
- Delete records, download CSV

---

## 📂 File Structure
.
├── app.py # Main Streamlit app
├── utils.py # GPT analysis, text extraction, PDF report generation
├── db_utils.py # SQLite database functions
├── .streamlit/
│ 
│ └── config.toml # UI theming
└── requirements.txt # Dependencies



---

## 🔧 Installation

1. **Clone this repository:**
```bash
git clone https://github.com/your-username/bia-scholar-verify.git
cd bia-scholar-verify
---
pip install -r requirements.txt

---
[openai]
api_key = "your-openai-api-key"

[trainer]
password = "your-trainer-password"

---
streamlit run app.py

📊 Tech Stack
Python

Streamlit

OpenAI GPT API

SQLite3

PDF Report Generation

Matplotlib / Pandas

📌 Project Status
✅ Fully Functional
🔜 Future Features:

Email report to student

Google Sheets logging

Multiple institute branches

📄 License
This project is under MIT License.
© 2025 Rohit Krishnan – rohitkrishnan.co.in

🔗 Connect with Me
🌐 Website: rohitkrishnan.co.in

💼 LinkedIn: linkedin.com/in/rohit-krishnan-320a5375

📸 Instagram: @prof_rohit_

📧 Email: rohitkrishnanm@gmail.com

