# ClicknFix 🚨  
### Smart AI-Powered Incident Reporting & Resolution System  
**Team: Fix Factor**

---

## 🧠 Problem Statement
In chemical plants and industrial facilities, small maintenance or safety issues—such as leaks, unusual smells, equipment wear, or vibrations—often go unreported or are handled inefficiently. Manual reporting systems lack prioritization, visual evidence, and real-time insights, leading to delayed responses, safety risks, and operational downtime.

---

## 💡 Solution Overview
**ClicknFix** is a smart incident management platform that enables workers to report incidents with text and visual evidence (photo/video).  
An AI-powered classifier automatically analyzes the incident description, assigns a **risk-based priority**, and suggests immediate actions.  
A dedicated **support team dashboard** ensures faster resolution and better safety compliance.

---

## 🎯 Key Features (MVP)
- 🔐 **Role-based Authentication**
  - User (Plant Worker)
  - Support Team (Maintenance/Safety)

- 📝 **Incident Creation**
  - Title, description, location
  - Photo or video upload of the affected area

- 🤖 **AI Incident Classification**
  - Category: Chemical / Mechanical / Electrical / General
  - Priority: Low / Medium / High
  - Suggested immediate action

- 🚦 **Instant Priority Visualization**
  - 🔴 High
  - 🟡 Medium
  - 🟢 Low

- 📊 **Dashboards**
  - **User Dashboard**: Track personal incidents and status
  - **Support Dashboard**: View all incidents, filter by priority/status, and update resolution state

---

## 👥 User Roles

### 👷 User (Plant Worker)
- Create incidents
- Upload photo/video evidence
- View AI-assigned priority
- Track incident status

### 🧑‍🔧 Support Team
- View all incidents
- Filter by priority and status
- Review uploaded media
- Update incident status (Open → In Progress → Resolved)

---

## 🧠 AI Usage (Explainable & Safe)
AI is used as a **decision-support tool**, not as an autonomous controller.

### AI Responsibilities:
- Analyze incident description (text)
- Classify category and risk level
- Suggest next action

### What AI does NOT do:
- Does not auto-resolve incidents
- Does not override human decisions
- Does not analyze media (future scope)

This ensures safety, transparency, and reliability.

---

## 🛠️ Tech Stack
- **Frontend:** Next.js + Tailwind CSS  
- **Backend:** FastAPI (Python)  
- **Database:** PostgreSQL  
- **Media Storage:** Cloud storage (URL-based)  
- **AI:** OpenAI API (LLM-based text classification)  
- **Deployment:** Vercel (Frontend), Render (Backend)

---

## 🗂️ Project Structure
