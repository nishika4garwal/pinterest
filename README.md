# 🎀 Pinterest Clone

A full-stack Pinterest-style image sharing app built with the MERN stack (MongoDB, Express, React, Node.js). Users can register, log in, upload pins, save pins follow/unfollow other users, and manage their profiles — all with smooth, responsive UI and dynamic updates.

---

## 🚀 Features

- 🔐 **Authentication**: Register, Login, Logout (with JWT & cookies)
- 🖼️ **Pins**: Create, view, save, and display posts using a masonry grid
- 👥 **Social Features**:
  - Follow/unfollow other users
  - View followers and following in a modal popover
  - Remove followers or unfollow users dynamically
- 👤 **Account/Profile Pages**:
  - View your own pins
  - Save pins
  - Check followers/following count
- 📦 **Reusable Components**: Toasts, Loaders, Modals, Protected Routes
- 💅 **Responsive UI**: Tailwind CSS, React Icons, Masonry layout

---

## 🧑‍💻 Tech Stack

### Frontend
- React
- React Router DOM
- Axios
- Tailwind CSS
- react-hot-toast
- react-icons
- react-masonry-css

### Backend
- Node.js
- Express
- MongoDB + Mongoose
- JSON Web Tokens (JWT)
- bcrypt (for password hashing)
- cookie-parser

---

## 📂 Folder Structure

```

pinterest-clone/
├── backend/
│   ├── controllers/
│   ├── models/
│   ├── routes/
│   ├── middleware/
│   ├── utils/
│   └── index.js
├── frontend/
│   ├── pages/
│   ├── components/
│   ├── context/
│   ├── assets/
│   └── App.jsx

````

---

## 🛠️ Getting Started

### Prerequisites
- Node.js and npm
- MongoDB (local or cloud)

### 1. Clone the repo

```bash
git clone https://https://github.com/nishika4garwal/pinterest.git
cd pinterest
````

### 2. Install dependencies

```bash
# Backend
cd backend
npm install

# Frontend
cd ../frontend
npm install
```

### 3. Setup environment variables

Create a `.env` file in root directory:

```
PORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret_key
```

### 4. Run the app

```bash
# In root/
npm run dev
```
Backend: `http://localhost:5000`

---
## 🙋‍♀️ Author

**Nishika Agarwal**
👩‍💻 B.Tech - AI & ML @ NIT Kurukshetra

---
