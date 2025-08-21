# InterviewPrep.io

A mock-interview platform where candidates can **book slots, join live interview rooms, collaborate on coding problems, chat in real-time, and receive rubric-based feedback**.  
_Tagline: Practice like it’s real, prepare like a pro._

---

## 🚀 Demo / Screenshots
*(Add screenshots or a Loom demo link once frontend is ready)*  

---

## ✨ Features
- Slot booking system with calendar export.  
- Live interview rooms with collaborative coding editor & chat.  
- Rubric-based feedback from interviewers.  
- Secure role-based authentication (candidate / interviewer).  
- Responsive UI with protected routes.  

---

## 🏗️ Architecture Overview
**Planned High-Level Flow:**
- **Frontend (React via Bolt.new)** → **REST/WebSocket APIs (Spring Boot)** → **Database (PostgreSQL, Redis cache)**.  
- **Services containerized with Docker** → **Orchestrated on Kubernetes** → **Monitored with Zipkin/Prometheus**.  

*(Insert diagram once ready)*  

---

## 🛠️ Tech Stack
- **Frontend:** React (Bolt.new, Tailwind CSS)  
- **Backend (planned):** Spring Boot, WebSockets, REST APIs  
- **Database:** PostgreSQL, Redis (cache/session store)  
- **DevOps:** Docker, Kubernetes, CI/CD (GitHub Actions)  
- **Cloud:** Google Kubernetes Engine (GKE)  
- **Auth & Security:** JWT, OAuth2  

---

## ⚡ Getting Started / Installation
```bash
# Clone the repo
git clone https://github.com/your-username/interviewprep.io.git
cd interviewprep.io

# Install frontend dependencies
cd frontend
npm install
npm run dev
```
