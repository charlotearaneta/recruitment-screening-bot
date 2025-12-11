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
No complex dependencies — easy to modify and extend.

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

## 📂 Project Structure

recruitment-screening-bot/
│
├─ data/
│ ├─ job_description.txt
│ ├─ candidate_resume.txt
│
├─ src/
│ ├─ screen_candidate.py
│
├─ assets/
│ ├─ ai-output.png
│ ├─ resume-sample.png
│ ├─ project-structure.png
│
├─ requirements.txt
└─ README.md

---

## 🚀 Getting Started

### 1. Clone the repo
```bash
git clone https://github.com/yourusername/recruitment-screening-bot.git

### **2. Install dependencies**
pip install -r requirements.txt

## **3. Add your OpenAI API key**
export OPENAI_API_KEY="your_key_here"     # macOS/Linux
$env:OPENAI_API_KEY="your_key_here"       # Windows PowerShell

4. Run the script
python src/screen_candidate.py

🖼 Screenshots / Demo
📂 Project Structure

📝 Job Description Input

👤 Candidate Résumé Input

🔎 AI Screening Output (Terminal)


---

# ✅ **2️⃣ ROADMAP (Standalone Version)**  
You can add this as a `ROADMAP.md` file or keep it inside your README.

```markdown
# 🗺 AI Recruitment Screening Bot — Roadmap

This roadmap outlines the planned development phases for transforming the Recruitment Screening Bot from a Python MVP into a fully functional HR-Tech automation tool.

---

## **Phase 1 — MVP (Current Release)**  
Foundation of the screening system  
- Single résumé + job description analysis  
- Python script reads `.txt` files  
- OpenAI-powered evaluation  
- JSON-style output (score, strengths, gaps, recommendation)  
- Basic documentation  
- Assets folder for screenshots  

---

## **Phase 2 — User Experience Enhancements**  
Making the tool accessible to non-technical users  
- Streamlit web interface  
- Resume upload (TXT / PDF extraction)  
- Clean, structured UI output  
- Adjustable scoring weight (skills vs experience)  
- Export results to CSV  

---

## **Phase 3 — Batch Screening & Ranking**  
Turning it into an HR productivity tool  
- Evaluate multiple candidates at once  
- Rank candidates by score  
- Highlight top candidates  
- Compare strengths & gaps side-by-side  
- Auto-generate shortlist reports  

---

## **Phase 4 — ATS-Grade Capabilities**  
Moving toward a fully automated recruitment system  
- PDF résumé parsing (OCR optional)  
- Duplicate detection  
- Bias-awareness reminders  
- Integration options (ClickUp, Notion, Google Sheets)  
- API version for external HR tools  

---

## ✨ Long-Term Vision  
A complete HR-Tech ecosystem that supports:

- AI-assisted screening  
- AI-driven interviews (future)  
- Automated hiring workflows  
- Real-time dashboards  
- HR analytics  

Empowering small companies, startups, and HR teams with accessible, automated recruitment tools.

---
