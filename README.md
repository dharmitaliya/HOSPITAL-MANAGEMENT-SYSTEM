# 🏥 Nandita Hospital Management System

A full-stack **MERN** (MongoDB, Express.js, React.js, Node.js) based Hospital Management System designed for efficient patient management and smooth hospital operations.

---

## 🚀 Project Overview

This system includes:
- **Frontend**: For normal users (patients and visitors).
- **Dashboard**: For Admin use only (manage doctors, appointments, messages).
- **Backend**: Handles API requests, stores data in **MongoDB Atlas**.

---

## 👥 User Roles

- **Patient**: Can register, login, view doctors, and book appointments after login.
- **Doctor**: Added and managed by Admin only.
- **Admin**: Can log into the Dashboard and manage doctors, appointments, and users.

> **Note:** Visitors who are not logged in can still send messages, but can only book appointments after logging in as a patient.

---

## ✨ Features

- Hospital Name: **Nandita Hospital**
- Secure Admin login and Dashboard
- Patients can view doctors and book appointments
- Admin can add/remove doctors in different branches
- Messaging system (open to all visitors)
- All data (users, appointments, doctors, messages) stored securely in **MongoDB Atlas**

---

## 🛠️ Tech Stack

- **Frontend**: React.js
- **Backend**: Node.js, Express.js
- **Database**: MongoDB Atlas

---

## 🖼️ Screenshots

> Upload your screenshots inside a folder named `/screenshots` in your repo, and replace the below links.

### 🧑‍⚕️ Patient Frontend
![Patient Frontend View](./screenshots/patient-frontend.png)

### 🛠️ Admin Dashboard
![Admin Dashboard View](./screenshots/admin-dashboard.png)

---

## 📂 Project Structure


---

## ⚙️ How to Run Locally

1. **Clone the repository**
   ```bash
   git clone https://github.com/dharmitaliya/HOSPITAL-MANAGEMENT-SYSTEM.git
Install dependencies

Backend:

bash
Copy
Edit
cd Backend
npm install
Frontend:

bash
Copy
Edit
cd ../Frontend
npm install
Dashboard:

bash
Copy
Edit
cd ../Dashboard
npm install
Set up environment variables

Inside the Backend folder, create a .env file:

ini
Copy
Edit
MONGODB_URI=your-mongodb-cluster-uri
JWT_SECRET=your-jwt-secret
Start the servers

Backend:

bash
Copy
Edit
npm run server
Frontend:

bash
Copy
Edit
npm start
Dashboard:

bash
Copy
Edit
npm start
📧 Contact
For any queries or suggestions, feel free to connect.

##🙌 Thank you for visiting Nandita Hospital Management System!
