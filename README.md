# 🏥 Caretaker Portal

A full-stack web application designed to support caretakers in managing clients, tasks, and daily responsibilities through a centralized portal.

This project demonstrates backend development, authentication flows, database integration, and server-rendered UI using Node.js and Express.

---

## ✨ Overview

The **Caretaker Portal** provides a structured system for caretakers to log in, manage assigned responsibilities, and interact with stored data through a clean and functional web interface. It is built with scalability and maintainability in mind and follows a modular backend architecture.

This repository serves both as a functional application and as a demonstration of full-stack development skills.

---

## 🚀 Features

* User authentication and session management
* Role-based access control (caretaker / admin logic ready)
* RESTful routing with Express
* Server-side rendering with Handlebars
* Database abstraction and models
* Modular utility and helper functions
* Integration tests for core functionality

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

* Configurable via environment variables
* Abstracted database layer

**Tooling & Testing**

* npm
* Integration testing framework
* Environment variable configuration

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
├── constants.js          # Application constants
├── database.js           # Database connection logic
├── methods.js            # Shared helper methods
├── server.js             # Application entry point
├── utils.js              # Utility functions
├── package.json
└── README.md
```

---

## ⚙️ Installation & Setup

### Prerequisites

Make sure you have the following installed:

* **Node.js** (v16 or higher recommended)
* **npm**

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

Create a `.env` file in the root directory:

```bash
cp .env.example .env
```

Then update the values inside `.env` with your database credentials and configuration details.

Example:

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

The application will be available at:

```
http://localhost:3000
```

---

## 🧪 Running Tests

To run integration tests:

```bash
npm test
```

---

## 🔐 Authentication Flow

* Users authenticate via server-side sessions
* Session middleware protects restricted routes
* Authentication logic is centralized for reuse and clarity

---

## 📈 Future Enhancements

* Dashboard analytics for caretakers
* Client progress tracking
* Notifications and reminders
* Enhanced role management
* API documentation
* UI/UX refinements

---

## 🤝 Contributing

Contributions are welcome!

1. Fork the repository
2. Create a new branch

   ```bash
   git checkout -b feature/your-feature
   ```
3. Commit your changes

   ```bash
   git commit -m "Add new feature"
   ```
4. Push to your branch

   ```bash
   git push origin feature/your-feature
   ```
5. Open a Pull Request

