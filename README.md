<div align="center">

🚀 CareerPilot
AI-Powered Resume Analyzer & Career Recommendation Platform








</div>

📌 Overview

CareerPilot is a full-stack MERN application that leverages Artificial Intelligence to analyze resumes, recommend relevant job opportunities, identify skill gaps, and generate personalized learning roadmaps. The platform helps students, fresh graduates, and professionals make informed career decisions and improve their employability through AI-driven insights.




✨ Features




AI Resume Analysis — Upload a PDF resume and automatically extract skills, education, projects, and experience.
Job Matching — Discover relevant job opportunities ranked using AI-powered match scoring.
Skill Gap Detection — Compare your current skills against job requirements and identify missing competencies.
Learning Roadmap Generation — Receive personalized learning plans with curated resources to bridge skill gaps.
AI Resume Enhancement — Optimize and improve resumes for ATS compatibility using Gemini AI.
PDF Export — Download analyzed reports and enhanced resumes.
Secure Authentication — JWT-based login and registration system.
Modern Dashboard — Manage resumes, job recommendations, and career insights from one place.
📊 Resume Dashboard




Create a new resume from scratch or upload an existing resume for automatic parsing and analysis. Manage resumes efficiently with quick actions such as editing, renaming, deleting, and job matching.

🎯 Job Recommendations




CareerPilot fetches real-time job opportunities and intelligently evaluates them against your resume profile. Using Gemini AI, each opportunity is scored based on your skills, experience, and qualifications, ensuring that the most relevant roles appear first.

📈 Skill Gap Analysis




The platform compares your resume with job requirements to identify missing skills and competencies. Based on these gaps, CareerPilot generates personalized learning recommendations and structured roadmaps to accelerate your career growth.

🛠️ Tech Stack
Layer	Technologies
Frontend	React.js, Vite, CSS3
Backend	Node.js, Express.js
Database	MongoDB Atlas
AI	Google Gemini AI
Authentication	JWT, bcrypt
Media Storage	ImageKit
APIs	JSearch API
🚀 Getting Started
Prerequisites
Node.js v18+
MongoDB Atlas Account
Google Gemini API Key
JSearch API Key
ImageKit Account
Installation
1️⃣ Clone the Repository
git clone https://github.com/Muhammed23B/CareerPilot.git
cd CareerPilot
2️⃣ Backend Setup
cd server
npm install

Create a .env file inside the server directory:

PORT=5000

MONGODB_URI=your_mongodb_connection_string

JWT_SECRET=your_jwt_secret

GEMINI_API_KEY=your_gemini_api_key

JSEARCH_API_KEY=your_jsearch_api_key

IMAGEKIT_PRIVATE_KEY=your_imagekit_private_key
IMAGEKIT_PUBLIC_KEY=your_imagekit_public_key
IMAGEKIT_URL_ENDPOINT=your_imagekit_url_endpoint

Start the backend server:

npm run dev
3️⃣ Frontend Setup
cd ../client
npm install
npm run dev

Application will run at:

http://localhost:5173
📂 Project Structure
CareerPilot/
├── assets/
│   └── Screenshots/
│
├── client/
│   ├── src/
│   │   ├── assets/
│   │   ├── components/
│   │   ├── pages/
│   │   ├── app/
│   │   └── configs/
│   │
│   └── package.json
│
├── server/
│   ├── configs/
│   ├── controllers/
│   ├── middlewares/
│   ├── models/
│   ├── routes/
│   ├── services/
│   └── server.js
│
└── README.md
🎨 Key Highlights
AI Resume Analysis
Resume Enhancement using Gemini AI
Job Recommendation Engine
Skill Gap Detection
Personalized Learning Roadmaps
Secure User Authentication
Real-Time Career Insights
Modern and Responsive UI
🎯 Use Cases
Students preparing for placements
Fresh graduates entering the workforce
Professionals planning career transitions
Individuals seeking AI-powered career guidance
Users looking to improve ATS compatibility
🔮 Future Enhancements
ATS Resume Scoring
AI Cover Letter Generator
LinkedIn Profile Analysis
Mock Interview Assistant
Job Application Tracking
Advanced Career Analytics
Personalized Interview Preparation
👨‍💻 Author
Mohammed Bilal Ulla Shariff
🎓 B.E. Computer Science Engineering (AI & ML)
🏫 The National Institute of Engineering, Mysuru
💻 Full Stack Developer | AI/ML Engineer
Connect With Me
GitHub: https://github.com/Muhammed23B
LinkedIn: https://www.linkedin.com/in/mohammed-bilal-ulla-shariff
⭐ Support

If you found this project useful, consider giving it a ⭐ on GitHub and sharing it with others.

CareerPilot — Empowering Careers Through AI 🚀
