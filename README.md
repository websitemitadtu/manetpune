# 🚢 MANET Website Migration

This project is a migration of the original MANET (Maharashtra Academy of Naval Education & Training) website to a modern full-stack web application using **React.js** for the frontend and **Node.js with Express** for the backend.

---

## 📁 Tech Stack

- **Frontend:** React.js, HTML5, CSS3, Bootstrap
- **Backend:** Node.js, Express.js
- **Database:** MongoDB / MySQL 
- **Other Tools:** Git, Postman, VS Code, Nodemon

---

## 📂 Project Folder Structure

manet/
│
├── client/ # React Frontend
│ ├── public/ # Static files (index.html, favicon, etc.)
│ └── src/ # Source files
│ ├── assets/ # Images, fonts, etc.
│ ├── components/ # Reusable UI components
│ ├── pages/ # Route-specific pages (Home, About, etc.)
│ ├── App.js # Main App component
│ ├── index.js # ReactDOM rendering entry
│ └── styles/ # Global or modular styles
│
├── server/ # Node.js Backend
│ ├── config/ # DB connection, environment config
│ ├── controllers/ # Route logic/controllers
│ ├── models/ # Mongoose or Sequelize models
│ ├── routes/ # Express route definitions
│ ├── middleware/ # Middleware (if any)
│ └── server.js # Entry point for backend
│
├── .env # Environment variables
├── .gitignore # Files to ignore in Git
├── package.json # Root package (can also split into client/server)
└── README.md # Project documentation

## Backend setup

cd Backend
npm install
npm run dev


## Frontend setup

cd client
npm install
npm start

## 🛠 Features
Modular and reusable React components

Responsive UI using Bootstrap

Clean RESTful APIs

Secure .env configuration for server credentials

Organized MVC pattern for backend


## 📧 Contact
For any queries or collaboration:

Email: info@manetpune.edu.in
Website: www.manetpune.edu.in

## ©️ License
This project is licensed under the MIT License.

