# 🚀 ProjectHub_NeverLooseTrack

A full-stack **Student Project Management & Discovery Platform** built to help students showcase their work professionally and help educators track innovation effortlessly.

---

## 📌 Overview

ProjectHub is designed to solve the chaotic mess of scattered student projects. It gives students a polished space to publish their work, and gives teachers a structured way to view, evaluate, and follow progress.

This repo contains the full codebase for the platform, including backend, frontend, and database layer.

---

## 🔧 Tech Stack

- **Backend:** Node.js, Express
- **Database:** MySQL
- **Frontend:** HTML, CSS, JavaScript

---

## ✨ Core Features

### 🔨 Project Creation & Management
- Create, update, and delete projects
- Add detailed descriptions, media, and tech stacks
- Privacy options: Public, Private, Organization-Only

### 🔍 Project Discovery
- Search by project title, tags, tools, or author
- Advanced filtering for organizations, categories, and visibility levels

### 🔐 User System
- Secure login & registration
- Profile pages with project portfolio
- Role-based access (Student / Educator)

### 🔔 Real-time Notifications
- Alerts for project updates, interactions, and organization activity

### 🏫 Organization-Based Sharing
- Students can publish projects specifically for their institute or department

---

## 📘 What I Learned

Building this platform taught me:
- Full-stack architecture and deployment workflows
- Clean API design and REST principles
- Secure authentication & database schema planning
- UX decisions for large-scale content platforms
- Handling real-time updates across a full-stack system

---

## 📁 Project Structure

```
ProjectHub_NeverLooseTrack/
│
├── backend/
│   ├── server.js
│   ├── routes/
│   ├── controllers/
│   ├── models/
│   ├── middleware/
│   │   └── auth.js
│   ├── utils/
│   │   └── validators.js
│   ├── config/
│   │   ├── db.js
│   │   └── authConfig.js
│   └── database/
│       ├── schema.sql
│       └── sample_data.sql
│
├── frontend/
│   ├── index.html
│   ├── css/
│   ├── js/
│   └── assets/
│       ├── images/
│       └── icons/
│
└── README.md
```

---

## 🚀 Getting Started

### 1️⃣ Clone the repo
```bash
git clone https://github.com/pillowarian/ProjectHub_NeverLooseTrack.git
cd ProjectHub_NeverLooseTrack
```

### 2️⃣ Install backend dependencies
```bash
cd backend
npm install
```

### 3️⃣ Configure the database
- Create a MySQL database
- Import the provided SQL schema from `backend/database/schema.sql`
- Add your DB credentials to the backend config

### 4️⃣ Start the server
```bash
npm run dev
```

### 5️⃣ Launch the frontend
Open `frontend/index.html` in your browser or serve it using a local development server.

---

## 🤝 Contributing

Feel free to open issues, suggest new features, or submit PRs. Contributions are always welcome!

---

## 💬 Feedback

Got ideas to improve ProjectHub? Open an issue or drop feedback — always appreciated.

---

## 👥 Collaborators

- **pillowarian** — MD Hasin Anjum
- **@sukhen2021331024** — Sukhen Dhar
- **@Sayeed-1207** — Sayeed Hassan

---

## 📄 License

MIT License. Use it however you want.
