# mernAssignment-by-CGG

Awesome! Since your MERN stack project is now fully deployed, let’s write a clean and professional **GitHub repository README description** that explains:

1. What the project does
2. Tech stack used
3. Live site link
4. Backend API link
5. Features
6. How to set it up locally
7. Deployment guide

---

## ✅ `README.md` Content for Your GitHub Repo

You can copy-paste this into your `README.md` file:

````md
# MERN Contact Form Landing Page

A full-stack MERN application with a responsive landing page, a contact form, and a contact management dashboard.

### 🌐 Live Website:  
[Visit Frontend](# MERN Contact Form Landing Page

A full-stack MERN application with a responsive landing page, a contact form, and a contact management dashboard.

### 🌐 Live Website:  
[Visit Frontend](https://mernassignment-frontend.onrender.com)  
[Visit Backend API](https://mernassignment-backend.onrender.com)

---

## 📌 Project Description

This is a simple yet complete MERN (MongoDB, Express, React, Node.js) project that includes:

- A responsive landing page built with React and Tailwind CSS
- A Contact page with a form that submits data to MongoDB
- A Contact Details page to view and delete submitted contacts
- Fully functional backend with API endpoints built using Express.js
- Live deployment on Render (backend) and Netlify (frontend)

---

## ⚙️ Tech Stack

- **Frontend**: React.js, Tailwind CSS
- **Backend**: Node.js, Express.js
- **Database**: MongoDB (via Mongoose)
- **Deployment**: Netlify (frontend), Render (backend)

---

## 🧩 Features

- 📄 Landing page with Hero, Features, and Footer sections  
- 📬 Contact form to submit name, email, and message  
- 📊 Contact details dashboard for viewing and deleting entries  
- 🔗 Connected to MongoDB database  
- 🌍 Fully deployed & mobile responsive  

---

## 🚀 Getting Started Locally

To run this project on your local machine:

### 1. Clone the repository

```bash
git clone https://github.com/himakshi16/mernAssignmentCGG.git
cd mernAssignmentCGG
)  
[Visit Backend API](https://mernassignment-backend.onrender.com/api/contact)

---

## 📌 Project Description

This is a simple yet complete MERN (MongoDB, Express, React, Node.js) project that includes:

- A responsive landing page built with React and Tailwind CSS
- A Contact page with a form that submits data to MongoDB
- A Contact Details page to view and delete submitted contacts
- Fully functional backend with API endpoints built using Express.js
- Live deployment on Render (backend) and Netlify (frontend)

---

## ⚙️ Tech Stack

- **Frontend**: React.js, Tailwind CSS
- **Backend**: Node.js, Express.js
- **Database**: MongoDB (via Mongoose)
- **Deployment**: Netlify (frontend), Render (backend)

---

## 🧩 Features

- 📄 Landing page with Hero, Features, and Footer sections  
- 📬 Contact form to submit name, email, and message  
- 📊 Contact details dashboard for viewing and deleting entries  
- 🔗 Connected to MongoDB database  
- 🌍 Fully deployed & mobile responsive  

---

## 🚀 Getting Started Locally

To run this project on your local machine:

### 1. Clone the repository

```bash
git clone https://github.com/himakshi16/mernAssignmentCGG.git
cd mernAssignmentCGG
````

### 2. Setup Backend

```bash
cd backend
npm install
```

Create a `.env` file in the backend folder:

```env
MONGODB_URI=your_mongodb_connection_string
PORT=5000
```

Start the server:

```bash
node index.js
```

### 3. Setup Frontend

Open a new terminal and run:

```bash
cd frontend
npm install
```

Create a `.env` file inside the `frontend/` folder:

```env
REACT_APP_API_BASE_URL=http://localhost:5000
```

Start the React app:

```bash
npm start
```

The app will be available at `http://localhost:3000`

---

## 🚢 Deployment

* **Frontend (Netlify)**:

  * Build Command: `npm run build`
  * Publish Directory: `frontend/build`
  * Environment Variable:
    `REACT_APP_API_BASE_URL=https://mernassignment-backend.onrender.com`

* **Backend (Render)**:

  * Node project from `backend/` folder
  * Add environment variable:
    `MONGODB_URI=your-mongodb-uri`

--
