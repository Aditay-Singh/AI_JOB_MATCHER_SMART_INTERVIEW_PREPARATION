# AI Job Matcher & Smart Interview Preparation System

A full-stack, AI-powered platform designed to streamline job description matching, automate candidate evaluation, conduct interactive mock technical/behavioral interviews, and generate recruiter-ready PDF resumes using modern web architectures and generative AI models.

 Table of Contents
- Core Principles & Architecture
- Key Features
- Tech Stack
- Project Directory Structure
- Environment Configuration
- Getting Started
- API Reference & Core Modules
- Security & AI Safeguards
- Interview & System Design Highlights

---

## Core Principles & Architecture

### 1. Context-Aware AI Matching Engine
Instead of basic keyword filtering, the system analyzes job description requirements against candidate project portfolios and skills using embeddings and generative intelligence to score alignment accuracy and generate tailored feedback.

### 2. Full-Stack Modular Separation
Decoupled architecture ensuring the frontend user interface communicates seamlessly via RESTful endpoints with a secure Node.js/Express backend service handling file processing, AI prompt orchestration, and dynamic PDF compilation.

### 3. Automated Document Generation
Transforms structured evaluation data and candidate credentials into cleanly formatted, downloadable PDF resumes without layout corruption or styling discrepancies.

---

##  Key Features

- **AI-Powered Mock Interviews:** Interactive technical and behavioral interview preparation modules backed by automated question-generation pipelines.
- **Dynamic Resume PDF Generator:** Automatically formats and compiles user data into clean, recruiter-ready PDF layouts.
- **Robust Input Validation & Sanitization:** Comprehensive field validation checks across all user-submitted parameters.
- **Secure Authentication & Token Management:** Secure session tracking, token verification, and environment-isolated credentials.
- **Centralized Error Handling:** Standardized error responses across all controllers to maintain client stability.

---

##  Tech Stack

| Component | Technology | Description |
| :--- | :--- | :--- |
| **Runtime** | Node.js | Asynchronous, event-driven JavaScript backend runtime |
| **Framework** | Express.js | Web framework for building clean RESTful APIs |
| **Frontend UI** | React / Vite & JavaScript | Responsive, high-performance single-page application interface |
| **Styling & Assets** | SCSS / HTML | Modern modular styling for clean component layout |
| **AI Integration** | Google Gen AI SDK | Generative models powering interview intelligence and feedback |
| **Document Processing** | PDF generation libraries | Dynamic server-side compilation of downloadable resume assets |

---

##  Project Directory Structure

interview-ai-yt/
├── Backend/
│   ├── src/
│   │   ├── app.js                 # Express application configuration & middleware
│   │   ├── controllers/           # Request handlers for interviews, matching, and resumes
│   │   ├── models/                # Database schemas and data models
│   │   ├── routes/                # API endpoint route definitions
│   │   └── services/              # AI prompt orchestration & email/PDF services
│   ├── package.json               # Backend dependencies and scripts
│   └── server.js                  # Application entry point & HTTP listener
├── Frontend/
│   ├── src/
│   │   ├── components/            # Reusable UI widgets (Interview panels, Dashboard)
│   │   ├── App.jsx                # Main application root component
│   │   └── main.jsx               # React DOM entry point
│   ├── package.json               # Frontend dependencies and Vite configuration
│   └── index.html                 # HTML root template
├── .env.example                   # Safe template of environment variables
└── README.md                      # Project documentation (this file)

---

##  Environment Configuration

Create a `.env` file inside the `Backend` directory based on required keys:

PORT=5000
NODE_ENV=development
GEMINI_API_KEY=your_gemini_api_key_here
JWT_SECRET=your_super_secret_jwt_key_here

---

## 🏁 Getting Started

### Prerequisites
- [Node.js](https://nodejs.org/) (v18 or higher recommended)
- Git installed on your local machine

### Installation & Local Setup

1. **Clone the repository:**
   ```bash
   git clone [https://github.com/Aditay-Singh/AI_JOB_MATCHER_SMART_INTERVIEW_PREPARATION.git](https://github.com/Aditay-Singh/AI_JOB_MATCHER_SMART_INTERVIEW_PREPARATION.git)
   cd AI_JOB_MATCHER_SMART_INTERVIEW_PREPARATION
