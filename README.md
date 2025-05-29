# CareLink 🩺

**CareLink** is a full-stack web application for booking doctor appointments online. It allows users to browse doctors by specialization, make appointments, and manage their profiles, while providing doctors and admins tools for scheduling and management. Built with **React**, **Node.js**, **Express**, **MongoDB**, and styled using **Tailwind CSS**.


![Uploading Screenshot (45).png…]()


## 🚀 Features

- 🔐 User authentication (Login, JWT-based security)
- 🧑‍⚕️ Browse doctors by specialization
- 📅 Book appointments with doctors
- 📄 View and manage personal appointments
- 📁 Profile management
- 🛡️ Admin routes & management
- 🌩️ Image uploads with Cloudinary
- 💸 Payment integration with Razorpay & Stripe
- 🌈 Modern responsive UI using Tailwind CSS
- 🔔 Notifications via React Toastify

## 🛠️ Tech Stack

### Frontend:
- React
- React Router
- Tailwind CSS
- React Toastify
- Axios

### Backend:
- Node.js
- Express.js
- MongoDB (via Mongoose)
- Cloudinary (for image storage)
- Stripe & Razorpay (payment gateways)
- Multer (file uploads)
- JWT Authentication
- dotenv for environment variables

## 📁 Project Structure
/frontend<br>
└── src<br>
├── pages/ # Home, Doctors, Login, etc.<br>
├── components/ # Navbar, Footer, etc.<br>
├── context/ # Global AppContext<br>
├── App.jsx<br>
└── main.jsx<br>

/backend<br>
├── routes/ # API route files (user, doctor, admin)<br>
├── config/ # DB & cloudinary config<br>
├── server.js<br>
└── .env



