# 🚗 Dealership Review Application

A full-stack web application developed as part of the **IBM Full Stack Software Developer Professional Certificate Capstone Project**. The application allows users to browse car dealerships, view dealership details, register/login, and submit reviews for dealerships.

---

## 📖 Project Overview

This application demonstrates modern full-stack development practices using React, Django, Node.js, MongoDB, Docker, and cloud-native deployment concepts.

### Key Features

- User authentication (Register & Login)
- Browse dealerships
- View dealership details
- Submit dealership reviews
- View existing reviews
- Responsive user interface
- RESTful API integration
- Containerized deployment with Docker

---

## 🛠️ Tech Stack

### Frontend
- React.js
- Bootstrap
- HTML5
- CSS3
- JavaScript

### Backend
- Django
- Django REST Framework
- Node.js
- Express.js

### Database
- MongoDB
- SQLite (Django)

### Cloud & DevOps
- Docker
- Kubernetes (deployment practice)
- IBM Cloud
- Git & GitHub

---

## 📂 Project Structure

```
xrwvm-fullstack_developer_capstone/
│
├── server/               # Backend services
├── database/             # Database configuration
├── frontend/             # React application
├── djangoproj/           # Django project
├── static/               # Static assets
├── deployment/           # Deployment files
├── Dockerfile
├── docker-compose.yml
└── README.md
```

---

## 🚀 Getting Started

### Prerequisites

- Git
- Python 3.10+
- Node.js 18+
- npm
- Docker (optional)

---

## Installation

### Clone the repository

```bash
git clone https://github.com/faisalMdSaud/xrwvm-fullstack_developer_capstone.git

cd xrwvm-fullstack_developer_capstone
```

### Backend Setup

```bash
cd server

python -m venv env

source env/bin/activate
# Windows
env\Scripts\activate

pip install -r requirements.txt

python manage.py migrate

python manage.py runserver
```

### Frontend Setup

```bash
cd frontend

npm install

npm start
```

---

## Running with Docker

```bash
docker-compose up --build
```

---

## Application Features

### Authentication

- User Registration
- User Login
- Secure Session Management

### Dealership Module

- View dealerships
- Dealer details
- Filter dealerships

### Reviews

- Add dealership reviews
- View all reviews
- User-specific submissions

---

## API Endpoints

| Method | Endpoint | Description |
|---------|----------|-------------|
| GET | /api/dealerships | Get all dealerships |
| GET | /api/dealerships/:id | Get dealership details |
| GET | /api/reviews | Get reviews |
| POST | /api/reviews | Submit review |
| POST | /login | User login |
| POST | /register | User registration |

---

## Screenshots

Add screenshots here:

- Home Page
- Login Page
- Dealership Listing
- Review Submission
- Review Details

---

## Learning Outcomes

This project demonstrates:

- Full Stack Development
- REST API Design
- Authentication
- React Components
- Django Backend Development
- Database Integration
- Docker Containerization
- Cloud Deployment Concepts
- Git Version Control

---

## Future Improvements

- User profile management
- Review editing and deletion
- Admin dashboard
- Search functionality
- Pagination
- Rating system
- Unit and integration testing
- CI/CD pipeline

---

## Author

**Faisal Md Saud**

GitHub:
https://github.com/faisalMdSaud

---

## Acknowledgements

- IBM Skills Network
- Coursera
- IBM Full Stack Software Developer Professional Certificate

---

## License

This project is developed for educational purposes as part of the IBM Full Stack Developer Capstone Project.
