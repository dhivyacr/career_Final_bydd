# 🎓 Intelligent Career Guidance System

An AI-powered career guidance platform that helps students identify suitable career paths based on their **skills, interests, academic performance, and mentor feedback**.

This system allows students to track their career progress while mentors monitor student performance and provide guidance.

---

# 🚀 Features

### 👩‍🎓 Student Portal

* Login using institutional email (`@bitsathy.ac.in`)
* Create and update academic profile
* Enter technical skills and interests
* Get AI-based career recommendations
* View **skill gap analysis**
* Receive **mentor guidance**
* Track career progress

---

### 👨‍🏫 Mentor/Admin Dashboard

* View all students who logged into the system
* Monitor student profiles
* Track CGPA and skill development
* Provide personalized feedback
* View department-wise student distribution

---

### 🤖 AI Career Recommendation

The system analyzes:

* Technical skills
* Soft skills
* Academic performance
* Career interests

and suggests possible career paths such as:

* Machine Learning Engineer
* Full Stack Developer
* Data Scientist
* DevOps Engineer

---

# 🧠 System Architecture

```text
Student Login
      ↓
Profile Creation
      ↓
MongoDB Database
      ↓
AI Career Recommendation Engine
      ↓
Mentor Dashboard
      ↓
Mentor Feedback → Student Guidance
```

---

# 🛠️ Tech Stack

### Frontend

* React.js
* Tailwind CSS
* Axios

### Backend

* Node.js
* Express.js

### Database

* MongoDB
* Mongoose

### Authentication

* Email based login (`bitsathy.ac.in` domain)

---

# 📂 Project Structure

```text
career_Final
│
├── backend
│   ├── controllers
│   ├── models
│   ├── routes
│   └── server.js
│
├── frontend
│   ├── components
│   ├── pages
│   └── App.js
│
├── screenshots
│   ├── login.png
│   ├── mentor-dashboard.png
│   └── student-dashboard.png
│
└── README.md
```

---

# 📸 Screenshots

### Login Page

![Login](screenshots/login.png)

### Student Dashboard

![Student](screenshots/student-dashboard.png)

### Mentor Dashboard

![Mentor](screenshots/mentor-dashboard.png)

---

# ⚙️ Installation Guide

### 1️⃣ Clone the repository

```bash
git clone https://github.com/YOUR_USERNAME/career_Final.git
cd career_Final
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
cd frontend
npm install
```

---

### 4️⃣ Setup Environment Variables

Create `.env` file inside backend.

Example:

```env
MONGO_URI=mongodb://localhost:27017/intelligent_career_guidance
PORT=5000
JWT_SECRET=careerai
```

---

### 5️⃣ Run Backend

```bash
cd backend
npm run dev
```

---

### 6️⃣ Run Frontend

```bash
cd frontend
npm run dev
```

---

# 📊 Future Improvements

* AI-based skill gap prediction
* Resume analysis
* Job recommendation engine
* Internship tracking
* Mentor analytics dashboard

---

# 👨‍💻 Author

Developed by:

**Dhivya Dharshini**

Artificial Intelligence & Machine Learning

---

# ⭐ Contribution

Feel free to fork this repository and contribute to improve the system.

---

# 📜 License

This project is created for **educational and research purposes**.
