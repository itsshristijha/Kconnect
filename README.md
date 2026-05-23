# kconnect 🚀

kconnect is a full-stack Question and Answer (Q&A) web application built using the MERN stack (MongoDB, Express.js, React, Node.js). It provides a community platform where users can post questions, share answers, and engage in knowledge exchange.

## 📌 Features
- **Ask Questions:** Users can post questions along with optional reference URLs.
- **Answer Questions:** Provide detailed answers linked specifically to individual questions.
- **State Management:** Integrated with Redux Toolkit (`@reduxjs/toolkit` & `react-redux`) for efficient global state handling.
- **Full-Stack Routing:** Managed via Express on the backend and React Router on the frontend.
- **Production-Ready Deployment:** Serves static optimized React production builds directly via the Node server.

---

## 🛠️ Tech Stack

**Frontend:**
- React.js (Bootstrapped with Create React App)
- Redux Toolkit (State Management)
- Axios (API Client)

**Backend:**
- Node.js & Express.js (Server framework)
- MongoDB & Mongoose (Database & ODM modeling)
- Body-Parser & Cors (Middleware)

---

## 📂 Repository Structure Overview
```text
kconnect/
├── backend/                  # Backend application logic
│   ├── server.js             # Main server entry point
│   ├── db.js                 # Database connection config
│   ├── routes.js             # API route handlers
│   └── models/               # Mongoose Schemas (Question, Answer, etc.)
├── frontend/                 # Frontend React application
│   ├── src/                  
│   └── build/                # Production build directory (generated)
├── uploads/                  # Local storage for user uploads/media
├── package.json              # Main project configuration & scripts
└── README.md                 # Project documentation
