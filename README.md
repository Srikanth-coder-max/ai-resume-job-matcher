# AI-Powered Smart Resume & Job Matcher

🚀 A full-stack platform to help students build strong resumes, enhance them with AI, and match resumes to jobs/internships.

## ✨ Features (MVP)
- Resume Builder (form-based → styled PDF export).
- Resume Upload & Parsing (PDF/DOCX).
- AI Resume Enhancer (LLM rewrites bullets).
- Job Ingestion (upload/paste job descriptions).
- Resume-Job Matching (embeddings similarity).
- Version Control (track resume changes).
- Simple Dashboard UI.

## 🛠️ Tech Stack
- **Frontend:** React (Vite) + Tailwind + React Router + React Query  
- **Backend:** Django REST Framework + Celery + Redis  
- **Database:** PostgreSQL  
- **Storage:** Azure Blob Storage  
- **AI/ML:** Azure OpenAI (LLM + embeddings) / Hugging Face  
- **Deployment:** Azure Static Web Apps (frontend), Azure App Service (backend), PostgreSQL (Azure), Blob Storage (Azure)

## 🏗️ Architecture
See [`docs/architecture.md`](./docs/architecture.md) for diagram.

## 🚦 Getting Started
### Prerequisites
- Python 3.10+
- Node.js 18+
- PostgreSQL 14+
- Azure account (with GitHub Student Pack credits)

### Clone Repo
```bash
git clone https://github.com/YOUR_USERNAME/ai-resume-job-matcher.git
cd ai-resume-job-matcher
