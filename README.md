# Hospital Management System

## Admin Login

### Seed Admin

```bash
cd backend
node seed.js
```

### Default Admin Credentials

```txt
Email: admin@hms.com
Password: admin123456
```

You can also login directly using these credentials if the admin already exists in the database.

---

A full-stack MERN-based Hospital Management System where patients can register, book appointments, and connect with doctors. Doctors can register themselves, but they must be approved by the admin before appearing in the patient doctor list.

Built using the MERN Stack:

* MongoDB
* Express.js
* React.js
* Node.js

---

# Features

## Admin

* Secure Admin Login
* Approve/Reject Doctor Registrations
* Manage Doctors
* Manage Patients
* View Appointments
* Dashboard Management

## Doctors

* Doctor Registration
* Login System
* Profile Management
* Appointment Handling
* Available only after admin approval

## Patients

* Patient Registration/Login
* Browse Approved Doctors
* Book Appointments
* Manage Profile

---

# Tech Stack

## Frontend

* React.js
* Axios
* React Router
* CSS / Tailwind CSS

## Backend

* Node.js
* Express.js
* MongoDB
* Mongoose
* JWT Authentication

---

# Installation & Setup

## 1. Clone Repository

```bash
git clone 
cd Hospital-Management-System
```

---

# Backend Setup

## Go to backend folder

```bash
cd backend
```

## Install dependencies

```bash
npm install
```

## Create `.env` file

```env
MONGO_URI=your_mongodb_uri
JWT_SECRET_KEY=your_secret_key
PORT=4000
FRONTEND_URL=http://localhost:5173
```

## Run backend server

```bash
npm start
```

or

```bash
npm run dev
```

---

# Frontend Setup

## Open new terminal

```bash
cd frontend
```

## Install dependencies

```bash
npm install
```

## Start frontend

```bash
npm run dev
```

Frontend runs on:

```bash
http://localhost:5173
```

---

# Doctor Approval Flow

1. Doctor registers
2. Doctor account remains pending
3. Admin approves doctor
4. Approved doctor becomes visible to patients
5. Patients can book appointments with approved doctors

---

# API Features

* Authentication using JWT
* Protected Routes
* Role-based Access
* Doctor Approval Middleware
* Appointment APIs
* Patient Management APIs

---

# Available Scripts

## Backend

```bash
npm start
npm run dev
```

## Frontend

```bash
npm run dev
npm run build
```

---

# Future Improvements

* Video Consultation
* Online Payments
* Email Notifications
* Prescription System
* Medical Reports Upload
* Chat System

---
This project is licensed under the MIT License.
