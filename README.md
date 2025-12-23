# ClickNFix 🚨  
### AI-Assisted Incident Reporting & Prioritization System  

**Team: Fix Factor**

---

## 🧠 Problem Statement
In industrial facilities and chemical plants, safety and maintenance issues such as leaks, unusual smells, equipment malfunction, or abnormal vibrations are often reported manually. These traditional systems lack prioritization, visual evidence, and structured tracking, leading to delayed responses, increased safety risks, and operational downtime.

---

## 💡 Solution Overview
**ClickNFix** is a smart incident management platform that enables workers to report incidents using text along with photo or video evidence.  
An AI-powered classifier analyzes the incident description to determine its category and priority (Low / Medium / High), helping the support team respond faster and more effectively through a centralized dashboard.

---

## 🎯 MVP Features
- 🔐 **Role-Based Authentication**
  - User (Worker)
  - Support Team (Maintenance / Safety)

- 📝 **Incident Creation**
  - Title, description, location
  - Upload photo or short video of the affected area

- 🤖 **AI-Powered Classification**
  - Incident category (Chemical / Mechanical / Electrical / General)
  - Risk priority (Low / Medium / High)
  - Suggested immediate action

- 🚦 **Instant Priority Visualization**
  - 🔴 High  
  - 🟡 Medium  
  - 🟢 Low  

- 📊 **Dashboards**
  - **User Dashboard:** View personal incidents and their status
  - **Support Dashboard:** View all incidents, filter by priority/status, review media, and update resolution status

---

## 👥 User Roles

### 👷 User (Plant Worker)
- Report incidents
- Upload photo or video evidence
- View AI-assigned priority
- Track incident status

### 🧑‍🔧 Support Team (Maintenance / Safety)
- View all reported incidents
- Filter incidents by priority and status
- Review uploaded media
- Update incident status (Open → In Progress → Resolved)

---

## 🧠 AI Usage (Explainable & Safe)
AI is used as a **decision-support tool**, not an autonomous controller.

### AI Responsibilities:
- Analyze incident description (text)
- Classify incident category
- Assign risk-based priority
- Suggest next action

### AI Limitations:
- Does not auto-resolve incidents
- Does not override human decisions
- Does not analyze images/videos (future scope)

This ensures transparency, safety, and reliability.

---

## 🛠️ Tech Stack
- **Frontend:** Next.js + Tailwind CSS  
- **Backend:** FastAPI (Python)  
- **Database:** PostgreSQL  
- **Media Storage:** Cloud storage (URL-based)  
- **AI:** OpenAI API (LLM-based text classification)  
- **Deployment:** Vercel (Frontend), Render (Backend)

---

## 📁 Project Structure
ClickNFix/

├── frontend/ # Next.js frontend

├── backend/ # FastAPI backend

├── docs/ # Architecture & diagrams

└── README.md


---

## 🚀 Future Enhancements
- AI-based image and video analysis
- Predictive maintenance insights
- Real-time notifications
- Advanced analytics dashboard
- Mobile application support

---

## 👨‍💻 Team Fix Factor
- **Aaru** – Backend Development, AI Integration, System Design  
- **Chakrshen** – Frontend Development, UI/UX Design, Demo & Presentation  

---

## 🏁 Hackathon Build Notes
This project was developed using AI-assisted coding to accelerate implementation, while all system architecture, logic, workflows, and safety considerations were designed and validated by the team.

