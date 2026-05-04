# E-TODO

## Project Overview

**E-TODO** is my first project developed at **Epitech**, created on **November 3rd**. This is a full-stack task management application designed to help users organize and track their daily tasks efficiently.

## Tech Stack

### Frontend
- **Framework**: Next.js with TypeScript
- **Styling**: CSS with PostCSS
- **Linting**: ESLint

### Backend
- **Runtime**: Node.js
- **Authentication**: Custom auth system with JWT support
- **Database**: MySQL (SQL file included)

### Deployment
- **Containerization**: Docker & Docker Compose

## Project Structure

```
E-TODO/
├── backend/              # Node.js backend server
│   ├── auth.js          # Authentication logic
│   ├── db.js            # Database connection
│   ├── route.js         # API routes
│   ├── package.json     # Backend dependencies
│   ├── Dockerfile       # Backend container configuration
│   ├── etodo.sql        # Database schema
│   └── key.env          # Environment configuration
├── frontend/            # Next.js frontend application
│   ├── app/             # Application pages
│   │   ├── accueil/     # Home page
│   │   ├── login/       # Login page
│   │   ├── register/    # Registration page
│   │   ├── taskmanager/ # Task management page
│   │   └── ...
│   ├── public/          # Static assets
│   ├── package.json     # Frontend dependencies
│   ├── Dockerfile       # Frontend container configuration
│   └── tsconfig.json    # TypeScript configuration
└── docker-compose.yml   # Docker Compose configuration
```

## Features

- User authentication and registration
- Task creation, editing, and deletion
- Responsive user interface
- Secure backend API
- Database persistence

## Getting Started

### Prerequisites
- Docker and Docker Compose installed on your system
- Node.js (v18 or higher) for local development
- MySQL (if running without Docker)

### Installation & Setup

1. **Clone the repository**
   ```bash
   git clone <repository-url>
   cd E-TODO
   ```

2. **Using Docker Compose (Recommended)**
   ```bash
   docker-compose up --build
   ```

3. **Local Development Setup**

   **Backend:**
   ```bash
   cd backend
   npm install
   npm start
   ```

   **Frontend:**
   ```bash
   cd frontend
   npm install
   npm run dev
   ```

## Environment Configuration

Create a `key.env` file in the backend directory with the necessary environment variables for database connection and authentication.

## Database

The database schema is provided in `backend/etodo.sql`. Import this into your MySQL instance to set up the required tables.

## Development Notes

This project serves as my first comprehensive full-stack application at Epitech, demonstrating:
- Frontend-backend integration
- Authentication implementation
- Database design and management
- Docker containerization
- RESTful API design

## License

This is a school project created for educational purposes.

---
