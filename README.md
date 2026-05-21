# codealpha_task3
This repository contains  my assignment and task source course
# Project Management Tool

A collaborative *Project Management Web Application* inspired by tools like *Trello* and *Asana*.  
This application helps teams manage projects, assign tasks, track progress, and communicate through comments.

The project is developed using *HTML, CSS, JavaScript* for the frontend and *Django / Express.js* for the backend.

---

# Features

- User Registration & Login
- Create Group Projects
- Project Boards
- Task Cards Management
- Assign Tasks to Team Members
- Comment & Communication System
- Responsive User Interface
- Database Storage for:
  - Users
  - Projects
  - Tasks
  - Comments

---

# Bonus Features

- Real-time Updates using WebSockets
- Notifications System
- Team Collaboration
- Task Status Tracking

---

# Technologies Used

## Frontend
- HTML
- CSS
- JavaScript

## Backend
- Django (Python) / Express.js (Node.js)

## Database
- SQLite / MySQL / MongoDB

---

# Project Structure

bash
Project-Management-Tool/
│
├── frontend/
│   ├── index.html
│   ├── dashboard.html
│   ├── projects.html
│   ├── style.css
│   └── script.js
│
├── backend/
│   ├── app.py / server.js
│   ├── models/
│   ├── routes/
│   ├── controllers/
│   └── database/
│
├── websocket/
├── images/
├── requirements.txt / package.json
└── README.md


---

# Installation

## Clone Repository

bash
git clone https://github.com/your-username/project-management-tool.git
cd project-management-tool


---

# Frontend Setup

Open the project folder and run:

bash
index.html


---

# Backend Setup (Django)

## Install Dependencies

bash
pip install django


## Run Server

bash
python manage.py runserver


---

# Backend Setup (Express.js)

## Install Dependencies

bash
npm install


## Start Server

bash
node server.js


---

# Functional Modules

## 1. User Authentication
- User registration
- Login and logout system
- Secure authentication

## 2. Project Management
- Create new projects
- Manage project boards
- Invite team members

## 3. Task Management
- Create task cards
- Assign tasks
- Update task status
- Track progress

## 4. Comments & Collaboration
- Add comments to tasks
- Team communication system
- Discussion within task cards

## 5. Notifications (Bonus)
- Real-time notifications
- Task assignment alerts
- Project activity updates

---

# Database Tables

## Users Table
- User ID
- Username
- Email
- Password

## Projects Table
- Project ID
- Project Name
- Description
- Created By

## Tasks Table
- Task ID
- Project ID
- Assigned User
- Task Status
- Deadline

## Comments Table
- Comment ID
- Task ID
- User ID
- Comment Text

---

# Sample Features

- Drag-and-drop style task organization
- Dynamic project boards
- Real-time team collaboration
- Interactive task cards
- User-friendly dashboard

---

# Future Enhancements

- File upload support
- Calendar integration
- Video meeting support
- Mobile application
- Advanced analytics dashboard
- AI-based task recommendations

---

# Applications

- Team collaboration platforms
- Software project management
- Academic project tracking
- Internship and portfolio projects
- Startup workflow management

---

# Conclusion

This project demonstrates the development of a collaborative project management system using modern full-stack technologies. It provides practical implementation of authentication, task management, database integration, and real-time communication features.

---

# Author

Software Internship Project – Task 3  
Project Management Tool
