# Automated Job Search & Cover Letter Generator (n8n + Gemini + Google Sheets)

## 📌 Project Description
This project automates the end-to-end process of job hunting.  
It fetches job postings from LinkedIn RSS feeds, extracts key job details using **Gemini LLM**, evaluates the candidate’s fit, generates a tailored cover letter, and stores the results in **Google Sheets**.  

The workflow saves time by reducing repetitive job search tasks and ensures each application has a professional, customized cover letter. Optionally, email notifications can be sent for new matches.

---

## 🚀 Features
- 🔎 **Automated Job Fetching** – Collect jobs from LinkedIn via RSS.  
- 🤖 **AI-Powered Parsing** – Extract company, role, benefits, and description using Gemini LLM.  
- 📊 **Match Scoring** – Compare job requirements with resume and assign a **1–5 match score**.  
- ✍️ **Cover Letter Generation** – Generate concise, professional cover letters tailored to each job.  
- 📑 **Google Sheets Integration** – Track jobs, match scores, and cover letters in one place.  

---

## 🖥️ How to Run

### 🔹 Run Locally with n8n (Docker)
1. Clone this repository:
   ```bash
[   git clone https://github.com/your-repo/job-automation-n8n.git
   cd job-automation-n8n](https://github.com/Lazy-Creature/n8n_job_auto/tree/main)
