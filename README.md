# 🧠 Task Manager

The *Task Manager* is a web application designed to streamline team task management. Built using the *MERN stack (MongoDB, Express.js, React, and Node.js)*, the platform provides a user-friendly interface for efficient task assignment, tracking, and collaboration. It serves both administrators and regular users, offering tools that enhance productivity and organization.

---

## ❓ Why / Problem

In modern work environments, traditional task tracking via spreadsheets or manual systems is often inefficient and error-prone. *Task Manager* solves this by centralizing task operations and boosting collaboration through a responsive web interface.

---

## 📜 Background

With the rise of *remote work* and *dispersed teams, effective communication and task coordination have become essential. This app leverages the MERN stack and modern frontend tools like **Redux Toolkit, **Headless UI, and **Tailwind CSS* to deliver a seamless task management experience.

---

## 👑 Admin Features

- *User Management*
  - Create admin accounts
  - Add/manage team members

- *Task Assignment*
  - Assign tasks to individual or multiple users
  - Edit task details and status

- *Task Properties*
  - Status labels: To Do / In Progress / Completed
  - Priority levels: High / Medium / Normal / Low
  - Manage sub-tasks

- *Asset Management*
  - Upload task assets (e.g., images)

- *Account Control*
  - Activate/Deactivate user accounts
  - Trash or permanently delete tasks

---

## 👤 User Features

- *Task Interaction*
  - Update task status
  - View detailed task information

- *Communication*
  - Comment/chat on tasks

---

## 🌐 General Features

- *Authentication*
  - Secure login
  - Role-based access control

- *Profile Management*
  - Update profile, change password

- *Dashboard*
  - Activity summary
  - Filter tasks by status

---

## 🧰 Technologies Used

### Frontend
- React (Vite)
- Redux Toolkit
- Headless UI
- Tailwind CSS

### Backend
- Node.js
- Express.js

### Database
- MongoDB (via MongoDB Atlas)

---

## ⚙ Setup Instructions

### 🔒 Server Setup

Create .env file in /server:

env
MONGODB_URI=your_mongodb_url
JWT_SECRET=your_jwt_secret
PORT=8800
NODE_ENV=development


*Run the server:*

bash
cd server
npm install
npm start


---

### 🛢 MongoDB Setup

1. Visit: [MongoDB Atlas](https://www.mongodb.com/cloud/atlas)
2. Create an account
3. Create a cluster and a database user
4. Whitelist your IP
5. Connect to the cluster and copy the connection string into .env

---

### 🌐 Client Setup

Create .env file in /client:

env
VITE_APP_BASE_URL=http://localhost:8800
VITE_APP_CLOUDINARY_URL=https://api.cloudinary.com/v1_1/{your_name}/image/upload
VITE_APP_UPLOAD_PRESET=mycloud
VITE_APP_NAME=Cloudinary Name


*Run the client:*

bash
cd client
npm install
npm start


Open [http://localhost:3000](http://localhost:3000) to view the app.

