# ATS Recruiter AI

**AI-Powered Resume Screening via n8n & OpenAI**  
📄 PDF Resume Parsing | 🔁 Workflow Automation | 🎯 Smart Candidate Matching

ATS Recruiter AI is a no-code applicant tracking and resume screening solution built using [n8n](https://n8n.io/) and [OpenAI](https://platform.openai.com/). It automates the end-to-end workflow of receiving resumes (PDF only), extracting content, and evaluating candidates against a given job description using GPT intelligence.

## 🚀 Features

- 📥 Accepts resumes in PDF format
- ⚙️ Automated workflows via n8n (no-code)
- 🧠 Uses OpenAI (GPT) for candidate evaluation
- 🎯 Matches resumes to job descriptions with scoring
- 📬 Optional alerts via email or messaging apps
- 📊 Integrate results into Google Sheets, Notion, or other databases

## 📌 How It Works

1. **Upload PDF Resume**: The candidate uploads or sends their resume.
2. **Extract Text**: n8n parses the PDF to extract raw text.
3. **Send to OpenAI**: The resume and job description are sent to GPT via API.
4. **Analyze & Score**: GPT returns a relevance score and optional summary.
5. **Log / Notify**: Results are saved to a sheet or database, and notifications are triggered.

## 🧩 Tech Stack

- **n8n** – Visual workflow builder
- **OpenAI GPT-4** – Resume analysis and scoring
- **PDF Parser (n8n Node)** – Text extraction from PDF files
- **Integrations (Optional)** – Google Sheets, Email, Notion, Slack, etc.

> ⚠️ **Please fork this repository before using or modifying it.**
> Direct pushes or pull requests from cloned copies will not be accepted.
