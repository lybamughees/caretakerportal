# 🧑‍⚕️ Caretaker Portal

The **Caretaker Portal** is a full-stack web application that serves as the backend management system for a smart care and monitoring solution. It allows caretakers and administrators to manage users, tasks, and care-related data through a secure web interface.

This portal is designed to function independently as a web app, while also acting as the **backend service** for a connected Smart Mirror interface (MagicMirror project).

---

## 📌 Purpose

The Caretaker Portal centralizes care management by providing:

* Secure access for caretakers and administrators
* Structured data management for care tasks and schedules
* A backend API layer that external interfaces (e.g., Smart Mirror UI) can consume

---

## ✨ Features

* User authentication and session handling
* Role-based access control (caretaker / admin logic)
* Server-rendered views using Handlebars
* RESTful routing with Express
* Modular database models
* Utility helpers and shared methods
* Integration-ready API endpoints
* Integration and mock testing support

---

## 🔗 Project Context

This repository represents the **backend and management portal** portion of a larger system.

* **Caretaker Portal (this repo):**
  Handles authentication, data storage, and caretaker workflows.

* **Smart Mirror Interface (separate repo):**
  Consumes backend data to display reminders, schedules, and care information.

➡️ Related project:
[https://github.com/lybamughees/magicmirror](https://github.com/lybamughees/magicmirror)

---

## 🧱 Tech Stack

**Backend**

* Node.js
* Express.js

**Frontend**

* Handlebars (HBS)
* HTML5
* CSS3
* Vanilla JavaScript

**Database**

* Environment-configured database connection

**Tooling**

* npm
* Integration testing framework
* Environment variable support

---

## 📁 Project Structure

```text
caretakerportal/
├── mock/                 # Mock data for testing
├── models/               # Database models
├── public/               # Static assets (CSS, JS)
├── tests/
│   └── integration/      # Integration tests
├── views/                # Handlebars templates
├── app.js                # Express app configuration
├── auth.js               # Authentication logic
├── constants.js          # App constants
├── database.js           # Database connection
├── methods.js            # Shared helper functions
├── server.js             # App entry point
├── utils.js              # Utility helpers
├── package.json
└── README.md
```

---

## ⚙️ Installation & Setup

### Prerequisites

* Node.js (v16+ recommended)
* npm

---

### Clone the Repository

```bash
git clone https://github.com/lybamughees/caretakerportal.git
cd caretakerportal
```

---

### Install Dependencies

```bash
npm install
```

---

### Environment Configuration

Create a `.env` file in the project root:

```env
PORT=3000
DB_HOST=localhost
DB_USER=your_user
DB_PASSWORD=your_password
DB_NAME=caretaker_portal
SESSION_SECRET=your_secret
```

---

### Run the Application

```bash
npm start
```

The app will run at:

```
http://localhost:3000
```

---

## 🧪 Running Tests

```bash
npm test
```

---

## 🔐 Authentication

* Server-side session-based authentication
* Protected routes for authenticated users
* Centralized authentication logic for reuse across routes

---

## 📈 Future Improvements

* Care task analytics dashboard
* Medication adherence tracking
* Notification and reminder system
* Expanded API documentation
* UI/UX enhancements

---

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch

   ```bash
   git checkout -b feature/your-feature
   ```
3. Commit changes

   ```bash
   git commit -m "Add feature"
   ```
4. Push to branch

   ```bash
   git push origin feature/your-feature
   ```
5. Open a Pull Request

---

## ⭐ Notes

This project was built to demonstrate backend architecture, authentication workflows, and full-stack integration with external interfaces.


