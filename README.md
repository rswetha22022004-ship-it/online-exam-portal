This project is a full-stack **Online Exam Portal** developed using **React.js** for the frontend and **Django** for the backend.
It is designed to streamline the process of conducting online examinations with a user-friendly and responsive interface. 
The system includes secure authentication with separate dashboards for administrators and students. 
Admins can create and manage exams, add questions, and monitor student performance, while students can log in, attend exams, and view their results instantly. 
The platform also features automatic score evaluation and an AI-based module to assist in generating important questions from the syllabus. 
Overall, the application focuses on improving efficiency, accuracy, and user experience in online exam management.
Tech Stack

Frontend:

React.js
HTML, CSS, JavaScript

Backend:

Django
Django REST Framework

Database:

SQLite (default) / MySQL

Backend Setup (Django)
cd backend
python -m venv venv
venv\Scripts\activate   # Windows
pip install -r requirements.txt
python manage.py migrate
python manage.py runserver


Frontend Setup (React)
cd frontend
npm install
npm start

Usage
Admin can:
Create exams
Add questions
View student performance
Students can:
Login
Attend exams
View results instantly
