## 📌 Overview

This project is a basic backend server built using **Node.js and Express.js**.  
It demonstrates how to set up a REST API project, manage dependencies, run a development server, and test endpoints using Postman.

---

## 🛠️ Tech Stack

- Node.js
- Express.js
- CORS
- Nodemon
- PNPM
- Postman (for testing)

---

## ⚙️ Installation & Setup

### 1. Install PNPM (if not installed)

```bash
npm install -g pnpm

pnpm add express cors
pnpm add -D nodemon


{
  "type": "module",
  "scripts": {
    "start": "node index.js",
    "dev": "nodemon index.js"
  }
}

node_modules/
.env
*.log
dist/

project-root/
│
├── controllers/    → Request handling logic
├── models/         → Data structures / schemas
├── routes/         → API route definitions
├── services/       → Business logic
│
├── index.js        → Entry point of server
├── package.json
├── pnpm-lock.yaml
└── .gitignore
