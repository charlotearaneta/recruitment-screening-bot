# 🤖 AI Recruitment Screening Bot  
## Case Study  

The AI Recruitment Screening Bot is a Python-based tool that analyzes résumés against job descriptions using an LLM (OpenAI). It provides structured, unbiased, and instant evaluations to support hiring teams in making more informed decisions.

This project combines my **HR background** with my **new technical skills** in Python, automation, and AI making it a perfect demonstration of my HR-Tech transition.

---

## 📌 Problem I Wanted to Solve  

During my years in recruitment and HR, I consistently saw these issues:

- Recruiters manually skim hundreds of résumés, increasing fatigue and errors.  
- Matching skills to job descriptions can be subjective and inconsistent.  
- Early-stage screening often misses good candidates due to time pressure.  
- Small teams or startups lack structured screening processes.  
- Recruiters do not always have technical knowledge for IT roles.  

I wanted to create a tool that:

- **automates the first-level screening**,  
- provides **objective, structured evaluation**,  
- and reduces the recruiter’s workload.

This project bridges **HR expertise** + **AI technology** to create a productivity tool that’s simple yet powerful.

---

## 👥 Who It Helps  

### This bot is helpful for:

- **Recruiters** doing high-volume screening  
- **HR assistants** who are new to technical roles  
- **Small businesses** without an HR team  
- **Job seekers** wanting to evaluate their own résumés  
- **Students** learning how job descriptions match skill profiles  

Ultimately, it increases efficiency, reduces bias, and provides a consistent evaluation framework.

---

## 🛠 My Process  

### **1. Defined the Core Task**  
Break down what happens in real résumé screening:  
- Review job requirements  
- Scan candidate résumé  
- Identify skill match  
- Identify gaps  
- Provide a clear decision  

This became the structure for the bot’s output.

---

### **2. Designed the Prompt for AI Reasoning**  
I engineered a prompt that ensures the AI evaluates:

- Skill alignment  
- Experience relevance  
- Gaps  
- Soft skills  
- Role suitability  
- Fit score (0–100)  
- Recommendation (Strong Fit, Good Fit, Needs Development, Not a Fit)

---

### **3. Built the Python Script**  
Key features of the script:

- Reads job description and résumé from `/data` folder  
- Sends both to the OpenAI model  
- Returns clean structured JSON-like output  
- Flexible for different job types  

The goal was to keep it lightweight and beginner-friendly.

---

### **4. Tested with Multiple Candidate Profiles**  
I tested:

- IT Support candidates  
- Customer service candidates  
- Fresh graduates  
- Mid-level tech professionals  

This allowed me to refine prompt clarity and scoring consistency.

---

## ⚙️ Tech Stack  

- **Language:** Python  
- **AI Model:** OpenAI (GPT-4.1 / GPT-4.1-mini)  
- **File Handling:** txt-based job and résumé inputs  
- **Output:** JSON-style structured evaluation  
- **Tools:** GitHub, Prompt Engineering, VS Code  
- **Future UI:** Streamlit (planned)

---

## 🖼 Demo  

```text
recruitment-screening-bot/
│
├─ data/
│   ├─ job_description.txt
│   ├─ candidate_resume.txt
│
├─ src/
│   ├─ screen_candidate.py

