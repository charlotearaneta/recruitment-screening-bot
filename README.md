# 🤖 AI Recruitment Screening Bot  
### *AI-powered résumé screening using Python + OpenAI*

The AI Recruitment Screening Bot is a lightweight Python tool that evaluates a candidate’s résumé against a job description. It uses an LLM (OpenAI GPT model) to generate a structured, bias-aware assessment including:

This project bridges my **HR background** with my growing skills in **Python, automation, and AI**, demonstrating how technology can improve hiring workflows.

---

## 🌟 Overview

The Recruitment Screening Bot is a lightweight Python application that compares a single résumé with a job description and produces an AI-generated evaluation.  

It outputs:
- A match score (0–100)
- A short summary of candidate fit
- Key strengths
- Skill or experience gaps
- A hiring recommendation

This tool is designed as a **foundational HR Tech building block**, suitable for first-round screening and as a stepping stone toward more advanced applicant tracking systems.

---

## 📂 Project Structure

```text
recruitment-screening-bot/
│
├─ data/
│   ├─ job_description.txt
│   └─ candidate_resume.txt
│
├─ src/
│   └─ screen_candidate.py
│
├─ assets/
│   └─ ai-output.png
│
├─ requirements.txt
├─ README.md
└─ case-study.md    

```

---

## 🌟 Features

### ✔ Automated Candidate Evaluation  
Reads résumé + job description files and returns AI-generated assessments.

### ✔ Structured JSON-style Output  
Clear scoring and breakdown for HR decision-making.

### ✔ Beginner-Friendly Python Code  
No complex dependencies, easy to modify and extend.

### ✔ Custom Prompt Engineering  
Guides the AI to respond with unbiased, HR-aligned analysis.

### ✔ Ready for Expansion  
Can be turned into a web app or integrated into ATS systems.

---


## 🧠 How It Works

### 1. Load Inputs  
The script reads:
- A job description (`job_description.txt`)
- A candidate résumé (`candidate_resume.txt`)

### 2. AI Evaluation  
Both inputs are sent to an AI model using a carefully designed prompt that instructs the model to act as an experienced recruiter.

### 3. Structured Response  
The AI returns a structured evaluation containing:
- Match score  
- Summary  
- Strengths  
- Gaps  
- Recommendation  

### 4. Output Display  
Results are printed in a clear, JSON-style format for easy interpretation.

---

## 📥 Input Example (candidate_resume.txt)

```text
IT Support Intern with hands-on experience in troubleshooting hardware and software issues.
Certified in Google IT Support and familiar with basic networking concepts.

```

## 📥 Output Example (AI Evaluation JSON)

```bash 
{
  "score": 82,
  "summary": "The candidate demonstrates a strong foundational skill set for the IT Support role, with relevant troubleshooting experience and customer-facing skills.",
  "strengths": [
    "Google IT Support certification",
    "Hands-on troubleshooting experience",
    "Strong communication skills"
  ],
  "gaps": [
    "Limited enterprise IT environment exposure"
  ],
  "recommendation": "Good Fit"
}

```

## 🛠 Tech Stack

- **Language:** Python  
- **AI Model:** OpenAI GPT-4.1 / GPT-4.1-mini  
- **Tools:** VS Code, GitHub, Prompt Engineering  
- **File Inputs:** `.txt` résumé + job description  
- **Optional UI (future):** Streamlit  

---

## 🚀 Setup Instructions

### 1. Clone the repo  

```bash
git clone https://github.com/yourusername/recruitment-screening-bot.git
cd recruitment-screening-bot

```

### 2. Install dependencies  

```bash
pip install -r requirements.txt

```

### 3. Add your OpenAI API key

macOS / Linux:

```bash
export OPENAI_API_KEY="your_key_here"

```

Windows PowerShell:

```powershell
$env:OPENAI_API_KEY="your_key_here"

```

### 4. Run the script

```bash
python src/screen_candidate.py


```

---


## 🖼 Demo

Here is an example of how the Recruitment Screening Bot evaluates a candidate against a job description.

### This output is generated directly from the Python script using the OpenAI model.


```json
{
  "score": 82,
  "summary": "The candidate demonstrates strong foundational skills for the IT Support role. Their background aligns with the required troubleshooting and customer support tasks, and they show willingness to grow in the field.",
  "strengths": [
    "Google IT Support Professional Certificate",
    "Hands-on troubleshooting experience",
    "Clear communication skills",
    "Understanding of basic networking"
  ],
  "gaps": [
    "Limited exposure to enterprise-level systems",
    "No direct experience with ticketing tools"
  ],
  "recommendation": "Good Fit"
}

```


---

## 🗺 Roadmap

This roadmap outlines how the Recruitment Screening Bot will progress from a simple Python script into a fully functional HR Tech automation tool.

Phase 1 — MVP 

- Single résumé + job description analysis
- Python script reads .txt files
- OpenAI-powered evaluation
- JSON-style output (score, strengths, gaps, recommendation)
- Basic documentation
- Assets folder for screenshots

Phase 2 — User Experience Enhancements
- Streamlit web interface
- Résumé upload (TXT / PDF extraction)
- Clean, structured UI output
- Adjustable scoring weights
- Export results to CSV

Phase 3 — Batch Screening & Ranking
- Evaluate multiple résumés at once
- Rank candidates by score
- Highlight top candidates
- Side-by-side comparison
- Auto-generate shortlist reports

Phase 4 — ATS-Grade Capabilities
- PDF résumé parsing
- Duplicate detection
- Bias-awareness reminders
- Integrations: ClickUp, Notion, Google Sheets
- API version for HR platforms

---

## 🎯 What I Learned

Building this project taught me:

- ✔ How to translate HR screening logic into structured AI prompts
- ✔ The importance of consistency and structure in AI-generated outputs
- ✔ How automation can reduce repetitive HR tasks
- ✔ How prompt engineering directly affects evaluation quality
- ✔ How small tools can form the foundation of scalable HR Tech systems

## 🌍 Long-Term Vision

This project serves as a stepping stone toward a full AI-powered Applicant Tracking System (ATS) that supports:

- Fairer and more consistent hiring

- Faster first-round screening

- Data-driven recruitment decisions

- Integration with HR workflow tools

### The goal is to augment human recruiters, not replace them.

---

## 📬 Contact
👩‍💻 Created by: **Charlote Araneta**

🔗 LinkedIn: https://www.linkedin.com/in/charlotearaneta

🌐 Portfolio: https://charlotearaneta.github.io



---
