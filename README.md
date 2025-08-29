# Project Setup

## Prerequisites

Make sure you have the following installed:

* Node.js (v18+ recommended)
* npm
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
npm run dev bcryptjs cloudinary cookie-parser cors dotenv express jsonwebtoken mongoose socket.io
npm install --save-dev nodemon
```

3. Create a `.env` file (see `.env.example`).
   
4. Start backend:

```bash
npm run dev
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
   
3. Start frontend:

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
PORT=5001
MONGO_URI=your_mongo_connection_string
JWT_SECRET=your_jwt_secret
CLOUDINARY_CLOUD_NAME=your_cloudinary_cloud_name
CLOUDINARY_API_KEY=your_cloudinary_api_key
CLOUDINARY_API_SECRET=your_cloudinary_api_secret
```


