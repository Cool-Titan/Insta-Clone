# 📸 InstaClone - MERN Stack Instagram-Style App

*InstaClone* is a fully functional, responsive **Instagram-style web application** built with the **MERN Stack** (MongoDB, Express.js, React.js, Node.js). It supports user authentication, image sharing, likes, comments, profile management, and seamless image uploads powered by Cloudinary.

---

## 🌐 Live Demo

🚀 [*Visit the Live Website*](https://insta-clone-95zl.onrender.com/)

---

## 📸 Preview

*Screenshots :*
![Landing Page of Site](landing.png)

---

![New Post](post.png)

---

![Profile page](profile.png)

---

## 📚 Features

### 👤 1. User Authentication
- Secure *sign-up* and *log-in* functionality.
- Passwords hashed using *bcrypt* for security.
- Authenticated sessions managed with *JWT tokens* stored in localStorage.

> 🔐 **Tech**: JWT, bcrypt, MongoDB

### 🖼 2. Image Upload & Posting
- Upload posts with captions and images.
- Images stored and managed via *Cloudinary* API.
- Posts displayed in the global feed and user profile.

> 🔧 **Tech**: React Forms, Cloudinary, MongoDB, Express API

### ❤ 3. Likes & Comments
- Authenticated users can *like* or *unlike* posts.
- Add and view *comments* on posts.
- Real-time UI updates without page refresh.

### 🙍‍♂ 4. User Profile
- View your posts, bio, and profile picture.
- Explore other users' public profiles.
- Edit profile details and upload profile images via Cloudinary.

---

## 🛠 Tech Stack

| Module            | Technologies                                      |
|-------------------|--------------------------------------------------|
| **Frontend**      | React.js, Axios, React Router, CSS Modules/Tailwind CSS |
| **Backend**       | Node.js, Express.js                              |
| **Database**      | MongoDB Atlas, Mongoose                          |
| **Authentication** | JWT, bcrypt                                      |
| **Image Upload**  | Cloudinary API                                   |

---

## ⚙ Setup & Installation

### 📝 Prerequisites
- [Node.js](https://nodejs.org/) (v16 or higher)
- [MongoDB Atlas](https://www.mongodb.com/cloud/atlas) account
- [Cloudinary](https://cloudinary.com/) account
- [Git](https://git-scm.com/)

### 📁 Clone the Repository
```bash
git clone https://github.com/Cool-Titan/Insta-Clone.git
cd Insta-Clone
```

### 🛠 Backend Setup
1. Navigate to the backend directory:
   ```bash
   cd backend
   ```
2. Install dependencies:
   ```bash
   npm install
   ```
3. Create a `.env` file in the `backend` directory and add:
   ```env
   MONGO_URI=your_mongodb_atlas_connection_string
   JWT_SECRET=your_jwt_secret_key
   CLOUDINARY_CLOUD_NAME=your_cloudinary_cloud_name
   CLOUDINARY_API_KEY=your_cloudinary_api_key
   CLOUDINARY_API_SECRET=your_cloudinary_api_secret
   ```
4. Start the backend server:
   ```bash
   npm start
   ```

### 🌐 Frontend Setup
1. Navigate to the frontend directory:
   ```bash
   cd frontend
   ```
2. Install dependencies:
   ```bash
   npm install
   ```
3. Create a `.env` file in the `frontend` directory and add:
   ```env
   REACT_APP_API_URL=http://localhost:5000/api
   ```
4. Start the frontend development server:
   ```bash
   npm start
   ```

### 🚀 Running the Application
- Ensure MongoDB Atlas and Cloudinary are configured.
- Run both backend and frontend servers.
- Open `http://localhost:3000` in your browser to view the app.

---

## 📂 Project Structure

```
Insta-Clone/
├── backend/                # Node.js + Express.js server
│   ├── models/             # Mongoose schemas
│   ├── routes/             # API routes
│   ├── controllers/        # Request handlers
│   ├── middleware/         # Authentication & error handling
│   └── .env                # Environment variables
├── frontend/               # React.js frontend
│   ├── src/                # React components, pages, and assets
│   ├── public/             # Static assets
│   └── .env                # Frontend environment variables
├── README.md               # Project documentation
└── package.json            # Project metadata and scripts
```

---

