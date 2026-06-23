# 🚀 Threadly – A Social Media Platform

Threadly is a modern full-stack social media application built using the MERN Stack. Users can create posts, upload images, like posts, comment on posts, manage profiles, and enjoy a responsive user experience with dark mode support.

## 🌐 Live Demo

### Frontend

https://threadly-a-social-app.vercel.app/

### Backend API

https://threadly-a-social-app.onrender.com

---

## ✨ Features

### 🔐 Authentication

* User Signup & Login
* JWT Authentication
* Protected Routes
* Persistent Login Sessions

### 👤 User Profile

* Profile Page
* Profile Avatar Upload
* User Posts Display
* Post Statistics

### 📝 Posts

* Create Text Posts
* Upload Images with Posts
* Delete Own Posts
* View All Posts Feed

### ❤️ Engagement

* Like / Unlike Posts
* Add Comments
* Real-time Feed Refresh

### 🎨 UI Features

* Responsive Design
* Dark Mode Toggle
* Modern Bootstrap UI
* Toast Notifications

### ☁️ Cloud Storage

* Cloudinary Image Uploads
* Profile Avatar Storage
* Post Image Storage

---

## 🛠️ Tech Stack

### Frontend

* React.js
* React Router DOM
* Axios
* Bootstrap 5
* React Toastify
* Date-fns

### Backend

* Node.js
* Express.js
* MongoDB
* Mongoose
* JWT Authentication
* Bcrypt.js
* Multer
* Cloudinary

### Deployment

* Frontend: Vercel
* Backend: Render
* Database: MongoDB Atlas

---

## 📂 Project Structure

```bash
Threadly/
│
├── frontend/
│   ├── src/
│   │   ├── components/
│   │   ├── pages/
│   │   ├── context/
│   │   ├── services/
│   │   └── App.jsx
│   │
│   └── package.json
│
├── backend/
│   ├── config/
│   ├── controllers/
│   ├── middleware/
│   ├── models/
│   ├── routes/
│   ├── server.js
│   └── package.json
│
└── README.md
```

## ⚙️ Installation

### Clone Repository

```bash
git clone https://github.com/shivamvermajss/Threadly---A-Social-App-.git
cd Threadly---A-Social-App-
```

### Backend Setup

```bash
cd backend
npm install
```

Create a `.env` file:

```env
PORT=5000

MONGO_URI=your_mongodb_connection_string

JWT_SECRET=your_secret_key

CLOUDINARY_CLOUD_NAME=your_cloud_name

CLOUDINARY_API_KEY=your_api_key

CLOUDINARY_API_SECRET=your_api_secret
```

Run Backend:

```bash
npm start
```

### Frontend Setup

```bash
cd frontend
npm install
```

Create a `.env` file:

```env
VITE_API_URL=http://localhost:5000/api
```

Run Frontend:

```bash
npm run dev
```

---

## 📡 API Endpoints

### Authentication

```http
POST /api/auth/signup
POST /api/auth/login
```

### Posts

```http
GET    /api/posts
POST   /api/posts
DELETE /api/posts/:id
POST   /api/posts/:id/like
POST   /api/posts/:id/comment
```

### Users

```http
GET /api/users/:username
```

---

## 📸 Screenshots

### Login Page

* Secure JWT Authentication

### Feed Page

* Create Posts
* Like Posts
* Comment on Posts
* Delete Posts

### Profile Page

* User Information
* User Posts
* Profile Avatar

### Dark Mode

* Light/Dark Theme Toggle

---

## 🚀 Deployment

### Frontend

Deployed on Vercel

https://threadly-a-social-app.vercel.app/

### Backend

Deployed on Render

https://threadly-a-social-app.onrender.com

---

## 🔮 Future Improvements

* Follow / Unfollow Users
* Real-Time Chat
* Notifications System
* Bookmark Posts
* Story Feature
* User Search
* Friend Requests
* Real-Time Updates using Socket.io

---

## 👨‍💻 Author

### Shivam Verma

**Full Stack Developer | MERN Stack Developer**

GitHub:
https://github.com/shivamvermajss

LinkedIn:
https://www.linkedin.com/in/shivam-verma-227b37384/

---

## ⭐ Support

If you like this project, please give it a ⭐ on GitHub and share your feedback.
