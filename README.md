# 🤖 AI Recruitment Screening Bot  
### *AI-powered résumé screening using Python + OpenAI*

The AI Recruitment Screening Bot is a lightweight Python tool that evaluates a candidate’s résumé against a job description. It uses an LLM (OpenAI GPT model) to generate a structured, bias-aware assessment including:

- Match score (0–100)  
- Summary of candidate fit  
- Key strengths  
- Skill gaps  
- Hiring recommendation  

This project bridges my **HR background** with my growing skills in **Python, automation, and AI**, demonstrating how technology can improve hiring workflows.

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

## 🛠 Tech Stack

- **Language:** Python  
- **AI Model:** OpenAI GPT-4.1 / GPT-4.1-mini  
- **Tools:** VS Code, GitHub, Prompt Engineering  
- **File Inputs:** `.txt` résumé + job description  
- **Optional UI (future):** Streamlit  

---

## 🚀 Getting Started

### 1. Clone the repo  

bash
git clone https://github.com/yourusername/recruitment-screening-bot.git
cd recruitment-screening-bot

### 2. Install dependencies  

bash
pip install -r requirements.txt

## 3. Add your OpenAI API key

macOS / Linux:

bash
export OPENAI_API_KEY="your_key_here"

Windows PowerShell:

powershell
$env:OPENAI_API_KEY="your_key_here"

## 4. Run the script

bash
python src/screen_candidate.py


---


## 🚀 Live Project

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

This roadmap outlines how the Recruitment Screening Bot will progress from a simple Python script into a fully functional HR-Tech automation tool.

Phase 1 — MVP (Current Release)

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

## 🤝 Contributions

Open to suggestions, improvements, and pull requests!

---

## 📬 Contact  

Created by **Charlote Araneta**  

🔗 **Portfolio**: https://charlotearaneta.github.io  

🔗 **LinkedIn**: https://www.linkedin.com/in/charlotearaneta/

---
