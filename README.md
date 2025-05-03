# Student Course Registration System

A full-stack web application built using the **MERN stack (MongoDB, Express, React, Node.js)** that allows students to register for courses based on department and semester, while also enabling faculty management features.

---

## 📌 Project Structure

### Frontend (React) 

- **HomePage**: Landing page with navigation options.
- **FacultyDashboard**: View and manage faculty-related course data.
- **StudentDashboard**: Students can enter details, select department/semester, and view available courses.
- **Course**: Displays detailed course information.

### Backend (Express)

- **Routes**:
  - `studentRoutes.js`: Handles all student-related API endpoints.
  - `courses.js`: Handles all course-related endpoints.
- **Models**:
  - `Student.js`: Defines the student schema.
  - `Course.js`: Defines the course schema.

### Database (MongoDB)

- Stores student details, course offerings, departments, and semester mappings.

---

## 🛠 Tech Stack

- **Frontend**: React, Axios, Tailwind CSS (optional)
- **Backend**: Node.js, Express.js
- **Database**: MongoDB with Mongoose ODM
- **API Communication**: RESTful APIs

---

## 🚀 Features

- Dynamic course listing based on selected department and semester
- Student data submission and course registration
- Faculty dashboard for course management (extendable)
- Clean UI with component-based structure

---

## 🔧 Installation & Setup

1. **Clone the Repository**

   ```bash
   git clone https://github.com/NarmadhaGanesan/student-course-registration-system.git
   ```
2. **Backend Setup**

   ```bash
   cd backend
   npm install
   npm run dev
   ```
3. **Frontend Setup**

   ```bash
   cd frontend
   npm install
   npm start
   ```
4. **MongoDB**

   - Set up a MongoDB database (local or Atlas)

---

## 📂 Folder Structure Overview

```
student-course-registration/
│
├── backend/
│   ├── models/
│   │   ├── Course.js
│   │   └── Student.js
│   ├── routes/
│   │   ├── courses.js
│   │   └── studentRoutes.js
│   ├── server.js
│   ├── package.json
│   └── package-lock.json
│
├── frontend/
│   ├── public/
│   ├── src/
│   │   ├── assets/
│   │   ├── components/
│   │   │   ├── LogoutButton.js
│   │   │   └── ProtectedRoute.js
│   │   ├── context/
│   │   ├── pages/
│   │   │   ├── CoursePage.js
│   │   │   ├── EnrollmentPage.js
│   │   │   ├── FacultyDashboard.js
│   │   │   ├── HomePage.js
│   │   │   ├── LoginPage.js
│   │   │   └── StudentDashboard.js
│   │   ├── styles/
│   │   ├── App.js
│   │   ├── App.css
│   │   ├── App.test.js
│   │   ├── index.js
│   │   ├── index.css
│   │   ├── logo.svg
│   │   ├── reportWebVitals.js
│   │   └── setupTests.js
│   ├── .gitignore
│   ├── package.json
│   └── package-lock.json
│
└── README.md
```

---

## 📸 Architecture Diagram

![Architecture Diagram](./path-to-your-diagram.png)
_Illustrates the data flow between frontend, backend, and database._

---

## ✅ Future Enhancements

- Authentication (JWT-based login)
- Role-based access control 
- Course enrollment limits

---

## 📬 Contact

For questions or contributions, reach out to [narmadhaganesan1@gmail.com] or open an issue.
