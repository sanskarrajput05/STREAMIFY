

# 🎵 Streamify - MUSIC IS THERAPY

[![React](https://img.shields.io/badge/Frontend-React.js-61DBFB?logo=react\&logoColor=white)](https://reactjs.org/)
[![Node.js](https://img.shields.io/badge/Backend-Node.js-43853D?logo=node.js\&logoColor=white)](https://nodejs.org/)
[![Express.js](https://img.shields.io/badge/Framework-Express.js-000000?logo=express\&logoColor=white)](https://expressjs.com/)
[![MongoDB](https://img.shields.io/badge/Database-MongoDB-4EA94B?logo=mongodb\&logoColor=white)](https://www.mongodb.com/)
[![Clerk](https://img.shields.io/badge/Auth-Clerk-blue?logo=clerk\&logoColor=white)](https://clerk.com/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)

Streamify is a **full-stack real-time music streaming web application** inspired by Spotify.
It comes with **music playback, playlist management, real-time updates, analytics, and an admin dashboard**.

---

## 🎬 Demo

🚀 **Live Demo:** [Streamify on Render](https://streamify-pjgx.onrender.com/)

---

## 🚀 Features

* 🔐 **Authentication** – Secure login & signup with **Clerk**
* 🎶 **Music Streaming** – Play, pause, skip, shuffle, next/previous
* 📂 **Playlist Management** – Create, edit & delete playlists
* 🎧 **Admin Dashboard** – Manage albums & songs
* 🔍 **Search & Explore** – Find songs, albums, and artists easily
* 💬 **Real-Time Chat** – Chat with other users inside the app
* 👀 **Live User Status** – See who’s online & what they’re listening to
* 📡 **Realtime Updates** – Sync queues, playlists & playback across devices
* 📊 **Analytics Dashboard** – Track listening habits and trends
* 📱 **Responsive UI** – Works seamlessly on desktop & mobile

---

## 🛠 Tech Stack

**Frontend:**

* React.js (Hooks, Context API)
* Tailwind CSS + ShadCN UI
* TypeScript
* Clerk (Authentication)

**Backend:**

* Node.js
* Express.js
* REST APIs
* Cloudinary (media storage)

**Database:**

* MongoDB (user data, songs, playlists)

---

## 📂 Project Structure

```
streamify/
│── client/         # React.js frontend
│── server/         # Node.js + Express.js backend
│── database/       # Database models & config
│── package.json    # Project metadata
│── README.md       # Documentation
```

---

## ⚡ Installation & Setup

1. **Clone the repository**

```bash
git clone https://github.com/yourusername/streamify.git
cd streamify
```

2. **Install dependencies**

```bash
# Frontend
cd client
npm install

# Backend
cd ../server
npm install
```

3. **Setup Environment Variables**

### Backend `.env`

```bash
PORT=5000
MONGODB_URI=your_mongodb_connection_string
ADMIN_EMAIL=your_admin_email
NODE_ENV=development

CLOUDINARY_API_KEY=your_cloudinary_key
CLOUDINARY_API_SECRET=your_cloudinary_secret
CLOUDINARY_CLOUD_NAME=your_cloudinary_name

CLERK_PUBLISHABLE_KEY=your_clerk_publishable_key
CLERK_SECRET_KEY=your_clerk_secret_key
```

### Frontend `.env`

```bash
VITE_CLERK_PUBLISHABLE_KEY=your_clerk_publishable_key
```

4. **Run the application**

```bash
# Backend
cd server
npm start

# Frontend
cd ../client
npm start
```

---

## 📸 Screenshots


![streamify (1)](https://github.com/user-attachments/assets/c0e6f332-861b-436d-866c-9de2a4f830ae)
<img width="1919" height="971" alt="image" src="https://github.com/user-attachments/assets/a66baca8-672e-48bd-bb58-e9ae8ea9a7e6" />
<img width="1919" height="970" alt="image" src="https://github.com/user-attachments/assets/7242250f-7b94-40f7-98bd-965810d6409c" />
<img width="1915" height="962" alt="image" src="https://github.com/user-attachments/assets/78ac5cb4-e351-4fde-99b4-71d8e1786325" />

---

## 📌 Future Enhancements

* 🎧 Spotify API integration for real music
* 🤖 AI-based recommendations
* 📊 Advanced analytics with dashboards
* 🫂 Collaborative playlists
* 📱 Mobile app version

---

## 🤝 Contributing

Contributions are welcome! Fork the repo & create a PR 🚀

---

## 📜 License

This project is licensed under the **MIT License**.

---

## 👨‍💻 Author

**Sanskar Rajpoot**

* [LinkedIn](https://www.linkedin.com/in/sanskarrajput05)
* [Email](mailto:sanskarrajput7880@gmail.com)

---

👉 This version combines your **professional project showcase** with your **course-style features** while keeping it elegant for recruiters, GitHub, and contributors.
