#  Gmail Clone - Full Stack Web App

A Gmail-inspired full-stack web application with user authentication, email sending/deleting, and a responsive UI — built using the 
MERN stack,Redux Toolkit, Tailwind CSS, and Vite. Hosted on Render (backend) and Vercel (frontend).

---

##  Features

-  User Registration & Login (JWT + Cookies)
-  Send, receive, and delete emails
-  Redux state management
-  Secure password hashing with bcrypt
-  Cloud Deployment (Render + Vercel)
-  Responsive UI with Tailwind CSS
-  Toast notifications for actions (react-hot-toast)
-  Avatar API integration for user profile photos

---

##  Project Structure

gmail-clone/
│
├── backend/
│ ├── controllers/ # Auth & email logic
│ ├── models/ # MongoDB Schemas
│ ├── routes/ # Express API routes
│ ├── middleware/ # (optional: auth middleware)
│ ├── connectDB.js # MongoDB connection
│ └── index.js # Express server entry
│
├── frontend/
│ ├── public/
│ ├── src/
│ │ ├── components/ # React UI components (Login, Signup, Mail, Navbar etc.)
│ │ ├── redux/ # Redux slice + store
│ │ ├── hooks/ # Custom data fetching hook
│ │ ├── App.jsx # Main component
│ │ ├── axios.js # Axios instance w/ baseURL
│ │ └── main.jsx # React entry
│ └── vite.config.js


---

##  Live Links

-  **Frontend (Vercel): [gmail-clone.vercel.app](https://gmail-clone-flax.vercel.app)
-  **Backend (Render): [gmail-clone.onrender.com](https://gmail-clone-1lbu.onrender.com)

---

##  Tech Stack

- Frontend: React, Vite, Tailwind CSS, Redux Toolkit, React Router, Toast
- Backend: Express.js, MongoDB (Atlas), Mongoose, bcryptjs, JWT, cookie-parser
- Hosting: Render (Backend), Vercel (Frontend)

---

💡 Future Improvements
- Add email search & filters
- Labeling & sorting
- Rich-text email editor
- Dark mode support

