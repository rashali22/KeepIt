# KeepIt 📝

A modern **Full Stack Note Management Application** built using the **MERN Stack**. KeepIt enables users to securely create, organize, search, edit, pin, and delete personal notes with a clean and intuitive interface.

---

## ✨ Features

- 🔐 User Authentication (Signup & Login)
- 📝 Create, Edit and Delete Notes
- 📌 Pin / Unpin Important Notes
- 🔍 Search Notes by Title or Content
- 👤 Personalized User Dashboard
- 🔒 JWT-based Secure Authentication
- 💾 MongoDB Database Integration
- 📱 Responsive User Interface
- ⚡ Fast and Interactive React Frontend

---

## 🛠️ Tech Stack

### Frontend

- React.js
- Vite
- Tailwind CSS
- Axios
- React Router
- React Icons
- React Modal

### Backend

- Node.js
- Express.js
- MongoDB
- Mongoose
- JSON Web Token (JWT)
- dotenv

---

## 📂 Project Structure

```
KeepIt/
│
├── backend/
│   ├── models/
│   ├── index.js
│   ├── utilities.js
│   └── package.json
│
└── frontend/
    └── notes-app/
        ├── src/
        ├── public/
        ├── package.json
        └── vite.config.js
```

---

## ⚙️ Installation

### 1. Clone the Repository

```bash
git clone https://github.com/YOUR_USERNAME/KeepIt.git
```

### 2. Backend Setup

```bash
cd backend
npm install
```

Create a `.env` file:

```env
ACCESS_TOKEN_SECRET=your_secret_key
MONGO_URI=your_mongodb_connection_string
```

Start the backend:

```bash
npm start
```

---

### 3. Frontend Setup

```bash
cd frontend/notes-app
npm install
npm run dev
```


## 🔮 Future Improvements

- 🌙 Dark Mode
- 🏷️ Categories & Labels
- 🎨 Note Color Themes
- 📅 Reminders
- ⭐ Favorite Notes
- 📤 Export Notes
