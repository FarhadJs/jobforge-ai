<div align="center">
  <h1>JobForge AI</h1>
  <p>
    <strong>AI-Powered Job Application Tracker & Smart Resume Optimizer</strong><br />
    Track applications, analyze resumes with AI, get improvement suggestions, and export polished PDFs — all in one modern full-stack app.
  </p>

  <p>
    <a href="https://github.com/FarhadJs/jobforge-ai/stargazers"><img src="https://img.shields.io/github/stars/FarhadJs/jobforge-ai?style=social" alt="Stars"></a>
    <a href="https://github.com/FarhadJs/jobforge-ai"><img src="https://img.shields.io/github/license/FarhadJs/jobforge-ai" alt="License: MIT"></a>
    <img src="https://img.shields.io/badge/Full%20Stack-React%20%2B%20NestJS-blue" alt="Full Stack">
    <img src="https://img.shields.io/badge/AI-OpenAI-orange" alt="AI Powered">
  </p>
</div>

## ✨ Features (Developing)

- Kanban-style board to track application status (Applied → Interview → Offer → Rejected) with drag & drop
- Add jobs manually or paste LinkedIn/Indeed URL (future: auto-scrape)
- Upload resume (PDF) → AI-powered scoring & match percentage against job description
- Smart suggestions: rewrite bullet points, fix keywords for ATS
- Dashboard with stats: applications count, success rate, charts (Recharts)
- PDF export of optimized resume
- User auth (email + Google OAuth planned)
- Dark mode & fully responsive

## 🛠 Tech Stack

| Layer       | Technology                          | Why?                              |
|-------------|-------------------------------------|-----------------------------------|
| Frontend    | React 18/19 + Vite + TypeScript     | Fast dev, modern hooks & types    |
| UI          | Tailwind CSS + shadcn/ui            | Beautiful, customizable components|
| State       | TanStack Query + Zustand            | Efficient data fetching & store   |
| Backend     | NestJS + TypeScript                 | Structured, scalable Node backend |
| Database    | PostgreSQL (Prisma ORM)             | Type-safe queries, easy migrations|
| AI          | Python + FastAPI + OpenAI API       | Separate microservice for AI tasks|
| Deployment  | Vercel (FE) + Railway/Render (BE)   | Free tiers for portfolio          |

## 🚀 Getting Started (Local Setup – Coming Soon)

1. Clone the repo  
   ```bash
   git clone https://github.com/FarhadJs/jobforge-ai.git
   cd jobforge-ai
   ```

2. Install dependencies (frontend & backend folders)  
   ```bash
   # Frontend
   cd frontend && npm install
   # Backend
   cd ../backend && npm install
   ```

3. Run dev servers  
   ```bash
   # Frontend
   npm run dev
   # Backend (in separate terminal)
   npm run start:dev
   ```

(Full setup guide with env vars coming after initial commit)

## 📸 Screenshots (placeholders – will update as built)

![Dashboard Preview](https://via.placeholder.com/1280x720?text=JobForge+AI+Dashboard)
![Kanban Board](https://via.placeholder.com/1280x720?text=Kanban+Board)
![Resume Analyzer](https://via.placeholder.com/1280x720?text=AI+Resume+Scoring)

## ⚡ Challenges & Learnings (Why this project?)

- Integrating AI (LLM prompts) with full-stack app while keeping costs low  
- Building drag & drop UI that's intuitive on mobile/desktop  
- Handling file uploads + PDF parsing for resume analysis  
- Structuring monorepo (frontend/backend/AI service) for clean dev experience  

This project is my personal portfolio showcase — built from scratch to demonstrate full-stack + AI skills for remote roles (US/Canada focus).

## 📄 License

MIT License — feel free to fork, learn from, or inspire your own projects!

Made with ❤️ by [Farhad Fallahi](https://github.com/FarhadJs)