A secure and scalable authentication backend built using Node.js, Express, MongoDB, and JSON Web Tokens (JWT).
This project demonstrates real-world backend concepts such as password hashing, stateless authentication, protected routes, and clean project architecture.
</br>
auth-backend/
├── src/
│   ├── config/
│   │   └── db.js
│   │
│   ├── models/
│   │   └── user.model.js
│   │
│   ├── routes/
│   │   └── auth.routes.js
│   │
│   ├── middleware/
│   │   └── auth.middleware.js
│   │
│   ├── app.js
│   └── server.js
│
├── .env
├── package.json
└── README.md
</br>
Project Overview

This backend provides core authentication functionality required by most modern web applications:

User Registration (Signup)

User Authentication (Login)

Password Hashing

JWT Token Generation

Protected Routes using Middleware

Secure Environment Configuration

Clean & Modular Backend Structure

The project is designed to be easy to understand, secure, and extendable.
