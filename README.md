# Full-Stack Project Management System (Mini Jira)

## Overview

This is a full-stack web application that allows users to manage projects and tasks.
It demonstrates backend development using Spring Boot, frontend development using React, and integration through RESTful APIs.

---

## Tech Stack

* Backend: Java, Spring Boot
* ORM: JPA / Hibernate
* Database: MySQL / PostgreSQL
* Frontend: React.js (JavaScript)
* API Communication: REST APIs (Axios)
* Testing: JUnit, Mockito, Jest
* Version Control: Git & GitHub

---

## Features

* Create and manage projects
* Create, update, and delete tasks
* Task status tracking (TODO / IN_PROGRESS / DONE)
* RESTful API integration between frontend and backend
* Persistent storage using relational database

---

## System Architecture

* Controller Layer → Handles API requests
* Service Layer → Business logic
* Repository Layer → Database interaction
* Frontend → React UI consuming APIs

---

## API Endpoints

### Projects

* GET /api/projects
* POST /api/projects

### Tasks

* GET /api/tasks?projectId={id}
* POST /api/tasks
* PUT /api/tasks/{id}
* DELETE /api/tasks/{id}

---

## How to Run Locally

### Backend

```bash
cd backend
./mvnw spring-boot:run
```

### Frontend

```bash
cd frontend
npm install
npm start
```

---

## What This Project Demonstrates

* Building RESTful APIs with Spring Boot
* Database integration using JPA/Hibernate
* Designing relational data models
* Developing interactive UI with React
* Integrating frontend and backend systems
* Writing unit tests for backend and frontend

---

## Future Improvements

* User authentication (JWT)
* Role-based access control
* UI enhancements
* Deployment (Docker / Cloud)

---

## Author

Vaibhav
