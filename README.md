

```bash
# MERN Blog

A full-stack blogging application built with the MERN stack: MongoDB, Express.js, React.js, and Node.js.  
It allows users to create, read, update, and delete blog posts with a modern and responsive UI.

## 🚀 Features

- Create, edit, and delete blog posts  
- User authentication with JWT  
- Responsive design using Tailwind CSS  
- Rich text editor for writing posts  
- Deployed on Vercel: https://mern-blog-three-orcin.vercel.app

## 🛠️ Technologies

- Frontend: React.js + Tailwind CSS  
- Backend: Node.js + Express.js  
- Database: MongoDB  
- Auth: JWT  
- Deployment: Vercel

## 📦 Installation

### Prerequisites

- Node.js (v14 or later)  
- npm or Yarn  
- MongoDB installed locally or MongoDB Atlas URI

### Clone the Repository

```bash
git clone https://github.com/Adamk1979/Mern-Blog.git
cd Mern-Blog
```

### Set Up Environment Variables

In the `server` folder, create a `.env` file:

```bash
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_secret_key
```

### Install Dependencies

Backend:

```bash
cd server
npm install
```

Frontend:

```bash
cd ../client
npm install
```

### Run the App

Start backend:

```bash
cd ../server
npm start
```

Start frontend:

```bash
cd ../client
npm start
```

Visit the app:

```bash
http://localhost:3000
```

## 📁 Folder Structure

```bash
Mern-Blog/
├── client/    # React frontend
├── server/    # Express backend
├── vercel.json
```

## 📄 License

This project is licensed under the MIT License.
```

---

Let me know if you want a version with emojis removed or translated into Swedish!
