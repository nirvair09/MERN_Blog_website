
# 📰 Blog App — Full-Stack MERN Blogging Platform

### 🚀 Live Demo → [mern-blog-website-cfr7.onrender.com](https://mern-blog-website-cfr7.onrender.com)

---

## 📖 Overview

**Blog App** is a full-stack **MERN** (MongoDB, Express, React, Node.js) blogging platform that allows users to **create, edit, publish, and interact with blogs** in real time.
It includes a full authentication system, image uploads via **Cloudinary**, Redux-powered state management, interactive comments, user profiles with stats, and a beautiful, responsive interface.

This project demonstrates strong command over **frontend architecture, backend API design, authentication flow, and production deployment** — everything a scalable web application requires.

---

## 💡 Motivation

This project began as a simple blog CRUD app and evolved into a **complete publishing system** with dashboards, profiles, and live user interactions.
The goal was to master the **MERN stack end-to-end**, implementing clean RESTful APIs, secure authentication, reusable components, and professional-grade deployment — just like a real production web app.

---

## ⚙️ Features

### 🧠 Core Functionality

* **User Authentication:** Register, login, logout using JWT tokens (secure cookies).
* **Blog Management:** Create, update, delete, and toggle publish/unpublish blogs.
* **Image Uploads:** Integrated with **Cloudinary** for storing blog thumbnails and profile pictures.
* **Dynamic Dashboard:** Personalized dashboard for every user showing total blogs, comments, likes, and views.
* **Profile Page:** Displays user information, total engagement stats, and recent activity.

### 💬 Social & Interactive Features

* **Comments System:** Add, edit, delete, and like/unlike comments on any blog.
* **Live Comment Updates:** UI updates dynamically on like/edit/delete actions.
* **Like System:** Track number of likes for blogs and comments.
* **Popular Authors Section:** Displays top authors fetched from the backend.
* **Recent Blogs Section:** Highlights the latest published blogs on the home page.
* **Newsletter Subscription Section:** Email subscription input (frontend feature).

### 🎨 UI / UX

* Responsive layout for mobile, tablet, and desktop.
* Reusable `BlockCard` and `BlogCardList` components with hover effects.
* Clean modern design with Chakra UI, Tailwind CSS utility classes, and Lucid React icons.
* Light/Dark mode styling for improved readability.

### 🛠️ Backend & DevOps

* RESTful APIs using **Express.js** and **MongoDB** (via Mongoose ODM).
* Secure authentication middleware.
* Environment variables for API keys and database credentials.
* Static frontend served from backend using Express in production.
* Deployed live on **Render** with auto-build configuration and environment variable setup.

---

## 🧩 Tech Stack

**Frontend:**
React.js, Redux Toolkit, React Router DOM, Axios, Chakra UI, Tailwind CSS, Lucid React Icons

**Backend:**
Node.js, Express.js, MongoDB, Mongoose, JWT, bcrypt.js, Cloudinary SDK

**Tools & Services:**
Postman (API testing), GitHub (version control), Render (deployment), VS Code (development)

---

## 📁 Folder Structure

```
project-root/
│
├── backend/
│   ├── controllers/
│   ├── models/
│   ├── routes/
│   ├── middleware/
│   ├── config/
│   ├── server.js
│   └── .env
│
├── frontend/
│   ├── src/
│   │   ├── components/
│   │   ├── pages/
│   │   ├── redux/
│   │   ├── utils/
│   │   ├── App.jsx
│   │   └── main.jsx
│   └── package.json
│
├── package.json
└── README.md
```

---

## ⚙️ Installation & Setup

### 1. Clone Repository

```bash
git clone https://github.com/<your-username>/mern-blog-website.git
cd mern-blog-website
```

### 2. Setup Backend

```bash
cd backend
npm install
```

Create a `.env` file with the following keys:

```
MONGO_URI=<your-mongodb-uri>
JWT_SECRET=<your-jwt-secret>
CLOUDINARY_CLOUD_NAME=<cloud-name>
CLOUDINARY_API_KEY=<api-key>
CLOUDINARY_API_SECRET=<api-secret>
```

Start the backend server:

```bash
npm run dev
```

### 3. Setup Frontend

```bash
cd ../frontend
npm install
npm run dev
```

Frontend runs on **[http://localhost:5173](http://localhost:5173)**, backend on **[http://localhost:5000](http://localhost:5000)** (or configured port).

---

## 🌟 Key Components Developed

| Component                      | Description                                                      |
| ------------------------------ | ---------------------------------------------------------------- |
| **Blogs Page**                 | Displays all published blogs using responsive grid and API data. |
| **BlockCard Component**        | Blog card showing thumbnail, category, date, and read-more link. |
| **RecentBlogs / BlogCardList** | Highlights recent posts on Home page.                            |
| **Categories Section**         | Blog categories with Chakra UI badges.                           |
| **PopularAuthors**             | Fetches top 3 authors with avatars and names.                    |
| **Comments System**            | Full CRUD + like/unlike functionality for comments.              |
| **Profile Stats**              | Displays total blogs, likes, views, and comments per user.       |
| **Comments Dashboard**         | Lists all user comments with quick navigation.                   |
| **Backend Controllers**        | Modular CRUD controllers for blogs, comments, and users.         |
| **Deployment Setup**           | Static frontend served via Express backend; hosted on Render.    |

---

## 🧠 Learning Outcomes

* Gained deep understanding of **MERN stack architecture**.
* Implemented **secure JWT-based authentication** with cookies.
* Practiced **Redux state synchronization** with backend APIs.
* Learned **file handling with Cloudinary**.
* Applied **responsive, component-driven design** with Chakra and Tailwind.
* Mastered **deployment and environment configuration** on Render.

---

## 🚧 Future Improvements

* Implement full **search and filter functionality** for blogs.
* Add **pagination and infinite scrolling** for blog feed.
* Enable **user-to-user following** and personalized feed.
* Integrate **email notifications** for comments and likes.
* Optimize backend queries for performance at scale.

---

## 👨‍💻 Author

**Rup**
Final-Year B.Tech Student @ IIT Patna
Aiming for Software Developer roles | Passionate about Full-Stack Development
🔗 [LinkedIn Profile](https://www.linkedin.com/in/)

---

## 🏁 Conclusion

This project is a complete demonstration of building, securing, and deploying a modern **full-stack web application** from scratch.
Every feature — from authentication to live comments — is built with production principles in mind.
It’s a showcase of solid MERN fundamentals, clean architecture, and practical, hands-on development skills.
