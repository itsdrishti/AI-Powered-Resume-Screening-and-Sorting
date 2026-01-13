# AI-Powered Resume Analyzer & ATS Scoring System
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
