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
- **Admin**: 
  - Can log into the Dashboard.
  - Manage doctors, appointments, users, and messages.
  - Can add new Admins (promote other users to Admin role).

> **Note:** Visitors who are not logged in can still send messages, but can only book appointments after logging in as a patient.

---

## ✨ Features

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

### 🧑‍⚕️ Patient Frontend
- **Home**
![home](https://github.com/user-attachments/assets/85e78083-088a-4345-978b-a04525c5ad21)
- **Apoointment**
![screencapture-localhost-5173-appointment-2025-04-27-22_34_57](https://github.com/user-attachments/assets/41bd8ba6-48d2-4e5d-941c-a549eaac103e)
- **About Us**
![about us](https://github.com/user-attachments/assets/7ffd9a11-05dc-406b-a8f8-244baf6e3386)
- **Registration**
![registraion](https://github.com/user-attachments/assets/4749bcad-5f2a-4405-bd45-d1a4d38942f3)
- **Login**
![image](https://github.com/user-attachments/assets/511bec52-2f29-49a8-9e95-7e503972d546)

### 🛠️ Admin Dashboard
- **Login**
![image](https://github.com/user-attachments/assets/cf9fe8ab-ea36-44e3-a018-75c52d51170f)
- **Dashboard**
![image](https://github.com/user-attachments/assets/2fa3cb8f-e248-4ab4-83cc-cece23702434)
- **Doctors**
![image](https://github.com/user-attachments/assets/c2584924-2f26-400c-88b0-594cc38b8905)
- **New Admin**
![image](https://github.com/user-attachments/assets/3900ce94-f31d-4806-9ed4-351c4cd4061e)
- **New Doctor**
![new doctor](https://github.com/user-attachments/assets/631fa4c6-60bd-46d8-9e5f-145c8ead1f83)
- **Messages**
![image](https://github.com/user-attachments/assets/b8526595-ff4f-4c69-80f2-3abfb1945fd2)


---

## 📂 Project Structure

- /Frontend --> User Interface (Patients & Visitors) 
- /Backend --> Server-side (APIs, Database connection) 
- /Dashboard --> Admin Panel (Hospital Management) 

---

## ⚙️ How to Run Locally

1. **Clone the repository**
   ```bash
   git clone https://github.com/dharmitaliya/HOSPITAL-MANAGEMENT-SYSTEM.git
2. **Install dependencies**
   <br>
   - Backend:
      ```bash
      cd Backend
      npm install
   - Frontend:
     ```bash
     cd ../Frontend
     npm install
   - Dashboard:
     ```bash
     cd ../Dashboard
     npm install
3. **Set up environment variables** <br>
Inside the Backend folder, create a .env file and add:
   ```bash
   MONGODB_URI=your-mongodb-cluster-uri
   JWT_SECRET_KEY=your-jwt-secret
   PORT=4000
   FRONTEND_URL=http://localhost:5173
   DASHBOARD_URL=http://localhost:5174
   JWT_EXPIRES=7d
   COOKIE_EXPIRE=7
   CLOUDINARY_CLOUD_NAME=your-cloud-name
   CLOUDINARY_API_SECRET=your-api-secret
   CLOUDINARY_API_KEY=your-api-key

CLOUDINARY_API_KEY=299154468946774
4. **Start the servers**<br>
   - Backend Server:
      ```bash
      npm run dev
   - Frontend :
     ```bash
     npm run dev
   - Dashboard :
     ```bash
     npm run dev 

---

## 📧 Contact <br>
For any queries or suggestions, feel free to connect. <br>
Email: [dharm.italiya5151@gmail.com](dharm.italiya5151@gmail.com)  LinkedIn: [Dharm Italiya](https://www.linkedin.com/in/dharm-italiya/)

---

## 🙌 Thank you for visiting Nandita Hospital Management System!
