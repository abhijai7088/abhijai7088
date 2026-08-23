# Hi, I'm Abhishek 👋

Backend & AI Developer focused on building scalable APIs, AI-powered systems, and production-ready full-stack applications.

---

## 🚀 About Me

I’m a B.Tech Computer Science (AI) student passionate about building real-world solutions using Artificial Intelligence, backend engineering, and modern web technologies.

I actively participate in national-level hackathons and innovation programs, building impactful systems across AI, computer vision, blockchain concepts, and full-stack platforms.

---

## 🏆 Hackathon Achievements

- 🥇 1st Prize – Hack-a-Pirate (NSUT, New Delhi)
- 🥇 1st Prize – NEXVERSE Hackathon (IITM, Janakpuri)
- 🥇 1st Prize – CodeAThon 4.0 (ABESIT)
- 🥈 2nd Prize – SuperNova Hackathon (GL Bajaj Institute of Technology)
- 🥈 2nd Position – Hackathon at Maharaja Agrasen Institute of Technology
- 🥉 3rd Prize – Innovator’s Knockout Startup Summit
- 🎯 Finalist – Hacknovate 6.0

Projects built during these events include AI systems, YOLOv8-based detection models, REST APIs, blockchain-based authentication systems, and full-stack dashboards.

---

## 🛠 Core Skills

### Backend
FastAPI • Flask • REST APIs • SQL • MongoDB • Docker

### Frontend
React • Vite • Tailwind CSS

### AI / ML
Scikit-learn • Pandas • NumPy • YOLOv8 • Model Deployment

### Programming
Python • Java (DSA)

---

## 🏗 What I Focus On

- Designing clean and modular backend architectures  
- Building ML-powered APIs and intelligent systems  
- Deploying Dockerized applications  
- Developing scalable full-stack platforms  
- Writing production-ready, maintainable code  

---

## 📌 Major Projects

### 🔹 ClimateTrack AI 🌍
AI-powered climate monitoring dashboard with AQI tracking, NASA API integrations, glacier monitoring, and chatbot assistance.

### 🔹 AI Lost Person Tracker 🧠
Real-time CCTV-based detection system using YOLOv8, ArcFace, ByteTrack, and ReID for intelligent identification and tracking.

### 🔹 Army Vehicle Dispatch System 🚛
Full-stack React + Flask dispatch platform with admin logs, vehicle status dashboard, and monitoring system.

### 🔹 Smart NFC + Blockchain Authentication 🔐
Product authentication system integrating NFC tags with Ethereum smart contracts for anti-counterfeit verification.

### 🔹 Patient Management API 🏥
Production-style FastAPI backend supporting CRUD, sorting, validation, and modular architecture.

### 🔹 E-Commerce Store 🛒
Shopping cart, billing, and checkout MVP designed for retail application.

---

## 📈 Current Focus

- Strengthening backend system design
- Building scalable AI-integrated platforms
- Preparing for Backend / AI Engineering roles
- Contributing to impactful open-source projects

---

## 📫 Open To

Backend Development • AI/ML Engineering • Hackathons • Open Source Collaboration



now since we have not yet updates did what you need to do you need to make it more professional and well structured and also design in such a way that recruites and the clienbts gets attracted and actualyy they give me worki you need to make it very well structured and also well uupdates as well 




you know the projects like the inherix , ai cms , ci cd agents 
also make sure you provide this in so that i paste this in the readme file of the profile and it looks done by advance designer and developer 




also details :
Digital Continuity Infrastructure for modern families
INHERIX is a premium, production-grade Next.js experience built to present a structured digital continuity platform for families, professionals, and trusted advisors. The repository powers the public marketing site, the app wireframe experience, legal and governance pages, and the product storytelling layer that sits behind the INHERIX brand.
Live Deployments

EnvironmentURLPurposePublic websitewww.inherix.netMain production-facing brand and marketing websiteApp wireframeapp.inherix.netProduct wireframe, dashboard preview, and experience demo
Product Summary

INHERIX is positioned as a calm, institutional, and trust-oriented continuity platform. It focuses on secure organization, nominee and family coordination, governance visibility, and controlled access workflows. The current repository is frontend-first and designed to communicate the product clearly rather than implement backend release logic.
What This Repository Includes

AreaDescriptionMarketing websitePremium homepage with storytelling, trust signals, product positioning, and calls to actionProduct pagesStructured pages explaining how the continuity workflow worksDashboard previewStatic Admin, Client, and Nominee wireframes that demonstrate the product experienceLegal and governance pagesTerms, privacy, consent, data access, disclaimer, grievance, and operating principlesMedia and assetsBrand imagery, dashboard references, use-case videos, and premium visual assetsSEO and metadataPage-specific metadata through shared helpers for production publishing
Key Features

Premium homepage with a high-end editorial visual language
Dedicated product pages for continuity, vault, access, security, and emergency workflows
Static dashboard preview built to look like a real product demo, not a generic admin template
Consultation-oriented contact experience with frontend-only form UI
Legal and governance content for a responsible public launch
Responsive layouts for desktop and mobile
Motion design and layered visual effects for a polished first impression
Production-aware SEO metadata and canonical URLs
Clear separation between marketing copy, demo content, and governance content


inherix product is also now ready and it is live at : app.inherix.net and wireframes is removed 



abhijai7088
Autonomous-CI-CD-Healing-Agent
Private
Go to file
t
T
abhijai7088
abhijai7088
README.md
71a751f
 · 
5 months ago
Name		
.github/workflows
fix(workflow): align RUNS_DIR with artifact upload path
5 months ago
PHOENIX-frontend
fix: vercel frontend vedio update
5 months ago
backend
fix: vercel frontend api resolution and robust cors origin matching
5 months ago
.gitignore
chore: ignore env files and run artifacts
5 months ago
README.md
README.md
5 months ago
ahishek.drawio (1).png
Add files via upload
5 months ago
Repository files navigation
README
🚀 Phoenix: Autonomous CI/CD Healing Agent
Status FastAPI React LangGraph

📋 Overview
Phoenix is an AI-powered self-healing repository engine that autonomously detects CI test failures, generates targeted AI-based fixes, commits changes, and iteratively repairs codebases. Simply provide a GitHub repository URL, and Phoenix's orchestrated multi-agent system handles the rest—no manual intervention required.

✨ Features
🤖 Fully Autonomous: Zero hardcoded logic; works with any repository structure.
🔍 Universal Framework Detection: Automatically identifies PyTest, Unittest, Jest, Mocha, Go test, and more.
🐳 Sandboxed Execution: Docker-isolated test runs with strict memory/time limits.
📊 Intelligent Parsing: Structures messy CI logs into actionable, classified issues.
🎯 Minimal Patches: Applies surgical fixes that preserve original business logic.
🔄 Smart Retry Loop: Iterative healing with configurable retry limits (default: 5).
📈 Multi-Language Support: Python, JavaScript, Go, and more.
🎥 Demo
Experience Phoenix in action. Click the image below to watch the full autonomous healing workflow:

Watch Demo Video

🏗 Architecture
Phoenix operates through a rigorous 7-stage agentic protocol orchestrated with LangGraph, ensuring reliable and transparent autonomous healing.

Phoenix Agentic Flow Diagram

The 7-Stage Agentic Protocol
Stage	Component	Responsibility
1️⃣	Repo Analyst	Detects ecosystem (Python, JS, Go) and project root.
2️⃣	Test Runner	Executes tests in secure, ephemeral Docker sandboxes.
3️⃣	Failure Parser	Converts raw logs into structured issues (SYNTAX vs. LOGIC).
4️⃣	Fix Planner	Prioritizes issues by severity and dependency graphs.
5️⃣	Code Editor	Generates precise patches via dual-pass LLM strategy.
6️⃣	Git Operator	Manages atomic commits and pushes to fix branches.
7️⃣	Verifier	Re-runs tests until codebase is healthy or limit reached.
💻 Tech Stack
Layer	Technologies
Backend	Python, FastAPI, LangGraph, Docker, OpenAI/Mistral LLMs
Frontend	React, TypeScript, Vite, GSAP, Framer Motion, TailwindCSS
Deployment	Render (Backend), Vercel (Frontend)
Orchestration	Custom multi-agent sequential pipeline
🔄 Workflow
User provides GitHub URL
         ↓
Repo Analyst detects ecosystem
         ↓
Test Runner executes in Docker sandbox
         ↓
Failure Parser structures issues
         ↓
Fix Planner prioritizes bugs
         ↓
Code Editor generates patches
         ↓
Git Operator commits & pushes
         ↓
Verifier re-runs tests
         ↓
    All tests pass? → ✅ Success
    Retry limit exceeded? → ⛔ Stopped
         ↓
    Dashboard displays results
📡 API Usage
Trigger a Self-Healing Run
Endpoint: POST /runs

Request:

curl -X POST "https://autonomous-ci-cd-healing-agent-c6vj.onrender.com/runs" \
     -H "Content-Type: application/json" \
     -d '{
       "repo_url": "https://github.com/example/broken-repo",
       "retry_limit": 5
     }'
Response:

{
  "run_id": "run_12345",
  "status": "in_progress",
  "repo_url": "https://github.com/example/broken-repo",
  "created_at": "2024-01-15T10:30:00Z"
}
Get Run Status
Endpoint: GET /runs/{run_id}

curl "https://autonomous-ci-cd-healing-agent-c6vj.onrender.com/runs/run_12345"
🛠 Supported Bug Types
Category	Examples
Syntax Errors	Missing colons, indentation issues, improper nesting.
Dependency Issues	Missing imports, outdated packages, environment mismatches.
Logical Regressions	Boolean errors, off-by-one errors, assertion failures.
Type Errors	Mismatched types (Python MyPy, TypeScript).
Test Failures	Failed unit tests with clear expected vs. actual values.
⚙️ Setup
Prerequisites
Python 3.9+
Node.js 16+
Docker
GitHub token (for private repo access)
OpenAI/Mistral API key
Backend Setup
cd backend
python -m venv venv
source venv/bin/activate  # Windows: .\venv\Scripts\activate
pip install -r requirements.txt
cp .env.example .env      # Configure your API keys
python main.py
The backend will start at http://localhost:8000.

Frontend Setup
cd PHOENIX-frontend
npm install
npm run dev
The frontend will be available at http://localhost:5173.

🔐 Environment Variables
Backend (.env)
# LLM Configuration
OPENAI_API_KEY=your_openai_key_here
MISTRAL_API_KEY=your_mistral_key_here

# GitHub Integration
GITHUB_TOKEN=your_github_token_here
GITHUB_USERNAME=your_github_username

# Docker & Execution
DOCKER_HOST=unix:///var/run/docker.sock
MAX_EXECUTION_TIME=300
SANDBOX_MEMORY_LIMIT=2GB

# API Configuration
API_PORT=8000
DEBUG=false
Frontend (.env)
// filepath: c:\knowledge\Autonomous-devops-agent\PHOENIX-frontend\.env
VITE_API_BASE=https://autonomous-ci-cd-healing-agent-c6vj.onrender.com
📁 Project Structure
Autonomous-devops-agent/
├── backend/
│   ├── agent/                    # Specialized AI agents
│   │   ├── repo_analyst.py
│   │   ├── test_runner.py
│   │   ├── failure_parser.py
│   │   ├── fix_planner.py
│   │   ├── code_editor.py
│   │   ├── git_operator.py
│   │   └── verifier.py
│   ├── api/
│   │   ├── routes.py
│   │   └── auth.py
│   ├── core/
│   │   ├── docker_runner.py
│   │   ├── llm_integration.py
│   │   └── pipeline.py
│   ├── main.py
│   └── requirements.txt
│
├── PHOENIX-frontend/
│   ├── src/
│   │   ├── pages/
│   │   │   ├── Dashboard.tsx
│   │   │   └── Architecture.tsx
│   │   ├── components/
│   │   │   ├── RunCard.tsx
│   │   │   └── AnimatedFlow.tsx
│   │   ├── App.tsx
│   │   └── main.tsx
│   ├── .env
│   ├── tailwind.config.js
│   └── package.json
│
├── artifacts/                    # Design docs & diagrams
│   └── agentic-flow-diagram.png
│
└── README.md
🌐 Live Deployments
Component	URL
Frontend Dashboard	phoenix-ci-dashboard.vercel.app
Backend API	autonomous-ci-cd-healing-agent-c6vj.onrender.com/docs
⚠️ Limitations
Requires valid GITHUB_TOKEN for private repository access.
Complex architectural refactors may need multiple iterations or manual intervention.
Very large repositories (>500MB) may exceed Docker sandbox memory limits.
Some advanced build systems (Bazel, Nix) have limited support.
👨‍💻 Contributors
Abhishek Jaiswal – System Architect & Lead Engineer
LinkedIn | GitHub

📄 License
This project is licensed under the MIT License—see the LICENSE file for details.

🙏 Acknowledgments
Built with LangGraph for agentic orchestration.
Powered by FastAPI and React.
Deployed on Render and Vercel.
Made with ❤️ for autonomous CI/CD healing.

About

AI-Powered Self-Healing Repository Engine. An autonomous system that detects CI test failures, generates minimal AI-based fixes, commits changes, and iteratively repairs repositories — given only a GitHub URL.

phoenix-ci-dashboard.vercel.app
Resources
Readme
Activity
Stars
0 stars
Watchers
0 watching
Forks
0 forks
Releases
No releases published
Create a new release
Deployments
13
 (13)
Production
5 months ago
Production – autonomous-ci-cd-healing-agent
inactive
Packages
No packages published
Publish your first package
Contributors
1
 (1)
@abhijai7088
abhijai7088Abhishek Jaiswal
Languages
Python
52.4%
TypeScript
45.4%
CSS
1.9%
Other
0.3%
Footer
© 2026 GitHub, Inc.
Footer navigation
Terms
Privacy
Security
Status
Community
Docs
Co














abhijai7088
clinic-management-ai-cms
Private
Go to file
t
T
abhijai7088
abhijai7088
README
27218e4
 · 
3 months ago
Name		
ai-service
second commit
3 months ago
backend
second commit
3 months ago
docs
second commit
3 months ago
frontend
third commit
3 months ago
infra/scripts
first commit
3 months ago
postman
first commit
3 months ago
.env.example
first commit
3 months ago
.gitignore
first commit
3 months ago
README.md
README
3 months ago
docker-compose.yml
first commit
3 months ago
Repository files navigation
README
AI-CMS - AI-Powered Clinic Management System
A clinic management platform for patient intake, appointments, consultations, prescriptions, billing, and assistive AI workflows.

Live Demo Stack AI Safety Docker License

Live Demo
Production demo: https://cms.ott-tube.in
Health check: https://cms.ott-tube.in/health
API health: https://cms.ott-tube.in/api/v1/health
API docs: https://cms.ott-tube.in/api-docs
The demo is hosted on a Hostinger VPS and should be reviewed as a real customer-facing deployment.

Production Snapshot
Area	Status
Hosting	Hostinger VPS, Ubuntu 24.04 LTS
Public URL	https://cms.ott-tube.in
Frontend	React + Vite, routed through Nginx
Backend	Node.js + Express API
AI Service	FastAPI assistive AI service
Database	MongoDB container in Docker
AI Provider	OpenRouter / OpenAI-compatible endpoint
Access Model	JWT + role-based access control
Overview
AI-CMS is a full-stack clinic management system designed to help clinics manage operational workflows from patient registration to billing. It combines a modern web dashboard with a backend API, MongoDB database, and a dedicated FastAPI-based AI service.

The system is built around one important principle:

AI supports doctors, but it does not replace doctors.
AI-generated suggestions must always be reviewed, edited, approved, or rejected by qualified medical professionals.

Live Product Flow
Patient / Staff Login
        ↓
Role-Based Dashboard
        ↓
Intake and Scheduling
  - Patient signup or staff login
  - Smart document upload and auto-fill
  - Patient profile creation and search
  - Appointment booking, rescheduling, or cancellation
        ↓
Clinical Workflow
  - Doctor opens the consultation workspace
  - Symptoms, vitals, diagnosis, and clinical notes are recorded
  - AI assists with note formatting, transcription, OCR, and suggestions
        ↓
Doctor Review
  - Doctor validates AI output
  - Final diagnosis and treatment remain doctor-controlled
  - Consultation draft is saved and finalized
        ↓
Orders and Records
  - Prescription is created and finalized
  - Invoice is generated and payment is tracked
  - Patient history stores consultations, prescriptions, and billing records
        ↓
Follow-Up and Audit
  - Clinic team reviews prior visits and outcomes
  - Role-based history screens remain available for future visits
Role Touchpoints
SUPER_ADMIN and ADMIN: create staff, manage clinic operations, and oversee workflows
RECEPTIONIST: register patients, manage appointments, and support billing
DOCTOR: conduct consultations, review AI output, and finalize prescriptions
PATIENT: access chatbot intake and personal visit history
PHARMACIST and LAB_TECHNICIAN: reserved for future workflow expansion
Screenshots
Screenshot files are stored in docs/Screenshots/.

Login
AI-CMS Login Screen	
Dashboard
AI-CMS Dashboard
Patient Registration
AI-CMS Patient Registration	
Appointment Booking
AI-CMS Appointment Booking
Consultation Workspace
AI-CMS Consultation Workspace	
AI Chatbot / Symptom Checker
AI-CMS AI Chatbot
Prescription Flow
AI-CMS Prescription Flow	
Billing Flow
AI-CMS Billing Flow
Core Modules
Module	Description
Authentication	JWT login, protected routes, and role-based access
Patient Management	Patient registration, profile management, and history
Doctor Management	Doctor profiles, availability, and consultation access
Appointments	Booking, rescheduling, cancellation, and calendar workflow
Consultation	Symptoms, vitals, diagnosis, notes, AI review, and final clinical record
AI Assistance	Symptom guidance, note formatting, OCR intake, transcription, and no-show analysis
Prescriptions	Prescription creation, finalization, and PDF download
Billing	Invoice generation, payment tracking, and invoice PDF download
Admin Operations	Staff workflows, role management, and clinic-level operations
Tech Stack
Layer	Technology
Frontend	React, Vite
Backend	Node.js, Express.js
Database	MongoDB
AI Service	Python, FastAPI
Authentication	JWT
API Documentation	Swagger / API Docs
Testing	Jest / Pytest / Frontend Build Checks
Deployment	Docker, Docker Compose, VPS-ready
Documentation	Markdown, Postman, Operator Guides
System Architecture
                       ┌────────────────────────┐
                       │     React Frontend      │
                       │      Vite Client        │
                       └───────────┬────────────┘
                                   │
                                   │ REST API
                                   ▼
                       ┌────────────────────────┐
                       │   Express Backend API   │
                       │ Auth, RBAC, Workflows   │
                       └───────┬────────┬───────┘
                               │        │
                               │        │ Internal AI API
                               ▼        ▼
                     ┌──────────────┐  ┌──────────────────┐
                     │   MongoDB    │  │ FastAPI AI Service│
                     │  Database    │  │ LLM/OCR/STT APIs  │
                     └──────────────┘  └──────────────────┘
Repository Structure
clinic-management-ai-cms/
│
├── frontend/                 # React + Vite frontend application
├── backend/                  # Express API and business logic
├── ai-service/               # FastAPI AI service
├── docs/                     # Manuals, guides, screenshots, and explanations
│   └── Screenshots/          # Product screenshots used in README
├── infra/                    # Infrastructure and deployment helpers
├── postman/                  # Postman collections and API artifacts
├── docker-compose.yml        # Full-stack Docker Compose setup
├── .env.example              # Example environment configuration
└── README.md                 # Main project documentation
User Roles
Role	Purpose
SUPER_ADMIN	Complete system-level access
ADMIN	Clinic operations and management
RECEPTIONIST	Patient registration, appointments, and billing support
DOCTOR	Consultation, AI review, prescriptions, and clinical workflows
PATIENT	Patient-facing access and chatbot/intake flow
PHARMACIST	Pharmacy-related workflow support
LAB_TECHNICIAN	Lab-related workflow support
AI_ADMIN	AI-related configuration and monitoring workflows
Public signup creates a PATIENT account only. Staff accounts should be created through the admin workflow.

Demo Credentials
After seeding demo data, these accounts are available:

Role	Email	Password
Admin	admin@aicms.local	Admin123!
Receptionist	receptionist@aicms.local	Reception@12345
Doctor	doctor@aicms.local	Doctor@12345
Patient	patient@aicms.local	Patient@12345
Local Setup
Prerequisites
Install the following:

Node.js 20+
Python 3.10+
MongoDB local instance or MongoDB Atlas
Git
Backend Setup
cd backend
copy .env.example .env
npm install
Set backend environment values:

NODE_ENV=development
PORT=5000
MONGO_MODE=local
MONGO_URI_LOCAL=mongodb://localhost:27017/ai-cms
JWT_SECRET=<strong-random-secret>
AI_SERVICE_URL=http://localhost:8000
FRONTEND_URL=http://localhost:5173
CLIENT_URL=http://localhost:5173
Seed demo/admin data:

npm run seed:admin
Start backend:

npm run dev
Backend URLs:

http://localhost:5000/health
http://localhost:5000/api/v1/health
http://localhost:5000/api-docs
AI Service Setup
cd ai-service
copy .env.example .env
python -m venv .venv
.venv\Scripts\activate
pip install -r requirements.txt
Set AI service environment values:

LLM_PROVIDER=openai
OPENAI_API_KEY=<your-key>
LLM_BASE_URL=<optional-openai-compatible-endpoint>
MODEL_MODE=gpt-4o-mini
WHISPER_ENABLED=true
OCR_ENABLED=true
Start AI service:

uvicorn app.main:app --reload --host 0.0.0.0 --port 8000
AI service URLs:

http://localhost:8000/health
http://localhost:8000/api/v1/health
Frontend Setup
cd frontend
copy .env.example .env
npm install
Set frontend environment values:

VITE_API_BASE_URL=http://localhost:5000/api/v1
VITE_AI_BASE_URL=http://localhost:8000/api/v1
Start frontend:

npm run dev
Frontend URL:

http://localhost:5173
Docker Setup
Use Docker Compose when you want to run the complete stack together.

copy .env.example .env
docker compose up --build
Recommended production values:

NODE_ENV=production
MONGO_MODE=direct
MONGO_URI=mongodb://mongo:27017/ai-cms
MONGO_URI_LOCAL=mongodb://mongo:27017/ai-cms
JWT_SECRET=<strong-random-secret>
CORS_ORIGIN=https://cms.ott-tube.in
FRONTEND_URL=https://cms.ott-tube.in
BACKEND_URL=https://cms.ott-tube.in
BACKEND_API_URL=https://cms.ott-tube.in/api/v1
VITE_API_BASE_URL=https://cms.ott-tube.in/api/v1
VITE_AI_BASE_URL=https://cms.ott-tube.in/api/v1
AI_SERVICE_URL=http://ai-service:8000
LLM_PROVIDER=openai
OPENAI_API_KEY=<your-key>
MODEL_MODE=gpt-4o-mini
BACKEND_PORT=5001
FRONTEND_PORT=5174
AI_SERVICE_PORT=8001
MONGO_PORT=27018
Environment Variables
Backend
Variable	Purpose
NODE_ENV	Runtime mode
PORT	Backend server port
MONGO_MODE	Local, Atlas, or direct Mongo mode
MONGO_URI_LOCAL	Local MongoDB connection string
MONGO_URI_ATLAS	MongoDB Atlas connection string
MONGO_URI	Generic MongoDB connection string
JWT_SECRET	JWT signing secret
JWT_EXPIRES_IN	JWT expiry duration
CORS_ORIGIN	Allowed frontend origin
FRONTEND_URL	Frontend URL
CLIENT_URL	Client URL
API_PREFIX	API route prefix
AI_SERVICE_URL	Internal AI service URL
UPLOAD_DIR	Upload storage directory
PRESCRIPTION_PDF_DIR	Prescription PDF storage path
INVOICE_STORAGE_DIR	Invoice PDF storage path
GST_DEFAULT_RATE	Default GST rate for billing
AI Service
Variable	Purpose
LLM_PROVIDER	AI provider name
OPENAI_API_KEY	OpenAI API key
LLM_API_KEY	Generic LLM provider key
LLM_BASE_URL	Optional OpenAI-compatible base URL
MODEL_MODE	Selected AI model
WHISPER_ENABLED	Enables transcription workflow
OCR_ENABLED	Enables OCR workflow
MAX_UPLOAD_MB	Upload size limit
Frontend
Variable	Purpose
VITE_API_BASE_URL	Backend API URL
VITE_AI_BASE_URL	AI API URL
How The Application Works
User signs in or registers as a patient.
Backend verifies the user and creates a JWT session.
Frontend loads routes according to the user role.
Reception/admin users register patients and create appointments.
Doctors open consultations and review clinical information.
AI provides assistive suggestions where enabled.
Doctor approves, edits, or rejects AI suggestions.
Prescriptions and invoices are generated.
Patient history stores consultations, prescriptions, and billing records.
AI Safety Principle
AI-CMS uses AI for support workflows only.

AI can assist with:

Symptom checking
Diagnosis suggestions
Clinical note formatting
OCR-based intake
Transcription
Prescription advice formatting
No-show analysis
AI must not be treated as the final medical authority. Doctors remain responsible for all final clinical decisions.

Testing
Backend tests:

cd backend
npm test
AI service tests:

cd ai-service
pytest
Frontend production build test:

cd frontend
npm run build
Deployment Notes
For production deployment:

Use HTTPS
Use strong JWT secrets
Keep MongoDB private
Do not expose internal service ports publicly
Store secrets in environment files or secret managers
Use a reverse proxy for frontend and API routing
Keep uploads and generated PDFs outside the Git repository
Use Docker Compose for isolated multi-service deployment
Keep existing server applications separate from this project folder
Recommended deployment folder:

/opt/ai-cms
Recommended subdomain example:

cms.ott-tube.in
Troubleshooting
Login is not working
Check:

Backend URL
JWT secret
Seeded user credentials
MongoDB connection
Browser console and backend logs
AI service returns 503
Check:

LLM_PROVIDER
OPENAI_API_KEY
LLM_BASE_URL
AI service logs
Network connectivity between backend and AI service
OCR or transcription is not working
Check:

WHISPER_ENABLED
OCR_ENABLED
Upload size limit
AI provider endpoint support
Doctor profile is missing
Seed demo data or create the doctor profile through the admin workflow.

MongoDB connection fails
Check:

MongoDB URI
MONGO_MODE
Atlas IP allowlist
Local MongoDB service status
Screenshots are not visible on GitHub
Check that the file names exactly match the README paths.

Current expected screenshot names:

docs/Screenshots/01-login.png
docs/Screenshots/02-dashboard.png
docs/Screenshots/03-patient-registration.png
docs/Screenshots/04-appointment-booking.png
docs/Screenshots/05-consultation-workspace.png
docs/Screenshots/06-ai-chatbot.png
docs/Screenshots/07-prescription.png
docs/Screenshots/08-billing.png
Security and Git Hygiene
Never commit:

.env files
API keys
Database connection strings
Generated PDFs
Uploaded documents
Browser test artifacts
Local logs
Private patient data
Recommended practices:

Use strong JWT secrets
Rotate exposed keys immediately
Keep production uploads outside Git
Restrict MongoDB network access
Use HTTPS in production
Review AI outputs before clinical use
Generate a strong JWT secret:

node -e "console.log(require('crypto').randomBytes(64).toString('hex'))"
Documentation
Operator Manual
Quick Start
Deployment Guide
Hostinger VPS Guide
Release Checklist
System Explanation
License
Internal project unless a license is added later.

About

AI-CMS is a clinic management MVP with role-based access, patient intake, appointments, consultations, prescriptions, billing, and assistive AI workflows.

Resources
Readme
Activity
Stars
0 stars
Watchers
0 watching
Forks
0 forks
Releases
No releases published
Create a new release
Packages
No packages published
Publish your first package
Contributors
1
 (1)
@abhijai7088
abhijai7088Abhishek Jaiswal
Languages
JavaScript
92.5%
Python
7.3%
Other
0.2%
Suggested workflows
Based on your tech stack

SLSA Generic generator logo
SLSA Generic generator
Generate SLSA3 provenance for your existing release workflows
By Open Source Security Foundation (OpenSSF)
Datadog Synthetics logo
Datadog Synthetics
Run Datadog Synthetic tests within your GitHub Actions workflow
By Datadog
Node.js logo
Node.js
Build and test a Node.js project with npm.
By GitHub Actions
More workflows
Footer
© 2026 GitHub, Inc.
Footer navigation
Terms
Privacy
Security
Status
Community
D
