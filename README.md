# NOU Digital Learning System

A full-stack **Learning Management System (LMS)** built using the **MERN Stack (MongoDB, Express.js, React.js, Node.js)**.
This system allows students to access learning materials, manage courses, and interact with the digital learning platform efficiently.

---

## 🚀 Features

* Student Authentication (Login / Register)
* Course and Learning Material Access
* Digital Learning Dashboard
* Admin Management System
* File and Resource Management
* Email Notifications using Nodemailer
* PDF & Report Generation
* API Integration
* Secure Password Hashing using bcrypt
* Responsive Frontend using React

---

## 🛠 Tech Stack

### Frontend

* React.js
* React Router
* Axios
* React Icons
* jsPDF (PDF generation)
* XLSX (Excel file support)

### Backend

* Node.js
* Express.js
* MongoDB
* Mongoose
* bcrypt.js
* Nodemailer
* dotenv

---

## 📂 Project Structure

```
NOU-Digital-Learning-System
│
├── backend
│   ├── models
│   ├── routes
│   ├── controllers
│   ├── server.js
│   └── package.json
│
├── frontend
│   ├── src
│   │   ├── components
│   │   ├── pages
│   │   ├── api
│   │   └── App.jsx
│   └── package.json
│
└── README.md
```

---

## ⚙️ Installation

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/RAJAT27-GIT/NOU-Digital-Learning-System.git
cd NOU-Digital-Learning-System
```

---

### 2️⃣ Install Backend Dependencies

```bash
cd backend
npm install
```

---

### 3️⃣ Install Frontend Dependencies

```bash
cd ../frontend
npm install
```

---

### 4️⃣ Setup Environment Variables

Create a `.env` file inside the **backend folder**

Example:

```
PORT=5000
MONGO_URI=your_mongodb_connection_string
EMAIL_USER=your_email
EMAIL_PASS=your_email_password
```

---

### 5️⃣ Run Backend Server

```bash
cd backend
npm start
```

---

### 6️⃣ Run Frontend

```bash
cd frontend
npm start
```

---

## 📸 Screenshots

You can add screenshots of:

* Login Page
* Student Dashboard
* Course Page
* Admin Panel

Example:

```
/screenshots/login.png
/screenshots/dashboard.png
```

---

## 👨‍💻 Author

**Rajat Chadda**

Frontend Developer | MERN Stack Developer

GitHub:
https://github.com/RAJAT27-GIT

---

## 📜 License

This project is developed for **educational and learning purposes**.
