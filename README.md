# Contact Management System

A full-stack contact management application built with Java (Spring Boot) and React.

## Tech Stack

- **Backend:** Java, Spring Boot, Maven
- **Frontend:** React, Vite

## Project Structure

```
.
├── backend/     # Spring Boot REST API
├── frontend/    # React (Vite) application
└── README.md
```

## Prerequisites

- JDK 17 or higher
- Maven 3.8+
- Node.js 18+ and npm

## Getting Started

### Backend

```bash
cd backend
mvn spring-boot:run
```

The API runs on `http://localhost:8080` by default.

Database settings are in `backend/src/main/resources/application.properties`.

### Frontend

```bash
cd frontend
npm install
npm run dev
```

The app runs on `http://localhost:5173` by default.

## Running Tests

```bash
cd backend
mvn test
```

## Author

Muhammad Haris
