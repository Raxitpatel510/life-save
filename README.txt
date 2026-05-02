LifeSave - Blood & Organ Donation Management System

This is a complete full-stack web application.

Technologies Used:
- Frontend: HTML, CSS, JavaScript
- Backend: Node.js, Express.js
- Database: MySQL

Project Structure:
LifeSave-Working-FullStack-Project/
│
├── frontend/
│   ├── index.html
│   ├── styles.css
│   └── script.js
│
├── backend/
│   ├── config/db.js
│   ├── controllers/
│   ├── routes/
│   ├── server.js
│   ├── database.sql
│   ├── package.json
│   └── package-lock.json
│
└── README.txt

Setup Instructions:

1. Import Database
   - Open phpMyAdmin
   - Create database: lifesave_db
   - Import backend/database.sql

2. Install Dependencies
   cd backend
   npm install

3. Run Backend
   npm run dev

4. Run Frontend
   Open frontend/index.html using Live Server.

Backend URL:
http://localhost:5000
