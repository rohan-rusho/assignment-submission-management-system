# 📚 Assignment Submission Management System

A role-based **Assignment & Submission Management System** developed as part of the **Assistant Software Engineer Recruitment Project**.

The application allows administrators to manage users, classes, and subjects, teachers to create and evaluate assignments, and students to submit assignments and view results.

---

# 🚀 Technology Stack

## Backend

- ASP.NET Core Web API
- C#
- Entity Framework Core
- PostgreSQL
- JWT Authentication
- Swagger / OpenAPI
- FluentValidation
- AutoMapper
- Serilog
- xUnit

## Frontend

- Next.js
- React
- TypeScript
- Tailwind CSS
- Axios
- React Hook Form

---

# 🏗️ Architecture

This project follows **Clean Architecture** principles.

```
Presentation (API)
        │
Application Layer
        │
Domain Layer
        │
Infrastructure Layer
        │
PostgreSQL Database
```

---

# 📁 Project Structure

```
AssignmentSubmissionSystem/

├── backend/
│   ├── AssignmentSystem.API
│   ├── AssignmentSystem.Application
│   ├── AssignmentSystem.Domain
│   ├── AssignmentSystem.Infrastructure
│   └── AssignmentSystem.Tests
│
├── frontend/
│
├── database/
│
├── docs/
│   ├── api/
│   ├── database/
│   ├── diagrams/
│   └── ui/
│
├── screenshots/
│
├── README.md
└── .gitignore
```

---

# 👥 User Roles

- Admin
- Teacher
- Student

---

# ✨ Features

## Admin

- User Management
- Class Management
- Subject Management
- Teacher Assignment
- Assignment Monitoring
- Submission Monitoring

## Teacher

- Create Assignment
- Edit Assignment
- Delete Assignment
- Publish Assignment
- View Student Submissions
- Grade Assignments
- Provide Feedback

## Student

- View Assignments
- Submit Assignments
- Update Submission (Before Deadline)
- View Marks
- View Teacher Feedback

---

# 🔒 Authentication

- JWT Authentication
- Role-Based Authorization

---

# 🧪 Testing

- Unit Testing using xUnit

---

# 📖 API Documentation

- Swagger / OpenAPI

---

# 📌 Project Status

🚧 Project setup in progress.

---

# 📄 License

This project was created for the Assistant Software Engineer Recruitment Assignment.
