# AI-Powered Resume Analyzer & ATS Scoring System

An **AI-enabled resume screening web application** built using **Flask (Python)** that analyzes resumes against job descriptions. The system provides an **ATS-style keyword matching score**, identifies **matched and missing skills**, and leverages **Google Gemini AI** to deliver intelligent resume insights, interview questions, and improvement suggestions.

---

## 🚀 Features

### ✅ Resume Upload & Text Extraction

* Supports **.txt, .pdf, and .docx** resume formats
* Extracts clean text from resumes for analysis

### ✅ ATS Keyword Matching

* Extracts keywords from job descriptions and resumes
* Calculates a **matching score (0–100%)**
* Shows:

  * ✔️ Matched keywords
  * ❌ Missing keywords

### ✅ AI Resume Analysis (Gemini AI)

* Generates:

  * Resume summary
  * Key strengths
  * Areas of improvement
* Returns structured **JSON responses**

### ✅ AI Interview Question Generator

* Produces **5–7 role-specific interview questions**
* Covers technical, behavioral, and situational aspects

### ✅ Resume Improvement Suggestions

* Provides actionable suggestions to improve ATS compatibility
* Focuses on content, keywords, and alignment with the job role

---

## 🛠️ Tech Stack

| Layer              | Technology              |
| ------------------ | ----------------------- |
| Backend            | Flask (Python)          |
| Frontend           | HTML (Flask Templates)  |
| Resume Parsing     | PyPDF2, python-docx     |
| AI Model           | Google Gemini 2.0 Flash |
| API Calls          | Requests                |
| Keyword Extraction | Regex-based NLP         |

---

## 📁 Project Structure

```
.
├── app.py
├── templates/
│   └── index.html
└── README.md
```

---

## 🔧 Installation & Setup

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/your-username/your-repo-name.git
cd your-repo-name
```

---

### 🔹 Resume ATS Scoring

**POST** `/score_resume`

```json
{
  "job_description": "Job description text",
  "resume_text": "Extracted resume text"
}
```

---

### 🔹 AI Resume Analysis

**POST** `/analyze_resume_ai`

Returns:

* Resume summary
* Strengths
* Weaknesses

---

### 🔹 Generate Interview Questions

**POST** `/generate_interview_questions`

---

### 🔹 Resume Improvement Suggestions

**POST** `/suggest_resume_improvements`

---

## 🎯 Use Cases

* ATS Resume Screening Systems
* HR & Recruitment Platforms
* College Placement Portals
* Interview Preparation Tools

---

## ⚠️ Limitations

* Keyword matching is regex-based (not semantic NLP)
* Works best with text-based PDFs
* AI features require an active Gemini API key

---

## 🔮 Future Enhancements

* Semantic keyword matching using NLP
* Resume ranking for multiple candidates
* Authentication and dashboard UI
* Cloud deployment (Docker + AWS/GCP)

---

## 👨‍💻 Author

**Drishti Panthari**
Computer Science Engineer
