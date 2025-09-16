# eduproctor
 EduProctor is a modern **Learning Management System** with built-in **AI-powered virtual exam proctoring**.   It helps institutions deliver online courses, manage students, and conduct secure exams.
 
EduProctor LMS

Repository name: eduproctor-lms

Features (MVP – Minimum Viable Product)

LMS Core

User registration (students, instructors, admins)

Course management (create, enroll, upload materials)

Assignment submissions & grading

Discussion forums

Exam Module

Schedule exams

Randomized question banks

Timer & auto-submit

AI Virtual Proctor

Webcam monitoring (face detection, multiple people alert)

Microphone monitoring (suspicious sounds)

Screen activity logging (tab switching alerts)

Cheat-detection dashboard for instructors

Reports & Analytics

Student performance

Proctoring violation logs

Export reports (CSV, PDF)

 Tech Stack (Suggested)

Frontend (Web): React.js (clean UI for students & instructors)

Backend/API: Django (Python) or Node.js (Express)

Database: PostgreSQL

AI/Proctoring:

OpenCV / Mediapipe (for face & gaze detection)

TensorFlow.js or PyTorch (basic ML models)

WebRTC (real-time webcam/audio streaming)


eduproctor-lms/
│── README.md
│── LICENSE
│── backend/            # API & LMS logic (Django/Node)
│   └── exams/
│   └── courses/
│   └── proctoring/
│── frontend/           # React.js app
│   └── src/
│── ai-proctor/         # AI models & scripts
│   └── face_detection.py
│   └── sound_monitor.py
│── docs/               # Documentation
│── tests/              # Unit tests
