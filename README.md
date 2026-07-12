# 🚀 CareerPilot – AI-Powered Career Development Platform

CareerPilot is an intelligent career guidance platform that helps users build professional resumes, analyze skill gaps, discover relevant job opportunities, and receive AI-powered career recommendations.

The platform combines modern web technologies with Generative AI to provide personalized career insights and help users make informed career decisions.

---

## ✨ Features

### 📝 AI Resume Builder
- Create professional resumes using multiple templates
- Live resume preview
- Download-ready resume formats
- Customizable themes and layouts

### 🎯 Job Matching System
- Match resumes with job requirements
- Analyze resume-job compatibility
- Detailed match score and insights

### 🧠 AI Career Recommendations
- Personalized career suggestions
- AI-generated improvement recommendations
- Career growth guidance

### 📊 Skill Gap Analysis
- Identify missing skills for target roles
- Compare current skills with industry requirements
- Personalized upskilling suggestions

### 🛣️ Learning Roadmaps
- AI-generated learning paths
- Recommended technologies and courses
- Structured career progression plans

### 🔐 User Authentication
- Secure registration and login
- JWT-based authentication
- Protected user data and resumes

---

## 🏗️ System Architecture

```text
Frontend (React + Vite)
          │
          ▼
REST APIs
          │
          ▼
Backend (Node.js + Express)
          │
 ┌────────┼────────┐
 │        │        │
 ▼        ▼        ▼
MongoDB  Gemini AI  External Services
```

---

## 🛠️ Tech Stack

### Frontend
- React.js
- Vite
- Redux Toolkit
- React Router
- CSS

### Backend
- Node.js
- Express.js

### Database
- MongoDB
- Mongoose

### AI Integration
- Google Gemini AI

### Authentication
- JWT (JSON Web Token)
- bcrypt

### File Handling
- Multer
- ImageKit

---

## 📂 Project Structure

```text
CareerPilot/
│
├── client/
│   ├── src/
│   │   ├── components/
│   │   ├── pages/
│   │   ├── app/
│   │   ├── assets/
│   │   └── configs/
│   │
│   └── package.json
│
├── server/
│   ├── controllers/
│   ├── routes/
│   ├── models/
│   ├── middlewares/
│   ├── services/
│   ├── configs/
│   └── server.js
│
└── README.md
```

---

## 🔥 Core Modules

### Resume Builder
- Personal Information
- Education
- Experience
- Skills
- Projects
- Professional Summary

### Job Recommendation Engine
- Job role recommendations
- Resume analysis
- Career suitability scoring

### Skill Gap Analyzer
- Missing skills detection
- Technology recommendations
- Industry-aligned learning suggestions

### AI Career Advisor
- Gemini-powered recommendations
- Career planning assistance
- Learning guidance

---

## ⚙️ Installation

### Clone Repository

```bash
git clone https://github.com/your-username/CareerPilot.git
cd CareerPilot
```

---

## Backend Setup

```bash
cd server
npm install
```

Create a `.env` file:

```env
PORT=5000

MONGODB_URI=your_mongodb_connection_string

JWT_SECRET=your_jwt_secret

GEMINI_API_KEY=your_gemini_api_key

IMAGEKIT_PUBLIC_KEY=your_imagekit_public_key
IMAGEKIT_PRIVATE_KEY=your_imagekit_private_key
IMAGEKIT_URL_ENDPOINT=your_imagekit_url
```

Start backend:

```bash
npm run dev
```

---

## Frontend Setup

```bash
cd client
npm install
```

Start frontend:

```bash
npm run dev
```

Application:

```text
http://localhost:5173
```

---

## 📸 Features Overview

- AI Resume Builder
- Resume Templates
- Skill Gap Analysis
- AI Career Guidance
- Job Matching Engine
- Personalized Roadmaps
- Learning Recommendations
- User Dashboard

---

## 🎯 Use Cases

- Students preparing for placements
- Fresh graduates
- Job seekers
- Career switchers
- Professionals looking to upskill

---

## 🚀 Future Enhancements

- ATS Resume Scoring
- LinkedIn Profile Analysis
- Mock Interview Assistant
- AI Cover Letter Generator
- Resume Optimization Suggestions
- Job Application Tracker

---
