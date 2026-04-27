# TealEdge Learning Management System

TealEdge is a modern, full-stack Learning Management System (LMS) designed to facilitate course management, student enrollments, and assignment tracking. It features secure Google OAuth authentication, role-based access control (Student, Faculty, Admin), and a robust API.

## 🚀 Tech Stack

### Frontend
- **Framework:** React 18 with Vite
- **Routing:** React Router v6
- **Authentication:** Google OAuth (`@react-oauth/google`), Custom JWT (`jwt-decode`)
- **Network Requests:** Fetch API / Axios

### Backend
- **Framework:** Spring Boot 3.2.5 (Java 17)
- **Database:** MySQL
- **ORM:** Spring Data JPA (Hibernate)
- **Authentication:** Google API Client & JJWT (JSON Web Token)
- **API Documentation:** Springdoc OpenAPI (Swagger UI)
- **Data Mapping:** ModelMapper

## ✨ Key Features

- **Secure Authentication:** Users log in securely via Google OAuth, which the backend verifies to issue custom JWTs for session management.
- **Role-Based Access Control (RBAC):** Distinct dashboards and permissions for Students, Faculty, and Admins.
- **Course Management:** Faculty can create and manage courses; students can view and enroll in them.
- **Assignment Workflow:** Full submission workflow enabling students to upload files for assignments and faculty to review them.
- **Interactive API Docs:** Built-in Swagger UI for easy backend API exploration and testing.

## 🛠️ Getting Started

### Prerequisites
- Node.js (v18+ recommended)
- Java 17
- Maven
- MySQL Server (Running locally or accessible remotely)

### Backend Setup
1. Navigate to the backend directory:
   ```bash
   cd backend
