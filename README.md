
# 📝 Blog – Post Management Platform

A web application where users can create, view, and manage posts.  
The project is divided into two parts: **Frontend** built with React and **Backend** built with Node.js + Express + MongoDB.

```

project/
├── frontend/ # React application
└── backend/  # Node.js + Express API

````

---

## 🎨 Frontend

**Tech Stack:**

- React 18  
- Redux + Redux Thunk  
- React Router DOM  
- React Hook Form + Yup  
- styled-components / CSS Modules  
- Font Awesome  

**Installation and Run:**

```bash
cd frontend
npm install
npm start
````

The application will be available at [http://localhost:3000](http://localhost:3000)

**Scripts:**

* `npm start` – start the React development server
* `npm run build` – build the production version

---

## ⚙️ Backend

**Tech Stack:**

* Express
* Mongoose (MongoDB)
* JSON Web Token (JWT)
* bcryptjs
* cookie-parser
* cors
* dotenv
* validator

**Installation and Run:**

```bash
cd backend
npm install
npm run dev
```

The server will run at [http://localhost:3002](http://localhost:3002) (or the port specified in `.env`)

**Environment Variables:**

Create a `.env` file in the `backend` folder:

```env
PORT=3002
MONGO_URI=your_mongodb_connection_string
```

**Scripts:**

* `npm run dev` – start the server in development mode (nodemon)

---

## 🚀 Features

* User registration and authentication
* Creating, editing, and deleting posts
* Viewing a list of all posts
* Form validation with React Hook Form + Yup
* Authorization using JWT

