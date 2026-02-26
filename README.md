🎓 Web-Based Learning Management System (LMS)

A full-stack web application for content delivery, student progress tracking, and performance analysis.

This system enables teachers to manage courses and assignments, students to access learning materials and track progress, and administrators to monitor overall performance.

📌 Project Overview

The Learning Management System (LMS) provides:

📚 Course creation and management

📝 Assignment and quiz management

📊 Student progress tracking

📈 Performance analytics and reports

🔐 Secure role-based authentication

🚀 Features
👨‍🎓 Student

Register/Login

Enroll in courses

Access lessons (video, PDF, notes)

Submit assignments

Attempt quizzes

View grades and progress reports

👩‍🏫 Teacher

Create and manage courses

Upload learning materials

Create assignments and quizzes

Evaluate submissions

Monitor student progress

🛠 Admin

Manage users

Manage courses

Generate system-wide reports

Monitor platform activity

🏗 System Architecture

This project follows a 3-Tier Architecture:

Frontend (Client Layer) – React-based UI

Backend (Application Layer) – Node.js + Express REST API

Database (Data Layer) – MongoDB

🛠 Tech Stack
Frontend

React

React Router

Axios

CSS / Tailwind (optional)

Backend

Node.js

Express.js

JWT Authentication

Bcrypt (Password Hashing)

Database

MongoDB

Mongoose ODM

Deployment (Optional)

Render / Vercel / AWS

Docker (if containerized)

📂 Folder Structure
lms-system/
│
├── frontend/        # React frontend
├── backend/         # Express backend
├── docs/            # UML, DFD, Architecture diagrams
├── database/        # Seed & migrations
├── uploads/         # Assignment submissions
├── tests/           # Unit & integration tests
├── .env.example
└── README.md
🔑 Installation Guide
1️⃣ Clone Repository
git clone https://github.com/your-username/lms-system.git
cd lms-system
2️⃣ Backend Setup
cd backend
npm install

Create a .env file:

PORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_secret_key

Run backend:

npm run dev
3️⃣ Frontend Setup
cd frontend
npm install
npm start
🔐 Authentication & Authorization

JWT-based authentication

Role-based access control

Secure password hashing

Protected API routes

📊 Core Modules
1. Content Delivery

Course management

Lesson uploads

Assignment and quiz system

2. Student Progress Tracking

Completion percentage

Submission tracking

Quiz attempt tracking

3. Performance Analysis

Grade calculation

Performance trends

Analytics dashboard

🧪 Testing

To run tests:

npm test

Tests include:

API endpoint validation

Authentication testing

Business logic testing

📈 Future Enhancements

AI-based performance prediction

Gamification (badges, leaderboard)

Live class integration

Discussion forum

Certificate generation

Microservices architecture upgrade

📚 Documentation

System design documents available in /docs:

UML Class Diagram

Data Flow Diagram (DFD)

System Architecture Diagram

ER Diagram

🤝 Contribution

Contributions are welcome.

Fork the project

Create a feature branch

Commit changes

Submit a Pull Request

📄 License

This project is licensed under the MIT License.

👨‍💻 Author

Harshdeep Singh
Bachelor’s Degree Project
Web-Based LMS System