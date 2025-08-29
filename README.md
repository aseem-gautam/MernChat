# Project Setup

## Prerequisites

Make sure you have the following installed:

* Node.js (v18+ recommended)
* npm or yarn
* MongoDB (local or MongoDB Atlas)
* Git

## Clone the Repository

```bash
git clone https://github.com/your-username/your-project.git
cd your-project
```

## Backend Setup

1. Go to backend folder:

```bash
cd backend
```

2. Install dependencies:

```bash
npm install 
```

3. Create a `.env` file (see `.env.example` in backend folder).
4. Start backend:

```bash
npm run dev bcryptjs cloudinary cookie-parser cors dotenv express jsonwebtoken mongoose socket.io
npm install --save-dev nodemon
```

Backend runs at: `http://localhost:5001`

## Frontend Setup

1. Go to frontend folder:

```bash
cd ../frontend
```

2. Install dependencies:

```bash
npm install tailwindcss vite daisyui axios lucide-react react react-dom react-hot-toast react-router-dom socket.io socket.io-client zustand
```

3. Create a `.env` file (see `.env.example` in frontend folder).
4. Start frontend:

```bash
npm run dev
```

Frontend runs at: `http://localhost:5173`

## Project Structure

```
root/
├─ backend/          # Node.js + Express API
│   ├─ .env.example
├─ frontend/         # React app (Vite)
└─ README.md
```

---

# `.env.example`

## Backend (`/backend/.env.example`)

```env
PORT= 5001
MONGODB_URI= mongodb+srv://gautamaseem3:4aacW9B9YZXW86cq@cluster0.c9ij1ij.mongodb.net/mernchat_db?retryWrites=true&w=majority&appName=Cluster0
JWT_SECRET= aseem
NODE_ENV= development
CLOUDINARY_CLOUD_NAME= dphrrda7r
CLOUDINARY_API_KEY= 851912235954471
CLOUDINARY_API_SECRET= L4fHhRtQT40H1TsVYW5XKfDB44E
    
```


