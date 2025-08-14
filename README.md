# 📢 DigiComplaint & Feedback Portal

A modern and secure **MERN stack application** designed to streamline the process of submitting, tracking, and managing complaints and feedback in institutions like colleges and organizations.

---

## 🚀 Features

### 🎓 Student Side
- 📝 Submit complaints with auto-generated **5-digit unique ID** 
- 🔍 Track complaint status using the ID
- 🗣️ Submit **anonymous feedback**
- 💡 Simple and responsive user interface

### 🛠️ Admin Side
- 📬 View all complaints and feedback submissions
- 📝 Update complaint status (Pending → In Progress → Resolved)
- 🔐 Secure login with role-based access

---

## 🧰 Tech Stack

| Frontend | Backend | Database | Other Tools |
|----------|---------|----------|-------------|
| React.js | Node.js | MongoDB  | Express.js, JWT, Axios, Mongoose |

---

## 📁 Folder Structure

DigiComplaint-Feedback/
├── client/ # React frontend
│ ├── src/
│ ├── public/
│ └── .env # Not included in Git
│
├── backend/ # Express backend
│ ├── models/
│ ├── routes/
│ ├── controllers/
│ ├── uploads/ # For file uploads (excluded from Git)
│ └── .env # Not included in Git
│
├── .gitignore
├── README.md

⚙️ Setup Instructions
1. Clone the Repository

2. Backend Setup
   cd backend
   npm install
   Create a .env file inside backend/:
   MONGO_URI=your_mongodb_connection_string
  JWT_SECRET=your_secret_key
  PORT=5000
Start the backend server:
npm start
3. Frontend Setup
   cd ../DigitalComplaint
   npm install
   npm start


✍️ Author
Amit Kumar
Computer Science & Engineering
Vignan’s Foundation for Science, Technology & Research
