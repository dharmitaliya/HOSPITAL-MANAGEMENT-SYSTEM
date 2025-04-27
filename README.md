🏥 Nandita Hospital Management System
A full-stack MERN (MongoDB, Express.js, React.js, Node.js) based Hospital Management System designed for efficient patient management and smooth hospital operations.

🚀 Project Overview
This system has three major components:

Frontend: For normal users (patients and visitors).

Dashboard: For Admin use only (manages hospital operations).

Backend: Handles API requests, stores all data in MongoDB Atlas.

👥 User Roles
There are three types of users:


User Type	Features
Patient	Can register, login, view doctors, and book appointments after login.
Doctor	Added and managed by Admin.
Admin	Can login to the dashboard, manage doctors across different branches, view all appointments, and manage users/messages.
✅ Even non-logged-in visitors can send a message, but appointments require patient login.

🏗️ Major Features
🏥 Hospital Name: Nandita Hospital

🛠️ Admin Dashboard:

Admin login (only Admins can access Dashboard)

Add / Remove Doctors in different branches

Manage Appointments, Users, and Messages

👨‍⚕️ Patients/Users:

User Registration & Login

View Doctor Listings

Book Appointments (after login)

Send messages (without login)

🛢️ Database:

All Users, Appointments, Messages, and Doctor data are stored securely in MongoDB Atlas.

🛠️ Tech Stack

Frontend	Backend	Database
React.js	Node.js, Express.js	MongoDB Cluster (Atlas)
📂 Project Structure
lua
Copy
Edit
/Frontend    --> User Interface for Patients & Visitors
/Backend     --> Server, API Routes, and MongoDB integration
/Dashboard   --> Admin Panel for Hospital Management
🔥 How to Run Locally
Clone the repo:

bash
Copy
Edit
git clone https://github.com/dharmitaliya/HOSPITAL-MANAGEMENT-SYSTEM.git
Navigate into folders and install dependencies:

bash
Copy
Edit
cd Backend
npm install

cd ../Frontend
npm install

cd ../Dashboard
npm install
Set up environment variables (MongoDB URI, etc.).

Start Backend:

bash
Copy
Edit
npm run server
Start Frontend:

bash
Copy
Edit
npm start
Start Dashboard:

bash
Copy
Edit
npm start
📧 Contact
For any queries or support, feel free to connect.

🙌 Thank you for visiting Nandita Hospital's Management System!
